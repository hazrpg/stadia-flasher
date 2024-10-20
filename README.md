# Stadia Controller Bluetooth Updater

## About
This is a local copy of the Stadia bluetooth update tool.
The reason for creating this is so that the tool can be preserved long after the site is removed on December 31, 2024.

Please note: For this to work you do need to run chrome with the flags `--allow-file-access-from-files` because of a CORS error.

## Getting started
- Make sure to run chrome with the flag above.
- Download the repo so that you have all the files.
- Go into the controller folder and look for the `index*.html` for your region/language e.g. `index_en_GB.html` is English (UK).
- Follow the steps on-screen. There is also a video of the whole process below (no commentary just music).

## Video
I created a video of the original process as it was live on the stadia website: https://www.youtube.com/watch?v=4iCb1uG145Y

## Website
This is the original website that the firmware was released on: https://stadia.google.com/controller

## TODO:
- [ ] Add in a way to be able to self-server this without needing the flag.
- [ ] Find the files `gotham_dvt_a_dev_signed.bin`, `gotham_dvt_a_stage_signed.bin` and ~~`gotham_pvt_a_prod_signed.bin`~~ since these are referenced and are the WiFi-based firmware.

## Special Thanks.

A massive thank you to the creators of Stadia, © 2019-2023 Google, for this excellent service - it will be missed. So long and thanks for all the fish.
