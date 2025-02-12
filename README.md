Bulgarian Typographic Keyboard Layouts
=======
Enter rare characters with ease.

<img src="https://ilyabirman.ru/typography-layout/i/layout-win@2x.png"
     alt="Typographic keyboard layout for Windows"
     style="float: left; margin-right: 10px;" />

## Overview

Being a connoisseur and admirer of Bulgarian culture and the Bulgarian language, I've developed a Bulgarian typographic keyboard layout that allows you to enter additional characters, such as regular quotes, long dashes, some simple fractions and other similar symbols. 

Layout is based on **Ilya Birman's Russian Typographic Keyboard Layout** (https://ilyabirman.ru/typography-layout/).
All special/typographic symbols are identical to the ones in Birman's Layout, with the exception of the Ruble symbol (**₽**) which for obvious reasons isn't used much in Bulgaria so I've replaced it with the old Bulgarian symbol **ѫ** (located on the same key).
BDS and Phonetic are reordered according to traditional Bulgarian keyboard layout standards. 

Created with **Microsoft Keyboard Layout Creator** (https://www.microsoft.com/en-us/download/details.aspx?id=22339)

The layout works in Windows 2000 / XP / Vista / 7 / 10 (32- and 64-bit versions). Not tested on Windows 11, but in theory should work there too.

You can [report any issues here](https://github.com/acnapyx/bg-typographic-layout/issues). Also you're free to download/modify it as you please.


## Usage

Characters are entered with the right Alt pressed, for example Alt +  < and Alt + > give **«** quotes **»** . If the symbol is shown at the top part of the button, this means you also need to press Shift, for example Alt + Shift + C will give **¢** .


## Installation, updates, uninstallation:

There are four installers in the archive: for BDS, Traditional Phonetic (ЯВЕРТЪ), New Phonetic (ЧШЕРТЪ) and for English layout.

Run the setup.exe files from the distribution folders.
Go to the "Options", "Time and Language", "Language". Choose Bulgarian, click "Options". Add typographic layout, remove the default one. Repeat for English.
Something is wrong? Reboot.

When upgrading, must first remove the old layout.

The layout is deleted in “Add or Remove Programs” after disabling it in “Keyboard Settings”.


## FAQ:

### No Mac typographic layout for Bulgarian? Really?

Yep. I don't have a Mac so I'm unable to prepare the necessary layouts for this platform. Use Birman's Typographic Layout for English, or create one on your own :)

### No Linux/Unix/Ubuntu/FreeBSD typographic layout for Bulgarian? Really?  

In modern distributions additional typographic symbols can be enabled in the keyboard settings ("Enable extra typographic characters" option). For more info about this check out Maxim Taranov's post (https://tinyurl.com/typolayout).

### Something doesn't work in Figma. 

Please contact Figma developers. Figma forcefully takes control of keyboard shortcuts used by the keyboard layout and there's nothing I can do. 

### How to write the Bulgarian accented ѝ?

You don't need a typographical layout to do this. In BDS layout, the ѝ symbol can be entered by pressing Shift + a (BDS: ь), in Traditional Phonetic — by Shift + x (Phonetic: ь). Uppercase ѝ can be entered by pressing Caps Lock and the above mentioned keys.

### How to write the ellipsis symbol? 

Alt + / . It is not in the picture, because it is not recommended to be used (its use is an abuse of common sense).

### How to use accents? 

All accents live on Alt + Shift + characters. To attach any such accent to the character that you just entered, you need to press Alt + Shift and, holding them, double-press on the button with the desired accent. If you want to enter a letter immediately with an accent, then you must first press Alt + Shift + Accent, and then the desired letter. But keep in mind that the letters that have immediate accent are very few, and this method may not work. If you need, let's say, just put stress symbol, use the first method. If you write the German word, and you need to write the letter ü, then the second.

### I've installed the layouts in Windows 8/8.1/10/11, they're not shown in Language Bar.

Reboot.

### How to remove from the list of layouts the standard ones I no longer use? 

The layout to be removed should not be set as default layout. Some versions of Windows cannot disable the layout the first time (after closing the keyboard settings window, the layout suddenly returns to the list) - in this case, you need to try again, and everything will work out.

### There is no right Alt on my laptop, how to use the layout? 

Use left Ctrl + Alt.

### Why do Control + Alt + Letters enter characters from the layout? 

There are two keyboard modes in Windows - when left and right Alt are equivalent and when right Alt is synonymous with Ctrl + Alt. Birman has used the second mode to put right Alt as binding key. As Bulgarian Typographic Layouts are based on his project,  combinations with the right Alt work also for Control + Alt. 

### Something doesn't work in Windows 10/11.

Cannot help. Please read the discussions in Birman's blog (http://ilyabirman.ru/meanwhile/all/tipografskaya-raskladka-pod-vindousom-10/) on this matter.

### How to make Control + Alt + keypresses still execute shortcuts in applications, and to enter the layout characters only when right Alt is pressed?

Vladislav Loktionov found a trick (https://github.com/microsoft/PowerToys/issues/14535#issuecomment-1146884513) to achieve this using the **Mahou app** (https://github.com/BladeMight/Mahou). The point there is that while pressing Control + Alt, the program quickly replaces the layout with the standard one. Follow the instructions below to achieve the desired result:
1. Unpack the latest release of Mahou (https://github.com/BladeMight/Mahou/releases/download/latest-commit/Release_x64.zip) and run Mahou.exe.
2. In the "Functions" tab, uncheck "Remap Caps Lock as F18" and check "Start with Windows".
3. In the "Layouts" tab, uncheck the "Switch between layouts" checkbox (if you are okay with the system keyboard layout switching hotkeys).
4. In the field "Temporarily change the layout on LCtrl + LAlt combination" enter 67699721; this is the English (US) layout code. It is not required to set it additionally in the system settings.
5. Click "Apply", the rest of the settings can be set at your discretion.
6. Profit :)

### I'm used to pressing Alt + Enter to expand  video to full screen.

Many people use for this hotkey right Alt key, and after setting the layout, it stops working, because the layout uses the second mode (see above). I can only suggest switching to left Alt key.

### Why do I need a special layout if all these symbols can be entered from the keyboard anyway? 

If you remember the alt codes of all symbols by heart, and you don't feel that this is an abuse of common sense, then this layout is of no use to you. However, practice shows that only after switching to it, many people start to actually use all the cool symbols (even if they knew their codes perfectly well). 

### I installed your keyboard and my Windows registry crashed (my hard drive broke, my favorite dog died, etc.), who compensates for my losses? 

No one. I'm not responsible for the negative consequences of the use of the Bulgarian typographical layouts. 

## Acknowledgements:

Image of the keyboard layout is © Ilya Birman, provided here without any modifications for illustrative purposes.
