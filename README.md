# Tiny M - Build log


### 17 Dec 2020
This will be a build log for my [Tiny-M](https://github.com/gsl12/Tiny-M) 3d printer.
I am planning to build a Tiny-M printer (which is in fact based on the Voron V0).
I'm still thinking if I should go for a Duet board or with a classic SKR Mini v2 which is way cheaper.
Things I need to figure out:
- find a list of vendors of 3d printer parts in France (since I recenly moved here and I want to get the best prices regarding shipping). - voron french discord group might be of help here
- find someone French or EU based that will be able to print the necessary parts - voron french discord group might be of help here as well
- study both V0 and Tiny-M step files, as well as [Xile's direct drive mod](https://github.com/Annex-Engineering/Sherpa_Mini-Extruder/tree/master/Toolheads/Xile_Tiny_M).
- figure out a rough total price and keep a [BOM](https://docs.google.com/spreadsheets/d/11mWE8fa2zXY_roV_JzbzSrPQFXFBaSaLcBKmSTfmr1g/edit) with links

#### Later edit 1:
These are the sites that I received:

- https://schraube-mutter.de/verbindungstechnik/muttern/
- https://fermio.xyz
- https://vonwange.com

One guy on the french voron/tinyM channel offered to help with screws & printed parts: iBLtz V2.400 :heart:

### 22 Dec 2020
Ok, so after downloading both step files, I started comparing the two designs: V0 and Tiny-M. Since the Tiny-M doesn't have a comprehensive guide like the Voron does ([manual](https://raw.githubusercontent.com/VoronDesign/Voron-0/master/VORON-0/Manuals/V0_Assembly_Manual.pdf) + [videos online](https://youtube.com/playlist?list=PLYQE46AVOibjHqGDk8tMlNDkAp-pmlN4l)), I don't wanna screw things up so I'm the kind of person that **needs** to know the differences.
Hence, I decided to spend a few hours navingating the two designs in Fusion, hide and unhide parts, measure things, compare parts, etc.

Here are the two step files:
- https://github.com/gsl12/Tiny-M/blob/master/CAD/ass_Tiny-M%20V0_step_11_july_2020.zip
- https://github.com/VoronDesign/Voron-0/blob/master/VORON-0/CAD/V0_Assembly_Rev2.rar

![Side by side comparison](https://i.imgur.com/0tDkg4X.png "Side by side comparison")

I also made a small comparison table to note the biggest differences:

↘︎| Tiny-M | V0
--- | --- | ---
Width size <sub><sup>*</sup></sub> | 300mm  |  230mm
Depth size <sub><sup>*</sup></sub> | 300mm | 230mm
Height size <sub><sup>**</sup></sub> | 366.2mm | 280mm
Print area | 150x150x150 mm<sup>3</sup> | 120x120x120 mm<sup>3</sup>
Extrudsion type | 2020 Nut 5 I-Typ alu | 1515 Makerbeam XL
Motors | Nema 17 | Nema 14 
Rails type XY | MGN9H | MGN7H
Rails type Z | MGN12H | MGN7H

<sub><sup>* - without side panels</sup></sub>

<sub><sup>** - with including feet</sup></sub>

Most printed parts are more or less the same ase V0 - most of the time only the size/scale of things are a bit different.







