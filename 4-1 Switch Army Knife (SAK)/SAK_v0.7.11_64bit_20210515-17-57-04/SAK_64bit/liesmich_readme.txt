################################################################################################################################
### DEUTSCHE BESCHREIBUNG
################################################################################################################################

********************************************************************************************************************************
*** Switch Army Knife (SAK) by kempa - Mai 2021
********************************************************************************************************************************

Version: beta v0.7.11
Ver�ffentlicht auf psxtools.de

ICH (kempa) �bernehme keine Verantwortung f�r Sch�den/Bricks jeglicher Art.
Die durch XCI's oder bei der sp�teren Installation auf der Switch von NSP's auftreten k�nnen!
Nutzt stets eure eigenen Spiele, die ihr auch legal besitzt!
So habt ihr sp�ter auch keine Probleme.

*** Ich unterst�tze kein Warez!!! ***

********************************************************************************************************************************

Urheberrecht:
Der Code wurde komplett von mir pers�nlich entwickelt.
So kann das Tool v�llig frei und legal angeboten werden!

Voraussetzung daf�r:
Das 7zip Archiv darf nicht ver�ndert werden
Immer mit Quellenangabe zum original Forum-Thread (siehe nachfolgenden Support Link)

Wichtige Infos: (hinzugef�gte Tools die nicht von mir sind):
4NXCI (4nxci.exe) - Hier gilt das Danke an The-4n und SciresM f�r die Entwicklung und das bereitstellen des Tools.
Quelle: https://github.com/The-4n/4NXCI

hacBrewPack / hptnacp (hacbrewpack.exe / hptnacp.exe) - Hier gilt das Danke an The-4n f�r die Entwicklung und das bereitstellen des Tools.
Quelle: https://github.com/The-4n/hacBrewPack

switchbrew (nx-hbloader) - Hier gilt das Danke an switchbrew Team, R-YaTian und HookedBehemoth f�r die Entwicklung und das bereitstellen des nx-hbloader/forks.
Quelle: https://github.com/switchbrew/nx-hbloader
Quelle: https://github.com/R-YaTian/nro-forwarder
Quelle: https://github.com/HookedBehemoth/nx-hbloader
Quelle: https://github.com/dezem/nx-hbloader

FAT32 Format (guiformat.exe) - Danke geht an Ridgecrop Consultants Ltd f�r die GUI Version vom FAT32 Format Tool.
Quelle: http://www.ridgecrop.demon.co.uk/index.htm?guiformat.htm

hactool (hactool.exe) - Hier gilt das Danke an SciresM f�r die Entwicklung und das bereitstellen des Tools.
Quelle: https://github.com/SciresM/hactool

NSC_BUILDER (squirrel.exe) - Hier gilt das Danke an julesontheroad f�r die Entwicklung und das bereitstellen des Tools.
Quelle: https://github.com/julesontheroad/NSC_BUILDER

LibHac (hactoolnet.exe) - Hier gilt das Danke an Thealexbarney f�r die Entwicklung und das bereitstellen des Tools.
https://github.com/Thealexbarney

reNXpack (renxpack.exe) - Hier gilt das Danke an The-4n und SciresM f�r die Entwicklung und das bereitstellen des Tools.
Quelle: https://github.com/The-4n/reNXpack

********************************************************************************************************************************

Support: Auf psxtools.de (https://psxtools.de/index.php/Thread/77281)

********************************************************************************************************************************
*** Funktionen
********************************************************************************************************************************

Mit diesem Switch Taschenmesser k�nnt ihr eure Inhalt XCI/NSP von eurer Switch einfach jonglieren.

- XCI patchen
- XCI splitten / zusammenf�gen
- Update XCI mit Spiele update + DLC's
- XCI nach NSP konvertieren
- Komprimiere XCI nach XCZ
- Dekomprimiere XCZ nach XCI
- Firmware von XCI entpacken
- NSP patchen
- NSP splitten / zusammenf�gen
- Update NSP mit Spiele update + DLC's
- NSP nach XCI konvertieren
- Komprimiere NSP nach NSZ
- Dekomprimiere NSZ nach NSP
- Extrahiere deine Switch Savegames diese du von der User Partition kopiert hast
- Erstelle NRO forwarder als installierbare NSP Datei
- SD Karte in FAT32 formatieren

*** Generell gilt:
Alle Dateien werden immer im Ordner von SAK erstellt.
Es werden nur XCI + NSP Dateien >= 4GB zum splitten akzeptiert.
Alle < 4GB macht dass splitten ja auch kein Sinn!

***  F�r XCI auf niedrige FW patche gilt:
keys.dat/prod.keys wird ben�tigt
Datei muss in XCI vorliegen

*** F�r XCI splitten gilt:
XCI k�nnen in voller Gr��e oder getrimmt gesplittet werden.
Getrimmt bedeutet, dass der leere Speicherplatz am Ende entfernt wird.
Dadurch gibt es einen kleinen Speicherplatz gewinn f�r das XCI Abbild.

Der neue Dateiname wird mit "_splitted" erg�nzt.

K�nnen auch direkt auf die �SD Karte via USB Reader gesplittet werden.

*** XCI zusammenf�gen gilt:
Dateiendungen.xc0 und .xci.00 werden akzeptiert

*** Update XCI mit Spiele Update gilt:
Dein gedumptes Spiel als XCI, neuste Update als NSP/NSZ und optional deine gedumpten DLC's als NSP

*** F�r XCI nach NSP konvertieren gilt:
keys.dat/prod.keys wird ben�tigt
Wie ihr die von euerer Switch erhaltet, schaut dazu hier vorbei
psxtools.de/index.php/Thread/76547

** F�r XCI nach XCZ komprimieren gilt:
keys.dat/prod.keys wird ben�tigt
Wie ihr die von euerer Switch erhaltet, schaut dazu hier vorbei
psxtools.de/index.php/Thread/76547

** F�r XCZ nach XCI dekomprimieren gilt:
keys.dat/prod.keys wird ben�tigt
Wie ihr die von euerer Switch erhaltet, schaut dazu hier vorbei
psxtools.de/index.php/Thread/76547

*** F�r Firmware entpacken gilt:
keys.dat/prod.keys wird ben�tigt
Datei muss in XCI vorliegen

***  F�r NSP auf niedrige FW patche gilt:
keys.dat/prod.keys wird ben�tigt
Datei muss in NSP vorliegen

*** F�r NSP splitten gilt:
Die gesplitteten Dateien werden in einem Ordner mit fortlaufender Nummer abgelegt.
Als Bezug f�r den Ordnername, wird der aktuelle NSP Dateiname genommen und mit "splitted" erg�nzt

K�nnen nun auch direkt auf die �SD Karte via USB Reader gesplittet werden.

Das Archivbit wird automatisch gesetzt.

** F�r NSP zusammenf�gen gilt:
Dein gesplittete NSP (00).
Alle anderen werden automatisch gew�hlt.

*** Update NSP mit Spiele Update gilt:
Dein gedumptes Spiel als NSP, neuste Update als NSP/NSZ und optional deine gedumpten DLC's als NSP

*** F�r NSP nach XCI konvertieren gilt:
nur Spiele unterst�tzt
keys.dat/prod.keys wird ben�tigt
Wie ihr die von euerer Switch erhaltet, schaut dazu hier vorbei
psxtools.de/index.php/Thread/76547

** F�r NSP nach NSZ komprimieren gilt:
keys.dat/prod.keys wird ben�tigt
Wie ihr die von euerer Switch erhaltet, schaut dazu hier vorbei
psxtools.de/index.php/Thread/76547

** F�r NSZ nach NSP dekomprimieren gilt:
keys.dat/prod.keys wird ben�tigt
Wie ihr die von euerer Switch erhaltet, schaut dazu hier vorbei
psxtools.de/index.php/Thread/76547

*** F�r Saves extrahiere gilt:
keys.dat/prod.keys wird ben�tigt
Wie ihr die von euerer Switch erhaltet, schaut dazu hier vorbei
psxtools.de/index.php/Thread/76547
Dein save Ordner von der User Partition (HacDiskMount oder via Homebrew Tool)
Mittels HacDiskMount, schaut dazu hier vorbei
psxtools.de/index.php/Thread/80260

*** NRO forwarder:
keys.dat/prod.keys wird ben�tigt
Wie ihr die von euerer Switch erhaltet, schaut dazu hier vorbei
psxtools.de/index.php/Thread/76547
icon als jpg/jpeg Aufl�sung 256x256
Um eigene startup Logos zu nutzen, erstelle einen Ordner "custom" bei der SAK.exe.
Platziere hier die Dateien als "NintendoLogo.png" und "StartupMovie.gif".
Als Beispiel schaue in den "bin" Ordner.

*** FAT32 Format:
Wenn du beim formatieren der SD Karte einen Fehler erh�lst.
(Failed to opene device) vergewissere dich, dass nichts auf die SD zugreift.
Schon alleine der ge�ffnete Windows Explorer reicht hierzu aus.

So sollte es immer gehen:
Starte FAT32 Format und stecke jetzt erst die SD Karte in Kartenleser.
Danach die SD Karte ausw�hlen und formatieren klicken.

********************************************************************************************************************************
*** �nderungshistorie
********************************************************************************************************************************

Beta v0.2.1: (25.11.2018)
Mit diesem Tool k�nnt ihr eure eigenen NSP Files f�r FAT32 SD-Karten splitten.
Damit ihr diese auf eurer Switch �ber die SD-Karte einfach installieren k�nnt.

- Es werden nur NSP Dateien >= 4GB akzeptiert.
  Alle < 4GB macht dass splitten ja auch kein Sinn! ;-)

- Die gesplitteten Dateien werden in einem Ordner mit fortlaufender Nummer abgelegt.
  Als Bezug f�r den Ordnername, wird der aktuelle NSP Dateiname genommen und mit "splitted" erg�nzt

- Das Archivbit wird automatisch gesetzt.

Beta v0.3: (26.11.2018)
- Mehrfachauswahl f�rs splitten nun m�glich

- Freier Speicherplatz wird bei jedem Titel vorher gepr�ft

Beta v0.4: (01.12.2018)
- Direktes splitten auf die SD-Karte

Beta v0.5: (12.12.2018)
- XCI teilen
- XCI zusammenf�gen
- XCI in NSP konvertieren (keys.dat erforderlich)
- FAT32 Format eingef�gt
- Update Funktion

Beta v0.5.1: (18.12.2018)
- M�glichkeit prod.keys f�r 4NXCI zu verwenden
- *please wait* Nachricht beim konvertieren von XCI nach NSP

Beta v0.6: (28.12.2018)
- Entpacke Firmware Update aus XCI
- XCI in NSP konvertieren Anpassungen:
  - Dateiname automatisch umbenannt
  - M�glichkeit direkt f�r FAT32 zu splitten
  - M�glichkeit direkt auf USB zu splitten

Beta v0.6.1: (04.01.2019)
- kleine Korrekturen und Optimierungen

Beta v0.6.2: (05.01.2019)
- Korrektur f�rs konvertieren XCI -> NSP immer in den SAK Ordner

Beta v0.6.2.1: (05.01.2019)
- Kleine Korrektur f�rs ausf�hren bei 4nxci

Beta v0.6.3: (26.01.2019)
- 4nxci update auf neue Version 3.0
- 4nxci freier Speicherplatz wird vor konvertieren gepr�ft
- Entpacke FW freier Speicherplatz wird vorher gepr�ft
- Anzeige der ben�tigten Zeit f�r den gesammten Prozess
- Erzwungene Administratorberechtigungen wurden von SAK entfernt.
  Falls du Probleme haben solltest, so starte SAK als Administrator!

Beta v0.6.3.1: (29.01.2019)
- 4nxci update auf neue Version 3.01
- Beim konvertieren von XCI nach NSP wird die Funktion f�r die Titelbenennung von 4nxci genutzt

Kleines Update: (01.02.2019)
- 4nxci update auf neue Version 3.05

Kleines Update: (05.02.2019)
- 4nxci update auf neue Version 3.06

Kleines Update: (12.03.2019)
- 4nxci update auf neue Version 4.0

Beta v0.6.4: (25.03.2019)
- Beim konvertieren von XCI nach NSP
  Ausgabe von Fehlermeldung f�r fehlerhafte/fehlende Eintr�ge in der prod.keys

Beta v0.6.4.1: (26.03.2019)
- Fix f�r falsche Meldung von fehlerhafte/fehlende Eintr�ge in der prod.keys beim XCI nach NSP konvertieren

Kleines Update: (01.04.2019)
- 4nxci update auf neue Version 4.01

Beta v0.6.5: (12.04.2019)
- kleine Fehlerbehebungen f�r SAK
- Neue Funktion hinzugef�gt NSP auf niedrige Firmware patchen

Beta v0.6.5.1: (21.04.2019)
- kleine �nderungen f�r reNXpack in SAK
- 4nxci update auf neue Version 4.03
- reNXpack update auf neue Version 1.16

Beta v0.6.6: (23.06.2019)
- Neue Funktion hinzugef�gt NSP nach XCI konvertieren

Kleines Update: (10.07.2019)
- NSC_BUILDER (nur squirrel.exe) update auf neue Version 0.87c

Beta v0.6.7: (05.09.2019)
- Neue Funktion hinzugef�gt extrahiere Saves von der User Partition
- NSC_BUILDER (nur squirrel.exe) update auf neue Version 0.89b

Beta v0.6.8: (01.10.2019)
- Neue Funktion hinzugef�gt update XCI mit Spiele Update
- Neue Funktion hinzugef�gt NSP zusammenf�gen

Beta v0.6.8.1: (04.10.2019)
- Fix falsche gui Titel
- NSC_BUILDER (nur squirrel.exe) update auf neue Version 0.90d

Beta v0.6.8.2: (13.10.2019)
- Kleiner fix Update XCI
- NSC_BUILDER (nur squirrel.exe) update auf neue Version 0.93

Beta v0.7: (21.10.2019)
- SAK Haupt GUI �berarbeitet
- SAK Logo hinzugef�gt
- Neue Funktion hinzugef�gt komprimiere XCI nach XCZ
- Neue Funktion hinzugef�gt komprimiere NSP nach NSZ
- hactoolnet update auf neue Version 0.6.0
- NSC_BUILDER (nur squirrel.exe) update auf neue Version 0.95

Beta v0.7.1: (26.10.2019)
- �nderungen bei XCI merge Unterst�tzung f�r 00 gesplittete Dateien
- Neue Funktion hinzugef�gt dekomprimiere XCZ nach XCI
- Neue Funktion hinzugef�gt dekomprimiere NSZ nach NSP
- Code Bereinigung

Beta v0.7.2: (17.11.2019)
- NSC_BUILDER (nur squirrel.exe) update auf neue Version 0.96c
- Splash Screen zu SAK hinzugef�gt

Beta v0.7.3: (22.11.2019)
- �nderungen bei Update XCI mit Spiele Update + DLC's (Mehrfachauswahl m�glich)

Beta v0.7.3.1: (02.12.2019)
- Kleiner fix bei extrahiere Saves
- hactoolnet update auf neue Version 0.7.0
- NSC_BUILDER (nur squirrel.exe) update auf neue Version 0.96d

Kleines Update: (19.12.2019)
- NSC_BUILDER (nur squirrel.exe) update auf neue Version 0.97

Beta v0.7.4: (05.01.2020)
- Neue Funktion hinzugef�gt update NSP mit Spiele Update
- hactoolnet update auf neue Version 0.8.0

Kleines Update: (07.01.2020)
- hactoolnet update auf neue Version 0.8.1

Kleines Update: (20.01.2020)
- hactool update auf neue Version 1.3.0
- NSC_BUILDER (nur squirrel.exe) update auf neue Version 0.98b

Kleines Update: (22.02.2020)
- hactool update auf neue Version 1.3.1

Kleines Update: (14.04.2020)
- hactool update auf neue Version 1.3.3
- hactoolnet update auf neue Version 0.10.0

Beta v0.7.5: (11.06.2020)
- �nderungen update NSP/XCI mit Spiele Update unterst�tz nun Updates als NSZ
- Neue Funktion hinzugef�gt XCI auf niedrige Firmware patchen
- hactool update auf neue Version 1.4.0
- hactoolnet update auf neue Version 0.11.3

Beta v0.7.6: (26.10.2020)
- �nderungen _patch wird beim patchen von XCI oder NSP angef�gt
- NSC_BUILDER (nur squirrel.exe) update auf neue Version 1.01b
- hactoolnet update auf neue Version 0.12.0

Beta v0.7.7: (31.12.2020)
- Fix beim patchen von NSP mit anf�gen von _patch
- NSC_BUILDER (nur squirrel.exe) auf alte version 0.98b

Beta v0.7.8: (04.05.2021)
- Neue Funktion hinzugef�gt NRO forwarder erstellen

Beta v0.7.9: (05.05.2021)
- Funktion hinzugef�gt Retroarch Core forwarder erstellen

Beta v0.7.10: (14.05.2021)
- Funktion hinzugef�gt �ndern der Versionsnummer im forwarder
- Funktion hinzugef�gt erlaube/verbiete Screenshots im forwarder
- Funktion hinzugef�gt aktiviere/deaktiviere Videoaufnahme im forwarder

Beta v0.7.11: (15.05.2021)
- Fix einige HB-Tools nicht als forwarder gehen

********************************************************************************************************************************
*** Switch Army Knife in Betrieb nehmen
********************************************************************************************************************************

Voraussetzung:
- Windows PC
- Gedumpte keys.dat/prod.keys von deiner Switch Konsole - um deine Keys zu bekommen schaue hier -> (https://psxtools.de/index.php/Thread/76547)

7zip entpacken:
- Switch keys (keys.dat/prod.keys) im "bin" Ordner bei der 4nxci.exe ablegen
- fertig

################################################################################################################################
### ENGLISH DESCRIPTION
################################################################################################################################

********************************************************************************************************************************
*** Switch Army Knife (SAK) by kempa - May 2021
********************************************************************************************************************************

Version: beta v0.7.11
Published on psxtools.de

I (kempa) take no responsibility for damages/bricks of any kind.
Which can occur from XCI's or during the installation of the NSP's on the switch!
Always use your own games, which you legally own!
So you have no problems later.

*** I don't support warez !!! ***

********************************************************************************************************************************

Copyright:
The code was completely developed by me.
So the tool can be published completely free and legal!

Prerequisite for this:
The 7zip archive must not be changed
Always with reference to the original forum thread (see Support Link below)

Important notices: (included tools that are not from me):
4NXCI (4nxci.exe) - The respect goes to The-4n and SciresM for developing and providing the tool.
Source: https://github.com/The-4n/4NXCI

hacBrewPack / hptnacp (hacbrewpack.exe / hptnacp.exe) - The respect goes to The-4n for developing and providing the tool.
Source: https://github.com/The-4n/hacBrewPack

switchbrew (nx-hbloader) - The respect goes to switchbrew Team, R-YaTian and HookedBehemoth for developing and providing the nx-hbloader/forks.
Source: https://github.com/switchbrew/nx-hbloader
Source: https://github.com/R-YaTian/nro-forwarder
Source: https://github.com/HookedBehemoth/nx-hbloader
Source: https://github.com/dezem/nx-hbloader

FAT32 Format (guiformat.exe) - Thanks goes to Ridgecrop Consultants Ltd for FAT32 Format as GUI version
Source: http://www.ridgecrop.demon.co.uk/index.htm?guiformat.htm

hactool (hactool.exe) - The respect goes to SciresM for developing and providing the tool.
Source: https://github.com/SciresM/hactool

NSC_BUILDER (squirrel.exe) - The respect goes to julesontheroad for developing and providing the tool.
Source: https://github.com/julesontheroad/NSC_BUILDER

LibHac (hactoolnet.exe) - The respect goes to Thealexbarney for developing and providing the tool.
https://github.com/Thealexbarney

reNXpack (renxpack.exe) - The respect goes to The-4n and SciresM for developing and providing the tool.
Source: https://github.com/The-4n/reNXpack

********************************************************************************************************************************

Support: On psxtools.de (https://psxtools.de/index.php/Thread/77281)

********************************************************************************************************************************
*** Functions
********************************************************************************************************************************

With Switch Army Knife you can easily juggle XCI / NSP content from your switch.

- Patch XCI
- Split / merge XCI
- Update XCI with game update and dlc's
- Convert XCI to NSP
- Compress XCI to XCZ
- Decompress XCZ to XCI
- Extract Firmware from XCI
- Patch NSP
- Split / merge NSP
- Update NSP with game update and dlc's
- Convert NSP to XCI
- Compress NSP to NSZ
- Decompress NSZ to NSP
- Extracting Switch savegames which you have copied from your User partition
- Create NRO forwarder as installable NSP file
- Format the SD card in FAT32

*** Generally:
All files are always created in the folder of SAK.
Only XCI + NSP files >= 4GB are accepted for splitting.
All files < 4GB makes splitting no sense!

***  Patch XCI to lower firm:
keys.dat / prod.keys is required
File must be as XCI

*** Split XCI:
XCI can be split in full size or trimmed.
Trimmed means that the empty space at the end will be removed.
This will saves you a lot of space for the XCI image.

The new file name will be append with "_splitted".

Can also be split directly to the ?SD card over the USB card reader.

*** Merge XCI:
Extensions.xc0 and .xci.00 are accepted

*** Update XCI:
Needed your dumped game as XCI, the latest update as NSP/NSZ optionally your dumped DLC's as NSP

*** Converting XCI to NSP:
keys.dat / prod.keys is required
How to get the keys from your switch, look here psxtools.de/index.php/Thread/76547

*** Compress XCI to XCZ:
keys.dat / prod.keys is required
How to get the keys from your switch, look here psxtools.de/index.php/Thread/76547

*** Decompress XCZ to XCI:
keys.dat / prod.keys is required
How to get the keys from your switch, look here psxtools.de/index.php/Thread/76547

*** Firmware extraction:
keys.dat / prod.keys is required
File must be as XCI

***  Patch NSP to lower firm:
keys.dat / prod.keys is required
File must be as NSP

*** Split NSP:
The split files are stored in a folder with a sequential number.
As reference for the folder name, the current NSP file name is taken and added with "splitted"

Can now be split directly to the ?SD card over USB card reader.

The archive bit is set automatically.

** Merge NSP:
Your splitted NSP only select the (00) file.
All others are automatically selected.

*** Update NSP:
Needed your dumped game as NSP, the latest update as NSP/NSZ optionally your dumped DLC's as NSP

*** Converting NSP to XCI:
only games supported
keys.dat / prod.keys is required
How to get the keys from your switch, look here psxtools.de/index.php/Thread/76547

*** Compress NSP to NSZ:
keys.dat / prod.keys is required
How to get the keys from your switch, look here psxtools.de/index.php/Thread/76547

*** Decompress NSZ to NSP:
keys.dat / prod.keys is required
How to get the keys from your switch, look here psxtools.de/index.php/Thread/76547

*** Extracting saves:
keys.dat / prod.keys is required
How to get the keys from your switch, look here psxtools.de/index.php/Thread/76547
Your save folder from the User partition (HacDiskMount or Homebrew Tool)
By HacDiskMount, look here psxtools.de/index.php/Thread/80260

*** NRO forwarder:
keys.dat / prod.keys is required
How to get the keys from your switch, look here psxtools.de/index.php/Thread/76547
icon as jpg/jpeg resolution 256x256
To use your own startup logo, create a dir called "custom" near SAK.exe.
And place there your files as "NintendoLogo.png" and "StartupMovie.gif".
For example look at "bin" dir.

*** FAT32 Format:
If you get an error when formatting the SD card.
(Failed to open device) make sure nothing access the SD card.
Already opening the windows explorer is enough to get the error.

This is how it should always be:
Start FAT32 Format and now insert the SD card in the card reader.
Then select the SD card and format it.

********************************************************************************************************************************
*** Changelog
********************************************************************************************************************************

Beta v0.2.1: (25.11.2018)
With this tool you can split your own NSP files for FAT32 SD cards.
So you can easily install them on your switch via the SD card.

- Only NSP files >= 4GB are accepted.
  All < 4GB files makes no sense to split! ;-)

- The splitted files are stored in a folder with a sequential number.
  As reference for the folder name, the current NSP file name is taken and added with "splitted"

- The archive bit is set automatically.

Beta v0.3: (26.11.2018)
- Multiple selection for splitting is now possible

- Free space will be checked for each title

Beta v0.4: (01.12.2018)
- Directly splitting on the sd-card

Beta v0.5: (12.12.2018)
- XCI split
- XCI merge
- XCI to NSP converting (keys.dat required)
- FAT32 Format implemented
- Update feature

Beta v0.5.1: (18.12.2018)
- possibility to use prod.keys for 4NXCI
- added *please wait* message at converting XCI to NSP process

Beta v0.6: (28.12.2018)
- Extract firmware update from XCI
- XCI to NSP converting changes:
  - filename auto renaming
  - possibility to directly split for FAT32
  - possibility to directly split to USB

Beta v0.6.1: (04.01.2019)
- small fixes and optimizations

Beta v0.6.2: (05.01.2019)
- fix for converting XCI -> NSP always to SAK folder

Beta v0.6.2.1: (05.01.2019)
- small fix for 4nxci execution

Beta v0.6.3: (26.01.2019)
- 4nxci update to new version 3.0
- 4nxci check free disk space before converting
- Extract FW from XCI check free disk space
- Show needed time for the complete action
- Removed required administrator rights from SAK
  If you have problems, run SAK as administrator!

Beta v0.6.3.1: (29.01.2019)
- 4nxci update to new version 3.01
- At converting process XCI to NSP now using titelnaming feature from 4nxci

Small update: (01.02.2019)
- 4nxci update to new version 3.05

Small update: (05.02.2019)
- 4nxci update to new version 3.06

Small update: (12.03.2019)
- 4nxci update to new version 4.0

Beta v0.6.4: (25.03.2019)
- At converting process XCI to NSP
  Output failure message for incorrect/missing entries in prod.keys

Beta v0.6.4.1: (26.03.2019)
- Fix for wrong incorrect/missing prod.keys message at XCI to NSP converting

Small update: (01.04.2019)
- 4nxci update to new version 4.01

Beta v0.6.5: (12.04.2019)
- small fixes for SAK
- Added new feature patch nsp to lower firm

Beta v0.6.5.1: (21.04.2019)
- small changes for reNXpack at SAK
- 4nxci update to new version 4.03
- reNXpack update to new version 1.16

Beta v0.6.6: (23.06.2019)
- Added new feature NSP to XCI converting

Small update: (10.07.2019)
- NSC_BUILDER (only squirrel.exe) update to new Version 0.87c

Beta v0.6.7: (05.09.2019)
- Added new feature extract saves form the User partition
- NSC_BUILDER (only squirrel.exe) update to new Version 0.89b

Beta v0.6.8: (01.10.2019)
- Added new feature update XCI with game update
- Added new feature merge NSP

Beta v0.6.8.1: (04.10.2019)
- Fix wrong gui titles
- NSC_BUILDER (only squirrel.exe) update to new Version 0.90d

Beta v0.6.8.2: (13.10.2019)
- Small fix Update XCI
- NSC_BUILDER (only squirrel.exe) update to new Version 0.93

Beta v0.7: (21.10.2019)
- Redesign SAK Main GUI
- Added SAK logo
- Added new feature compress XCI to XCZ
- Added new feature compress NSP to NSZ
- hactoolnet update to new version 0.6.0
- NSC_BUILDER (only squirrel.exe) update to new version 0.95

Beta v0.7.1: (26.10.2019)
- Changes for XCI merge added support for 00 split files
- Added new feature decompress XCZ to XCI
- Added new feature decompress NSZ to NSP
- Code cleanup

Beta v0.7.2: (17.11.2019)
- NSC_BUILDER (only squirrel.exe) update to new Version 0.96c
- Added splash screen to SAK

Beta v0.7.3: (22.11.2019)
- Changes for Update XCI with game update + dlc's (multiselect possible)

Beta v0.7.3.1: (02.12.2019)
- Small fix at extract saves
- hactoolnet update to new version 0.7.0
- NSC_BUILDER (only squirrel.exe) update to new version 0.96d

Small update: (19.12.2019)
- NSC_BUILDER (only squirrel.exe) update to new Version 0.97

Beta v0.7.4: (05.01.2020)
- Added new feature Update NSP with game update
- hactoolnet update to new version 0.8.0

Small update: (07.01.2020)
- hactoolnet update to new version 0.8.1

Small update: (20.01.2020)
- hactool update to new version 1.3.0
- NSC_BUILDER (only squirrel.exe) update to new version 0.98b

Small update: (22.02.2020)
- hactool update to new version 1.3.1

Small update: (14.04.2020)
- hactool update to new version 1.3.3
- hactoolnet update to new version 0.10.0

Beta v0.7.5: (11.06.2020)
- Changes Update NSP/XCI with game update now support Updates as NSZ
- Added new feature patch XCI to lower firm
- hactool update to new version 1.4.0
- hactoolnet update to new version 0.11.3

Beta v0.7.6: (26.10.2020)
- Changes add _patch label if you use the patch XCI or NSP option
- NSC_BUILDER (only squirrel.exe) update to new version 1.01b
- hactoolnet update to new version 0.12.0

Beta v0.7.7: (31.12.2020)
- Small fix for patching NSP with changing label _patch
- NSC_BUILDER (only squirrel.exe) revert to version 0.98b

Beta v0.7.8: (04.05.2021)
- Added new feature create NRO forwarder

Beta v0.7.9: (05.05.2021)
- Added feature create Retroarch Core forwarder

Beta v0.7.10: (14.05.2021)
- Added feature change version number in forwarder
- Added feature allow/deny screenshot in forwarder
- Added feature enable/disable video capture in forwarder

Beta v0.7.11: (15.05.2021)
- Fix some HB-Tools not working in forwarder

********************************************************************************************************************************
*** Put Switch Army Knife into operation
********************************************************************************************************************************

Requirement:
- Windows PC
- Dumped keys.dat/prod.keys from your Switch console - to get your keys look here -> (https://psxtools.de/index.php/Thread/76547)

Unzip 7zip:
- Switch keys (keys.dat/prod.keys) copy it to the "bin" dir near 4nxci.exe
- finished
