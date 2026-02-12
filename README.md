<h1 align="center">Techne-300</h1>

<p align="center">
  <img src="https://github.com/65294f/techne-300/blob/main/Assets/Techne-300%20(2).png" alt="wiring"
  width="30%">
</p>

Inspired by builds like Chris Borges printed CNC. Using thin-walled prints with threaded rods and concrete to add weight and structure for a budget. 
The Techne-300 is a simple CNC mill primarily made of 3D printed and readily available parts. It is designed for consistent milling for prototyping, with a total cost between 350 and 500 dollars depending on where parts are sourced. 

<h4 align="center">
  BOM at the bottom of the README and 
<a href="https://docs.github.com)](https://github.com/65294f/techne-300/blob/main/Techne-300%20-part-list.csv">Part-list for amounts, stls, filament, and print time for 3d printed parts.</a>
</h4>

I wanted to make this to help my FTC team quickly prototype parts that would normally take weeks to make or get. We have tons of innovative design ideas that are impossible for us to bring into reality without a CNC machine. This build is supposed to be iterated and improved over time for whatever application is needed. I wanted to make an interesting machine, something that hadn’t been made before — that’s why I went for the movement and the structure that I designed.

<h1 align="center">Design</h1>
This design started on paper, just small ideas that compounded into the machine you see now.

<p align="center">
  <img src="https://github.com/65294f/techne-300/blob/main/Assets/IMG_0873.jpeg" alt="wiring"
  width="40%">
</p>

<p align="center">
  <img src="https://github.com/65294f/techne-300/blob/main/Assets/IMG_0875.jpeg" alt="wiring"
  width="40%">
</p>

The designs were further refined in CAD into what is the Techne-300.

<p align="center">
  <img src="https://github.com/65294f/techne-300/blob/main/Assets/Screenshot%202026-02-10%20180413.png" alt="wiring"
  width="60%">
</p>

<p align="center">
  <img src="https://github.com/65294f/techne-300/blob/main/Assets/Screenshot%202026-02-10%20180334.png"
  width="60%">
</p>

<p align="center">
  <img src="https://github.com/65294f/techne-300/blob/main/Assets/Screenshot%202026-02-10%20180436.png" alt="wiring"
  width="60%">
</p>

For this project I used:
<h4>
<a href="https://github.com/winder/Universal-G-Code-Sender">Universal-G-Code-Sender</a>
</h4>
<h4>
<a href="https://www.onshape.com/en/">OnShape</a>
</h4>
For inspiration: <h4>
<a href="https://www.youtube.com/watch?v=L8t82OQXefM">Chris Borges</a>
and 
<a href="https://www.youtube.com/watch?v=ctyLjOHg7Ag">Ivan Miranda</a>
</h4>

<h1 align="center">Bill of materials</h1>



| Part | Link | Amount | Price |
|------|------|--------|-------|
| (Purchased) Threaded Rod 1/4 in. x 6 ft | [Home Depot](https://www.homedepot.com/p/Everbilt-1-4-in-x-6-ft-Zinc-Plated-Steel-Threaded-Rod) | x4 | $23.92 |
| (Purchased) Hex Nut 1/4 in. | [Home Depot](https://www.homedepot.com/p/1-4-in-20-Zinc-Plated-Hex-Nut) | x1 | $2.18 |
| (Purchased) Concrete Mix 80 lb. | [Home Depot](https://www.homedepot.com/p/Quikrete-80-lb-Concrete-Mix) | x1 | $5.98 |
| MGN12 Linear Rail Guide 500mm | [Amazon](https://amazon.com/gp/product/B0119BUKVW) | x2 | $68.99 |
| Nema 17 Stepper | [Amazon](https://www.amazon.com/STEPPERONLINE-Stepper) | x3 | $31.97 |
| Aluminum 5mm Bore 2GT Pulley | [Amazon](https://us.amazon.com/Aluminum-Pulley-Synchronous) | x2 | $25.98 |
| GT2 Belt 150mm Length 75 Teeth | [Amazon](https://www.amazon.com/uxcell-Timing-Closed) | x1 | $9.99 |
| 5mm x 100mm Steel Rod | [Amazon](https://www.amazon.com/uxcell-Stainless) | x1 | $6.59 |
| 10 Teeth HTD 5M | [AliExpress](https://www.aliexpress.us/item) | x2 | $13.81 |
| Ball Bearings | [Amazon](https://us.amazon.com/HARFINGTON-Groove) | x1 | $9.49 |
| Flanged Ball Bearings | [Amazon](https://www.amazon.com/F605ZZ-Miniature) | x1 | $9.99 |
| 150mm Lead Screw | [Amazon](https://www.amazon.com/LICTOP-Diameter) | x1 | $12.49 |
| 60 Teeth Pulley | [Amazon](https://www.amazon.com/8mm-Bore-60-Teeth) | x1 | $9.49 |
| Power Supply | [Amazon](https://www.amazon.com/ALITOVE-Transformer) | x1 | $17.99 |
| CNC Shield | [Amazon](https://www.amazon.com/AITIAO-DRV8825) | x1 | $15.99 |
| Emergency Stop | [Amazon](https://www.amazon.com/mxuteuk-Stainless-Emergency) | x1 | $13.99 |
| Timing Belt | [Amazon](https://www.amazon.com/uxcell-Timing-Length) | x1 | $19.99 |
| 500mm MGN12 Linear Rail | [Amazon](https://www.amazon.com/Linear-Stainless) | x2 | $57.98 |
| 20x20 Extrusion | [ZYLtech](https://www.zyltech.com/2020-t-slot-aluminum-extrusion) | x2 | $7.90 |
| Heated Inserts | [Amazon](https://www.amazon.com/Yaocom-Inserts-Threaded) | x1 | $9.99 |
| Micro Limit Switch | [Amazon](https://us.amazon.com/HiLetgo-KW12-3-Roller-Switch-Normally/dp/B07X142VGC/ref=sr_1_1?crid=KPHU5Q5MLPZV&dib=eyJ2IjoiMSJ9.CRkRhZ-JiEm5GgIiGEGZZQU9fgowsX_u7OXY3PVkHUkQFBo2WuuER34YGtZ-AL_peIuh1SrrimQqKqDGdVDxBAZZSBpVx1_-LhmXcbLalGKyyv7rRMRWjYK92WwdJBCt_qVVso0OnoVMR-UWsa_B-RQhRMQ50Yzc-ARrH_gWnfYAT9A5jCSg8RJ1GJQILfCeb-THpisAnGtz5vBtu7WStYpLyo8tlZxywTn2qmLfDZNJHyUyF_YIDFA_w67wFdvezImtaaTJKcewCrTPw4bgEjj7xba2AkiAURzQfktcffA.rjgLybM47uwMv4XpdMSOFXquqSt7RXFPN9B2Mk0y9G8&dib_tag=se&keywords=micro+switch&qid=1770578322&s=industrial&sprefix=micro+switch+%2Cindustrial%2C200&sr=1-1) | x1 | $5.99 |
| M3 Screws Assortment Kit | [Amazon](https://www.amazon.com/Screws-Assortment) | x1 | $7.99 |
| M3 T Nuts | [Amazon](https://www.amazon.com/HELIFOUNER-Pieces-2020) | x1 | $4.99 |
| (Purchased) 4kg PLA | [Amazon](https://us.amazon.com/SUNLU-2-0-Filament) | x1 | $42.99 |
