QuickPSoC3 V2
--------------

This is a quick-to-make development envrionment for the Cypress PSoC3 Platform.It is intended for students,hobbyists 
or anyone who wants a PSoC3 platform to play with,without paying a ton of money for it.

The goal is to have a home-etchable,cheap to put together,USB capable PSoC3 environment running with the least of hassle.

To know more about the PSoC3 platform - http://www.cypress.com/?id=2232

This board:
-Uses the CY8C3866PVI-021/CY8C3246PVI-147 or any PSoC3 part in a 48pin SSOP package
-Has 26 GPIOs brought out to 0.1" headers.
-Uses the internal oscillator.
-Has a miniprog compatible header on the top right,for easy programming.
-Has a miniUSB connector,so can use a USB bootloader,for easier programming.
-Has extra long pads for soldering the PSoC,to make it easier for beginners to put together.
-The Mhz Crystal lines have not been routed out,but USB doesnt need an external crystal/resonator.
-Has smd passives of 0805 size,and the LEDs are 1206,but you can easily replace them with their through hole variants and get a fully through-hole board.
-Has an *Unregulated* voltage input which can be selected over USB's 5VDC.

I have successfully etched this using nothing but ordinary copier paper and a household iron,on some paper phenolic copper clad.So you dont require special techniques to etch it.

Updated 19-Jun-12:
Did away with some more components,to make this a quick-er board to put together.
Edited silkscreen at some places to make it more meaningful.

-kmmankad

http://kmmankad.blogspot.com

This work is licensed under a Creative Commons Attribution-ShareAlike 3.0 Unported License.