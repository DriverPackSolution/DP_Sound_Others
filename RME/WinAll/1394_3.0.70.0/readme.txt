RME  Intelligent Audio Solutions

Fireface 800 / 400 / UFX / UCX

Driver for Windows XP/Vista/7/8 32/64 Bit

Important information: Driver version 3.070

General news, changes and fixes


------------------

V 3.070 (12/19/2012, current firmware: 2.77 / 1.71 / 341 / 23)

- New TotalMix FX 0.989 (UFX, UCX)

------------------

V 3.069 (08/27/2012, current firmware: 2.77 / 1.71 / 341 / 23)

- New TotalMix FX 0.984 (UFX, UCX)

------------------

V 3.068 (07/12/2012, current firmware: 2.77 / 1.71 / 341 / 23)

- New TotalMix FX 0.983 (UFX, UCX)

------------------

V 3.067 (01/17/2012, current firmware: 2.77 / 1.70 / 340)

- Support for Fireface UCX added

- New TotalMix FX 0.963 (UFX, UCX)

------------------

V 3.062 (11/09/2011, current firmware: 2.77 / 1.70 / 340)

- New TotalMix FX 0.96 (UFX)

- Settings dialog: wrong settings fixed when using more than one unit


------------------

V 3.059 (10/10/2011, current firmware: 2.77 / 1.70 / 340)

- New TotalMix FX 0.95 (UFX)

- New option 'Lock Registry' in the Settings dialog, About tab

- Store/Read Flash in the Settings dialog did not work correctly

- Small fixes


------------------

V 3.047 (06/21/2011, current firmware: 2.77 / 1.70 / 339)

- New TotalMix FX 0.942 (UFX)


------------------

V 3.046 (06/17/2011, current firmware: 2.77 / 1.70 / 339)

- Support for kAsioCanInputMonitor added

- New TotalMix FX 0.941 (UFX)


------------------

V 3.044 (04/01/2011, current firmware: 2.77 / 1.70 / 336)

- All files changed to language neutral


------------------

V 3.043 (03/18/2011, current firmware: 2.77 / 1.70 / 336)


- New TotalMix FX 0.93 (UFX)

- TotalMix FX help and Settings dialog are correctly installed under Win 64

- Settings dialog saves the current position

- Settings dialog FF400/800: Buffer size 4096 in QS mode removed (more than 2048 is not supported by the hardware)

- Settings dialog: Pitch menu/list box improved

- Settings dialog: sample rate list box improved

- Various small improvements of the WDM driver

- WDM UFX: ADAT 2 1/2 is no longer labelled SPDIF

- FF 800 stand-alone channel 1: Limiter state is stored correctly

- Multi-client playback mixing on identical channels

- FF 400 Encoder: selecting invalid channels caused crash



- TotalMix Update (for FF 400/800):

- - 4 fader groups definable. Use 'Save All Presets' to store them to a file.

- - Undo of the last Preset loading

- - New options to deactivate the Mackie protocol and the Level Meters

- - Level Meter data added to Mackie protocol

- - Post fader mode added (Mackie: F16. On: MIDI channel 1, note on A 4. Off: MIDI channel 1, note off A 4)

- - Direct submix selection via Control Change commands (channel 1/2: BC 68/69 xx, channel 3/4: BC 6A/6B xx etc.)


------------------

V 3.034 (12/17/2010, current firmware: 2.77 / 1.70 / 336)

- New TotalMix FX help

- Missing ADAT WDM devices added to inf file


------------------

V 3.033 (12/03/2010, current firmware: 2.77 / 1.70 / 336)

- New TotalMix FX 0.924


------------------

V 3.032 (11/08/2010, current firmware: 2.77 / 1.70 / 333)

- ASIO sample rate can now be changed while DIGICheck is used with the DAW software


------------------

V 3.031 (11/05/2010, current firmware: 2.77 / 1.70 / 332)

- TotalMix FX 0.915

- Bigger buffers for Double and Quad Speed in the Settings dialog

- Fixed possible hang when changing the sample rate

- Settings for the FF 400 headphone level had been reversed in the Settings dialog

- Latency can now be changed while more than one ASIO program is used (useful for a parallel operation of DIGICheck)


------------------

V 3.028 (10/20/2010, current firmware: 2.77 / 1.70 / 328)

- TotalMix FX 0.913

- Settings dialog UFX reworked

- Clock mode master (Internal) was not set correctly in the UFX


------------------

V 3.027 (10/04/2010, current firmware: 2.77 / 1.70 / 328)

- Supports the Fireface UFX. TotalMix FX 0.91.


------------------

V 3.020 (08/23/2010, current firmware: 2.77 / 1.70)

- Sonar WDM KS: 16 bit mode added


------------------

V 3.018 (08/19/2010, current firmware: 2.77 / 1.70)

- Sonar WDM KS: workaround added to enable detection


------------------

V 3.017 (08/17/2010, current firmware: 2.77 / 1.70)

- TMS for ASIO can be disabled in the Settings dialog

- Random delay when starting the ASIO driver fixed


------------------

V 3.016 (06/30/2010, current firmware: 2.77 / 1.70)

- the FF 800 did not show all I/Os under WDM

- using multiple FFs the latency and sample rate setting was not synchronized in the Settings dialog

- the front/rear setting for input 1 did not become active immediately

- In clock mode slave a warning for wrong input clock is now displayed


------------------

V 3.015 (04/23/2010, current firmware: 2.77 / 1.70)

- Removed double 24 bit entry in WDM device properties

- Changed names in inf file (caused Settings and Mixer window to be opened)

- Changed Store/Read button position (problem under XP)


------------------

V 3.014 (04/22/2010, current firmware: 2.77 / 1.70)

- Fireface 800 had one MIDI I/O too much

------------------

V 3.013 (04/19/2010, current firmware: 2.77 / 1.70)

- ASIO and WDM-KS sample rate change did not work as expected

- Firmware check added to Settings dialog

- Factory presets of FF 400 and FF 800 were exchanged

------------------

V 3.012 (03/29/2010, current firmware: 2.77 / 1.70)

- New core routines, better P&P support, several BSODs removed

- Entering Standby possible even while playback active

- Improved compatibility to Windows 7 FW driver

- New Settings dialog with WDM sample rate control

- Improved WDM compatibility, Loudspeaker surround routines reworked


------------------

V 2.9992 (01/18/2010, current firmware: 2.77 / 1.70)

- Fixed order of multiple units change across different operating systems

------------------

V 2.9991 (12/11/2009, current firmware: 2.77 / 1.70)

- MME support removed (fireface_mme.dll)

------------------

V 2.999 (11/27/2009, current firmware: 2.77 / 1.70)

- Under Windows 7 64 bit the red Host LED stayed lit after standby, despite correct communication with the host.

------------------

V 2.998 (11/05/2009, current firmware: 2.77 / 1.70)

- This driver requires firmware 2.77 (FF 800) and 1.70 (FF 400)!

- New transmission mode to work around a bug in Windows 7

- Additional reset after sleep to work around a bug in Windows 7

- ADM bug fixed  for OEMs (missing initialisation when ASIO is not used)


-------------------

V 2.993 (10/13/2009, current firmware: 2.70 / 2.47 / 1.69)

- WDM: Change for Adobe Audition's DirectSound ASIO wrapper (8-channel input device removed)

-------------------

V 2.992 (10/01/2009, current firmware: 2.70 / 2.47 / 1.69)

- Bugfix of version 2.98. Driver update under XP caused crash (BSOD) at the end of the install

-------------------

V 2.98 (09/28/2009, current firmware: 2.70 / 2.47 / 1.69)

- Compatible to Windows 7 (see note below)

- Reliable stop of an ASIO thread even in difficult situations

- Process management of multiclient ASIO did not work as expected on some computers

- Settings dialog: New icons

- Settings dialog: MMCSS option removed

- TotalMix: New skin and new icons

- TotalMix: Scrolling limited to fader section, Quickpanels are fixed to the right

- TotalMix Matrix: Missing refresh when I/O labels change added

- TotalMix: Password for locking the mixer state added

- TotalMix: Bugfix Faderfox submix selection in third row

- TotalMix: Option 'Ignore I/O Labels' did not work correctly


--------------------------

V 2.95 (01/30/2009, current firmware: 2.70 / 2.47 / 1.67)

- Mixer is reloaded after Standby

- Added offset of one ASIO buffer in LTC mode


--------------------------

V 2.94 (12/15/2008, current firmware: 2.70 / 2.47 / 1.67)

- FF400: LTC function optimized

- FF400/800: MIDI Output performance optimized


--------------------------

V 2.91 (10/31/2008, current firmware: 2.70 / 2.47 / 1.67)

- ASIO: Stop could cause BSOD in Sonar

- TotalMix: Added support for Faderfox TM1


--------------------------

V 2.898 (08/22/2008, current firmware: 2.70 / 2.47 / 1.67)

- ASIO: Memory leak removed. This happened only when starting/stopping ASIO, and with the amount of the current buffer size, so usually stayed completely unnoticed.

- A forced driver installation (non Plug and Play, Legacy hardware) should no longer cause a BSOD.

- TotalMix: Over LED moved by one pixel


--------------------------

V 2.896 (07/09/2008, current firmware: 2.70 / 2.47 / 1.67)

- Vista: MMCSS setting is stored and MMCSS is 'off' as default

--------------------------

V 2.895 (07/02/2008, current firmware: 2.70 / 2.47 / 1.67)

- Vista: MMCSS can be disabled in the Settings / About dialog

--------------------------

V 2.894 (06/16/2008, current firmware: 2.70 / 2.47 / 1.67)

- Vista: Priority handling of the audio thread improved

- Vista: New routines for the startup confirmation problem added


--------------------------

V 2.89 (06/05/2008, current firmware: 2.70 / 2.47 / 1.67)

- WDM: Speaker setup defines 6 or 8 channel playback

- WDM: Pitch shift problem fixed with external clocking


--------------------------

V 2.87 (05/16/2008, current firmware: 2.70 / 2.47 / 1.67)

- Support for DirectMusic MIDI added


--------------------------

V 2.86 (03/04/2008, current firmware: 2.66 / 2.47 / 1.66)

- TotalMix: Support for custom bitmaps. More information can be found in the RME forum.

- TotalMix: 1 pixel offset removed on bus menu background

- TotalMix: New option 'Level Meter Text Color'

- WDM: 8-channel playback did not work correctly

--------------------------

V 2.85 (02/06/2008, current firmware: 2.66 / 2.47 / 1.65)

- TotalMix: code changed to prevent crashes when changing the channel names in the mixer

- TotalMix: Names no longer appear on empty channel plates after changing labels

- TotalMix: New option 'Ignore I/O Labels'

- ASIO driver could crash when no Fireface present

--------------------------


First time Driver Installation:
During the installation of the driver point to the directory where it resides. For more detailed information see manual, found on the RME Driver-CD.


*****************************

!!!!! Driver Update: !!!!!

This driver includes a changed fireface.inf file. To prevent Windows from using an old fireface.inf (of a former driver installation) be sure NOT to let Windows search for the driver! Instead tell Windows what to do:

- Under Control Panel /System /Device Manager /Sound, Video and Game Controllers /RME Fireface 800 /Properties /Driver you'll find the 'Update Driver' button. Select 'Install from a list or specific location (advanced)', click 'Next', select 'Don't search I will choose the driver to install', click 'Next', then 'Have Disk'. Now point to the directory containing the driver update.

- After the installation reboot the computer.

- After the reboot open TotalMix and Ctrl-click on Preset 1.

*****************************


Driver files explained:

fireface.cat: catalog file for signing
fireface.sys: Windows hardware driver, WDM audio and MIDI
fireface_64.sys: Windows 64 bit hardware driver, WDM audio and MIDI
fireface.exe: Settings dialog
firefacemix.exe: TotalMix
fireface_asio.dll: ASIO driver
fireface_asio_64.dll: 64 bit ASIO driver
fireface.inf: Hardware installation script for Windows XP/Vista/7
TotalMixFX.exe: TotalMix FX for Fireface UFX
TotalMixFX.chm: Help file for TotalMix FX


Copyright RME 12/2012
All rights reserved. Windows XP/Vista/7/8 are trademarks of Microsoft Corporation. ASIO is a trademark of Steinberg Media Technologies GmbH.

