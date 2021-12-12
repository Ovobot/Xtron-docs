# Xtron Pro tutorial

![](_static/xtron_pro.jpg)

In this tutorial you will learn the basic use of Xtron Pro, download a game from MakeCode Arcade to the device, and create a simple game yourself.

The tutorial is armed at people interested in learning how to make pixel  games and apps with MakeCode Arcade and run them on Xtron Pro. No prior experience with programming is required.

The things you will need to follow are a Xtron Pro, a web browser and an Internet connection.

## Getting started

### Preparing your Xtron Pro

To start, press the Start button of your Xtron Pro to turn it on. Xtron Pro has two program areas, the bootloader area and the user application area. You must first make sure which program is started.

### Bootloader

The bootloader is a program to load user application, in the boodloader program, you can download your games or apps to the device, and view the application list in the device storage.

The following interface is the bootloader home, where you will see our website url and button instructions, press **Select** button to enter application list interface.

<p align="center">
<img src="_static/xtron-pro-bootloader-home.png" alt="" width="300"/>
</p>

In the appliction list interface, you can navigate by press "Up/Down" buttons on the gamepad or "<" button on the core, and press "A" button on the gamepad or "Menu" button on the core to run an application.

<p align="center">
<img src="_static/xtron-pro-bootloader-list.png" alt="" width="300"/>
</p>

### User application

A user application is a program that you made using MakeCode Arcade. It can be a game, a watch app or other apps.

The following pictue is the screenshot of falling duck game.

<p align="center">
<img src="_static/arcade-falling-duck.png" alt="" width="300"/>
</p>

### Switch between the bootloader and the user app

## Download a game

### Go to arcade.makecode.com

Go to [arcade.makecode.com](https://arcade.makecode.com) web application, scroll down to the **Blocks Games** section, select the first one - Falling Duck, then you will see a game introduction card.

![](_static/arcade-home-blocks-games.png)

Press Open Example button to enter the Editor, where you can code in the Editor, and play the game on the simulator.

![](_static/arcade-editor.png)

Press download button to download the game, scroll down to select the Xtron Pro in the Hardware list page. Then you will get the game on you computer.

![](_static/arcade-hardware-xtronpro.png)

### Connect your Xtron Pro

Now connect your Xtron Pro to your computer, and reset it to Bootloader, there will be a drive disk named XTRON on your computer.

<p align="center">
<img src="_static/xtronpro-plug-usb.jpg" alt="" width="350"/>
</p>

### The default files in drive disk

The XTRON drive disk contains the following device related files defaultly that don't show in the bootloader application list:

`INFO_UF2.TXT`

> Basic information of the device, it contains the bootloader version, the model and the BOARD-ID of the device.

`CONFIG.BIN`

> The device configuration file in binary format.

`CURRENT.UF2`

> The current firmware on the device in UF2 format.

`INDEX.HTM`

> The HTML document you click will go to the MakeCode Arcade website. 

### Copy

Copy the game file to the XTRON drive disk, it will take a while to download the game to the device, the game will execute automatically after the download is complete.

## Make a game

You can use Blocks, Javascipt and Python to make your games on the MakeCode Arcade, the following picture shows how your block code generate a binary firmware runs on your Xtron Pro:

![MakeCode Arcade System](_static/makecode-arcade-system.png)

You can start making a game from the tutorial or skillmap on the MakeCode Arcade homepage.

[Select a tutorial to get started](https://arcade.makecode.com/tutorials)

or

[Start from skillmaps](https://arcade.makecode.com/skillmaps)