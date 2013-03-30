--------------------------------------------------------------------------------------------------
THIS TEXT WILL ALSO FOLLOW IN ENGLISH, PLEASE SCROLL DOWN!
--------------------------------------------------------------------------------------------------
Windows 2000 WDM Driver Installation
--------------------------------------------------------------------------------------------------
[DEUTSCH]
--------------------------------------------------------------------------------------------------

Sehr geehrte Kundin, sehr geehrter Kunde,
das aktuelle Build von Windows 2000 enthält bereits generische Treiber für die XLerate Pro, 
die als Aureal Vortex WDM oder ähnlich im Gerätemanager installiert sind. Um eine einwandfreie 
Funktionalität der neuen Treiber zu gewährleisten ist es notwendig die vorherigen Treiber zu 
deinstallieren und anschließend die neuen Treiber zu installieren.

Die vorliegenden Treiber sind BETA und die Installation und Benutzung erfolgt auf eigenes Risiko.
Außerdem gibt es keinerlei Support seitens TerraTec für die Installation und/oder den Betrieb der 
Karte mit diesen Treibern. Eine Weiterentwicklung der Treiber findet nicht statt, da Aureal in 
Konkurs gegangen ist und TerraTec nicht im Besitz der Sourcen ist.
Der Treiber liegt nur in englischer Sprache vor und wurde soweit angepasst, das er für die
XLerate Pro verwendet werden kann.

Die Installation gestaltet sich leider etwas umständlicher als gewöhnlich. 
Fortgeschrittene PC-Kenntnisse sind sicherlich von Vorteil bei den folgenden Installationsschritten.

Folgende Funktionen werden im Vergleich zu den Win9x VxD-Treibern NICHT unterstützt.
• 4-Kanal-Unterstützung, obwohl im ControlPanel angezeigt (geghosted)


DEINSTALLATION

• Stellen Sie zunächst sicher, dass die gewählten Ordnereinstellungen alle Systemverzeichnisse und 
  Systemdateien anzeigen und nicht verstecken. Um zu überprüfen, ob die gewählten Einstellungen richtig 
  sind, können Sie nach folgenden Ordnern suchen:
  o c:\winnt\inf
  o c:\winnt\system32\dllcache

• Gehen Sie auf Start --> Einstellungen --> Systemsteuerung.

• Gehen Sie auf System --> Geräte-Manager.

• Markieren Sie den Eintrag  Vortex Multifunction PCI Parent

• Klicken Sie mit der rechten Maustaste und wählen Sie aus dem Kontextmenü Deinstallieren.

• Wechseln Sie ins INF-Verzeichnis Ihrer Windows2K-Installation (z.B. c:\winnt\inf) und löschen 
  Sie die folgenden Dateien:
  o wdma_aur.inf
  o wdma_aur.pnf
  o adm_mult.inf
  o adm_mult.pnf
  o adm_port.inf
  o adm_port.pnf

• Wecheln Sie ins Verzeichnis c:\winnt\driver cache\i386. Benennen Sie die Datei driver.cab z.B. nach 
  driver.bak um.

• Wechseln Sie ins Verzeichnis c:\winnt\system32\dllcache

• Im Verzeichnis löschen Sie die folgenden Dateien:
  o adm8830.sys
  o admjoy.sys

• Wechseln Sie ins Verzeichnis c:\winnt\system32\drivers und löschen Sie die folgenden Dateien:
  o adm8830.sys
  o admjoy.sys
• Starten Sie Ihren Rechner jetzt neu.


INSTALLATION

• Nach dem Neustart sollte der Hardware-Setupassistent ein Multifunktions-Gerät erkennen.

• Geben Sie den Ordner, indem Sie die Treiberdateien entpackt haben, als Quelle an.

• Während der Installation wird u.U. nach folgenden Dateien gesucht:
  o kuser.dll	--> c:\winnt\system32 
  o ks*dll	--> c:\winnt\system32\drivers
  o *.drv	--> c:\winnt\system32
  o portcls.sys	--> c:\winnt\system32\drivers

• Wird während der Installation nach anderen Dateien gefragt, verweisen Sie bitte immer auf den 
  Quellordner, in dem sich die XLerate Pro Treiberdateien befinden

• Benennen Sie die Datei driver.bak (oder wie Sie sie benannt haben) wieder in driver.cab um.


--------------------------------------------------------------------------------------------------
Windows 2000 WDM Driver Installation
--------------------------------------------------------------------------------------------------
[ENGLISH]
--------------------------------------------------------------------------------------------------

Dear customer,
the current build of Windows 2000 contains already generic drivers for the XLerate Pro, that display 
theirself as Aureal Vortex WDM or similiar within the device manager. To guarantee flawless 
functionality of the new drivers it is necessary to uninstall the previous drivers and install the new 
ones afterwards.

The present driver is BETA and installation and use is on your own risk. TerraTec does not provide any 
kind of support for the installation and/or use of these drivers with the XLerate Pro. 
Eventhough the drivers are BETA there will be no further development, since the company the driver are 
originating from quitted business.
TerraTec does not have the complete sources and is not able to maintain further development.
The driver is only available in english language and was customised to work for the XLerate Pro.

Unfortunately installation does not follow the usual way. 
Advanced PC know how is recommended to follow the following installation steps.

Functions NOT supported in comparison to the Win9x VxD driver
• 4 channel support, although displayed in the ControlPanel (ghosted)


UNINSTALLATION

• Make sure, that your folder options allow acces to system folders and files. 
  To check you can search for existence of the following folders:
  o c:\winnt\inf
  o c:\winnt\system32\dllcache

• Click on Start --> Settings -> Controlpanel

• Click on System --> Device manager

• Select the entry Vortex Multifunction PCI Parent

• Click on the right mouse button to get the contex menue and choose Uninstall.

• Change to INF folderof your Win2K installation (e.g. c:\winnt\inf) and delete the following files:
  o wdma_aur.inf
  o wdma_aur.pnf
  o adm_mult.inf
  o adm_mult.pnf
  o adm_port.inf
  o adm_port.pnf

• Change to the folder c:\winnt\driver cache\i386. Rename the 'driver.cab' file to something like 
  'driver.bak' (so that your Adm8830.sys file doesn't keep getting installed by the OS)

• Change to the folder c:\winnt\system32\dllcache and delete the following files:
  o adm8830.sys
  o admjoy.sys

• Change to the folder c:\winnt\system32\drivers and delete the following files:
  o adm8830.sys
  o admjoy.sys

• Restart your PC.


INSTALLATION

• After reboot the "Found new Hardware wizard" should detect a multifunction device.

• Point to the folder, where you unzipped the drivers to.

• During installation the following files might be requested:
  o kuser.dll	--> c:\winnt\system32
  o ks*dll	--> c:\winnt\system32\drivers
  o *.drv	--> c:\winnt\system32
  o portcls.sys	--> c:\winnt\system32\drivers

• If other file are requested, point again to the folder with the XLerate Pro driver files

• Rename the ‘driver.bak’ (or whatever you named it) back to ‘driver.cab’.
