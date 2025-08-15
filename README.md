# M.2/mPCIe KiCAD Library

## A modern M.2/mPCIe footprint library

Handmade following the [PCI Express M.2 Electromechanical Specification Revision 1.0](https://web.archive.org/web/20200613074028/http://read.pudn.com/downloads794/doc/project/3133918/PCIe_M.2_Electromechanical_Spec_Rev1.0_Final_11012013_RS_Clean.pdf) and the [PCI Express Mini Card Electromechanical Specification Revision 1.2](https://web.archive.org/web/20250508025852/https://heap.ovh/files/mPCIe-electromechanical.pdf).

## Status

- ✅: Done & KLC compliant
- ☑️: Done
- 📶: Has antenna variant
- 🚧: WIP
- ✖️: Not Planned
- ❌: Not in spec

### M.2 Card form-factor

|         	| 2230 	| 2242 	| 2260 	| 2280 	| 22110 	| 1630 	| 3030 	| 3042 	|
|---------	|------	|------	|------	|------	|-------	|------	|------	|------	|
| Key A   	| ☑️📶    	| ❌    	| ❌    	| ❌    	| ❌     	| 🚧    	| ☑️📶    	| ❌    	|
| Key B   	| ☑️    	| ☑️    	| ☑️    	| ☑️    	| ☑️     	| ❌    	| ❌    	| ☑️📶    	|
| Key E   	| ☑️📶   	| ☑️📶\*  	| ❌    	| ❌    	| ❌     	| 🚧    	| ☑️📶    	| ❌    	|
| Key A+E 	| ☑️📶    	| ☑️📶\*   	| ❌    	| ❌    	| ❌     	| 🚧    	| ☑️📶    	| ❌    	|
| Key M   	| ☑️    	| ☑️    	| ☑️    	| ☑️    	| ☑️     	| ❌    	| ❌    	| ❌    	|
| Key B+M 	| ☑️    	| ☑️    	| ☑️    	| ☑️    	| ☑️     	| ❌    	| ❌    	| ❌    	|
| Key G 	| ✖️    	| ✖️    	| ✖️    	| ✖️    	| ✖️     	| ✖️    	| ✖️    	| ✖️    	|

<sub>[\*] Technically not in spec, but widely used.</sub>

### M.2 Soldered-down form-factor

|        	| 2226 	| 1216 	| 3026 	|
|--------	|------	|------	|------	|
| All Keyings 	| 🚧    	| 🚧    	| 🚧    	|

### Mini PCI Express form-factor
| Full-Mini (F2) | ☑️ |
|----------------|---|
| Half-Mini (H2) | ☑️ |

## M.2 PCB design considerations

Some PCB design considerations couldn't be specified in the footprint, so they will be here.

- You *must* have a PCB stackup that is 0.8mm in thickness.

- You *should* use ENIG (chemical gold plating) on the M.2 connector, to guarantee the longevity is within spec.

- You *should* have the PCB connector edge chamfered at 20° to facilitate insertion and removal. (diagram 2.3.5.1, page 38)

## Mini PCI Express PCB design considerations

You *must* have a PCB stackup that is 1mm in thickness.

You *should* use ENIG (chemical gold plating) on the edge connector, to guarantee the longevity is within spec.

You *should* have the PCB connector edge chamfered at 45° to facilitate insertion and removal. (diagram 2-6, page 18)

Generally, reading the spec is not a bad idea to design a good card.
