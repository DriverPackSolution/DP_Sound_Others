RME  Intelligent Audio Solutions

HDSP Series (AES-32, MADI, 9652, 9632, Multiface, Digiface, RPM)

HDSPe Series (PCI, MADI, MADIface, ExpressCard, RayDAT, AES, AIO)

Driver for Windows XP/Vista/7/8, 32 and 64 Bit

Important information: Driver version 3.31


This is the HDSP(e) series WDM streaming driver, offering additional features like WDM streaming, kernel streaming, 64 bit support and full Vista/7 compatibility. It supports all HDSP and HDSPe series cards and systems simultaneously. The TCO can be operated with the HDSP AES-32, the HDSPe PCI/MADI/AES/RayDAT/AIO, but not with the HDSP 9632.


Notes on the driver
-----------------

- The driver requires a new Firmware (flash) in case you are updating from driver 2.94 or older.

- The driver does not support MME.

- This driver requires a newer version of DIGICheck, version 5 or higher. Please download it from the RME website, section Downloads/DIGICheck.


Installation
-------------

Latest driver:
http://www.rme-audio.com/download/hdsp_wdm_3xxxx.zip


The driver requires a new Firmware (Flash Update Tool, FUT) in case you are updating from driver 2.94 or older.


Firmware for HDSP series cards:
http://www.rme-audio.com/download/fut_wdm_dsp.zip


Firmware for HDSPe series cards:
http://www.rme-audio.de/download/fut_wdm_dspe.zip

The firmware update is not possible unless the driver had been installed before.

Both driver installation and flash update are explained in detail in the manual!


*** First time installation of RME Audio Interfaces under Windows 7/8 ***

The procedure and instructions found in the manual are correct and stay valid, except for the start of the installation. In Windows 7 Microsoft removed the automatic start of the Driver Software Update dialog. Therefore this dialog has to be started manually after the failed driver installation.

- Hit the Win key, type 'Device Manager', start the Device Manager by selecting it from the list and hit Return.

- The device is shown with a yellow warning symbol. Usually it is already found in the correct category, Sound, Video and Game Controller (Plug & Play detects a multimedia device). The Fireface UC is even shown with its correct name.

- Right click on the device and select 'Update Driver Software' from the context menu.

- The dialog 'Update Driver Software' appears. Now follow the instructions given in the manual.


----------------------

Update 3.31, 11/16/2012

- 'Lock Mixer' now completely locks TotalMix 

----------------------

Update 3.30, 11/06/2012

- New TCO option 23.976

----------------------

Update 3.29, 05/07/2012

- Changing the sample rate could cause a problem (stop) with programs that do not support kASIOResetRequest

- AIO only: using the AI4S-192 module the phones out did not work correctly under Win 7, under Win XP the device names were wrong.

----------------------

Update 3.27, 12/14/2011

- Settings dialog: clock state could show wrong info (MADIface)

- Settings dialog: Label 'ADAT' changed to 'Optical' on some cards

----------------------

Update 3.26, 08/03/2011

- HDSPe MADI: since firmware 28 MIDI over MADI did not work during 32 bit playback

- RPM: Settings dialog was only partly implemented

- HDSPe PCI/ExpressCard: without attached box 'ock' was shown in the sample rate menu

- HDSPe AES: WDM Devices in the Settings dialog influenced the number of ASIO channels

- General WDM: The driver used the state of the Interleaved button of older drivers, which could cause the loss of surround playback capability

- General WDM: After selecting Stereo in the Loudspeaker setup a stereo playback blocked the first 8 channels


----------------------

Update 3.24, 05/09/2011

- Improved TCO function. For the best, sample-aligned operation via APP the following firmware versions should be used: HDSPe MADI rev. 28, HDSPe RayDAT rev. 12, HDSPe AES rev. 8, HDSPe AIO rev. 12, or higher.


----------------------

Update 3.21, 03/14/2011

- Correct installation of the Settings dialog under Win 64

- Settings dialog completely reworked

- Settings dialog saves the current position

- WDM driver completely reworked. Sample rate is now set in the Settings dialog (Win 7).

- Multi-client playback mixing on identical channels

- Optimized callbacks for multiple cards usage on multi-processor machines


- TotalMix Update:

- - 4 fader groups definable. Use 'Save All Presets' to store them to a file.

- - Undo of the last Preset loading

- - New options to deactivate the Mackie protocol and the Level Meters

- - Level Meter data added to Mackie protocol

- - Post fader mode added (Mackie: F16. On: MIDI channel 1, note on A 4. Off: MIDI channel 1, note off A 4)

- - Direct submix selection via Control Change commands (channel 1/2: BC 68/69 xx, channel 3/4: BC 6A/6B xx etc.)


----------------------

Update 3.085, 08/05/2010

- MADIface: Quad Speed did not work in slave mode
- HDSP 9632: Firmware 152 was missing in the driver, so the card was not detected

----------------------

Update 3.084, 07/08/2010

- TCO: timecode offset changed for Magix software
- TotalMix: The tooltips on the preset buttons did not work
- HDSPe AIO: The WDM loudspeaker device can now be used for 6/8-channel playback

----------------------

Update 3.083, 02/19/2010

- HDSP MADI Settings dialog: TCO removed
- About Dialog: Vista MMCSS option removed
- WDM: SPDIF AC-3 is only supported on SPDIF devices
- WDM: MADIface had no Loudspeaker device
- WDM: Analog DVD multi-channel playback via Loudspeaker device (change loudspeaker configuration to 5.1 or 7.1)
- ADAT Sync (HDSP9652, Multiface, Digiface): APP did not work correctly since Cubendo 4

----------------------

Update 3.082, 10/20/2009

- Support for Flash Tool 2.19

----------------------

Update 3.081, 08/12/2009

- Since 3.079 the buffer size was not stored on some systems


----------------------

Update 3.080, 05/28/2009

- Since 3.079 multi-client ASIO did not work correctly when using multiple cards


----------------------

Update 3.079, 05/14/2009

- Settings dialog: Added password protected storage of the current settings for the next reboot

- Settings and TM: Experimental extension for operation of up to 6 cards. Selection in TM by left mouse click with held shift key

- Incompatibility of the driver to cards with PLX (PCIe to PCI) bridge fixed

- Reliable stop of an ASIO thread even in difficult situations

- Process management of multiclient ASIO did not work as expected on some computers

- TotalMix: New skin and new icons

- Settings dialog: new icons


----------------------

Update 3.077, 03/27/2009

- TM: Scrolling limited to fader section, Quickpanels are fixed to the right

- TM: Missing refresh when I/O labels change added


----------------------

Update 3.076, 03/16/2009

- TM: AIO only: Small display error in mixer view with AI added

- TM: Grid in Matrix fixed for several cards

- TM: Over LED position fixed

- WDM: Change for Adobe Audition's DirectSound ASIO wrapper (8 channel input device removed)


----------------------

Update 3.075, 02/25/2009

- RayDAT only: Changing the number of WDM devices disabled ASIO channels as well

----------------------

Silent Update 3.074 (4), 02/17/2009

- ASIO: Latency information of AES and AES-32 changed

----------------------

Silent Update 3.074 (3), 02/03/2009

- TotalMix: Bugfix Faderfox submix selection in third row

- ASIO APP: Improved behaviour with stopped Timecode

----------------------

Update 3.074, 01/05/2009

- TotalMix: Several changes for the HDSPe AIO (channel order, presets and naming)

- New firmware V 9 for the HDSPe AIO

- TotalMix: MS Processing added to menu Options for the whole HDSPe series 

- ASIO APP: Missing run flag caused Nuendo 4 transport to stop responding

----------------------

Update 3.073, 10/28/2008

- APP: Loss of LTC caused the cursor to jump to the beginning

- New firmware ID 154 of the HDSP 9632 added to the inf-file

----------------------

Update 3.071, 09/08/2008

- TotalMix: Name-popups above the Preset buttons were deactivated

- Settings dialog: The button 'Sync In' did not work for the RayDAT and AIO


----------------------

Update 3.069, 08/26/2008

- Settings dialog: Several small text changes

- Settings dialog DDS: When DDS had been switched on but was not active (AutoSync Mode) some cards did not allow to use double or quad of the currently incoming sample frequency (necessary for example in SMUX operation).

- TotalMix: Added support for Faderfox TM1 remote control

- TotalMix: Mackie Control F16 now activates Post mode

- Fixed factory presets HDSPe MADI and MADIface to have -12 dB for submix on channels 63/64.

----------------------

Update 3.068, 08/22/2008

- HDSPe PCI (Multiface/Digiface) now supports the TCO. This requires firmware 14.*

- TotalMix: OVER LED moved by one pixel.

- TotalMix: The folder for custom bitmaps must now have the name bmp_hdsp (before bmp). This change allows to have different custom bitmaps for the Fireface mixer (bmp) and the HDSP mixer (bmp_hdsp).

- WDM: The Settings dialog of HDSP 9652 and Digiface allows to limit the number of WDM devices. The entered number is checked for validity.

- Factory presets of HDSPe MADI / MADIface fixed.

- Vista: MMCSS can be enabled in the Settings / About dialog (not recommended)

*Note: This version supports ASIO timecode (APP) only, converting LTC to MTC is not supported. Please note that the hardware design requires to use an additional word clock cable in the folling case:
Generating an audio clock out of the incoming timecode requires a BNC cable from the TCO's word clock output to the word clock input of the Multiface/Digiface. In the Settings dialog Pref. Sync Ref has to be set to TCO and Clock Mode must be set to AutoSync. If the incoming timecocde is not used to clock the HDSP system the BNC cable is not needed.


----------------------

Update 3.067, 08/07/2008

- Completely new memory routines to prevent BSODs

----------------------

Update 3.066, 08/06/2008

- WDM: Speaker setup defines 6 or 8 channel playback

- Support for DirectMusic MIDI added


-----------------------


Copyright RME 11/2012
All rights reserved. Windows XP/Vista/7/8 are trademarks of Microsoft Corporation. ASIO is a trademark of Steinberg Media Technologies GmbH.

