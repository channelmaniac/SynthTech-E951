# SynthTech-E951 - My take...
What I learned building mine... Updated 11/12/2024, or 12/11/2024 for ROW.

The repository for the Synthesis Technologies E951 Looping Expander at https://github.com/emeb/SynthTech-E951 is incomplete. NONE of their files are
replicated or included here. Go to their Github pages for their files and information on this module. There you will find a front panel layout, 
gerbers and schematics for the main PCB and switch PCB, and code for it.

Here you will find the missing the input jack PCB, OLED display PCB, Bill of Materials, and information on sizes of components needed to build. You 
will also find assembly instructions and notes on programming and initial testing. You will NOT find a hex file here to load the STM32 microcontroller. 
The required files are out on the original GitHub site for you to compile and use. I will not describe how to do that.

I laid out the missing front panel in Front Panel Designer then created one in KiCAD. Those files are in the Hardware folder for you to decide if you
want to order a front panel from the folks who made FPD or if you want to order a PCB from your favorite fab. I used JLCPCB and ordered the front panel
PCB in aluminum with black mask and white silk screen. Just be aware that the FPD files do not have any labeling for the module or controls. That is
only on the silkscreen layer of the gerbers for ordering from your favorite PCB fab. The mockup for the Thonk jack version graphical layout has been
added and a final picture showing a completed Thonk version has been added to this repository.

I created a BoM for Mouser. I live across the metromess from them so I get parts next day if I order early enough. Take off the 3 digits and the dash
from the part numbers to search them elsewhere.

The original E951 used Doepfer jacks and a generic .96" OLED display. The PCB layout was nice in that it used 0 ohm resistors to choose which pins
to use for power and ground on the OLED displays since their power and ground pins are swapped on some of the generic units out there. The assembly
instructions I wrote calls this out and outlines which to install for the version of OLED module you purchase.

OLED PCB and a new Jack PCB that uses Thonk jacks have both been laid out and tested. Their files are in the Hardware folder here.

The NKK MB2411 momentary SPDT switches with .290" caps are very hard to find and when you find them they are at exorbitant prices. I'll be looking to
create a new switch PCB at a later date to use a cheaper brand, currently manufactured push-button momentary SPDT switches. Note that the cheap ones
at Tayda costing a whopping $.69 USD will not work. They are require far too much force to activate and will flex the PCBs. Most of the C&K push 
button momentary switches I've tried also require too much force to activate. One series looks promising and will be looked into at a later date.

I have spare PCBs and may put some for sale as sets in the future out on the Arcadecomponents web site.
