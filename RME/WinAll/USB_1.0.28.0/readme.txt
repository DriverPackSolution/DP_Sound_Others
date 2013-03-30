RME  Intelligent Audio Solutions

Fireface UC / Babyface / UFX / UCX

Driver for Windows XP/64 / Vista/7/8 32/64

Important information: Driver version 1.028


----------------------------

Attention Fireface UC! The TotalMix autorun entry from old driver 0.938 is not deleted from the Windows registry  by installation of this driver. Therefore the entry has to be deleted once by the user before (or after) the driver update. Remove the entry

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Run\FirefaceUsbTray2 = firefaceusbmix.exe

The most easiest and safest way to do this is to double-click on the file 

remove old mixer autostart.reg

which is found within the driver archive. Windows will then remove the autostart of the old mixer.

----------------------------

Attention Babyface! In case driver 0.956 had been installed from the driver CD the above applies to the Babyface as well. Driver 0.956 includes supports de-installation (see manual). If the driver is de-installed prior to the update the old autostart entry is already removed.

----------------------------


News, changes and fixes


V 1.028 (12/11/2012)

- New TotalMix FX 0.989

- TM FX: Optimized behavior of Babyface Echo/Reverb when changing the sampe rate. Crash fixed when using invalid values for the submix selection.

- Improved Windows 8 compatibility

- Improved behavior on stop, changing the sample rate and Settings dialog

----------------------

V 1.025 (08/27/2012)

- New TotalMix FX 0.984

----------------------

V 1.024 (07/12/2012)

- New TotalMix FX 0.983

----------------------

V 1.022 (05/03/2012)

- Compatibility problem wit Windows 8 fixed

- Fixed slow shutdown/hardware removal

----------------------

V 1.019 (01/17/2012)

- Support for Fireface UCX added

- New TotalMix FX 0.963


----------------------

V 1.013 (11/09/2011)

- New TotalMix FX 0.96

- Settings dialog: Latency setting is synchronized when using more than one unit

Babyface:
- Improved Speaker B function, see TotalMix FX, Options/Key Commands. Note: does not work with SPDIF/ADAT!


----------------------

V 1.01 (10/10/2011)

- New TotalMix FX 0.95

- Settings dialog: New option 'Lock Registry' on the About tab

- Fireface UFX: AC-3 was not signalled correctly on the AES/SPDIF output


----------------------

V 0.984 (06/21/2011)

- New TotalMix FX 0.942


----------------------

V 0.983 (06/17/2011)

General:
- Support for kAsioCanInputMonitor added

- New TotalMix FX 0.941


----------------------

V 0.981 (05/20/2011)

General:
- Settings dialog: TMS had been switched off on every restart

- Settings dialog: In some situations a tab for non-existing devices was shown

- New TotalMix FX 0.94 RC1


Babyface:
- Bug fix high interrupt load when removing the driver under W7 SP1


----------------------

V 0.979 (04/15/2011)

- WDM: playback with buffer size 512 or higher had clicks and drop outs

----------------------

V 0.977 (04/01/2011)

- All files changed to language neutral

----------------------

V 0.976 (03/18/2011)

- New TotalMix FX 0.93

- TotalMix FX help and Settings dialog are correctly installed under Win 64

- Settings dialog saves the current position

- Settings dialog: Pitch menu/list box improved

- Settings dialog: sample rate list box improved

- Settings dialog UC: partly wrong status information fixed

- WDM UFX: ADAT 1 1/2 is no longer labelled SPDIF

- Various small improvements of the WDM driver

- Multi-client playback mixing on identical channels


--------------------------

V 0.966 (12/20/2010)

- New TotalMix FX help

- Removed double 24 bit entry in WDM device properties

--------------------------

V 0.964 (12/03/2010)

- New TotalMix FX 0.924


--------------------------

V 0.963 (11/19/2010)

- Using more than one WDM device could cause a BSOD


--------------------------

V 0.961 (11/03/2010, current firmware: 338)

- Changing the buffer size reverted to the sample rate used before in the Settings dialog

- Fixed possible hang when changing the sample rate

- TotalMix 0.915


--------------------------

V 0.960 (10/21/2010, current firmware: 336)

- Driver sets the correct sample rate when loaded

- Driver sets the correct sample rate after standby

- Settings dialog: added +D string

- TotalMix 0.913


--------------------------

V 0.959 (10/04/2010, current firmware: 336)

- Official support for Fireface UFX, TotalMix 0.91


--------------------------


Babyface:

V 0.956 (09/20/2010, current firmware: 176)

Version for Babyface driver CD, TotalMix 0.87

--------------------------

V 0.954 (08/25/2010, current firmware: 175)

- SPDIF In TMS Option

- WDM KS 16 bit for Sonar

- De-installation via Windows/Programs

- TotalMix FX 08341, adds MIDI remote


--------------------------

V 0.951 (08/11/2010, current firmware: 173)

- First public release

--------------------------



Fireface UC:

V 0.954 (08/25/2010, current firmware: 111)

- SPDIF In TMS Option

- WDM KS 16 bit for Sonar

- De-installation via Windows/Programs

- Faders on the Gain tab removed - control via TotalMix FX

- TotalMix FX 08341, adds MIDI remote


--------------------------

V 0.938 (03/30/2010, current firmware: 111)

- Entering Standby possible even while playback active

- Improved WDM compatibility, Loudspeaker surround routines reworked

--------------------------

V 0.936 (01/27/2010, current firmware: 91)

- ASIO Direct Monitoring funktionierte nicht

--------------------------

V 0.935 (06/18/2009, current firmware: 82)

Initial release

--------------------------


This driver may require an update of the Fireface firmware. To update download the Flash Update Tool from our website:

http://www.rme-audio.com/download/fut_usb_win.zip


First time Driver Installation:
During the installation of the driver point to the directory where it resides. For more detailed information see manual.


*****************************


Driver files explained:

fireface_usb.sys: Windows hardware driver, WDM audio and MIDI
fireface_usb_64.sys: Windows 64 bit hardware driver, WDM Audio and MIDI
firefaceusb.exe: Settings dialog
firefaceusbmix.exe: TotalMix
fireface_usb_asio.dll: ASIO driver
fireface_usb_asio_64.dll: 64 bit ASIO driver
fireface_usb.cat: catalog file for signed install
fireface_usb.inf: Hardware installation script for Windows
TotalMixFX.exe: TotalMix FX for Fireface UFX
TotalMixFX.chm: Help file for TotalMix FX


Copyright RME 12/2012
All rights reserved. Windows XP/Vista/7/8 are trademarks of Microsoft Corporation. ASIO is a trademark of Steinberg Media Technologies GmbH. ADAT is a trademark of the Alesis Corp.

