# Sindo

An open source full custom keyboard based on the Ergodox keyboards.

## Goal

The objective is to ultimately create a bluetooth low-profile switch version of the Ergodox, with a different layout for the thumbkeys. This design will probably not be RGB backlit, but that might change in the future. This project has no affiliation with Ergodox or ZSA.

## Hardware overview

The current goal is to use the ESP32-WROOM from Expressif, it has built-in bluetooth, a low-power processor and additional peripheral support via I2S and I2C that can later be used to drive a RGB matrix. It has enough IO to facilitate the scanning matrix. It is pretty easy to get your hands on one, and is very well priced for the massive feature set that it is comprised of. 

I am currently considering using blue low profile gateron switches. This is purely personal preference. There are also brown varieties in the same form factor.

## Software

Still considering whether or not to write my own firmware, fork an existing project or just make minimal customizations to and existing project. A few promising projects:

- https://github.com/asterics/esp32_mouse_keyboard
- https://github.com/Galzai/MK32

## Contributing

This is intented to be my personal keyboard, feel free to use this design as a base for your own, however, I cannot guarantee the stability of the designs in this repo. As such, I will not be accepting PR's or attending to issues :) This might change depending on the popularity of this project.
