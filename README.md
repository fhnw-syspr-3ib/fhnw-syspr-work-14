# System-Programmierung
## Hands-on zu Lektion 14
Für Slides und Code Beispiele, siehe [Lektion 14](../../../fhnw-syspr/blob/master/14/README.md)

> *Achtung: Arbeiten Sie nicht direkt auf diesem Repository.*<br/>
> *[Erstellen Sie eine persönliche Kopie, mit diesem GitHub Classroom Link](https://classroom.github.com/a/Jrqi8tPD).*

### a) GPIO, 15'
* Diese Hands-on Übung basiert auf dem [GPIO Pinout](https://pinout.xyz/pinout/wiringpi) des Raspberry Pi und kann gut zu zweit gelöst werden.
* Schreiben Sie ein Programm *my_switch.c* das mittels GPIO den Zustand eines Buttons liest, und damit eine LED ein- bzw. ausschaltet (Breadboards, Schalter, LED, Jumper Kabel und Widerstände werden im Unterricht ausgegeben).
* Während dem Aufbau der Schaltung sollte das Gerät vom Strom getrennt sein, zum Schutz der Elektronik.

### b) UART, 20'
* Diese Hands-on Übung basiert auf dem GPIO Pinout des Raspberry Pi, und kann in Gruppen gelöst werden.
* Schreiben Sie ein Programm *my_gps.c* das über UART mit AT Commands ein GPS Modul anspricht und ausliest.
* Als Hardware dient das ublox PAM 7Q GPS Modul (die Anzahl ist auf 4 beschränkt, arbeiten Sie in Gruppen).
