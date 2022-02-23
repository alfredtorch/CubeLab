![OverViewPSULoadSignal](https://user-images.githubusercontent.com/38537119/149653142-db223177-ef2d-45b5-9a63-e9331920b4f2.jpg)

# CubeLab
Small electronic tools for trouble-less prototyping and debugging!
* 2x USB 5V-3A output for light sticks, power your arduino or charge your phone 
* Modular fixation based on camera tripod screw (endless possibilites with ball head, magnetic or suction cup ...)
* USB-C powered, so it can run also from a power bank, or ♻️ recycle your old laptop charger...  


Flexible fixation | Standard Components | Many plug possibilities
--- | --- | ----
<img width="344" alt="image" src="https://user-images.githubusercontent.com/38537119/149670741-7076fe5e-8bbc-4755-86a9-3d7c91b413e8.png"> | <img width="342" alt="image" src="https://user-images.githubusercontent.com/38537119/149670761-4bdf0e61-8876-4396-8914-44c2a105d40a.png"> | <img width="343" alt="image" src="https://user-images.githubusercontent.com/38537119/149670777-4d768808-8813-4bf3-be92-5018438204c5.png">


# 🛍 Basic Equipement & BoM

### 🛒 BoM
Part Name | Quantity | Price | Supply Link | Notes 
--- | --- | --- | --- | ---
USB-C Trigger | 1x | 2€ | [Aliexpress](https://s.click.aliexpress.com/e/_ATlhPz) [Amazon](https://amzn.to/33yQBKh) | Different options 5-20V - best 20V
Dual USB Converter | 1x | 4€ | [Aliexpress](https://s.click.aliexpress.com/e/_AS1GbZ) [Amazon](https://amzn.to/3KiBt4q) | Based on LM2596 DCDC Module 5V@3A
2,5 mm Jack Input| 1x | 0,1€ | [Aliexpress](https://s.click.aliexpress.com/e/_AmPKvl) | 5,5x2,1
Banana Plugs | 1x | 0,1€ | [Aliexpress](https://s.click.aliexpress.com/e/_A6h9jV) | Needs to have flat (nonthreaded) internal connector (short circuit)
Screw M3x10mm | 4x | [Aliexpress](https://s.click.aliexpress.com/e/_9hzJqX) |

### 🛠 Tools
Laser Cutter | [Maps](https://www.fablabs.io/labs/map) | Easy access to an local Fablab with your dxf files
Drill Tap M3 | 1x | 3€ | [Aliexpress](https://s.click.aliexpress.com/e/_ADUi5N) | for 2,5mm bore holes in plexi pieces
Solder Iron | 1x | 45€ | [Aliexpress](https://s.click.aliexpress.com/e/_9799pH) | To solder USB-C 

### 🧱 Raw Material
Part Name | Quantity | Price | Supply Link | Notes 
--- | --- | --- | --- | ---
Heat Shrinking | 1x | 1,5€ | [Aliexpress](https://s.click.aliexpress.com/e/_9Hk3YT) | To avoid short circuit (mainly on banana plugs)
Wire Block Clamp | 1x | 13€ | [Aliexpress](https://s.click.aliexpress.com/e/_AYUJzl) | Optional if you want to avoid soldering
Silicon Glue | 1 | 3€ | [Aliexpress](https://s.click.aliexpress.com/e/_ANanVD) | Any strong glue - good results with this one
Silicone Wire 20-28AWG| 1x | [Aliexpress](https://s.click.aliexpress.com/e/_APnuy7) | Smooth flexible wire to hassle-free assembly
Wood & Plexi 3mm | less 1m2| Source from your local hardware store

## 🔌 CubeLab:PSU

A portable power supply. Compact solution to delivery energy to your workbench. Possible bluetooth connectivity or [hack](https://github.com/kanflo/opendps) it yourself to wifi capabilities. 
<p align="center">
<img width="444" alt="image" src="https://user-images.githubusercontent.com/38537119/150142559-dfa176cd-baff-4a33-a61c-b6ff8e776c20.png" align="center">
</p>

### Technical Overview with 20V USB-C Input
IO|Ratings|Notes
---|---|---
Vinput|20V max|Limited by USB Trigger 
Voutput|26V max|DPS3005 
Vusb||

### [DPS5005](https://amzn.to/33EGl38) Specifications
<p align="center">
<img width="300" alt="image" src="https://user-images.githubusercontent.com/38537119/149657625-68d4345a-e622-45b6-9420-037aef4f8245.png">
</p>

Ratings | Values
--- | ---
Input Voltage Range | 6-40V DC
Output Voltage Range | 0-32V 
Output Current Range | 0-5A
Output Power Range | 0-160W
Output Voltage Resolution | 0.01V 
Output voltage accuracy | ± (0.5% +1). 
Output current resolution | 0.001 A 
Output current accuracy | ± (0.5% +2). 
Protection function | Reverse connection protection & Output short circuit protection
Dimensions |  8 x 4.5 x 4.5 cm; Weight: approx. 115g

### USB-C Trigger Specifications
<p align="center">
 <img width="300" alt="image" src="https://user-images.githubusercontent.com/38537119/149657695-b63b65c2-b19b-4a51-aa57-97a51fc559f9.png">
Best performance 20V - Based on [IP2721](https://datasheet.lcsc.com/szlcsc/2006111335_INJOINIC-IP2721_C603176.pdf)
</p>

Ratings | Values
--- | ---
Absolute Input Voltage Range | -0.3V-30V DC
Recommended Input Range | 3V-25V DC
Output Voltage Range | 0-20V 
Output Current Range | 0-5A
Output Power Range | 0-100W

### USB-5V Module Specifications

<p align="center">
  <img width="300" alt="image" src="https://user-images.githubusercontent.com/38537119/149657646-2f55ee25-7b02-4467-9c5b-f453020dee8d.png">
Based on LM2596
</p>

Ratings | Values
--- | ---
Recommended Input Range | 6-40V DC
Output Voltage  | 5V 
Output Current Range | 0-3A
Output Power Range | 0-15W


# 🛒 BoM
## Parts
Part Name | Quantity | Price | Supply Link | Notes 
--- | --- | --- | --- | ---
DPS3005 PSU | 1x | 28€ | [Aliexpress](https://s.click.aliexpress.com/e/_AUNrVh) [Amazon](https://amzn.to/33EGl38) | Different option - best DPS3005
USB-C Trigger | 1x | 2€ | [Aliexpress](https://s.click.aliexpress.com/e/_ATlhPz) [Amazon](https://amzn.to/33yQBKh) | Different options 5-20V - best 20V
Dual USB Converter | 1x | 4€ | [Aliexpress](https://s.click.aliexpress.com/e/_AS1GbZ) [Amazon](https://amzn.to/3KiBt4q) | Based on LM2596 DCDC Module 5V@3A
2,5 mm Jack Input| 1x | 0,1€ | [Aliexpress](https://s.click.aliexpress.com/e/_AmPKvl) | 5,5x2,1
Banana Plugs | 1x | 0,1€ | [Aliexpress](https://s.click.aliexpress.com/e/_A6h9jV) | 5,5x2,1
Thread M3

Screw M3x10mm | 4x |
Screw 4 Pin Terminal

## 🛠 Tools and 🧱 Raw Material
Part Name | Quantity | Price | Supply Link | Notes 
Wood & Plexi 3mm | | | |
Silicone Wire | | [Aliexpress]https://s.click.aliexpress.com/e/_APnuy7
Silicon Glue | 1 | 3€ | [Aliexpress](https://s.click.aliexpress.com/e/_ANanVD) | Any strong glue - good results with this one
Laser Cutter | Easy acess with a local Fablab
Drill Tap M3 | 1x | 3€ | [Aliexpress](https://s.click.aliexpress.com/e/_ADUi5N) 
Solder Iron & Electrical Wire 20-28AWG 



Alternative Wago
Screw Terminal | Pluggable Terminal
--- | ---
<img width="344" alt="image" src="https://user-images.githubusercontent.com/38537119/150144124-4f49fa67-e8c0-44e6-853a-6a6dea6957e4.png"> | <img width="344" alt="image" src="https://user-images.githubusercontent.com/38537119/150144242-79ab81bf-65b5-4a93-aa34-15ac3d86cbd8.png">



# 🛠 Assembly
* Laser Cut the files



# License & Disclaimer

Affiliates partner links on Amazon
