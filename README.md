# M.2 KiCAD Library

## A modern M.2 footprint library

Handmade following the [PCI Express M.2 Electromechanical Specification Revision 1.0](https://web.archive.org/web/20200613074028/http://read.pudn.com/downloads794/doc/project/3133918/PCIe_M.2_Electromechanical_Spec_Rev1.0_Final_11012013_RS_Clean.pdf)

## Status

- ✅: Done & KLC compliant
- ☑️: Done
- 📶: Has antenna variant
- 🚧: WIP
- ✖️: Not Planned
- ❌: Not in spec

### Card form-factor

|         	| 2230 	| 2242 	| 2260 	| 2280 	| 22110 	| 1630 	| 3030 	| 3042 	|
|---------	|------	|------	|------	|------	|-------	|------	|------	|------	|
| Key A   	| ☑️📶    	| ❌    	| ❌    	| ❌    	| ❌     	| 🚧    	| 🚧    	| ❌    	|
| Key B   	| ☑️    	| ☑️    	| ☑️    	| ☑️    	| ☑️     	| ❌    	| ❌    	| ❌    	|
| Key E   	| ☑️📶   	| ☑️📶\*  	| ❌    	| ❌    	| ❌     	| 🚧    	| 🚧    	| ❌    	|
| Key A+E 	| 🚧    	| 🚧*   	| ❌    	| ❌    	| ❌     	| 🚧    	| 🚧    	| ❌    	|
| Key M   	| ☑️    	| ☑️    	| ☑️    	| ☑️    	| ☑️     	| ❌    	| ❌    	| ❌    	|
| Key B+M 	| ☑️    	| ☑️    	| ☑️    	| ☑️    	| ☑️     	| ❌    	| ❌    	| ❌    	|

<sub>[\*] Technically not in spec, but widely used.</sub>

### Soldered-down form-factor

|        	| 2226 	| 1216 	| 3026 	|
|--------	|------	|------	|------	|
| All Keyings 	| 🚧    	| 🚧    	| 🚧    	|

## PCB design considerations