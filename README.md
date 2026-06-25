# Avzaman-Voron-Switchwire
Mods and configurations for the Voron Switchwire build.

Printer: Voron Switchwire

Toolhead: Voron Stealthburner

Extruder: Voron Clockwork2

Hotend: Phaetus Dragonfly BMO - 0.4mm Brass Nozzle

Bed Probe: 

Motors XYZ: LDO-42STH40-1684AC
	1.8° Nema 17 Stepper
	Run Current = 

Motor E: Moons CSE14HRA1L410A-01
	1.8° Nema 14 Stepper
	Run Current =

Electronics
MCU: Orange Pi 4 LTS V1.2
Mainboard: BTT SKR Mini E3 V2.0
PSU: Meanwell LRS-350-24V
PSU: Meanwell RS-25-5V
Toolhead Board: BTT EBB SB2209 CAN V1.0
CANBus Board: BTT U2C V2.1
LCD: mini12864

Mods
Double Shear Motor Mounts - @nhchiu
More Robust XZ Belt Paths - @yenda
	*only use XZ blocks and upper support parts. Use motor mounts from the double shear mod instead.
Y Tensioner - @RobotRogue
U2C Mounting - @samwiseg0
Orange Pi 4 Mount - @SavidDanders
LDO - @LDO Motors
	counterweight_wheel.stl
	heatbed_terminal_cover.stl
	led_pcb_mount.stl
	wago_221-413_3x3_vertical_mount.stl
EBB SB2240_2209 CAN - @BTT
	Cable_Cover_EBB.stl
	Main_Body_EBB.stl
	CW2 Cable BRidge.STL
	Printed Part for USB-C Cable.STL
	Printed_Part_for_CAN_Cable_V1.2.stl
	Cable Clip Printed Part.STL
  
| Mod                           | Download    | Description                                                                                                                                                                                                                                                                                                                                               | Photo |
|-------------------------------|-------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------|
| Double Shear Motor Mounts - @nhchiu | [Printables](https://www.printables.com/model/1013691-voron-switchwire-double-shear-motor-mount)                            | Double shear support and more robust printed parts.                                                                                                                                              |![Double Shear Motor Mounts - @nhchiu](https://github.com/SavidDanders/Avzaman-Voron-Switchwire/blob/main/Images/Double%20Shear%20Motor%20Mounts%20-%20%40nhchiu.png)       |
| More Robust XZ Belt Paths - @yenda  | [Git](https://github.com/VoronDesign/VoronUsers/tree/main/printer_mods/yenda/vsw_more_robust_belt_paths)                    | Only use XZ blocks and upper support parts. Use motor mounts from the double shear mod instead..                                                                                                                            |![More Robust XZ Belt Paths - @yenda](https://github.com/SavidDanders/Avzaman-Voron-Switchwire/blob/main/Images/More%20Robust%20XZ%20Belt%20Paths%20-%20%40yenda.png)       |
| Y Tensioner - @RobotRogue           | [Printables](https://www.printables.com/model/387081-voron-switchwire-y-tensioner-mod/files)                             | Easier to set tension for the Y axis.                                                                                                                                            |![Afterburner PCB Mod](https://github.com/SavidDanders/SavidDanders-Ender-Switchwire/blob/main/Images/PCB.png?raw=true)       |
| Afterburner Microswiss Hotend | [Thingiverse](https://www.thingiverse.com/thing:4826740)                                                              | Instead of buying a new hotend I decided to re-use the Trainglelabs Micro-Swiss clone. Since it's all metal it has no issues printing ABS                                                                                                       |       |
| hymness1 Quickdraw ABL Probe  | [Git](https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/hymness1/Quickdraw_probe_Voron_Switchwire)   | I skipped the inductive probe and went straight to Quickdraw. The Quickdraw probe is mechanical so the reading shouldn't change as temps fluctuate. Only downside is losing some build volume on the x-axis since the probe need space to dock. |![Original Switchwire ABL Probe](https://github.com/SavidDanders/SavidDanders-Ender-Switchwire/blob/main/Images/quickdraw_SW_remix.png?raw=true)       |
| Mairis Skuja (Iconic FAB) Klicky Dock       | [Printables](https://www.printables.com/model/949854-clicky-quickdraw-probe-dock-arm-for-ender-sw-voron) | The standard Quickdraw dock doesn't fit the Ender frame. I use the adjustable dock with heatset arm.                                                                                                                                            |       |
| yenda More Robust Belt Paths  | [Git](https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/yenda/vsw_more_robust_belt_paths)            | I prefer this XZ motor assembly design over the stock ones.                                                                                                                                                                                     |![Robust XZ Motor Mounts](https://github.com/SavidDanders/SavidDanders-Ender-Switchwire/blob/main/Images/Robust_XZ.PNG?raw=true)       |
| Nevermore Micro V4            | [Git](https://github.com/nevermore3d/Nevermore_Micro)                                                                 | Activated carbon filter to reduce ABS fumes.                                                                                                                                                                                                    |![Nevermore V4 Carbon Filter](https://github.com/SavidDanders/SavidDanders-Ender-Switchwire/blob/main/Images/Nevermore_V4.png?raw=true)       |
| Klicky Probe                  | [Git](https://github.com/jlas1/Klicky-Probe/tree/main/Printers/Voron/Switchwire)                                      | Replacing the Quickdraw probe with Klicky. This will allow me to take back some space on the X-axis while still using a button switch for accurate bed meshing.                                                                                 |![Klicky Switchwire Probe](https://github.com/SavidDanders/SavidDanders-Ender-Switchwire/blob/main/Images/Klicky_SW.jpg?raw=true)       |
| SavidDanders Beeg Y-Motor     | [Git](https://github.com/SavidDanders/SavidDanders-Ender-Switchwire/tree/main/Beeg%20Y-Motor%20Mod)                   | Overhalls the Y-Axis assembly to allow for larger motors while keeping everything inside the enclosure.                                                                                                                                         |![Beeg Y-Motor Mod](https://github.com/SavidDanders/SavidDanders-Ender-Switchwire/blob/main/Images/y_motor.PNG?raw=true)        |

Filament
Polymaker ASA - Black
Polymaker ASA - Pop Pink
