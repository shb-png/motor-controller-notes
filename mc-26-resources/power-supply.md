![](power-supply-3D.png)

the power supply project file schematics are set up as a *flat* schematic (as opposed to hierarchical, like the [power stage](power-stage.md)). this means that there is no top sheet/hierarchy. below listed are the different sheets and what the functionality of the circuits on each are

sheet name: LT8316
![](psu-LT8316.png)

contains the [LT8316](https://www.snapeda.com/parts/LT8316IFE%23PBF/Analog+Devices/view-part) which is a *560VIN Micropower No-Opto Isolated Flyback Controller*. 
- 560VIN
	- this is in reference to the input voltage range, which is from 16V to 560V (600V max)
- micropower
	- referring to the fact that this chip has very low power dissipation (when the chip isn't actively doing anything it enters a standby mode that has a lower switching frequency and quiescent/"inactive" current) 
- no-opto isolated
	- this means that this chip isn't isolating its output through something like an [optocoupler](../learning-materials/optocoupler) but rather it works by looking at the flyback pulse waveform that appears on the tertiary winding on the transformer. 
	- learn more about galvanic isolation [here](../learning-materials/galvanic-isolation.md)
- flyback controller
	- the main attraction
	- means that this chip regulates power in a [switch-mode power supply](../learning-materials/switch-mode-power-supply.md) that uses a coupled inductor ([flyback transformer](motor-controller-notes/learning-materials/flyback-transformer)) to store and transfer energy while providing   isolation between the input and output

the datasheet for the LT8316 can be found [here](https://www.analog.com/media/en/technical-documentation/data-sheets/lt8316.pdf)
