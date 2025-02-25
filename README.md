# Komono #
-----
Komono is intended as a universal, orthoganal, and ergonomic layout designed for 36 keys. 
Designed to function the same on any ortholinear or egonomic keyboard of 36 or more keys, with any additional keys available free for additional function.

---

Komono is a fork of [Miryoku](https://github.com/manna-harbour/miryoku) with some additional functionality.
As such, most guiding principles are the same. Namely:

- Use layers instead of reaching
- Use both hands instead of contortions
- Use home positions as much as possible
- Full use of thumbs for primary utility
- Avoid complication
- When practical, reflect or imitate standard Ansi layout for ease of skill transference
---
## Details ##
Most functions are identical to miryoku, as such refer to [miryoku reference doc](https://github.com/manna-harbour/miryoku/blob/master/docs/reference/readme.org) on original for any functions not exlplicitly discussed here

This iteration contains 2 primary deviations:
1. flipping of some default layers to more closely mirror the standard ANSI 108 key layout
     This is _almost_ entirely possible using miryoku's `MIRYOKU_LAYERS=FLIP` functionality with some additional keymap moves. included by default here for convenience
3. addition of a unique base layer replacing the "Extra" base layer built into miryoki
     Miryoku is intended primarily as a typist's or coder's tool, as such has multiple base layer defaults for alpha base layer configuration, and a quick swap feature to go, for instance, from Colemak to QWERTY and back. This edition is meant to soften dissonance between standard ANSI 108 key layout and usage of this layout. As such. QWERTY is default base layer and extra base layer has been supplanted with a shifted layer designed for gaming with as few keybinding changes as possible in app. this extra layer has 1 addtional layer to provide additional key options on same hand as layer key, for one handed use in game.
---
### Base Layer ###

![Base Layer](https://github.com/user-attachments/assets/0a8d93f4-f16d-4656-870d-b67cee330398)


Base Layer is identical to default QWERTY layout in miryoku, except layer control positions are modified

---

### Number/Symbol Layer ###

![Num Layer](https://github.com/user-attachments/assets/8ec74d6d-3312-416d-a804-d05c569cc8cd)


Num Layer is flipped to more closely match 108 key numpad. holding Num2 accesses duplicate key, but numbers are Numpad keypresses rather than Num/Sym combo keys

---
### Function Layer ###

![Fun Layer](https://github.com/user-attachments/assets/78815682-bc97-4dfd-a446-e198870164a1)


Function Layer mirrors Num layer with F keys when possible to avoid dissonance, adding additional control keys

---
### Mouse Emulation Layer ###

![komonomouselayer](https://github.com/user-attachments/assets/148d3cb5-bd16-440c-a5b1-3727562ed07f)


Mouse layer provides mouse movement on home row, with matching scroll wheel movement under. simple macros on top row, with clicks on thumb

---
### Navigation Layer ###

![komononavlayer](https://github.com/user-attachments/assets/743aef5f-9034-4f95-bf52-220e7d61aab9)


Nav layer contains arrow keys and navigation cluster controls, with common macros above

---
### Media/Extras Layer ###

![komonomedialayer](https://github.com/user-attachments/assets/0ac73c90-6240-4635-8c39-fcd605d24a12)


Media layer contains media controls, as well as firmware controlled keyboard controls

---
### Base 2 Layer ###

![komonobase2layer](https://github.com/user-attachments/assets/8427616a-26b5-46a3-bedd-d08d970a5b4e)


Base 2 is designated default layer by double tap of Base 2 key in secondary menus. Intended as a gaming layer to minimize in game keybind alteration, with mouse emulation on right hand, including 3 additional mouse buttons

---
### Base 2x Layer ###

![komonobase2xlayer](https://github.com/user-attachments/assets/fd2e8da7-87ed-4b50-b9f3-9f1b2530e947)


Base 2x Layer replaces alpha kepresses from Base 2 with alternates while maintaining mouse emulation and standard hold keys

---

Mod Tap and LT functions displayed on front edge of keys, and grayed legends on secondary and Base 2 layers require double tap to avoid accidental engagement
