## BEFORE YOU START

you should know that I DID NOT test all the combinations of plates and PCBs listed here, and therefor I am not responsible for any issues you may encounter using this tutorial.
However, if you find any incompatibilities please report it as an issue in this repository and I will look at it.


# lego65

A repository for lego keyboard with 65 PCB and plate

Feel free to contribute by creating pull request.

# TODO

- lego instructions are missing completely. Currently, only way anybody can assemble this is by looking into stud.io project and moving pieces around to see which piece goes where
- some changes to structure so it is less likely to bend (make it more sturdy) - needs a lot of try/errors to get the best results
- maybe something different for feet, because current feets are slippery on deskmat - maybe just buy the rubber ones like normal keyboards?
- assembly video or at very least a good set of photos to work with

# Tutorial

In short, this project should help you build Lego65 keyboard kit.

Keyboard kit consists of 3 parts: 
- lego housing
- PCB
- plate

Switches and keycaps are preference as always.

## PCB
Anything that can work with Rama m65-a plate (as current plate is just a modified version of that one):
- DZ65 from [kbd-fans](https://kbdfans.com/)
- TF65 from [kbd-fans](https://kbdfans.com/)
- TA65 from [anykeys](https://anykeys.eu/)
- CK65 from [candykeys](https://candykeys.com/)
- Rama m65-a pcb
- maybe some more (anything compatible with the aboce pcb layouts)

## Plate + gaskets
The plate should be mounted with gaskets. The gaskets will not be super soft like usual high-end board, but it is needed in order to make a good pressure fit in between lego. At the end, some plates are going to flex because of flex-cuts, not because a keyboard is using gaskets. There is three plates currently available:
* default - no flex cuts or anything, stiff typing experience
* flex cuts - modifield default version with a lot of flex cuts all around the plate
* half plate - modified version of flex cuts, the alpha keys do not have any plate but modifiers do have flex cuts around just like the option above

### 1.2mm plate!
You can find DXF files for plates in plates folder, so just use any plate cutting services to get your plate. The plate should be 1.2mm thick (explained below), unless you want to find gaskets which would fit with different plate thickness.

### The 3.2mm rule
A Lego stud is exactly 3.2mm high.

**The rule means that your plate combined with gaskets needs to be 3.2mm thick. Nothing else matters here more than that - if you mess this up, the keyboard will not work properly.**
If your plate + gasket combination is less than 3.2mm the lego will not grip it tight, and this will result in plate bouncing inside keyboard.
If your plate + gaskets is more than 3.2mm thick, the lego will not close all the way, or it will constantly pop-open at the top.

My idea is to use plate which is 1.2mm thick, and then add 1mm gaskets to the bottom and to the top of plate, which means that your plate would be perfectly thick at 3.2mm.

For gaskets, I used some 3M 10x1mm self adhesive tape which I bought on Aliexpress. Just search for "self adhesive 1mm rubber" or something like that - It's very easy to find, so I will not link it. Instead of gaskets at the top and bottom, I also recommend a U type seal, which can fit plate on both sides at the same time, just search aliexpress for:  "1 Meter Silicone Rubber U- type Sealing Strip", and buy the smallest version 3x6mm

the final math for my keyboard looks like this:
- 1mm gasket below plate + 1.2mm plate + 1mm gasket on top = 3.2mm 😎 👍

### Gasket length and width
1m of tape is enough if you will put it all the way around the plate, but you don't have to necessarily do that. What you can do is cut the tape into stripes, for example: 12 pieces of 4cm stripes should be enough to go around the entire plate on both sides.

The width of the tape should be 5mm, so if you bought the one from example above, you will need to cut it length vise to narrow it down.

## Keyboard

Now for the Lego part... This can actually be very cheap - I payed entire lego set about 30€ ($35), which is very cheap for keyboard case but also varies a lot on few conditions:
1. current stock of lego pieces in your area
2. used vs new lego pieces (I don't mind used pieces, but new ones do generally look better, therefor your keyboard would look better)
3. colors of your lego pieces (the same piece can cost 10x more if it's weird color, I used only black color for my version)

This is very rough tutorial on how to use bricklink and stud.io, but maybe in future I'll add some screenshots and/or photos to complement steps.

Step by step:
1. go to [Bricklink](https://www.bricklink.com/v2/main.page)
2. create account
3. download [Stud.io from Bricklink](https://www.bricklink.com/v3/studio/download.page) and install it
4. download `.io` file from this project
5. load up the file in stud.io
6. change any color for any piece you like (but don't change anything if you are not 100% sure what you are doing)
7. once you are satisfied with keyboard, login to your bricklink account through stud.io (upper right corner)
8. through options in stud.io upload project as your wish list to bricklink account
9. go to bricklink account in web browser
10. find your wish list for keyboard
11. OPTIONAL - if you have a lot of keyboard pieces yourself, now you can easily remove those from your wish list so that you don't have to buy them again
12. select option for bricklink to find all pieces automatically 
13. buy pieces (there could easily be 2 or more sellers for the entire lego set)
14. once you have all the pieces -> assemble keyboard

Very rough tutorial on how to assemble a lego keyboard:
1. solder switches to PCB and plate - test that everything works
2. using stud.io project as instructions - assemble lego keyboard half way up (until you reach point where gaskets will sit)
3. put gaskets (either on lego or plate, depends on what's easier for you - I prefer to NOT glue gaskets on keyboard, but instead I glued them on plate)
4. put plate/pcb into lego assembly
5. finish lego construction to the top to cover plate
6. put keycaps on


This is it, congratulations, you have made yourself a nice lego keyboard.
