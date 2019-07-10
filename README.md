# ![](https://www.lpice.eu/fileadmin/_processed_/csm_LinuxEssentials-01_0ab118aa19.jpg)  Linux Essentials Exam 010

## Fahrplan
***


| Datum | behandelte Unterrichtsinhalte: | Gewichtung |
| -------- | ------ | -------- |
| 15.05.19 | Installation SW, Einrichten Linux VM<br>1.1 Linux Evolution and Popular Operating Systems<br>1.3 Open Source Software and Licensing | 2 + 2 |
| 22.05.19 | [2.1 Command Line Basics]<br>[2.3 Using Directories and Listing Files](https://github.com/w901-fr19-mi/E010#23-using-directories-and-listing-files)<br>2.4 Creating, Moving and Deleting Files  | 2 + 3 + 2 |
| 29.05.19 | 3.2 Searching and Extracting Data from Files<br>3.3 Turning Commands into a Script | 3 + 4 | 
| 05.06.19 | 4.4 Your Computer on the Network | 2 |
| 12.06.19 | 702.1 Container Usage - Studium | - |
| 19.06.19 | 702.1 Container Usage - Umsetzung | 7 (14) |
| 26.06.19 | LB1 Theoretische Prüfung und Abschluss LB2 | - |
| 03.07.19 | Sommersporttage | - |
|          | Total Punkte | 24 (31) !

Kapitel aus E010 sind einzeln erarbeitet worden. Kapitel aus E701 in der Gruppe mit ....

## Dokumention des Lern- und Entwicklungsprozesses
***
### Kapitel: 1.1 Linux Evolution and Popular Operating Systemss (Status: In Arbeit)

**Weight:** 2

**Beschreibung:** Knowledge of Linux development and major distributions

**Beispiele und Arbeitsergebnisse:**
* Distributions:
Eine Distribution ist ein Paket welcher auf einer Software/Kernel läuft. Nehmen wir z.B Linux, viele Betriebsysteme laufen auf Linux wie z.B: Ubuntu, Debian, Red Hat usw., diese gennante Linux-Destributins sind spezialisierte Images.

* Embedded Systems:
Embeded Systems sind Geräte welche mit einem eingebetetn System laufen. Aber was genau bedeutet das? Nehmen wir and wir haben eine Kafeemaschine. Hinter der Kafeemaschine steckt ein System(z.B: Linux) welches alles leitet.

* Linux in the Cloud:
Auch Cloud-Computing gennant. Damit meint man vor allem Server in die Coud zu verschieben. Man zahlt/benutzt nur das was man braucht.
Es gibt viele Anbieter wie Microsoft, die das zur verfügung stellen "Microsoft Azure". Dadurch ist man viel flexibler & spart Platz da alles in der Cloud liegt & man sich über das Internet darauf verbinden kann.


***

### Kapitel: 1.2 Major Open Source Applications

**Weight:** 2

**Beschreibung:** Awareness of major applications as well as their uses and development
    
**Beispiele und Arbeitsergebnisse**

* Desktop application
    * Thunderbird: Thunderbird ist ein E-Mail-Programm wie Outlook von Firefox. Auf Ubuntu-Desktop ist es standardmässig schon vorinstalliert.
    * LibreOffice: Libreoffice ist mit Microsoft Office zu vergleichen. Man kann es auf Ubunut herunterladen
* Server application
    * Nextcloud: Nextcloud ist eine Software welche für das Speichern von Daten auf einem eigenen Server. Ist mit Dropbox vergleichbar jedoch hat man die vollständige Kontrolle über die Daten.
    * Samba: Samba ermöglicht  Windows-Funktionen wie die Datei- und Druckdienste unter anderen Betriebssystemen zu nutzen und die Rolle eines Domain Controllers anzunehmen.
    * NFS: Das Network File System ist eine Client/Server-Anwendung, die es einem Benutzer ermöglicht, eine Datei auf einem Remote-Computer so anzuzeigen, zu speichern und zu aktualisieren, als ob sie sich auf seinem eigenen Rechner befinden würde. 
* Package management tools and repositories:
    * dpkg: dpkg ist das Format der Software Packages für Linux-Distributionen wie Ubuntu, Debian usw., apt ist das Paketverwaltungssystem für dpkg. Sie sind vergleichbar mit den bei Windows bekannten MSI-Dateien.
    * apt-get(apt): apt ist ein Paketverwaltungssystem welches für Linux-Distribustionen verwendet wird wie Ubuntu, Debian usw.
    * rpm: rpm ist das Format der Software Packages. Yum ist die Paketverwaltungsystem für rpm. Sie sind vergleichbar mit den bei Windows bekannten MSI-Dateien.  
    * yum: yum ist ein Paketverwaltungssystem genau wie apt jedoch wird yum bei Linux-Distributionen wie CentOS, Red Hat usw. verwendet

***

### Kapitel: 1.3 Open Source Software and Licensing

**Weight:** 1

**Beschreibung:** Open communities and licensing Open Source Software for business

**Tagesziele:**

**Vorgehen:** z.B. Installation einer Ubuntu Linux Umgebung. Durcharbeiten ...., Dokumentation der einzelnen Befehle in ...

**Beispiele und Arbeitsergebnisse:**

* Open source
	* Open Source ist die freie Verfügbarkeit von Software-Quellcodes. Welche im Rahmen von Open-Source-Lizenzmodellen unentgeltlich genutzt und verändert werden können. Der Begriff entstand im Jahre 1998 mit der gegründeten Open Source Initiative (OSI) und prägt seitdem das Bild der Softwareentwicklung.
* Copyleft
	* Copyleft ist eine allgemeine Methode, ein Programm (oder ein anderes Werk) frei (im Sinne von Freiheit, nicht „Nullpreis“) zu machen und zu verlangen, 
dass alle modifizierten und erweiterten Programmversionen ebenfalls frei sind.
* GNU / GPL
	* GNU/GPL ist die am weitesten verbreitete Softwarelizenz, die einem gewährt, die Software auszuführen, zu studieren, zu ändern und zu verbreiten
* Foss=  Free Open Source Software
	* sind freie Software. Jeder ist berechtigt, die Software zuverwenden, kopieren, bearbeiten und änderungen vorzunehmen
* Floss = Free Libre Source Software
	* sind kostenpflichtige Software. Dafür dass es kostet hat es auch dem entsprechend eine höhere Sicherheit und funktioniert auch stabiler
* Urheberrecht
	* Urheberrecht bedeutet dass dem Urheber eines Werks, also dem Autor eines Buchs, Maler eines Bildes, … das Recht zuerkannt wird, als Einziger darüber zu verfügen, was mit dem Werk passiert. Urheber kann Rechte, in Form einer Lizenz, an andere weitergegeben


***

### Kapitel: 1.4 ICT Skills and Working in Linux

**Weight**: 2 (Wert aus Exam 010)

**Beschreibung:** Basic Information and Communication Technology (ICT) skills and working in Linux


**Beispiele und Arbeitsergebnisse**

* Desktop skills: 
    * Privacy concerns: Vor dem Benutzen eines Linux-Rechners müssen Sie sich mit Benutzername und Kennwrt anmelden und hinterher wieder abmelden. Im Desktop-Modus sieht es ähnlich wie bei Windows aus. Im Terminal wird nach dem Benutzername gefragt und dann das Passwort(wenn man das Passwort eintippt bleibt sieht es aus als ob man nichts eingegeben hat)
    * Configuration options: Linux bietet verschiedene Grafikumgebungen an, die zum grössten teil ähnlich und ziemlich intutiv funktionieren. (KDE & GNOME/LXDE & XFCE/Windowsmanger -> wenn man keine komplette Arbeitsumgebung möchte)
    * Using a browser: Firefox & Chrome sthet uns für Linux zur Verfügung genau wie für Windows mit dem unterschied, dass sie anderst heissen(Open-Source-Version).Firefox -> Iceweasel / Chrome -> Chromium. Wie man den Browser öffnet und bedient sollte im klaren sein.
* Getting to the command line:
    * Terminals und Shells: In einem Terminalfenster können Sie in einer Grafikumgebung textuelle Shell-Komandos eingeben. Um Textdateien anzulegen kann man mit den folgenden Editoren die Dateien anlegen oder ändern <vi oder GNU Nano>. GNU Nano ist ein Klon eines Editor namens pico.
* Cloud computing with Linux
	* In Cloud computing und Speicher virtualisation werden die Physikale Ressourcen z.B Prozessor, Ram und Festplatten über das Internet als ein Service zur verfügung gestellt. Das ganze kann mit mehr skalierbarkeit umgesetzt werden in dem Server Komponente Virtualiert werden.Cloud computing stellt dem User eine grosse Menge an Speicher und Performance zur verfügung
* Getting to the commmand line

| Befehl   | Beschreibung                                               |
|----------|------------------------------------------------------------|
| adduser  | Hinzufügen eines Benutzers                                 |
| chsh     | Änderung der Standard-Shell des Benutzers ("change shell") |
| deluser  | Löschung eines Benutzers ("delete user")                   |
| groupadd | Hinzufügen einer Gruppe ("add group")                      |
| groupdel | Löschung einer Gruppe ("delete group")                     |
| groupmod | Bearbeitung einer Gruppe ("modify group")                  |
| id       | Anzeige der Benutzer- und Gruppenkennung (ID)              |
| newgrp   | Änderung der Gruppe des aktuellen Benutzers ("new group")  |
| passwd   | Änderung des Passworts eines Benutzers ("password")        |
| usermod  | Bearbeitung eines Benutzerkontos ("modify user")           |
| chfn     | erweiterte Benutzerinformationen anpassen 


***

### Kapitel: 2.1 Command Line Basics (Status: In Arbeit)

**Weight**: 3 (Wert aus Exam 010)

**Beschreibung** des Unterkapitels, z.B. Basiswissen um mit der Kommandozeile von Linux zu arbeiten.

**Beispiele und Arbeitsergebnisse**

* basic shell

| Befehl            | Beschreibung                                                      |
|-------------------|-------------------------------------------------------------------|
| ls                | Um die Liste aller Dateien oder Ordner zu erhalten.               |
| cd                | um den Verzeichnis zu wechseln.                                   |
| du                | Aktuelle Festplatten Speicher anzeigen.                           |
| pwd               | Zeigt das aktuelle Arbeitsverzeichnis an.                         |
| rmdir             | Löscht ein Verzeichnis wenn es leer ist.                          |
| ln file1 file2    | Erstellt eine physische Verbindung.                               |
| ln -s file1 file2 | Erstellt eine symbolische Verknüpfung.                            |
| chown             | Dient zum Ändern des Dateieigentümers                             |
| chmod             | Used to modify the access/permission of a user.                   |
| man               | Dient zum Ändern des Zugriffs / der Berechtigung eines Benutzers. |

* Command line syntax

| Variabel | Beschreibung                                                                                                                                                                                                                                                                                               |
|----------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| cat      | Zeigt den gesamten Inhalt einer Textdatei an.                                                                                                                                                                                                                                                              |
| more     | Zeigt den gesamten Inhalt einer Textdatei an. Zeigt den Inhalt einer Textdatei bildschirmweise an. Drücke die Leertaste, um zu jedem weiteren Block zu gelangen. |
| less     | Zeigt den Inhalt einer Textdatei bildschirmweise an, jedoch so, dass Sie mit der Aufwärtspfeiltaste eine Sicherungskopie erstellen können.                                                                                                                                                                 |
| file     | Identifiziert Dateien nach Typ (z. B. ASCII-Text, ausführbare Datei, Image, Verzeichnis)                                                                                                                                                                                                                   |

* bash
	* bash ist die GNU/Linux-Standard-Shell. Damit kann man nicht nur einfache Abläufe wie unter DOS mit Batches automatisieren, sonder man kann richtige Programme erstellen.
* echo
	* Mit dem Befehl echo lassen sich Zeichenketten und Variablen zeilenweise auf dem Standardausgabegerät anzeigen


***

### Kapitel: 2.2 Using the Command Line to Get Help

**Weight:** 2

**Beschreibung:** Running help commands and navigation of the various help systems


**Beispiele und Arbeitsergebnisse:**

* man
	* Der Kommando "man" zeigt Handbuchseiten des Sysems an
	* Für die meisten Prgramme gibt es mit man abrufbare Handbuchseiten. Mit dem Kommando "apropo" sucht man in allen Handbuchseiten nach Stichwörtern & "whatis" nach den Namen von Kommandos
* info
	* Zeigt GNU-Info-Seiten auf einem Textterminal an
	* Für manche Programme sind die Infoseiten nur eine Alternative zu Handbuchseiten
* /usr/share/doc/
	* "/usr/share/doc/" ist der Speicherort der paketbezogene Dokumnetationsdateien


***
### Kapitel: 2.3 Using Directories and Listing Files

**Weight:** 2

**Beschreibung:** Navigation of home and system directories and listing files in various locations

* files, directories
	* Linux speichert Daten und Programme in Dateien. Diese sind in Verzeichnissen organisiert. Auf einfache Weise ist ein Verzeichnis nur eine Datei, die andere Dateien enthält.
	*

**Beispiele und Arbeitsergebnisse:**

* files, directories
	* Linux speichert Daten und Programme in Dateien. Diese sind in Verzeichnissen organisiert. Auf einfache Weise ist ein Verzeichnis nur eine Datei, die andere Dateien enthält.
* Hidden files and directories
	* Um versteckte Dateien und Verzeichnisse afuzuzeigen muss den Befehl ls -a für all eingeben
* Home directories
	* Ein Ausgangsverzeichnis, auch Anmeldeverzeichnis genannt, ist das Verzeichnis auf Unix-ähnlichen Betriebssystemen, das als Repository für die persönlichen Dateien, Verzeichnisse und Programme eines Benutzers dient.
* ls

| Variabel          | Beschreibung                                                                            |
|-------------------|-----------------------------------------------------------------------------------------|
| ls                | Dateien des Verzeichnisses anzeigen                                                     |
| ls -f             | Dateien des Verzeichnisses anzeigen                                                     |
| ls -l             | Details von Dateien und Verzeichnissen anzeigen                                         |
| ls -a             | Auflistung von Versteckte Dateien                                                       |
| cd /home          | In das Verzeichnis '/ home eingeben                                                     |
| cd ..             | eine Ebene zurück gehen                                                                 |
| cd ../..          | Zwei Ebenen zurück gehen                                                                |
| cd                | zum Home-Verzeichnis                                                                    |
| cd -              | Zum vorherigen Verzeichnis wechseln                                                     |
| cp file1 file2    | Dateien kopieren                                                                        |
| cp dir/* .        | Kopiert alle Dateien eines Verzeichnisses innerhalb des aktuellen Arbeitsverzeichnisses |
| cp -a /tmp/dir1 . | Kopiert ein Verzeichnis innerhalb des aktuellen Arbeitsverzeichnisses   

***

### Kapitel: 2.4 Creating, Moving and Deleting Files

**Weight:** 2

**Beschreibung:** Create, move and delete files and directories under the home directory

**Beispiele und Arbeitsergebnisse:**

* mv
	* Mit mv kann man eine Datei verschieben. Auch kann man mit diesem Befhel Dateien umbennen.
* cp
	* Mit cp kann man Dateien oder sogar ganze Verzeichnisse kopieren
* rm
	* Mit rm kann man Dateien und komplette Verzeichnisse löschen
* touch
	* Mit touch lassen sich Zugriffs- und Änderungs-Zeitstempel von Dateien ändern
* mkdir
	* Mit mkdir kann man einen oder mehrere Verzeihnisse anlegen
* rmdir
	* Mit rmdir kann man Verzeichniss Löschen welche leer sind.


### Kapitel: 3.1 Archiving Files on the Command Line

**Weight:** 2

**Beschreibung:** Archiving files in the user home directory.

**Beispiele und Arbeitsergebnisse:**

* tar:
    * tar ist ein Befehl unter Linux welcher Dateien/Verzeichnisbäume archivieren. Der Vorteil von tar sind: Die Anwendung ist einfach, zuverlässig dazu ist es universell einsetzbar auf allen Unix- und Linux-Systemen. 
    * Wichtige Optionen sind:
        * -c erzeugt ein neues Archiv
        * -f <Datei> erzuegt oder liest das Archiv von der Datei, wobei dies eine Datei oder ein Gerät sein kann
        * -m  bearbeitet ein tar-Archiv, das sich über mehrere Datenträger erstreckt
* tar options
    * -c erzeugt ein neues Archiv
    * -f <Datei> erzuegt oder liest das Archiv von der Datei, wobei dies eine Datei oder ein Gerät sein kann
    * -m  bearbeitet ein tar-Archiv, das sich über mehrere Datenträger erstreckt
    * -r hängt Dateien an das Archiv an 
    * -t zeigt den Inhalt des Archivs
    * -u ersetzt Dateien, die neuer als eine bereits archivierte Version sind
* gzip, bzip2, xz:
    * gzip: Gzip ist ein Programm welche man mit tar benutzen kann. Gzip ist ein Kompressionprogramm welche Dateien komprimiert und dekomprimiert.
    * bzip2: bzip2 ist auch eine Kopmressionprogramm welche eine höhere Kompressionrate erzeugt als gzip jedoch braucht es mehr Zeit und Speicherplatz als gzip
    * xz: xz ist ein weiteres Kompremierungsprogramm, welcher bersser komprimiert als gzip & bzip2 jedoch benötigt er dafür am längsten.
* zip, unzip:
    * Unter Linux gibt es auch die Programme zip & unzip welche im Windows Umfeld verbreitet ist
    * zip: Das Programm zip kann Archiviereun und Komprimieren (PKZIP)
    * unzip: unzip ist ein Entkomprimierungsprogramm für zip-Archive
    

***

### Kapitel: 3.2 Searching and Extracting Data from Files

**Weight**: 3 

**Vorgehen**, z.B. Installation einer Ubuntu Linux Umgebung. Durcharbeiten ...., Dokumentation der einzelnen Befehle in ...

**Beispiele und Arbeitsergebnisse**
* Command line pipes:
    * Über Pipelines lassen sich die Standard-Aus- und -Eingabe von Programmen direkt miteinander verbinden
* I/O redirection
    * Die I/O Redirection ist eine Funktion, dass bei der Ausführung eines Befehls die Standard-Ein-/Ausgabegeräte ändern kann. Der grundlegende Workflow eines Linux-Befehls besteht darin, dass er eine Eingabe und eine Ausgabe benötigt.
    * Der Standard Input device ist die Tastatur -> stdin
    * Der Standard Output device ist der Bildschirm -> stdout
* grep:
    * dadurch lassen sich Dateien nach bestimmten Textstücken durchsuchen
* less:
    * ist ein Pager zum Anzeigen von Dateien auf der Kommandozeile
* cat:
    * hängt Dateien aneinander
* head:
    * Zeigt den Anfang eine Datei an 
* tail:
    * zeigt das Ende einer Datei an 
* sort:
    * sortiert  die zeilen seiner Eingabe
* cut:
    * extrahiert Felder oder Spalten aus seiner Eingabe
* wc:
    * dient zum Zählen von Wörtern, Zeichen und Bytes in Textdateien


***


### Kapitel: 3.3 Turning Commands into a Script

**Weight**: 4

**Beschreibung** des Unterkapitels, z.B. Basiswissen um mit der Kommandozeile von Linux zu arbeiten.

**Beispiele und Arbeitsergebnisse**

* Basic shell scripting
    * Linux unterstützt beliebige Scriptsprachen. Der 1.Eintrag in einer Datei bestimmt die Scriptsprache #!/bin/bash – Bash Script, #!/usr/bin/node – Node JavaScript
* #! (shebang)
    * #! (shebang) auch gennant hashbang steht am Anfang eines Scripts. Der Grundsatz von Linux, es unterstütz belibige Scriptsprachen. Hier ein Beispiel in dem (shebang) am Anfang des Scripts steht: #!/usr/bin/node
* /bin/bash
    * Auch hier sollte vor /bin/bash ein #! stehen. Wie man hier sieht ist dieses Scirpt ein Bash script. Wie schon oben erwähnt unterstütz Linux beliebige Scriptsprachen 
* Variables
    Auch bei Bash ist es möglich (wie in anderen Programmiersprachen) Text/nummerische Werte in Variabeln abzulegen. Ein Variable wird wie im folgenden Beispiel gesetzt: "bla=fasel". Was man beachten ,uss man darf keine Leerzeichen haben. Dazu unterscheidet man zwischen Umgebungsvariable und Shellvariable.
* Arguments
    * Ein Argument(wird auch Kommandozeilenargument gennant) ist ein Dateiname oder ander Daten, welche einem Befehl zur Verfügung gestellt werden, damit der Befehl ihn als Eingabe verwenden kann. Beispiel: <command> <argument> -> sudo date 08181715 -> hier ist der date der befehl & 08181715 das Argument.
* echo
    * Das Kommando echo gibt seine Argumente aus zum Beispiel:
    
 ```Shell
	$ bla=fasel
    $ echo bla
    bla
```
   
* Exit status
    * Jeder Unix-Prozess liefert einen Rückgabewer, der angibt, ob er korrekt ausgeführt wurde oder ob irgendwelcher Fehler aufgetreten sind. Man kann den Rückgabewert heraufinden, indem man die Variable $? angibt.Hier ein Beispiel mit exit:

```Shell
    $ bash
    $ exit 33
    exit
    $ echo $?
    33
```

***

### Kapitel: 4.1 Choosing an Operating System

**Weight**: 1

**Beschreibung:** Knowledge of major operating systems and Linux distributions

**Beispiele und Arbeitsergebnisse**

* Differences between Windows, OS X and Linux
	* Windows ist das verbreiteste Betriebssystem für Windows. Es wurde von Microsoft entwickelt. Windows muss auf allen möglichen PCs laufen und eine grosse Anzahl von Hardwarekomponenten unterstützen.
	* OS X wird nur mit Apple-Computern verkauft. Somit läuft es nicht auf normalen PCs. Deshlab müssen sie sich nicht um das Problem mit den vielen Hardwarekomponenten.
	* Linux im gegensatz zu Windows & OS X wird nicht nur von einer einzigen Firma entwickelt, sondern an dem viele Freiwillige mitarbeiten. Linux Distributionen erwietern den Linux Beriebsystemkern mit Benutzerprogramme.
* Distribution life cycle management
* GUI versus command line
	* GUI
		* Ein GUI benötigt mehr Systemressource.
		* Ein GUI ist klarer für "einfache" Users -> man lernt schneller wie man ein GUI benutzt
		
	* CLI
		* Ein Computer welche nur CLI verwendet benötigt weniger Systemressourcen des Computer
		* Für CLI braucht man nur eine Tastatur.
		* Ein CLI erfordet meistens, dass Benutzer bereits Skripbefhele und Syntaxe kennen, was für neuen/unerfahrene Benutzer es erschwert Skritpe zu erstellen


***


### Kapitel: 4.2 Understanding Computer Hardware

**Weight**: 2

**Beschreibung:** Familiarity with the components that go into building desktop and server computers

**Beispiele und Arbeitsergebnisse**

* Motherboards
	*  Motherboard ist die zentrale Platine eines Computers. Auf ihr sind die einzelnen Bauteile wie Prozessorsockel, RAM-Steckplätze, der BIOS-Chip mit der integrierten Firmware, Schnittstellen-Bausteine und Steckplätze für Erweiterungskarten 
* processors
	* Der Prozessor ist das herzstück des Computers. Hier findet die automatische programmgesteuerte  Datenverarbeitung statt. 
* optical drives
	* Unter opitsche Laufwere versteht man Medien wie CD-ROm, DVDs welche lesen und unter Umständen auch schreiben können.
* peripherals
	* Unter Pheripheriegeräte versteht man Geräte welche man am Computer anschliessen kann wie zum Beispiel: Kamera, Roborter, Drucker usw...
* /dev/sd*
	* Die devices ohne Number sind die disks: sda,sdb,sdc usw, 
	* Die mit einer Nummer sind Partitionen auf der disk: sda1, sda2, sdc2 usw..
* Drivers
	* Treiber sind Computerprogramme oder Softwaremodule, welche die Kommunikation mit angeschlossene Harware oder virtuellen Geräten steuert. 

***


### Kapitel: 4.3 Where Data is Stored 

**Weight**: 3 

**Beschreibung** Where various types of information are stored on a Linux system

**Beispiele und Arbeitsergebnisse**

Key Knowledge Areas:

* ps
	* zeigt alle laufende Prozesses an
		* wichtigste Optionen
			* -a: von anderen benutzer
			* -e: Umgebungsvariabeln jedes Prozesses
			* -f: anzeige einer Baumstruktur
			* -u: anzeige des Eigentümers
* top
	* top zeigt eine dynamische Übersicht der auf dem System laufenden Prozesses und die Systemressourcen
		* wichtigste Optionen
			* -c: Zeigt das vollständige Kommando inklusive Pfadangaben an 
			* -i: Prozesses, welche den Status "idle" besitzen, werden nicht angezeigt
			* -s: zeigt die absolute Zeit an, seit der Prozess gestartet wurde
* free
	* zeigt die momentane Speicherbelgung an
		* wichtigsten Optionen
			* -t: anzeige einer Zeile mit Gesamtübersichten
			* -v: zeigt Versioninfomationen an
			* -h: zeigt alle Werte in automtaisch in GiB, MiB oder KiB an 
			
* syslog
	* Syslog-Dienst ist zuständig für das Systemprotokoll. Das Programm "syslogd" nimmt die Nachrichten von den Programmen entgegen und sortiert dieses anhand  iherer Herkunft und Priorität in Datein in "/var/log" ein. Dazu kann der Syslog-Dienst die nachrichten über das Netz an einen anderen Rechner(z.B Syslog-Server).
* dmesg
	* Gibt den Inhalt des Kernel-Nachrichtenpuffers aus
	* Der Linux-Betriebssystemkern erstellt jede Menge Nachrichten aus,bevor das System überhaupt so weit ist, dass syslogd läuft und diese Nachrichten tatsächlich entgegennehmen kann. Da die Nachrichten trotzdem wichtig sein können, speichert der Linux-Kern sie intern ab, und man kann mit dem Kommando dmesg zugreifen
* /etc/
	* Dieses Verzeichnis beinhaltet Konfigurationdateien für die allermeisten Dateien.
* /var/log/
	* Unter "/var/log" werden Anmelde- und Abmeldevorgänge sowie andere Systemereignisse protokolliert
* /boot/
	* In diesm Verzeichnis liegt das Betriebsystem, ausserdem befinden sich Dateien, die für den Bootlader wichtig sind
		* /boot/grub/menu.lst
			* Unter "/boot/grub/menu.lst" befindet sich die zentrale Konfigurationsdatei von GRUB Legacy. Hier werden die Grundeinstellungen vorgenommen und die einzelnen zu bootenden Betriebssysteme festgelegt und konfiguriert.
* /proc/
	* "/proc/" ist eines der wichtisten Verzeichnisse."/proc/" ist eigentlich ein Pseudo-Dateisystem. In diesem Verzeichniss findet man sämtliche Informationen zu den laufenden Prozessen und weitere Informationen, die der Kernel über die Hardware des Rechners besitzt.
* /dev/
	* In diesem Verzeichnis findet sich eine Unmenge von Einträgen für die Gerätedateien. Gerätedateien bilden die Schnittstellen von der Shell zu den Gerätetreibern im Systemkern. Sie haben keinen Inhalt wie andere Dateien , sondern verweisen über Gerätenummern auf einen Treiber im Systemkern
* /sys
	* Dieses Verzeichnis findet man im Linux Kernel ab der Version 2.6. Dieses Verzeichnis ist ähnlich wie /proc. Es ist für die Hardwaresteuerung zuständig

***

### Kapitel: 4.4 Your Computer on the Network

**Weight**: 2 

**Beschreibung** Querying vital networking configuration and determining the basic requirements for a computer on a Local Area Network (LAN)

**Beispiele und Arbeitsergebnisse**


* route 
	* mit dem Kommando "route" kann man die Routing-tabelle abrufen
* ifconfig / ip addr show
	* Mit diesen beiden Befehlen kann man die IP-Adresse, Netzmaske, Gateway usw. herausfinden. Ein Host kann auch mehrere IP-Adressen haben, wenn es mehrere Schnittstellen hat
* netstat
	* netstat ist ein Diagnosewerkzeug, mit dem man verschieden Informationen über den Status der Netzwerkschnittstellen in Erfahrung bringen kann. Das heisst man kann sehen welche Dienste auf dem host laufen & welche nicht usw.	
* ss
	* Ist ein Alternativ Programm für netstat und gehört zu dem Paket iproute
* /etc/resolv.conf 
	* Programme auf einem Linux Rechner reden nicht direkt mit dem DNS, sondernüber den Resolver. Die Konfigurationdatei für den Resolver ist "/etc/resolv.conf". 
* /etc/hosts
	* Diese Datei ist eine der Konfigurationdatein des TCP/IP Netzwerks. Dadrin werden die Namen der Netzwerkrechner meiner IP-Adressen zugeordnet. Kann in kleinen Netzwerken den Name-Server ersetzen.
* IPv4
	* Eine IPv4 besteht aus 4 Oktetten. Damit sind 2 hoch 32 Adressen darstellbar.
* IPv6
	* Mit IPv6 kann man 2 hoch 128 Adressen darstellen.
* ping
	* Mit "ping" kann man die Erreichbarkeit von hosts prüfen

***

### Kapitel: 5.1 Basic Security and Identifying User Types

**Weight**: 2 

**Beschreibung** Various types of users on a Linux system

**Beispiele und Arbeitsergebnisse**

* /etc/passwd
	* Die Datei "/etc/passwd" ist die zentrale Benutzerdatenbank. Jeder Benutzer auf dem System hat einen Eintrag in dieser Datei
* /etc/shadow
	* Bei fast allen aktuellen Linux-Distributinen die Benuterkennwörter in verschlüsselter Form in der Datei /etc/shadow gespeichert. Diese Datei kann nur root und Mitglieder der Gruppe shadow lesen/schreiben.
* /etc/group
	* Diese Datei hinterlegt die Gruppeninformationen. Jede Gruppe enthält einen einzeiligen Eintrag.
* id
	* Jeder Proezess, User, Gruppe, host usw. hat eine ID 
* last
	* Der Befehl last erstell eine Liste der erfolgreichen Login und Logouts jedoch muss man die Datei /var/log/wtmp anlegen, welche nicht auf jeden Linux System automatisch erstellt wird.
* who
	* Zeigt die Inofmationen des angemeldeten Benutzer an
* w
	* Gibt Ansukungt überdie Benutzer, die am System angmeldet sind.
* sudo
	* ist die erweiterte Rechte. Dies braucht man z.B für chown
* su
	* hat die gleiche Funktion wie sudo
	
***

### Kapitel: 5.2 Creating Users and Groups

**Weight**: 2 

**Beschreibung** Creating users and groups on a Linux System

**Beispiele und Arbeitsergebnisse**

* /etc/passwd
	* Die Datei "/etc/passwd" ist die zentrale Benutzerdatenbank. Jeder Benutzer auf dem System hat einen Eintrag in dieser Datei
* /etc/shadow
	* Bei fast allen aktuellen Linux-Distributinen die Benuterkennwörter in verschlüsselter Form in der Datei /etc/shadow gespeichert. Diese Datei kann nur root und Mitglieder der Gruppe shadow lesen/schreiben.
* /etc/group
	* Diese Datei hinterlegt die Gruppeninformationen. Jede Gruppe enthält einen einzeiligen Eintrag.
* useradd
	* Mit dem Befehl adduser legt man neue Benutzer an 
* groupadd
	* Mit dem Befehl groupadd legt man eine neue Gruppe an
* passwd
	* passwd ändert die Passwörter eines benutzers oder einer ganzen Gruppe

***

### Kapitel: 5.3 Managing File Permissions and Ownership

**Weight**: 2 

**Beschreibung** Understanding and manipulating file permissions and ownership settings

**Beispiele und Arbeitsergebnisse**

* ls -l
	* Datei-Information in Langrom werden ausgegeben 
* ls -a
	* listet alle Dateien, auch versteckte Dateien und Verzeichniseinträge wie . und .. auf
* chmod
	* Mit "chmod" kann man die Zugriffrechte einer Datei verändern
* chown
	* Mit "chown" kann man den Eigentümerbenutzer/Eigentümergruppe von Dateien ändern
	
***

### Kapitel: 5.4 Special Directories and Files

**Weight**: 1

**Beschreibung** Special directories and files on a Linux system including special permissions

**Beispiele und Arbeitsergebnisse**


* /tmp/
	* Viele Dienstprogramme brauchen tempöreren Speicherplatz. Viele Distributionen löschen beim Booten alle Dateien unterhalb dieses Verzeichnisses deshalb sollte man nichts auf Dauer dort speichern 
* /var/tmp/
	* Nach dem Booten werden hier die Dateien nicht gelöscht. 
* Sticky Bit
	* Programmdateien, aufd denen das sticky bit gesetzt war, wurden nach dem Programmende im Swap-Speicher liegen gelassen somit beschleunigte man den Startvorgran für das Programm, weil der anfängliche Kopiervorgang entfiel 
* ls -d
	* Zeigt Verzeichnisse und keine Inhalte an
* ln -s
	* erzeugt eine symbolische Verknüpfung anstatt eines Hardlinks


	
			
## Links
* https://wiki.ubuntuusers.de/Startseite/
* [Linux Essentials Exam 010](htt://www.lpi.org/our-certifications/exam-010-objectives)
* [E010 Dokumentation](https://github.com/w901-fr19-mi/E010) 
* [myE010 Original Repository](https://github.com/w901-fr19-mi/myE010)

