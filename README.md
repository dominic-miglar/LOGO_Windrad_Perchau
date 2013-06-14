#############################
# Windrad  Perchau          #
#############################

Ein Windrad soll drehzahlgesteuert Phasen dazu- und wegschalten.

L1 ist permanent angeschlossen, und wird nicht über die LOGO gesteuert.

L2 und L3 werden mittels der LOGO 12/24RC geschalten (siehe Seite mit Anschlussklemmen).

Zusätzlich gibt es noch zwei Stufen: VNT (Vernichtung) und BR (Motorbremse).

Die VNT-Stufe (Vernichtung) soll die Drehzahl des Motors verringern, indem ein zusätzlicher Verbraucher dazugeschalten wird.

Die BR-Stufe (Bremse) dient als Notfallstufe, falls die VNT-Stufe die Drehzahl nicht ausreichend drosseln kann. Hier wird eine Motorbremse aktiviert.
Die Motorbremse hat keinen eingebauten Endschalter. Deswegen wird eine Treppenhausautomatfunktion verwendet, um sie genau für 5 Sekunden zu aktivieren.



Drehzahlmessung:
    - 4x Impuls pro Umdrehung
    - mittels induktiven Näherungssensor (Pepperl & Fuchs)
    ---> Wertaktualisierung alle 6 Sekunden

Verwendete Steuerung:
    Siemens LOGO 12/24RC 0BA6


Stand 10.06.2013
