# lego-m65a
A repository for lego keyboard with m65a pcb and plate

Feel free to fork repository then make your changes.

If you wish to have a branch in this repository, open issue on current master with small description on what differences you made, and I will create branch for you to make PR.

All nice boards will get a mention in this list:

1. [Lego M65A master](https://github.com/darkosmoljo/lego-m65a.git)
2. TBD...

M65-A plates and pcb files can be downloaded from original source here: [Keyclack M65-A](https://github.com/Keyclack/M65-A)


# TODO

- some small changes in plate files to better fit sides of lego keyboard. If anyone knows how to edit dxf file, I'd appriciate the help with it
- lego instructions are missing completely. Currently, only way anybody can assamble this is by looking into stud.io project and moving pieces around to see which piece goes where
- some changes to structure so it is less likely to bend (make it more sturdy) - needs a lot of try/errors to get the best results
- maybe something different for feet, becuase current feets are slippery on deskmat
- once we have a perfect plate file, we can then make some other options with it - like half plate maybe :)
- assembly video or at very least a good set of photos to work with

# Tutorial

In short, this project should help you build Lego M65-A keyboard kit.

Keyboard kit consists of 3 parts: 
- lego housing
- pcb
- plate

Keyswitches and keycaps are on you to choose.

## PCB

I've bought mine (TA65) from [anykeys](https://anykeys.eu/) but it doesn't look like it's in stock any more. I would suggest to contact Evelyn on discord, and maybe you can work something out.
Some other solutions are [mechmarket](https://www.reddit.com/r/mechmarket/) or maybe [Rama](https://rama.works/#/m65a/)...

once you have PCB, everything else should be a breeze :) so I guess this is the hardest part.

## Plate

Current plate used for lego kit can be found in this repo, but it is just original plate for Rama M65-A keyboard. 
It fits this project almost perfectly, there is no problems using it, but there could be some small changes to make it even better for lego kit. I'm currently in search of person who knows how to edit `.dxf` files to help me get this done.

Currently you can just use it as is.

**Please note, I do not have any ideas where you will find your gaskets, but thicness of those gaskets determine how thick your plate should be, because at the end, the entire plate assembly should be EXACTLY 3.2mm.**

There is three possible configurations:
1. gasket + plate + gasket
2. gasket + plate (gasket is only below plate)
3. plate + gasket (gasket is only above plate)

This rule must be true 100%, if you don't have gaskets and plate perfectly thick at 3.2mm it will not be a snug fit like it should. This can cause the plate to bounce up and down while typing.

The gaskets I'm using are very thin at 1mm, and they are also not very soft. They just allow me to assamble the entire keyboard with gaskets from both sides of plate, and that's all I want. It's not very *soft* to type on this keyboard as some other gasket kits.

since my gaskets are 1mm, I chose plate to be exactly 1.2mm, so my calculation is:
- 1mm gasket + 1.2mm plate + 1mm gasket = 3.2mm 😎 👍

The reason for this is that one lego stud high is exactly 3.2mm, and the entire plate assembly goes in between one lego stud.

## Keyboard

Now, for lego part... This can actually be very cheap - I payed entire lego set about 30€ ($35), which is very cheap for keyboard case but also very much varries on few conditions:
1. current stock of lego pieces in your area
2. used vs new lego pieces (I don't mind used pieces, but new ones do generally look better, therefor your keeb would look better)
3. colours of your lego pieces (the same piece can cost 10x more if it's weird colour, I used only black colour for master version)
4. version of case you chose (rgb is a little bit more expensive than non-rgb)

Step by step:
1. go to [Bricklink](https://www.bricklink.com/v2/main.page)
2. create account
3. download [Stud.io from Bricklink](https://www.bricklink.com/v3/studio/download.page) and install it
4. download io file from this project
5. load up this file in stud.io
6. change any colour for any piece you like (but don't change anything if you are not 100% sure that it will fit)
7. once you are sattisfied with keeb, login to your bricklink account through stud.io (upper right corner)
8. through options in stud.io upload project as your wishlist to bricklink account
9. go to bricklink account in web browser
10. find your wishlist for keyboard
11. OPTIONAL - if you have a lot of keyboard pieces yourself, now you can easily remove them from your wishlist so that you don't have to buy them
12. select option for bricklink to find all pieces automatically 
13. buy pieces (there could easily be 2 or more sellers for the entire keyboard lego set)
14. once you have all the pieces -> assemble keyboard

now, this is very rough tutorial on how to use bricklink and stud.io, but maybe in future I do some more explanation with screenshots. It's actually very easy to just learn this yourself.

Assembling keyboard goes something like this:
1. solder switches to PCB and plate - test that everything works
2. assemble lego keyboard half way up - until you reach point where gaskets will sit
3. put gaskets (either on lego or plate, depends on what's easier for yor)
4. put plate/pcb into keyboard
5. finish lego construction to the top to cover plate
6. put keycaps on


This is it, congradulations, you have made yourself a nice lego keyboard.
