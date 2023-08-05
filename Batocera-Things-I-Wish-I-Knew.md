---
title: Batocera Things I Wish I Knew Starting Out 
version: Batocera V37
---

# Swap A and B buttons in navigation of Batocera
set this option toggle to "on": 
> MAIN MENU > SYSTEM SETTINGS > FRONTEND DEVELOPER OPTIONS [the very last option in this menu] > SWITCH CONFIRM & CANCEL BUTTONS IN EMULATIONSTATION [toggle this to the right]

# Improve emulation performance Raspberry Pi 4 with Nintendo 64:
set this option: 
> MAIN MENU > SYSTEM SETTINGS > HARDWARE > OVERCLOCK > TURBO(B0 HEATSINK - 1800MHZ)

# Improve emulation performance on single board computers with Nintendo 64, Dreamcast: 

## N64: 
> Go into Nintendo 64 list 
> Open View Options [not "Main Menu"]
set aspect ratio: 
> OPTIONS > ADVANCED SYSTEM OPTIONS > GAME ASPECT RATIO > 4/3 
set rendering resolution: 
> OPTIONS > ADVANCED SYSTEM OPTIONS > 4:3 RENDERING RESOLUTION > 1X (640X480)
optional: set display's resolution 
> OPTIONS > VIDEO MODE > [set to something lower than default, like 1280x720 ]
optional: add retro look to offset 'pixelated output'
> OPTIONS > ADVANCED SYSTEM OPTIONS > GAME RENDERING & SHADERS > SHADER SET > CURVATURE [or users choice]

## Dreamcast: 
> Go into Dreamcast list 
> Open View Options [not "Main Menu"]
> OPTIONS > ADVANCED SYSTEM OPTIONS > RENDERING RESOLUTION > 1X (640X480)

# Improve navigation performance on low end single board computers: 
> MAIN MENU > SYSTEM SETTINGS > FRONTEND DEVELOPER OPTIONS > PRELOAD UI ELEMENTS ON BOOT [on] + PRELOAD UI METADATA MEDIA ON BOOT [on]

# Scraper stops running if you turn off or disconnect your monitor.

# The popular/affordable retro controllers are sold by 8bitdo. 
Their SN30 pro has L2 and R2 buttons that are easy to miss. 

In addition to Start and Select buttons, there are two more buttons that you can set to batocera's hotkey > 
![Imgur Image](https://i.imgur.com/JHkJn5p.png)

The wired controller has been pain free. 

Note I have 0 affiliation with 8bitdo. 

# libretro's default bindings: 
[default bindings](https://docs.libretro.com/guides/input-and-controls/)

# retroarch default joypad hotkeys: 
Select = Hotkey	
Select+Start = Exit	
Select+Right Shoulder = Save	 
Select+Left Shoulder = Load	 
Select+Right = Input State Slot Increase	
Select+Left Input = State Slot Decrease	
Select+X = RGUI Menu	
Select+B = Reset	

[RetroArch Controller Configuration](https://retropie.org.uk/docs/RetroArch-Configuration/)
