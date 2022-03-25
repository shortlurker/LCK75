# LCK75 SL Mod

This is a modification of Lysol's <a href="https://github.com/lyso1/LCK75">LCK75 Rev1</a>. A 75% through-hole keyboard originally designed by <a href="https://github.com/lyso1">Lysol</a>.

#### LCK75 main PCB changes:

- Keyswitch footprints replaced with MXOnly-*U-Hotswap-Antishear footprints for Kailh hotswap sockets.
- Removed optional modifier, spacebar and keyswitch instead of the rotary encoder footprints.
- Diode and resistor footprints replaced with 5.08mm pin pitch footprints for more physical space.
- Added diode rows.
- Swapped OLED display positions with buttons and ISP header.
- Crystal and filter caps have been moved beside the corresponding pins on the ATmega.
- USB-C connector unfortunately has been mirroed across the center to the right. I didn't like any of the ways I could route the data traces near the diodes if the connector was not moved.
- Other components have been pushed around for clearance of the repositioned USB-C connector.
- Art adjusted.

#### Switch plate changes:

- Removed optional modifier and spacebar openings.
- Extended top edge of the plate by 1mm and removed any thin sections to reduce the risk of breaking during manufacturing.
- Reduced holes down to support m2 screws and added two additional holes for case/trim mounting options.

#### The bottom PCB, foam and acrylic guard files have not been changed.

#### Notes: 

- <a href="https://octopart.com/bom-tool/kmsRsySl">BOM</a> of the parts used in the build.
- If you already own a LCK75 then all you need is the main PCB.
- Use QMK/VIA firmware for the Rev1 LCK75. Rev2 adds another column to the key matrix.
- The Kailh hotswap sockets may add bit of additional gap between the main PCB and the bottom PCB depending on the density of the foam.
- Existing cases made for the original LCK75 will not work with this PCB because of the repositioned USB-C connector. I am not responsible for any damages if you attempt to modify an existing case.

Any questions or feedback of this specific edit of the LCK75 please leave here.

![LCK75_SL](https://raw.githubusercontent.com/shortlurker/LCK75_SL/SL_mod/LCK75%20Images/LCK75_SL.jpg)

![LCK75_SL_top](https://raw.githubusercontent.com/shortlurker/LCK75_SL/SL_mod/LCK75%20Images/LCK75_SL_top.jpg)

![LCK75_SL_front](https://raw.githubusercontent.com/shortlurker/LCK75_SL/SL_mod/LCK75%20Images/LCK75_SL_front.png)

![LCK75_SL_back](https://raw.githubusercontent.com/shortlurker/LCK75_SL/SL_mod/LCK75%20Images/LCK75_SL_back.png)

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.
