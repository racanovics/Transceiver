###NOTES

####CC1101FH library

#####GDO0 signal
* Wired to Arduino D2 (interrupt 0)
* Register IOCFG0 (addr 0x02) default is 0x3F CLK_XOSC/192 
* Overridden by configuration header with 0x06 sync sent/received
* Might be used for interrupt instead of polling method currently
used.

#####GDO2 signal
* Wired to Arduino D9 (nothing special)
* Register IOCFG2 (addr 0x00) default is 0x29 CHP_RDYn
* Not used

