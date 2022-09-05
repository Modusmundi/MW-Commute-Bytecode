# MW-Commute-Bytecode
[//]: # (Greets: Footfingers for making Púca, Chewy for making the art, the QMK team for being amazing.  I stand on the shoulders of giants.)
A set of Bytecode to make a nice little sunset on OLEDs in honor of MW Commute, a keycap set.  This work is entirely derivative of the efforts contained in [QMK]
(https://github.com/qmk/qmk_firmware) and is licensed appropriately.

Here is what the full set of images look like together.

![Here is what the full image set looks like](sunset.gif)

This is ultimately 32px by 45px, and looks pretty good on an 32px by 128px OLED but  takes up several KB when implemented fully.  You will want to adjust the speed to meet your needs.  I have included an example of implementation to FFKeeb's Púca- ([Their latest works can be found here](https://ffkeebs.com/), Púca can be bought at [OmegaKeys](https://omegakeys.ca/)), which is simply a fork of the code off of the [Púca QMK implementation](https://github.com/qmk/qmk_firmware/tree/master/keyboards/ffkeebs/Púca).  Steps to flash your Púca with QMK (Or really any QMK-compatible keyboard with QMK) can be found in the [documentation for QMK](https://docs.qmk.fm/#/).

I am also providing a super basic implementation based off of the same Púca code that contains all of the bytecode from the above image- it will in all likelihood not compile on your keyboard or numpad due to its size, but I figured I'd offer it for completeness.  

Finally, I am providing the individual BMPs in case you yourself want to take a crack at making it fit on your OLED- perhaps you have a 64px by 128px OLED and want to try your hand and blowing it up, or maybe you're looking to implement it horizontally.  I don't know!  That's the beauty of offering stuff up to the community.  The artist who created this image set was [ChewyGummo](https://twitter.com/chewygummo), and she has consented to this work being licensed as it is (Which should be the same as QMK licensing).
