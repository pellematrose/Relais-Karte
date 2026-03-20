# Relais-Karte
Relais Karte für 24V System auf ELIDA  
## Gedachte Verwendung
Über J1 wird die Schaltung mit Strom versorgt. Über J2 kann eine weitere Platine mit Spannung versorgt werden.  
Mit der Autosicherung wird die Schaltung bzw. die Last geschützt. Der Schiebeschalter kann die Last unabhängig vom Relais einschalten.  
An J4 wird das Schaltsignal angeschlossen, womit das Relais aktiviert werden soll. Hier kann z.B. ein Schwimmerschalter angeschlossen werden.  
An J3 wird die Last, z.B. eine Pumpe, angeschlossen. Soll die Last bestromt werden, wenn das Relais aktiviert wird, muss die Last zwischen NO (+24V) und GND angeschlossen werden.  
Soll die Last über die Relaisaktivierung ausgeschaltet werden, wird die Last zwischen NC (+24V) und GND angeschlossen. Es können auch zwei Lasten angeschlossen werden. Es ist immer nur eine aktiv.  
Das weiße Feld ist für Notizen gedacht wie z.B. eine Nummer oder welche Last angeschlossen ist.

PCB Maße: 38,5mm x 75,5mm  
![alt text](https://github.com/pellematrose/Relais-Karte/blob/main/3D_render.png "3D Render")
