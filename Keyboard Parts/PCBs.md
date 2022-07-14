### Hotswap
Hotswap sockets are one of the most ingenious solutions to a problem found in the Keyboard community. They are very simple little sockets that sit, soldered, on the back of the pcb, allowing for the switch to function but without the hassle of having to solder the switch to the PCB.

They are highly recommended by everyone in the community for their ease of use for beginners and intermediate users who are still trying to find switches that they like the sound and feel of, as the little sockets allow you to easily interchange the switches without having to take the board apart and without having to use a de-soldering gun.

It is important to note though, that the sockets have to be compatible with the switch type you are using (MX, choc, alps), and that the PCB you wish to attach them to is hotswap compatible, as you can't just solder them onto a standard soldered board.

### LEDs
There are 4 possible options for having LEDs on a board. North facing, South facing, Underglow, and none. As with everything in this hobby, what you choose is based on preference. I have gone into more details about the direction of backlight LEDs (north and south facing) on the LEDs and OLEDs page so here I will talk about underglow, and what I would recommend for LEDs.

Underglow is a fairly standard term across many hobbies, however in this one, it refers to the bleeding of light out from underneath the board. This can obviously only happen if the case isn't opaque, or if, like with the idabao id80/75, it has an opaque case but a clear base only allowing for light to bleed out of the bottom not out of the sides. Underglow is almost always achieved by attaching bright LED's to the bottom of the PCB, so no wires are required, and then programming them through the PCB firmware, though I have seen people just use LED strips taped or glued to the bottom of the case.

And of course, there areboards with no LEDs at all. There is no special name for this even though it is practically standard at this point for all custom boards. The reason many people don't use LEDs is they can take away from the aesthetics of the board, and provide a distraction from its beauty. For this reason, lots of lower quality boards use LEDs to move your attention away from the potentially lackluster aesthetic appeal otherwise, leading to its tacky feel and negative stigma. Therefore, I personally recommend no LEDs, however if for any reason you want to have them (dark room or poor eyesight etc.), it shouldn't ruin the board.

### Sizing
Similar to with plates, it is vital that the PCB is compatible with the plate and the case. If you buy a PCB for a certain layout (like a 60%) then there is a fairly high likelihood that the PCB will work with a case and plate for that size. However for anything larger than a 65% or any board with a slightly different layout to a standard 60%, it is vital that you check the sizes and layouts between all parts as it will be very hard to change the shape of your PCB without destroying it. Again like the plate, buying a *barebones* kit negates all sizing and compatability issues you may have.

### Features
PCBs are the most versatile part of the board beause there is the greatest possibility of features that can be added to it. These include: rotary encoders, LEDs, OLED panels and many more.

Rotary encoders: otherwise known as 'knobs' are a simple way of adding more flexibility to a PCB as it allows for a continous scale of input, often used for volume. It can have many other functions, such as a button buit into it, allowing for an extra input, often used to toggle mute the volume.

I have covered LEDs earlier in this page, and have a separate page on OLED panels on a dedicated page.

### Key rollover
Key rollover, often writen as KRO, comes in a few forms, based on the quality of the board. The most common types are 2KRO and NKRO, but you sometimes see boards advertised as 12 or 18KRO. Key rollover is the maximum number of keys that can be detected by the board and sent to the computer at once.

NKRO is standard for a board of fairly high quality, where diodes are used to prevent the keys from *ghosting*. This comes with a limitation though, as USB 3.0 has a maximum bandwidth of 6 keypresses that can be registered and sent to the computer at once.

2KRO is standard for lower quality, cheaper boards as it allows the PCB to no longer need diodes. It instead uses an algorithm to detect when the keypresses that could cause ghosting are pressed, and then negates the one of the 2 keypresses, allowing for 2 keys to be detected, thus 2 key rollover. This obviously then can causes issues when trying to type certain words, if you 'roll' your fingers across keys, like 'Wedding or Free'.

12 or 18KRO are slightly more questionable features for boards, as it takes advantage of the making the keyboard act like a USB hub, allowing for more keys to be detected, up to 6 x the number of input devices the fake usb hub is emulating. This however has its downsides in that the board won't be cross compatible with operating systems that the USB hub has been emulated for.

Boards that advertise as 10 or 14KRO are disregarding the standard used for how to identrify the KRO of a PCB, as the modifier keys are often used with a separate matrix, so can have higher than 6 keys (technically) sent at once. This is a dirty trick that takes advantage of less experienced buyers as it makes the user feel like they are buying a better product than an NKRO board.
