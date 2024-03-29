# The project formerly known as BreakNeck

<p align="center">
  <img src="https://github.com/leddhedd/BreakNeck/blob/main/Images/ArmpitHeightTeaser.png" alt="Header"/>
</p>


Check out the Armchair Engineering Discord, and join the Breakneck User-Project ***[HERE](https://discord.com/channels/1029426383614648421/1071214081236816012)***

## THIS PROJECT HAS EVOLVED
BreakNeck is about to move over to the armchair engineering github, as well as undergoing some changes and additions.

## WE STAND ON THE SHOULDERS OF GIANTS

i want to give a particularly huge thanks to DoubleT, aTinyShellScript, Derpimus, Corvid, Zruncho, Maz, Kmobs, Smokescreens, Zackm0n, ohpvp, DWTas, ByThorsThunder, Frank.af, Kyleisah cBon, many of the members of the annex community and team, as well as many others for getting stuck in, test printing parts, and in some particularly idiotic cases, trialing, fitting and using the toolhead. the 3dp community wouldnt be what it is without the contibution and help of individuals like these, and i certainly wouldnt have completed the project to this level of polish without their help.

Huge thanks to all the guys over at the Armchair Engineering, Voron, and Annex discord for all the help and support in bringing this project together.

## What is this?

if you have stumbled across this repo, you are looking at the predecessor to **ARMPITHEIGHT** , i will leave the following description of what Breakneck was below for some back-lore.

Breakneck was a toolhead designed primarily for the Voron ecosystem, and any other front rail, front belt CoreXY Printer.
The main features and testing focus of the toolhead were remote air cooling, and a deliberate bend in the post-extruder filament path, for the purposes of inducing a bowden-like buffering effect.

## [> > > ASSEMBLY GUIDE < < <](https://github.com/leddhedd/BreakNeck/blob/main/Images/Assembly/Assembly-Instructions.md)

<p align="center">
  <img src="https://github.com/leddhedd/BreakNeck/blob/main/Images/sizes.png" alt="Header"/>
</p>

![image](https://github.com/leddhedd/BreakNeck/blob/main/Images/Core.png)
![image](https://github.com/leddhedd/BreakNeck/blob/main/Images/Header.png)




![image](https://github.com/leddhedd/BreakNeck/blob/main/Images/airflow%20path.png)


Cpap cooling somewhat speaks for itself, its more cooling than you can typically get. more to come with updates, but the project focuses currently on 7040 blower fans commonly avaliable on AliExpress, and looking into small dyson hairdryer blower fans and other BLDC ducted fan options. As development continues, the focus will move away from the toolhead and more toward maximising performance from the remote fan whilst sourcing cheap and openly avaliable parts.

![image](https://github.com/leddhedd/BreakNeck/blob/main/Images/filament%20path.png)

The post-extruder filament path bend is a solution to 2 problems, first is duct pathing is a nightmare with an extruder directly above the hotend, but most critically, bowden machines have been shown in several examples to produce cleaner walls and prints than direct drive machines. this effect comes at a tradeoff of course, with bowden machines having PA values that are essentially uncontrollable at high speed printing.
the filament path bend aims to create a small buffer of filament between the extruder and the hotend, in order to deliberately increase PA values and reduce the visibility of any extruder artifacting in the extruded lines.
The claims about bowden in general and easy to verify, and 24/7 printing has several videos, as well as MirageC on their efforts to reduce issue6 and VFA artifacting on their prints, with many commenters, and MrageC himself showing how clean a bowden machine can print when looking at this isolated artifact
in testing so far, the breakneck extruder mount seems to be producing a similar effect to the bowden tube, but keeping PA values much more in check than a full bowden system, allowing for more potential quality and less limitations on high-speed printing.

After Breakneck was tested thoroughly for a few months by various wonderful community members, it was decided to up the scope and try to provide the benefits of the above, whilst also providing a ground up toolhead ecosystem that would allow tinkers and builders to easily modify and integrate their hotends,,extruders, and cooling solutions into a hyper-rigid, totally modular, and above all, lightweight and performant toolhead that shed the constraints of older toolheads.

**ARMPITHEIGHT** will debut on the armchair engineering github organisation, and will superceed Breakneck.

## Currently Supported Hardware:
strikethrough is incomplete but planned

### Carriages
- MGN12 6mm Belts
- MGN12 9mm Belts
- MGN9 6mm Belts
- MGN9 9mm Belts

### Extruders
- VZ-Hextrudort
- microsherpa
- Kyro
- ~~DFA~~

### Hotends:
- Goliath - LARGE
- RapidoUHF - Medium
- RapidoHF - Small
- DragonUHF
- ~~Volcmosq/Magnum+~~
- ~~Waterheater~~

### Probes
- Beacon
- Klicky
- Klicky/PCB
- ~~Euclid~~
- ~~TAP~~

More to be added as development continues.


