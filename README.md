# Breakout PCB for RFM69W radio transceiver 

Eagle CAD PCB designs for radio transceiver breakout boards. 
Converts the RFM69W radio transceiver from SMT to 0.1" breadboard format.  

See the following link for drivers for the RFM69W
  * https://github.com/LowPowerLab/RFM69

Hookup of the breakout board to 5V Arduino SPI connection.  All board components populated.

	Arduino	RFM69W BOB
	5V	<-->	5V
	GND	<-->	GND
	D11	<-->	SDI
	D12	<-->	SDO
	D13	<-->	SCK
	D10	<-->	SEL
	D2	<-->	IRQ
 
Hookup of the breakout board to 3.3V Arduino SPI connection.  On PCB populate radio, C2 and C3 only.

	Arduino	RFM69W BOB
	3.3V	<-->	3.3V
	GND	<-->	GND
	D11	<-->	SDI
	D12	<-->	SDO
	D13	<-->	SCK
	D10	<-->	SEL
	D2	<-->	IRQ
 

## Order PCBs  

You will be able to order any of these PCBs from OSH Park.  Click on one of the following links.
  * Radio Breakout - http://oshpark.com/shared_projects/bJRprI06  

## Status
  * PCB layout tested not yet tested, board has been ordered   

## File Formats  

Design files are in "CadSoft EAGLE PCB Design Software" .brd and .sch formats.  
A free version of the software can be downloaded from www.cadsoftusa.com.  

## Distribution License  

All PCB designs in this repo are Public Domain.  No liability accepted.  