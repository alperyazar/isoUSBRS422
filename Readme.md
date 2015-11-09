# isoUSBRS422

isoUSBRS422 is an **isolated** USB <-> RS422/RS485 converter board (~5x5 cm). It should work with Windows, Linux and MacOSX (not fully tested for all operating systems by me).

You can find video tutorials and other details on the project web page:

http://www.alperyazar.com/r/isoUSBRS422v1

**THIS PROJECT IS PUBLISHED UNDER CC BY-NC-SA 4.0 LICENSE**

**AS IS, ABSOLUTELY NO WARRANTY**

## Folders

* *BOM* Contains bill of materials of board

* *Driver* Contains necessary drivers. Online Windows 7 (and probably newest versions) should install driver automatically. If you are running on an offline machine you may use drivers at that folder. However, I strongly recommend to get the newest driver from USB chip vendor website: **http://www.ftdichip.com/Drivers/VCP.htm** I won't update drivers at that folder when FTDI publishes new drivers. They are latest drivers at that time.

* *Firmware* Contains profile file for utility called FT_Prog (contains in Utility folder). Once you finish isoUSBRS422 board, FT230x will not work as RS422/RS485 converter. This chip should be programmed only once. You may use the given profiles for proper operation.

* *Gerber* Contains Gerber files for PCB production. You may produce exactly same board as mine using these files.

* *KiCad* Contains KiCad project files. My KiCad version is (2013-07-07 BZR 4022)-stable. You should able to open project files and edit according to your needs (please consider license).

* *PCB* Contains ZofzPCB (see: http://www.alperyazar.com/r/jHtc3 ) rendered board file and some computer generated images of PCB.

* *Schematic* Contains PDF of schematic.

* *Utility* Some programs to program isoUSBRS422 board an test it.

*You are always welcomed to contact me: http://www.alperyazar.com/contact*

*15461*