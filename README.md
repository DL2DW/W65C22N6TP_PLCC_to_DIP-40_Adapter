# W65C22N6TP PLCC to DIP-40 Adapter



![](https://github.com/DL2DW/W65C22N6TP_PLCC_to_DIP-40_Adapter/blob/main/Images/6522PLCC-Adapter.jpg)



The company WDC (Western Design Center), not to be confused with Western Digital, had released a new edition of the well-known MOS 6522 Versatile Interface Adapter a few years ago.

Among other things, there are also NMOS compatible versions with the "N" versions, which can be dipped directly with the old versions of MOS/CSG or Rockwell.

It is important to pay attention to the type. There are two series, once the W65C22N and the W65C22S. The latter "S" version cannot be used as a replacement for the old devices due to the output circuitry.



## PLCC-Version

There is also a SMD version as 44 pin PLCC. This version is often a bit cheaper, as 40 pin DIP version for through hole mounting.

Because I once had a few dozen of these in stock, I developed a simple adapter that simply adapts from the 44-pin PLCC housing to a 40-pin DIP chip.

So you can easily use a PLCC version in a device that was actually intended for a 40 pin DIP version.




## Assembly

![](https://github.com/DL2DW/W65C22N6TP_PLCC_to_DIP-40_Adapter/blob/main/Images/6522PLCC-Adapter_assembled.jpg)



The adapter therefore also consists only of a 44-pin PLCC socket and two 20-pin headers, preferably with precision turned pins.

There is nothing special to consider when assembling. I recommend soldering the two pin headers first, and then the PLCC socket. 

Then plug the W65C22N into the socket; done. After that, the adapter board can simply be plugged into the corresponding socket, which normally contains a 40 pin DIP version of a 6522.



## BOM



- 2x Precision Pin Header, Pitch= 2,54mm, 20pos.
- 1x PLCC-44 Socket, THT



## PCB

The PCB can either be ordered directly from [PCBWay](https://www.pcbway.com/project/shareproject/W65C22N6TP_PLCC_to_DIP_40_Adapter.html), or you can create it yourself from the Gerber files available here.

[![PCBWay](https://www.pcbway.com/project/img/images/frompcbway.png)](https://www.pcbway.com/project/shareproject/W65C22N6TP_PLCC_to_DIP_40_Adapter.html)



If you liked my project, I would be very happy about a small coffee donation.

[![ko-fi](https://www.ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/R6R62T6RN)



# License

The contents of this repository, with the exception of the Docs and Software directories, are released under the following license:

- the "Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License" (CC BY-NC-SA 4.0) full text of this license is included in the [LICENSE.CC-NC-BY-SA-4.0](https://github.com/DL2DW/W65C22N6TP_PLCC_to_DIP-40_Adapter/blob/main/LICENSE.CC-NC-BY-SA) file and a copy can also be found at https://creativecommons.org/licenses/by-nc-sa/4.0/
