RME  Intelligent Audio Solutions

Hammerfall DSP System

Driver for Windows 2000/XP

Important information: Driver version 2.94(6)


News, changes and fixes

2.94(6)
Inf file updated for firmware 108 (HDSP 9652)

2.94(5)
Inf file updated for firmware 154 (HDSP 9632)

2.94(4)
Inf file updated for firmware 17 and 55 (PCI and CardBus)

2.94(3)
Inf file updated for firmware 16 and 54 (PCI and CardBus)


2.94(2)

TotalMix:

- Fixed small memory leak

- Automatic submix selection when activating Monitor Main/Phones

- MIDI Remote: Starting TotalMix via a click on the systray symbol refreshes the LC-Display


2.94(1)

Bugfixes for HDSP 9632:

- TotalMix settings were not loaded correctly after Standby/Hibernation

- Quick Access Panel graphics reset added

- Level meter display problem (numerical) in some specific situations - fixed 


General:

- TotalMix MIDI remote: Mute and solo buttons were not always displayed correctly


Note: the manuals of the HDSP series have been updated. Please download the latest version from:

http://www.rme-audio.com/english/download/manuals.htm


-------------------

2.94

TotalMix:

- Since 2.93(3) ASIO Direct Monitoring had been inactive 
- Internal Loopback optimized (digital I/Os)

Known problems:
Starting a notebook and inserting the CardBus after a completeted boot of Windows will cause the MIDI port list in TotalMix (for MIDI remote control) to become corrupted. To reset the list, exit TotalMix and restart it. This issue ONLY affects MIDI remote control of TotalMix after a boot with delayed CardBus insertion. Removing and reinserting the CardBus during continued operation of the notebook, or even going to sleep or hibernation in-between, does not show this problem.

-------------------

2.93(3)

TotalMix:

- Performance improved when Matrix window is open
- Tooltip is turned off when window is closed via ESC
- Tooltip is turned off when mouse is moved quickly across the window border
- Graphical problems with 9632 and RPM fixed

General:

- Plug and Play behaviour of the Settings dialog optimized
- Internal bugfix (registry access) which did not cause any trouble so far


-------------------

This driver may require an update of the HDSP systems's firmware. To update download the Flash Update Tool from our website:

http://www.rme-audio.com/download/fut_win_dsp.zip


First time Driver Installation:
During the installation of the drivers point to the directory where they reside. For more detailed information see manual, found on the RME Driver-CD.


*****************************

!!!!! Driver Update: !!!!!

This driver includes a changed hdsp32.inf file. To prevent Windows 2000/XP from using an old hdsp32.inf (of a former driver installation) be sure NOT to let Windows search for the driver! Instead tell Windows what to do:

- Under Control Panel /System /Device Manager /Sound, Video and Game Controllers /RME Hammerfall DSP or HDSP 96xx/Properties /Driver you'll find the 'Update Driver' button. Select 'Install from a list or specific location (advanced)', click 'Next', select 'Don't search I will choose the driver to install', click 'Next', then 'Have Disk'. Now point to the driver update.

- After the installation perform a cold boot. Multiface/Digiface: also be sure to reset the I/O-box by pulling the Firewire cable. The CardBus system requires to remove the I/O-box power supply for a second.

- After the reboot open TotalMix and click on Preset 1.

*****************************


Driver files explained:

hdsp.sys: Windows hardware driver
hdsp32.exe: Settings dialog
hdspmix.exe: TotalMix
hdspasio.dll: ASIO driver
hdspmme.dll: MME and MIDI driver

Copyright RME 02/2009
All rights reserved. Windows 2000/XP are trademarks of Microsoft Corporation. Hammerfall is a registered trademark of RME Germany. ASIO is a trademark of Steinberg Media Technologies AG.

