# SynthTech-E951 - My take...
What I learned building mine...

The repository for the Synthesis Technologies E951 Looping Expander at https://github.com/emeb/SynthTech-E951 is incomplete. NONE of their files are
replicated or included here. Go to their Github pages for their files and information on this module. There you will find a front panel layout, 
gerbers and schematics for the main PCB and switch PCB, and code for it.

Here you will eventually find the missing the input jack PCB, display PCB, Bill of Materials, and information on sizes of components needed to build.

I laid out the front panel in Front Panel Designer then created one in KiCAD. Those files are in the Hardware folder for you to decide if you want to
order a front panel from the folks who made FPD or if you want to order a PCB from your favorite fab. I used JLCPCB and ordered the front panel PCB
in aluminum with black mask and white silk screen. The mockup is on here and I'll add a photo of the panel after they arrive from China.

I created a BoM for Mouser. I live across the metromess from them so I get parts next day if I order early enough. Take off the 3 digits and the dash
from the part numbers to search them elsewhere.

The original E951 used Doepfer jacks and a generic .96" OLED display. The PCB layout was nice in that it used 0 ohm resistors to choose which pins
to use for power and ground on the OLED displays since their power and ground pins are swapped on some of the generic units out there. I will be
trying to use perf board to mount the OLED display to the main PCB, but if that does not line up I'll create a custom PCB and place it here at a
later date. I will also be looking to create a jack PCB that uses easier to source Thonkiconn jacks and place it here at a later time.

The NKK MB2411 momentary SPDT switches with .290" caps are very hard to find and when you find them they are at exorbitant prices. I'll be looking to
create a new switch PCB at a later date to use cheaper C&K or other brand push-button momentary SPDT switches.
