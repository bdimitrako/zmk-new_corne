## Corne consolidated keymap

![Manual keyboard layout creation](keymap-drawer/keyboard-layout-manual.png "manually generated by babis")
[Manual Keymap](https://www.keyboard-layout-editor.com/#/gists/2dfccb10efb1b1b25d5ebd17b6acdc26)
[English](README_EN.md)

# Customising Corne

## Base Layer
Customising a base layer to hadle some basic needs

1. Replace QUERTY with a more speedy layout
Layout of choice is COLEMAK DH with a slight rotation of the ', /, ; characters because i wanted an easier access to the accent giver (;:) button for my right pinky as almost every word gets accented in greek words.

2. Easily change between my main languages (English/Greek)
There is an on tap behaviour on the middle left thumb key that has win+space (language switcher for windows) that gives me that simple way to flow between languages even in the most difficult sentences without losing speed. e.g. "Το Project Plan μας αποτελείται από 4 sprints των 3 εβδομάδων."

3. Easily input even the most difficult keyboard shortcuts
For this i am using a custom behaviour of altered home row modifiers on the rest position of my fingers with tap preferred logic to avoid accidental triggering. This makes me a bit slower on the initiation of the combo but it is acceptable for me.

Most common keyboard shortcuts used
* win+arrow (from the joystick) to move app windows around
* win+number to activate the equivalent pinned item of windows taskbar
* win+shift+number to open a new session -//- 
* win+L to lock in windows
* win+r to run cmd etc
* win+i to access windows settings and connect to my wireless headset if not immediately connected (i find it faster than win+k that is searching devices)
* win+e to open file explorer
* win+shift+tilde(`) to access the windows power toys app zones editor
* win+alt+k as a combo stored in rotary encoder click to easy toggle mic mute accross system (yes overrides teams mute also) super handy
* ctr+t new tab in browsers, file explorer, format as table in excel
* ctr+n new window, new folder
* ctr+shift+r to hard refresh tab
* ctr+1 to open options in excel
* ctr+w to quit
* ctr+f to find
* ctr+L to access the address bar (combo this with win+number makes me super fast in opening new tabs or copying url to provide to another app)
* ctr+backspace to delete word by word (backspace is combo of n,e)
* ctr+tilde to reveal formulas in excel
* alt+arrow to navigate in file explorer 

Why is there a dedicated alt button although I have alt also in home row mods?
Well the home row mods holds down a key and needs a bit of time to do so and especially in excel where with alt press and release you can access the ribbon giving you access to any item by hitting a series of keys. I can also trigger these with / for excel but in windows alt+whatever key is underlined gives you keyboard access to any item of the context menu.

Sticky shift / caps dtap/tap mod on the right hand side thumb cluster super handy for Capitalising First Word Of Each Word with a single tap reducing the stress of shift being held and increasing my typing speed with punctuation by just adding a tap in the flow. Double tap provides Caps lock. Caps lock is also in a two key combo of c,d but i am not sure what to keep yet so i have them both. There is also Caps word behaviour on the combo of s,t. I was afraid that i would trigger ctrl+shift accidentally but I was happy to discover there was no such issue.

Backspace and delete were residing on my thumb cluster in the past but now I have them on two key combos in the home row n,e and e,i. Very handy and insane fast to delete with ctr n,e word by word.

Smart num functionality on the right thumb cluster to have num_word on tap and mo for num layer on hold.

Added a custom behaviour sl_mo that provides a sticky layer on tap and a mo on hold that is used on the right hand cluster to provide a single symbol on tap and a symbol layer on hold. Might study how to build a smart sym logic similar to smart num but I currently dont think I have that many cases of a series of symbols to be typed other than double brackets and the markdown of headers with hashtags.

## Number Layer
## Symbol Layer
## Navigation Layer
## Bluetooth & RGB Layer
## Function Layer
## Minecraft & Numpad Layer

## Corne keymap by layer
![Diagram of config/eyelash_corne.keymap](keymap-drawer/eyelash_corne.svg "generated by @caksoylar's Keymap Drawer")

