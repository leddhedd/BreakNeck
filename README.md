# BreakNeck
BreakNeck Toolhead for the Voron ecosystem. CPAP + experimental filament path


What is this?
if you have stumbled across this repo somehow in the early stages of development, and there is very little info here, a little summary of what is going on:
Breakneck is a toolhead designed primarily for the Voron ecosystem, and any other front rail, front belt CoreXY Printer.
The main features and testing focus of the toolhead are remote air cooling, and a deliberate bend in the post-extruder filament path, for the purposes of inducing a bowden-like buffering effect.

Cpap cooling somewhat speaks for itself, its more cooling than you can typically get. more to come with updates, but the project focuses currently on 7040 blower fans commonly avaliable on AliExpress, and looking into small dyson hairdryer blower fans and other BLDC ducted fan options. As development continues, the focus will move away from the toolhead and more toward maximising performance from the remote fan whilst sourcing cheap and openly avaliable parts.

The post-extruder filament path bend is a solution to 2 problems, first is duct pathing is a nightmare with an extruder directly above the hotend, but most critically, bowden machines have been shown in several examples to produce cleaner walls and prints than direct drive machines. this effect comes at a tradeoff of course, with bowden machines having PA values that are essentially uncontrollable at high speed printing.
the filament path bend aims to create a small buffer of filament between the extruder and the hotend, in order to deliberately increase PA values and reduce the visibility of any extruder artifacting in the extruded lines.
The claims about bowden in general and easy to verify, and 24/7 printing has several videos, as well as MirageC on their efforts to reduce issue6 and VFA artifacting on their prints, with many commenters, and MrageC himself showing how clean a bowden machine can print when looking at this isolated artifact
in testing so far, the breakneck extruder mount seems to be producing a similar effect to the bowden tube, but keeping PA values much more in check and compatible with current high-speed development and trend.



Currently Supported Hardware:

Extruders:
VZ-Hextrudort ; 
microsherpa

planned:
DFA

Hotends:
Goliath - LARGE
RapidoUHF - Medium
RapidoHF - Small
planned:
NFcrazy
DragonUHF
Waterheater
Rapido2

Probes:
Beacon
planned:
TAP
Klicky/PCB
Euclid

More to be added as development continues.

Huge thanks to all the guys over at the Armchair Engineering discord for all the help and support in bringing this project together
