# demoradio
 sound von deinem lauti streamen lernen

<h1> HANDOUT - Aufbau Public Address (PA) System + DemoRadio </h1>


## Fragen, Anregungen demoradio@lists.riseup.net oder kontakt@mygruni.de



**Aufbau: PA System und Radio Setup:**

![](https://s3.hedgedoc.org/demo/uploads/1c3d8ee3-b052-4364-ab0f-3bfdf63c18b7.jpg)



## Weiterführende Links und Hinweis:

How to Demoradio auf Youtube: https://www.youtube.com/watch?v=oxv3a_ob56c

English DemoSound Tutorials: https://distributedsoundcollective.org/Index

Teaser Video: https://www.youtube.com/watch?v=saAvu-LScOo

**Achtung:** Wenn ihr euch dazu entschließen solltet einen LiveStrema zu senden, müsst ihr euch bewusst sein, dass alles von allen aufgezeichnent werden kann. 


## Equipment, Human Power, Strom, Arbeitsplätze

### Equipment

* 5 XLR-Kabel
* 4 Speakon-Kabel
* 4 Soundboxen **passiv**
* 1 Verstärker
* 1 Mischpult/ Mixer/ Mischer (Hardwaregerät zum Koppeln der Geräte)
* 7 PCs (inklusive Backup, kann teils durch Tablet oder Handy ersetzt werden)
* 2 Mics
* 2 Soundkarten
* 2 DI Boxen
* 1 Interface (Aufnahmegerät eignet sich auch dafür)
* 3 Kopfhörer
* Router mit Simkarte 


### Human Power
* Person 1-2 Moderation
* Person 3 Regie
* Person 4-5 Mischen
* Person 6 Stream 
* Person 7 Schalten
* Person 8 Backup

### Strom
* Generator- Phase 1 an Verstärker, PCs (12 Ausgänge Schuko)
* Generator- Phase 2 an Mischpult (2 Ausgänge)


### Überblick Arbeitsplätze
* Mischen: PC_01MischenPlaylist (Einspieler); PC_02MischenSoftware
* Stream:  PC_03StreamMonitor (Soundcheck, auch via Handy möglich); PC_04StreamSenden 
* Schalten: PC_05Schalten
* Regie: PC_06Regie (nicht auf Skizze abgebildet)
* Moderation: Mic_01 und Mic_02, Handy für LiveSchalte
 
## Anschließen und Aufgaben
### Mischen 

**Mischen Anschließen:**
* PC_01MischenPlaylist 
    -> über USB an Soundkarte, an 2 DI-Boxen (optional, je nach Soundqualität), an Mischpult
    
    Notiz: Wenn es kein Rauschen zwischen Laptop und Mixer gibt, kann der PC auch direkt per kleine Klinke doppel-Chinch angeschlossen werden

* PC_02MischenSoftware 
    -> (oder auch Tablet möglich) über Internet via Wlan mit Analof Mischpult verbinden
    -> MixerSoftware draufladen (. z.B. Behringer xAir 18)

         **Grundeinstellung MixerSoftware**
            * Gain: "Eingangstür" für den Sound > Wie laut max (1x Grundeinstellung)
            * Mikrophon Einstellungen: 25-30db Grundeinstellung | Nur Kondensatormikrophone brauchen Phantomstrom
            * Equalizer > Störfrequenzen abschneiden (bei mik > alles unter 100 Hz) abschneiden (low cut)
            * Kompressor: -20dB | Ratio auf 2 | Attack 10ms 
            * Kanäle Koppeln? Channel > Stereolink

* Anschluss Mischpult an Verstärker 
    -> aus Mischpult 2x XLR-Kabel von Main L + R in -> Verstärker in Input L + R
    -> von Verstärker mit 4x Speakon-Kabel an > Soundboxen (passiv)

**Beispiel Channel-Belegung Mischpult:**

    * MainR - Verstärker
    * MainL - Verstärker
    * Aux 1 - PC_04StreamSenden
    * Aux 2 - PC_04StreamSenden
    * CHANNEL 1 - PC_01MischenPlaylist
    * CHANNEL 2 - Mic_01 Moderation
    * CHANNEL 3 - Mic_02 Moderation
    * CHANNEL 4 - PC_05Schalten
    * CHANNEL 5 - PC_05Schalten
    * CHANNEL 6 - Handy Liveschalte
    * CHANNEL 7 - Handy Liveschalte
    


**Mischen Aufgaben:**

    * Songs/Beiträge abspielen von Band (z.B. über VLC-Player)
    * Fadeout-fadein von vorgegebener Playlist
    * Eingänge auf -10 db pegeln [j: am mixer]
    * Mic die nicht benötigt werden muten
    * Einspieler vorauswählen, starten
    * alles muten was nicht laufen soll 
    * Über Mixer Schalten, Songs etc vorhören 
    * braucht Kopfhörer um das Signal zu checken
    * Mikrophone mischen auf -20
    * wenn es pfeift > Mikrophone muten 



### Schalten

#### Schalten Anschließen:
* PC_05Schalten 
    -> beliebige Software für die Schalte wählen
    -> PC_05Schalten (USB) -> Soundkarte und Soundkarte (Chinch) -> in 2x DI Boxen (optional]große Klinke) und DI Boxen (XLR)-> Mischpult (XLR) - DI Boxen optional bei Liveschalte über Laptop > nur wenn Rauschen 
    -> Debugging, wenn es rauscht: DI Boxen auf 20 stellen
    -> Soundkarte (USB Strom), mit Kopfhörer check
    -> wenn Direktverbindung, dann Soundkarte (Chinch) -> Mixer (große Klinke)


#### Schalten Aufgaben:
    -> vergleichbar mit Aufnahmeleitung: Kommunikation andere Bühne, einspielen weitere Signale, Kommt das Signal extern an?

### Regie 

**Regie Anschließen:**
* nichts zum Anschließen, ist auch nicht auf Skizze dokumentiert


**Regie Aufgaben:**
* koordiniert die Beiträge; sagt an, wer was machen muss (Management vom Team)
* hat 1 Regieplan
* checkt den Zeitplan, müssen wir was füllen/checken? 
* PC für Regie optional


### Stream 

**Stream Anschließen:**
* PC_03StreamMonitor (oder einfach Handy)
    -> Radio im Browser öffnen und mit Kopfhörern Signalflow kontrollieren (Signal da, Lautstärke und Quali gut?)
    
* PC_04StreamSenden (Streamen,  und Netzwerkkontrolle)
    -> Mischpult Aux1 und Aux2 (Doppel XLR) -> Interface und Interface (USB) -> PC_04StreamSenden 
    -> mit PC_04StreamSenden den Ressourcenmonitor (bzw Netzwerkanalyse) öffnen und Netzwerkverbindung konrollieren, ob Internetverbindung stabil ist
    -> PC_04StreamSenden ist mit Lan-Kabel an Router verbunden (statt Router auch Handyhotspot oder LTE Stick möglich)
    -> Pegeln an Aufnahmegerät (Interface) (Pegelwert? -10db) und bei butt (butt -10 - -6db einstellen)
    -> PC_04StreamSenden via LAN an Router 
    -> Anmerkung: Aufnahmegerät auf Quelle stellen _> Stromversorgung gleichzeitig per USB, 
    -> Troubleshooting: Kein Signal? Check: Internetproblem? Wird Sound gesendet? (in Butt schauen), falls Ja - > Soundkarte checken, Stream neu starten, Butt neu starten


**Stream Aufgaben**

    -> verantwortlich für Sendetechnik und SignalMonitoring
    -> bei Radiojahr im Webbrowser anmelden
    -> Butt Software downloaden und Übertragungsdaten von Radiojar in Butt eintragen (siehe Radiotutorial)
    -> Am PC in der "Netzwerkanalyse" die Netzwerkverbindung beobachten
    -> ggf. bei Butt die Serververbindung stoppen und neustarten
 
 
    
### Backup aka Springer:in 
* Sprit nachfüllen im Generator auf dem Dach 
* kommt Ton aus den Boxen raus?
* Troubleshooter:in - Pausen 
* Kommunikation nach außen
* Allgemein Strom Orga etc


### Moderation
* Mic_01 und Mic_02
-> an Mischpult via XLR

* Handy für LiveSchalte
-> Handy Liveschalte(kleine Klinke) -> Soundkarte(Chinch) und Soundkarte (Doppel Chinch)-> Mischpult (Doppel XLR)
-> Soundkarte(Klinke) Kopfhörer

* Kommunikation mit Moderation
    -> wir sind bereit, Kanal ist offen, bitte weiterreden etc


### Nützliche Tipps

- Demostrecke vorherabfahren und Netzabdeckung checken -> Kurze Ausfälle lassen sich kaum vermeiden, längere Ausfälle wären nervig. Macht es Sinn dann ein Demoradio anzubieten? Kann eine andere Strecke gewählt werden?
- Für einen reibungslosen Ablauf bietet es es sich an eine Generelprobe mit allen beteiligten durchzuführen. Funktioniert die Tedchnik, Übergänge, ungeklärte Fragen zum Ablauf?
- Es wäre auch eine Möglichkeit, statt Livebeiträge die voraufgezeichneten Redebeiträge der Redner_innen zu senden
- kurze Gingles vorher aufnehmen und zwischendrin einspielen frischt das Programm etwas auf :)



### Glossar 
- DI Boxen: wandeln ein unsynchrones in synchrones Signal - Rauschunterdrückung // Einstellung > Lift and Ground 
- Soundkarte: Signalwandler von Digital in Analog - Verbessert die ÜBersetzungsqualität vom Stream 
- Chinch Kabel: sollte nicht länger als 2 m sein, weil sonst die Qualität leidet



 
![photo_2022-04-25_08-20-35](https://github.com/hotmail030/demoradio/assets/120741476/fb4251d0-1380-4e1f-b703-18f5de8eb08c)
