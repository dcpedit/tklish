# TKLish

![TKLish keyboards](https://i.imgur.com/pxLNHCd.jpeg)

TKLish is a series of PCBS that mimic the style of a traditional TLK (Ten Key Less) keyboard.  Below are the 3 variants:

* s40 - 40% layout with staggered keys. [KLE layouts](https://www.keyboard-layout-editor.com/#/gists/37cd11a38042b60f3afcef27ad9ed609)
* o40 - 40% layout with ortholinear keys. [KLE layouts](https://www.keyboard-layout-editor.com/#/gists/dfc48e95a2b35d166118a279e23edf5c)
* o80 - 80% layout with ortholinear keys. [KLE layouts](https://www.keyboard-layout-editor.com/#/gists/64b1c8ef28d2a8a90b8a3357935d477c)

Features:

* s40 can use standard keycaps (no 40s kit required)
* s40 & o80 can utilize any ergo/ergodox kit with 1.5u modifier keys (ex. GMK Sixes, SA Carbon)
* PCB can support up to 3 rotary encoders
* Utilizes Unified Daughterboard (C4 version with Molex Pico-EZmate connectors)

The o80 PCB should work with any case that does require the PCB to be mounted (PCB has no mounting holes) and utilizes a USB-C daughterboard.  I've only been able to test it with the Thecca x Rubrehose case.

## Stacked Acrylic Case

![TKLish 40s case](https://i.imgur.com/5NLhVg1.jpeg)

I've designed a stacked acrylic case that works with the 40% PCBs.  You can look at the build guide in the [case](./case/README.md) directory.

## Firmware

Vial source code located here:

https://github.com/dcpedit/vial-qmk/blob/tklish/keyboards/dcpedit/tklish/

Vial: https://get.vial.today