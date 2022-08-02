---
layout: page
title: Guide
permalink: /guide/
---

# Content

1. [Overview](#overview)
2. [SmartScreen](#smartscreen)
3. [Install](#install)
4. [First run](#first-run)
5. [CMS editor](#cms-editor)

# Overview

YOPT is achronim for "your own presets tweaker" for DCS. This is an opensource and free to use tool originally made to provide convinient way of editing CMS programs. 

The list of features might be expanded in future releases.
Anyone from the community may suggest a feature or contribute to the project.

# SmartScreen

This software is not a commercial one and made in a free time for pursonal use. As an act of a goodwill author shared this software with community. 
Author **unable** to make regular **payments** for the **authority certificate**. Because of that the software distributed with unsigned installer. 
Sometimes attempts to run an unsigned installer may cause Windows **SmartScreen caution** like that one:

![Windows SmartScreen caution](img/smart_screen.png)

This caution informs you that software you are going to run is made by **unknown for the Microsoft** developer. And because Microsoft knows nothing about the author and software it **can not guarantiee it is safe** to run this software.

**I guarantiee the YOPT editor is not a malware.** 

I suggest to skip this warning and continue install. It is always **up to you to decide** (not Microsoft) wheather you trust the author or not.

You may review the source code of the editor on our [github page](https://github.com/SilverSwift/DCS_CMS_Editor) if you would like to.

Also you can actually build the YOPT from the source code. 

It is known that at least Symantec Endpoint Protection also cautions about risk of installing software from unknown authors:

![Symantec Endpoint Protection](img/sep.png)

We suppose that there might be similar cautions from other security packages.

# Install

Download an archive with the latest installer.
Unzip the archive.
You may use free 7z package if needed: https://www.7-zip.org/
Run installer and follow the instructions.
![Installer](img/install.png)

Wait for installation to complete.
Run YOPT with desktop shorcut or via start menu.
![Start menu](img/start.png)

# First run
With YOPT you will edit files on your hard drive located in the DCS World and DCS saves directories.

To work correctly YOPT needs the following paths:
* path to root of DCS installation, in most cases it is a "DCS World" dir;
* path to saves of DCS, in most cases it is a "DCS" dir in your user's "Saved Games" dir.

On a first run settings screen will be popped up and you are required to setup these paths.

**If YOPT won't be able to find a valid DCS install or saves it will inform you with an error message.**

You can always modify your paths using settings screen.

After settings was changed you may simply go to a home screen, changes applied immediately.

If there are several versions of DCS installed on your machine (release and open-beta for example) please ensure you have set correct paths to the version of DCS you want to edit.

**YOPT unable to operate if some paths invalid.**

# CMS editor
Editor screen displays a list of CMS programs. A list of parameters and allowed values varies from one aircraft to another.

It is still quite intuitive though.

This one is for A-10C and mimics CMSP a lot.
![A-10C](img/cms.png)


This one is for Harrier, same style but different functionality: 
![AV-8B](img/cms2.png)

To edit any parameter a standrd spinbox is used. Click once or hold for a while up and down arrows to edit a parameter.

Press **Apply** button to actually write changes you've made. Those changes will be stored in a DCS game folder and also in backup folder inside of DCS saves. 

*If you'll leave editor screen without applying changes they won't be written anywhere.*

Press **Restore** button to write stored in a backup folder CMS programs to a game folder. 

*This feature is usefull if you've just reinstalled or updated sim.*

Press **Reset** button to write default CMS programs to a game.
