# Firmware
These are the necessary firmwares for board for different modes. These files are used by FT_Prog found in the Utility folder. 

* *isoUSBRS422_v1_default.xml*	This is the read configuration from new chip. Given as reference. **Should not be used for production.**
* *isoUSBRS422_v1_RS422.xml* 	RS422 operation. Transmitter and receiver are always enabled. It is suitable for multi-point topology. It is also good for loopback testing. 
* *isoUSBRS422_v1_RS485.xml* 	4-wire and 2-wire RS485. Receiver is always enabled. Transmitter is enabled when there is a transmission otherwise it is in high-z state. It is suitable for multi-drop topology.
* *isoUSBRS422_v1_RS485_sE.xml* 2-wire RS485 with echo suppression. Transmitter works same as the RS485 mode, it is enabled when there is transmission only. Additionally, receiver is disabled when there is a transmission. It is useful to suppress echo during transmission for 2-wire RS485 connection. It is impossible to do a loopback test with this mode.

*15461*