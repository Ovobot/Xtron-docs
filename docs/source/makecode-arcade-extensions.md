# MakeCode Arcade Extensions

This is a list of MakeCode Arcade extensions forked from [https://github.com/UnsignedArduino/Awesome-Arcade-Extensions](https://github.com/UnsignedArduino/Awesome-Arcade-Extensions).

## Table of contents
- [**Built-in extensions**](#built-in-extensions)
  - [arcade-sprite-data](#arcade-sprite-data)
  - [Timers](#timers)
  - [settings-blocks](#settings-blocks)
  - [Color Fading](#color-fading)
  - [pxt-button-combos](#pxt-button-combos)
  - [arcade-minimap](#arcade-minimap)
  - [arcade-grid](#arcade-grid)
  - [arcade-storytelling](#arcade-storytelling)
- [**Not built-in extensions**](#not-built-in-extensions)
  - [character-animations](#character-animations)
  - [arcade-tilemap-a-star](#arcade-tilemap-a-star)
  - [arcade-custom-menu](#arcade-custom-menu)
  - [arcade-block-objects](#arcade-block-objects)
  - [arcade-story](#arcade-story)
  - [arcade-sprite-util](#arcade-sprite-util)
  - [arcade-image-text](#arcade-image-text)
  - [pxt-lantern](#pxt-lantern)
  - [pxt-rtttl](#pxt-rtttl)
  - [arcade-shader](#arcade-shader)
  - [small-tilemaps](#small-tilemaps)
  - [Fast-Random-Blocks](#fast-random-blocks)
  - [pxt-arcade-image-transform](#pxt-arcade-image-transform)
  - [pxt-password-save](#pxt-password-save)
  - [pxt-scaling](#pxt-scaling)
  - [notifications](#notifications)
  - [Achievements](#achievements)
  - [pxt-countup](#pxt-countup)
  - [pxt-sight](#pxt-sight)
  - [smaller-tilemaps](#smaller-tilemaps)
  - [arcade-background-scroll](#arcade-background-scroll)
  - [pxt-image-morph](#pxt-image-morph)
  - [grafxkid-tiles](#grafxkid-tiles)
  - [Inventory](#inventory)
  - [Stats](#stats)
  - [pxt-real-multiplayer](#pxt-real-multiplayer)
  - [pxt-arcade-database](#pxt-arcade-database)
  - [TilemapPath](#tilemappath)
  - [arcade-premium-life](#arcade-premium-life)
  - [ColorBlock](#colorblock)
  - [arcade-camera-offset](#arcade-camera-offset)
  - [RPGMuisic](#rpgmuisic)
- [**Experimental-extensions**](#experimental-extensions)
  - [arcade-soundtrack](#arcade-soundtrack)
- [**Tools**](#tools)
  - [Convert-Image-to-MakeCode-Arcade-Sprite](#convert-image-to-makecode-arcade-sprite)
  - [pxt-arcade-asset-tool](#pxt-arcade-asset-tool)
  - [arcade-sprite-pack](#arcade-sprite-pack)
  - [arcade-image-tools](#arcade-image-tools)
  - [arcade-font-renderer](#arcade-font-renderer)
  - [games-gallery](#games-gallery)

## Built-in extensions
These extensions are already built in to the editor, all you have to do is go to the toolbox, open the `Advanced` tab, click on `Extensions`, and click on the extension you want to import!

### arcade-sprite-data
It's local variables, but for sprites! Super useful for saving certain attributes of a sprite like the health of an enemy. This will add a section full of blocks called `Data` under the `Sprites` category in the toolbox.

[Official docs](https://arcade.makecode.com/pkg/microsoft/arcade-sprite-data) | [GitHub repo](https://github.com/microsoft/arcade-sprite-data) | [Forum post](https://forum.makecode.com/t/sprite-data-extension/1590)

### Timers
It's literal multithreading! Setup a callback for your code or run it in a separate fiber (thread) with this extension! This will add another category in the toolbox called `Timer`. 

[Official docs](https://arcade.makecode.com/pkg/microsoft/arcade-timers) | [GitHub repo](https://github.com/microsoft/arcade-timers) | [Forum post](https://forum.makecode.com/t/timers-extension-after-x-debounce-throttle-and-in-background/1925)

### settings-blocks
Save data in an easy-to-use JSON-like format, now avaliable for the block users! This will add another category in the toolbox called `settings`.

[Official docs](https://arcade.makecode.com/pkg/microsoft/pxt-settings-blocks) | [GitHub repo for block defs](https://github.com/microsoft/pxt-settings-blocks) | [GitHub repo for implementation](https://github.com/microsoft/pxt-common-packages/tree/master/libs/settings) | [Forum post](https://forum.makecode.com/t/settings-extension/1594)

### Color Fading
Want some cool fade-in and fade-out effects for your cutscenes? Or want to change the default colors at runtime? This is the extension for you! This extension goes together nicely with the Story extension linked down below. This will add another category in the toolbox called `Color`.

[Official docs](https://arcade.makecode.com/pkg/jwunderl/pxt-color) | [GitHub repo](https://github.com/jwunderl/pxt-color) | [Forum post](https://forum.makecode.com/t/fireworks-and-pxt-color-extension/315)

### pxt-button-combos
A simple-to-use extension that allows you to have handlers when buttons are pressed in a certain order. Great for a dancing game! This extension adds a section called `Combos` in the `Controller` category.

[Official docs](https://arcade.makecode.com/pkg/jwunderl/pxt-button-combos) | [GitHub repo](https://github.com/jwunderl/pxt-button-combos)

### arcade-minimap

Want a map for your tilemap? You've come to the right extension! This will take your tilemap and scale it down to a specified ratio - you can also add sprites that will be drawn on top of the map! This extension adds a new category called `Minimap` in the toolbox.

[Official docs](https://arcade.makecode.com/pkg/microsoft/arcade-minimap) | [GitHub repo](https://arcade.makecode.com/pkg/microsoft/arcade-minimap) | [Forum post](https://forum.makecode.com/t/minimap-extension-beta/1709)

### arcade-grid

Have an extension do that hard work of aligning sprites to a tilemap! This will add a new category called `Grid`.

[Official docs](https://arcade.makecode.com/pkg/microsoft/arcade-grid) | [GitHub repo](https://github.com/microsoft/arcade-grid) | [Forum post](https://forum.makecode.com/t/gemcrush-and-sprite-grid-extension-beta/1842)

### arcade-storytelling

The new and improved `arcade-story` now part of the built-in extensions with new improvements! This will add a category called `Story` in the toolbox. Note the old story extension is not compatible at all with this one!

[Official docs](https://arcade.makecode.com/pkg/microsoft/arcade-storytelling) | [GitHub repo](https://github.com/microsoft/arcade-storytelling) | [Forum post](https://forum.makecode.com/t/new-arcade-story-extension/6744) 

## Not built-in extensions
The following extensions, while just as good as the ones listed above, will require some slightly different steps while importing. First go to the toolbox, open the `Advanced` tab, click on `Extensions`, and you will see a text box that says `Search or enter project URL...`. This is where you will paste in the URL to the extension. The URL will be posted along with the listing.

### character-animations
Import this extension with the URL:
> https://github.com/riknoll/character-animations
A version of the `Animation` extension but much more easier to handle if your sprites (Ex. main player) has a lot of different movements, like moving up, down, left, and right. The `character-animations` extension will automatically start and stop animations depending on what the player is doing. This will add another category in the toolbox called `Character`.

[GitHub repo](https://github.com/riknoll/character-animations)

### arcade-tilemap-a-star
Import this extension with the URL:
> https://github.com/jwunderl/arcade-tilemap-a-star
Help your sprites find their way around your tilemaps with this extension! Just provide 2 locations on a tilemap and it will automagically compute the fastest path between the 2 spots while also moving around walls using the [A* algorithm](https://en.wikipedia.org/wiki/A*_search_algorithm)! This will add another section in the `Scene` category called `Path Following` in the toolbox.

[GitHub repo](https://github.com/jwunderl/arcade-tilemap-a-star) | [Forum post](https://forum.makecode.com/t/tilemap-path-finding-a-beta/1846) | [Wikipedia article on the A* algorithm](https://en.wikipedia.org/wiki/A*_search_algorithm)

### arcade-custom-menu
Import this extension with the URL:
> https://github.com/riknoll/arcade-custom-menu
One of my favorite extensions, it allows you to make a menu out of a list of strings! Use this for selecting options where using `game.askForNumber()` and `game.askForString()` would be unintuitive or clumsy. This will add another category in the toolbox called `BlockMenu`.

[GitHub repo](https://github.com/riknoll/arcade-custom-menu)

### arcade-block-objects
Import this extension with the URL:
> https://github.com/microsoft/arcade-block-objects
Object-oriented programming is no doubt an important topic in prograaming. This extension will help you make objects in blocks! Attach all sorts of data to an object, like numbers, strings, images, sprites, locations, and more! This will add a category in the toolbox called `BlockObject` with 7 sub-categories.

[GitHub repo](https://github.com/microsoft/arcade-block-objects)

### arcade-story

> NOTE: This extension is depreciated! There is a new better extension under the same name but different repo that is now part of the built-in extensions! Check out the Forum post about it [here](https://forum.makecode.com/t/new-arcade-story-extension/6744). 
Import this extension with the URL:
> https://github.com/riknoll/arcade-story
Need some cutscenes with dialog? This extension is for you! Comes with a variety of blocks designed to make writing stories and scenes much easier. This extension pairs great with the `Color Fading` extension linked above. This will add a new category called `Story` in the toolbox.

[GitHub repo](https://github.com/riknoll/arcade-story)

### arcade-sprite-util
Import this extension with the URL:
> https://github.com/jwunderl/arcade-sprite-util
As the name says, this extension has a bunch of utilities for sprites and more, especially anything dealing with trigonometry. This extension adds a new category called `Sprite Utils` in the toolbox.

[GitHub repo](https://github.com/jwunderl/arcade-sprite-util) | [GitHub pages demo](https://jwunderl.github.io/arcade-sprite-util/)

### arcade-image-text
Import this extension with the URL:
> https://github.com/pelikhan/arcade-image-text
Simple but sweet, this extension adds the very much-need blocks to print text onto images. This will add a new section called `Text` under the `Images` category in the toolbox.

[Official docs](https://pelikhan.github.io/arcade-image-text/README) | [GitHub repo](https://github.com/pelikhan/arcade-image-text) | [Forum post](https://forum.makecode.com/t/arcade-print-text-extension/1827)
### pxt-lantern
Import this extension with the URL
> https://github.com/felixtsu/pxt-lantern
Light up your games with this extension! It allows you to turn the lights on or off and add lanterns to sprites so that they have light around them when you turn the lights off. This will add 2 categories called `Lantern` and `Multilights` under the toolbox.

[GitHub repo](https://github.com/felixtsu/pxt-lantern) | [GitHub pages demo*](https://riknoll.github.io/pxt-lantern/) | [Forum post](https://forum.makecode.com/t/hope-this-ext-can-bring-some-light-s/3229)

*Note that the GitHub pages demo only demonstrates the original features of the lantern extension written by @riknoll [here](https://github.com/riknoll/pxt-lantern). A more up-to-date example can be found [here](https://arcade.makecode.com/25139-51900-79237-05503).

### pxt-rtttl
Import this extension with the URL:
> https://github.com/pelikhan/pxt-rtttl
Play beautiful melodies encoded in the RTTTL language in MakeCode with this extension! You can use this [website]([http://midi.mathewvp.com/midi2RTTL.php](http://midi.mathewvp.com/midi2RTTL.php)) to turn yoru `.mid` and `.midi` files into a RTTTL-compatible string of text! This extension adds a block in the `Melody` section in the `Music` category in the toolbox.

[GitHub repo](https://github.com/pelikhan/pxt-rtttl) | [GitHub pages demo](https://pelikhan.github.io/pxt-rtttl/) | [Forum post](https://forum.makecode.com/t/rtttl-tunes-extension/4193/6) | [MIDI to RTTTL converter](http://midi.mathewvp.com/midi2RTTL.php)

### arcade-shader
Import this extension with the URL:
> https://github.com/riknoll/arcade-shader
Arcade games can get more realistic with shadows! This extension will add a category called `Shaders` in the toolbox.

[GitHub repo](https://github.com/riknoll/arcade-shader) | [Forum post](https://forum.makecode.com/t/shader-extension/4860) 

### small-tilemaps
> NOTE: This extension is depreciated! There is now an 8x8 tilemap block in the built-in tilemaps extension!
Import this extension with the URL:
> https://github.com/riknoll/small-tilemaps
Easy access to an 8x8 tilemap in blocks! Note: If you are switching from an 16x16 to an 8x8 tilemap, don't forget to switch tiles in your code! And delete the 16x16 tiles in the tilemap editor, otherwise you are going to get really confused. This will add a block under `Tiles` section in the `Scene` category.

[GitHub repo](https://github.com/riknoll/small-tilemaps) | [Forum post](https://forum.makecode.com/t/why-is-it-going-strait-to-level-2/4290/25)

### Fast-Random-Blocks
Import this extension with the URL:
> https://github.com/UnsignedArduino/Fast-Random-Blocks
Blocks for Fast Random! Have separate RNG objects for different aspects of your game, and with seeding! This will add a `Random` category in the toolbox.

[GitHub repo](https://github.com/UnsignedArduino/Fast-Random-Blocks) | [Forum post](https://forum.makecode.com/t/fast-random-extension/5365)

### pxt-arcade-image-transform
Import this extension with the URL:
> https://github.com/robo-technical-group/pxt-arcade-image-transform
Rotate images with this extension! This works best with large images. Don't forget to enlarge the base image so when it rotates it has enough room to spin! This will add a `Sprite Transforms` category in the `Advanced` section of the toolbox.

[GitHub repo](https://github.com/UnsignedArduino/Awesome-Arcade-Extensions/issues/11) | [Example](https://arcade.makecode.com/27800-70465-05726-62974) | [Forum post](https://forum.makecode.com/t/having-a-blast-with-makecode-arcade/59/6)

### pxt-password-save
Import this extension with the URL:
> https://github.com/jacobcarpenter/pxt-password-save
Shove bytes and bools into a string as a save code! Note: This extensions seems to still be in beta (as of January 30, 2021) as importing the extension causes the example code to run instead of your own. This will add a category in the toolbox called `Password Save`.

[GitHub repo](https://github.com/jacobcarpenter/pxt-password-save) | [GitHub pages demo](https://jacobcarpenter.github.io/pxt-password-save/) | [Forum post](https://forum.makecode.com/t/password-save-extension-work-in-progress/5819)

### pxt-scaling
Import this extension with the URL:
> https://github.com/jwunderl/pxt-scaling
Like [pxt-arcade-image-transform](#pxt-arcade-image-transform), this also allows you to rotate images and scale them too!!! Much better than manually doing it, at the expense of RAM. This extension adds a category called `Scaling` in the toolbox.

[GitHub repo](https://github.com/jwunderl/pxt-scaling) | [GitHub pages demo](https://jwunderl.github.io/pxt-scaling/) | [Forum post](https://forum.makecode.com/t/arcade-advanced-stream-128-spinning-dishes/3885)

### notifications
Import this extension with the URL:
> https://github.com/unsignedarduino/notifications
Shows and scrolls notifications like a sprite-say dialog but s c r e t c h e d out! It also supports variable speed and 8x8 icons! (Although it doesn't push notifications down when you display more than one at a time - you need to wait until the current notification is over otherwise you will cover it up - but there are blocks to wait for the notification to finish) This adds a category called `Notification`. 

[GitHub repo](https://github.com/unsignedarduino/notifications) | [GitHub pages demo*](https://unsignedarduino.github.io/Notifications/) | [Forum post](https://forum.makecode.com/t/notification-extension/5557)

*Note that the GitHub pages demo was generated a long time ago so you won't be able to see the code in `main.ts` or `test.ts` but the notification still looks the same. 

### Achievements
Import this extension with the URL:
> https://github.com/UnsignedArduino/Achievements
Your games can ascend to a new level with freaking _achievements_ in MakeCode Arcade! Easily track and display achievements with this extension! This will add a category called `Achievements` in the toolbox. 

[GitHub repo](https://github.com/UnsignedArduino/Achievements) | [Demo](https://arcade.makecode.com/89228-26205-83094-83249) | [Forum post](https://forum.makecode.com/t/achievements-extension/6308)

### pxt-countup
Import this extension with the URL:
> https://github.com/shakao/pxt-countup
Stop hacking the built-in countdown in your code - it's ugly! Instead, use this extension which does the same thing for you in a nice little extension! This adds a section called `Countup` in the `Info` category. 

[GitHub repo](https://github.com/shakao/pxt-countup) | [Demo](https://arcade.makecode.com/48048-78498-38407-75985) | [Forum post](https://forum.makecode.com/t/small-count-up-timer-extension/6786)

### pxt-sight
Import this extension with the URL:
> https://github.com/felixtsu/pxt-sight
Inteligent sight now comes to your sprites in MakeCode Arcade! This extension can help you detect whether one sprite can "see" another sprite with some math! (Much better than sending "see" sprites everywhere) This adds a section called `Sprite Sight` in the toolbox. 

[GitHub repo](https://github.com/felixtsu/pxt-sight) | [Demo](https://arcade.makecode.com/97022-62922-00013-89813) | [Forum post](https://forum.makecode.com/t/sneaking-demo/4961)

### smaller-tilemaps
Import this extension with the URL:
> https://github.com/riknoll/smaller-tilemaps
Now we get 4x4, 2x2, and "1x1, at your own risk" tilemaps! Initialize a tilemap and use 4x4 or 2x2 or 1x1 images to manually draw your tiles by code. Note this extension was made in 1 hour so it may be buggy and performance will not be as good as a 8x8 or 16x16 tilemap. This will add a `Smaller Tilemaps` category.

[GitHub repo](https://github.com/riknoll/smaller-tilemaps)

### arcade-background-scroll
> NOTE: This extension is depreciated! There is a new better extension under the same name but different repo that is now part of the built-in extensions! 
Import this extension with the URL:
> https://github.com/riknoll/arcade-background-scroll
Don't use a sprite to manually scroll the background - use this extension instead! It can scroll your background in with variable vx and vy too! This will add a `Scroller` category in the toolbox.

[GitHub repo](https://github.com/riknoll/arcade-background-scroll)

### pxt-image-morph
Import this extension with the URL:
> https://github.com/UnicycleDumpTruck/pxt-image-morph
"Morph" images in MakeCode Arcade! Very cool for switching between images and could be used in say, the reveal of a bad guy's true form! Also very fun for switching between images that are used as instructions instead of a snap change which is boring. This adds an `Imagemorph` category in the toolbox. 

[GitHub repo](https://github.com/UnicycleDumpTruck/pxt-image-morph) | [Demo](https://arcade.makecode.com/04630-02278-77688-89486) | [Forum post](https://forum.makecode.com/t/pixel-by-pixel-morphing-slows-down/2980/7?u=unsignedarduino)

### grafxkid-tiles
Import this extension with the URL:
> https://github.com/riknoll/grafxkid-tiles
Don't want to draw up a platformer tileset? @logic_lab on the MakeCode Forums has converted GrafxKid's tileset into MakeCode tiles so you can use them as well! Comes in 4 different seasons and adds 4 new dropdown categorys in the tile category picker in the tilemap editor.

[GitHub repo](https://github.com/riknoll/grafxkid-tiles) | [Forum post](https://forum.makecode.com/t/platformer-tileset/3023) 

### Inventory
Import this extension with the URL:
> https://github.com/UnsignedArduino/Inventory
Man, rendering inventories are a pain in the butt. Until you add this extension! This extension allows you to make items, (which can hold an image, a name, and more) toolbars, (like Minecraft hotbars) and inventories! This extension adds an `Inventory` category in the toolbox. 

[GitHub repo](https://github.com/UnsignedArduino/Inventory) | [Demo](https://makecode.com/_geYE0mfE2Ds6) | [Forum post](https://forum.makecode.com/t/inventory-extension/8662)

### Stats
Import this extension with the URL:
> https://github.com/UnsignedArduino/Stats
The only reason this extension exists so you can programmatically turn the FPS and sprite count on and off lol. This adds a `Stats` category to your toolbox.

[GitHub repo](https://github.com/UnsignedArduino/Stats) | [Forum post](https://forum.makecode.com/t/stat-extension/8859)

### pxt-real-multiplayer
Import this extension with the URL:
> https://github.com/distintiva/pxt-real-multiplayer
Makes coding multiplayer games over JACDAC easier! It also works in the simulator as well! Note at the time of writing, JACDAC for Arcade is in the middle of a rewrite so things are most likely broken. This will add a `Real Multiplayer` category to the toolbox.

[GitHub repo](https://github.com/distintiva/pxt-real-multiplayer) | [Demo](https://arcade.makecode.com/84138-42853-06448-38206) | [Forum post](https://forum.makecode.com/t/new-extension-real-multiplayer-with-blocks/1202)

### pxt-arcade-database
Import this extension with the URL:
> https://github.com/distintiva/pxt-arcade-database
Extremely similar to the built-in `settings-block` extension, this extension also allows you to save data like a database! This will add a `Database` category.

[GitHub repo](https://github.com/distintiva/pxt-arcade-database) | [Demo](https://arcade.makecode.com/07492-27953-74313-26225) | [Forum post](https://forum.makecode.com/t/new-extension-arcade-database-in-flash-memory/1198)

### TilemapPath
Import this extension with the URL:
> https://github.com/UnsignedArduino/TilemapPath
Don't manually place walls to make your A-star paths do what you want, use this! You can set a sprite to follow a path between tilemap locations and have handlers when they finish. Note that everytime you set a path, it will recalculate the paths using the A-star extension which can take a long time depending on how big the tilemap is and how many elements there are. This extension adds a `TilemapPath` category. 

[GitHub repo](https://github.com/UnsignedArduino/TilemapPath) | [Demo](https://makecode.com/_87j1jxLV358K) | [Forum post](https://forum.makecode.com/t/tilemappath-extension/9480)

### arcade-premium-life
Import this extension with the URL:
> https://github.com/jwunderl/arcade-premium-life
It's life but _better_. This extension uses the default set life and change life by blocks to change the values, but for configuring the look you can use the blocks in the `Profile Life` category. 

[GitHub repo](https://github.com/jwunderl/arcade-premium-life) | [Demo](https://jwunderl.github.io/arcade-premium-life/)

### ColorBlock
Import this extension with the URL:
> https://github.com/UnsignedArduino/ColorBlock
Imagine memorizing the values of colors in MakeCode Arcade. This extension will add a block at the very bottom of the `Images` category. 

[GitHub](https://github.com/UnsignedArduino/ColorBlock) | [Forum post](https://forum.makecode.com/t/colorblock-extension/9518)

### arcade-camera-offset
Import this extension with the URL:
> https://github.com/riknoll/arcade-camera-offset
This simple extension adds a block to the `Scene` category that allows you to follow a sprite with the camera with an offset! Much better then hacking a sprite to always be off a certain amount. 

[GitHub repo](https://github.com/riknoll/arcade-camera-offset) | [Forum post](https://forum.makecode.com/t/camera-offset/10263?u=unsignedarduino)

### RPGMuisic
Import this extension with the URL:
> https://github.com/LucasMayhew/RPGMuisic
This extension adds another category called `Music` which contains a block to play some (very nice) looping music made by @LucasMayhew!

[GitHub repo](https://github.com/LucasMayhew/RPGMuisic) | [Demo](https://arcade.makecode.com/06547-32796-52098-57963) | [Forum post](https://forum.makecode.com/t/an-extension-that-adds-loopable-songs-to-use-in-your-games/10894?u=unsignedarduino)

## Experimental-extensions

Shouldn't need an explanation: "VERY UNSTABLE" - @livcheerful

### arcade-soundtrack
Import this extension with the URL:
> https://github.com/livcheerful/arcade-soundtrack
In this extension you can make soundtracks within images! But it is pretty confusing and "might break your game." This extension was made by @livcheerful in a hackathon.

[GitHub](https://github.com/livcheerful/arcade-soundtrack) | [Forum post](https://forum.makecode.com/t/hackathon-link-request/9751/2?u=unsignedarduino) | [Demo](https://arcade.makecode.com/10829-55411-68884-03658) 

## Tools
Yes, this is about useful MakeCode Arcade extensions but these tools will level up your game-making experience!
### Convert-Image-to-MakeCode-Arcade-Sprite
This tool will convert your images (like `.png` files) to Arcade code! Simply copy the output, open JavaScript mode in your project, navigate to where you want the image block to go, and paste in the image code! You may need to remove some redundant characters. Remember that Arcade has a maximum image size of 500x500!

Find this tool here:
> https://kristianpedersen.github.io/Convert-Image-to-MakeCode-Arcade-Sprite/
[GitHub repo](https://github.com/kristianpedersen/Convert-Image-to-MakeCode-Arcade-Sprite) | [Forum post](https://forum.makecode.com/t/ive-made-an-image-file-to-arcade-sprite-converter-feedback-and-code-improvements-wanted/2076)

### pxt-arcade-asset-tool
This tool will also convert you images to Arcade code, but it also supports using 16-color palettes, in case you don't want to use the default palette! Simply copy the output, open JavaScript mode, navigate to where you want the image to go, and paste away! You may need to remove some redundant characters. Remember that Arcade has a maximum image size of 500x500!

Find this tool here:
> https://riknoll.github.io/pxt-arcade-asset-tool/
[GitHub repo](https://github.com/riknoll/pxt-arcade-asset-tool/)

### arcade-sprite-pack
Have a bunch of images you want to send to someone, but they hate exercising their pinkie and pointer finger? This will convert a set of images into a MakeCode project that, when you import, will put the images into the image gallery!

Find this tool here:
> https://shakao.github.io/arcade-sprite-pack/
[GitHub repo](https://github.com/shakao/arcade-sprite-pack)

### arcade-image-tools
The ultimate Arcade image manipulator! Rotate and flip your sprites with this!

Find this tool here:
> https://felixtsu.github.io/arcade-image-tools/
[GitHub repo](https://github.com/felixtsu/arcade-image-tools/) | [Forum post](https://forum.makecode.com/t/sprite-image-tools-rotating-flipping/5375)

### arcade-font-renderer
Stop drawing your title screen text by hand! With this tool, you can render _any_ (well, any font on your computer and in Google Fonts) font onto a Arcade image with outlines _and_ shadows!

Find this tool here:
> https://arcade-font-renderer.jacobcarpenter.com/
[GitHub repo](https://github.com/jacobcarpenter/arcade-font-renderer) | [Forum post](https://forum.makecode.com/t/arcade-font-renderer/7174)

### games-gallery
@jacobcarpenter [on GitHub](https://github.com/jacobcarpenter) has written a neat tool that scrapes the [MakeCode Forum's arcade section](https://forum.makecode.com/c/share-your-arcade-projects-here/5) and shows the games in a gallery-like view! So you don't have to ~~suffer~~ and scroll through debug programs and tons of comments to find that dang link. You can also view the most liked-games of all-time and by author, like [me](https://games-gallery.jacobcarpenter.com/author/416) for example hehe.

Find this tool here:
> https://games-gallery.jacobcarpenter.com/
[GitHub repo](https://github.com/jacobcarpenter/games-gallery) | [Forum post](https://forum.makecode.com/t/games-gallery-an-alternate-view-for-games-posted-to-these-forums/4025)

***
Written with [StackEdit](https://stackedit.io/).