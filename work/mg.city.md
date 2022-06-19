#up/mg general strategy and utils

[😊#up/mg general strategy and utils](http://47.111.95.20:6001/user/1/start/%23up%2Fmg%20general%20strategy%20and%20utils)

## [[2022-06-16]]
- [ ] mPowerSimple, move it to easyeda
- [ ] test out mPowerSimple boards

- [ ] CN3704
	- [ ] constant current set by external resistor
	- [ ] constant voltage charging sets voltages at 16.8V
	- [ ] deeply discharged battery, chip charges at 15% of the current set by resistor
	- [ ] charges finished at current set by external resistor
	- [ ] when voltage drops below 16v, a new charging cycle begins
	- [ ] when Vin drops below battery voltage, chip enters sleep mode
## [[2022-04-06]]

![[jlc.com.jpg]]

- TVS transient voltage suppressor diode
	- [(187) How to Select a Diode?? | TVS diode Selection | What is TVS Diode? - YouTube](https://www.youtube.com/watch?v=d6jllSmmwkE)
	- Vrwm reverse standoff voltages
	- Vbr breakdown voltage
	- Ipp max surge current
	- Vc clamping voltage
- [(188) Electronic Basics #31: Schottky Diode & Zener Diode - YouTube](https://www.youtube.com/watch?v=GtH8lAzQf2A)
	- schottky diode has lower forward voltage
- [How to Select a TVS Diode for Maxim's IO-Link Devices](https://www.maximintegrated.com/en/design/technical-documents/app-notes/6/6965.html)
	- **Reverse Breakdown Voltage (VBR)**  Also known as breakdown voltage, this is the voltage threshold at which the TVS diode begins to conduct a specified amount of current. Voltage VBR should not exceed the abs max rating for the IC it is protecting.

## [[2022-04-03]]
- ![[mp2225 inductor selection.png]]
	- 9x(18-9)/18/500k/1A = 9*(18-9)/18/500000/1) = 9uH
- SMAJ20A transient voltage protection
	- 


## [[2022-04-01]]

[[孙老师dc-dc4]]


## [[2022-03-30]]
- [[altium create component footprint and PCB layout]]

- ## 2022-03-29
	- [MP2225GJ-Z Monolithic Power Systems Inc. | Integrated Circuits (ICs) | DigiKey](https://www.digikey.com/en/products/detail/monolithic-power-systems-inc/MP2225GJ-Z/7361392)
	- FB = 0.6V
	- [[smd resistor values]]
	- 0.6/6.04*(84.5+6.04)

### components
- MP2225GJ-Z TSOT23-8
	- [[TSOT23]]
	- [[altium create schematic component]]
	- ![[MP2225 5V-5A reference circuit.png]]

[[孙老师dc-dc5]]

- [一起设计12V转5V模块，开关电源物料怎么选？How to Design 12V to 5V Buck Converter #3: Selection of Materials - YouTube](https://www.youtube.com/watch?v=hwi66PWVf_I)
	- ![[dc-dc buck converter topology.png]]
	- The larger the inductor, the less the ripple
	- Inductor max saturation current needs to be larger than required
	- ![[Inductor inductance vs Istat.png]]
	- ![[dc-dc input capcitor choice.png]]
	- ![[dc-dc output capcitor choice.png]]
	- ![[dc-dc sw frequency.png]]

- [新手不要怕！5分钟带你入门开关电源PCB设计 How to Design 12V to 5V Buck Converter #4: Beginner Guide to PCB Design - YouTube](https://www.youtube.com/watch?v=W3furVRQ9UQ&list=PLBpCr1fi_kFbyh0TMSjQk9jeb3ThH9svX&index=4)
	- MP2315
	- 通顺
	- 防干扰


- 2022-03-19
- Solidworks - Editing Linear Sketch Pattern https://www.youtube.com/watch?v=COJ5z7QHrOE
 - Right click -> edit linear pattern


- 2022/03/17
https://www.cadtek.com/make-threads-solidworks/
		Let’s take the example of a plate with a number of tapped holes. The process for adding these holes during manufacture is to drill the tap holes first and then add the thread using a tap. As the thread is defined by the tap tool, there is no need to model the thread. All we need to know is what thread should be applied and ensure this is annotated on the 2D drawing. This example lends itself perfectly for use with a cosmetic thread.
	
[Simple Hole Thread in SolidWorks](https://www.youtube.com/watch?v=fV1dvy3C7Xw)
![[solidworks-m3-hole-specs.png]]

https://hawkridgesys.com/blog/get-rid-of-funnel-filter-icon-in-solidworks

https://help.solidworks.com/2020/english/SolidWorks/sldworks/t_Scaling_Sketches.htm


2022/03/15

[[solidworks-–-using-the-multi-thickness-shell-setting]]

2022/03/11

Measuring distance in altium

This command can be accessed from the PCB Editor and the PCB Library Editor by:

-   Choosing the **Reports » Measure Distance*- command from the main menus.
-   Using the **Ctrl+M*- keyboard shortcut.

![[mPowerSImpleBoardMeasure.png]]

Solidworks -> Evaluate -> Measure
https://hawkridgesys.com/blog/mastering-the-measure-tool-in-solidworks

2022/03/10 22:06
Slide Cover case
https://www.youtube.com/watch?v=V9DulCD5e_I

