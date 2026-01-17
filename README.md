## Bambu Lab Klipper Conversion!

![Klipper Logo](/images/logo_new.png)

## Join the [**Community Discord!**](https://discord.gg/W6B5mBejuC)

## Support me on [**Ko-Fi**](https://ko-fi.com/chazmakes). It's not necessary, but if you want to help out at all then all support is greatly appreciated!

> [!Caution]
> This Project is in **BETA**, doing this conversion is fully at your own risk, I am not responsible for any damages done to your machine. This also will likely void your warranty.

Welcome to the Bambu Lab Klipper Conversion page! The project is STILL in beta, with 2 working P1K in the wild. This is a **non-destructive (PCB Only)**, or **destructive** upgrade path to [**Klipper**](https://www.klipper3d.org/), on a Bambu Lab P1 or X1. This means replacing the existing electronics with OSHW. A custom PCB has been designed to make everything plug and play with the fans, heatbed etc. BLKC runs on a fork of Klipper known as [**Kalico**](https://github.com/KalicoCrew/kalico). Make sure to get yourself familiarized with [**The Klipper Docs**](https://www.klipper3d.org/) or [**The Kalico Docs**](https://github.com/KalicoCrew/kalico/tree/main/docs)

If you wish to re-use your AMS 1, please check out [OpenAMS](https://openams.si-forge.com/), they have drop in electronics to make the AMS work with Klipper systems!

Find extensive documentation, including a BOM and lots more [**here**](https://docs.chazmakes.com/)!

The current release is <ins>**0.1** </ins>, updates coming soon (pinky promise)

## What works? (as of release <ins>**0.1**</ins>)
- ✓ The full hotend and extruder assembly
- ✓ Heatbed control with the Stock SSR
- ✓ The entire motion system is unchanged
- ✓ All fans work if wired correctly (PWM and Tach control needs to be added)
- ✓ Bambu Lab AMS does work via the [**OpenAMS project**](https://github.com/OpenAMSOrg)
- ✓ Piezoelectric Probing was proven to work, check out [the docs](https://docs.chazmakes.com/piezoelectric-sensors.html)

- ✖ Webcam (You can purchase the X1C camera and wire it up as a USB camera)
- ✖ Stock display (Never will)
- ✖ Toolhead boards
- ✖ Filament runout detection
- ✖ Not everything is plug and play. There is a PCB design available to make this non destructive You will need to splice on extension cables + JST XH 2.54 or DuPont 2.54 connectors.

## Literally why, what is the damn point.. my Bambu works fine!!!!????

At first, this was entirely just a joke. More of a "why not" sort of thing. But as time went on the benefits outweighed the drawbacks. It provides a great platform for modding and gives you full control. Most importantly, having the heatbed capable of running at 110C! Whatever you can think of, you can do it with this platform. Another upside is it also completely eliminates the Bambu Cloud, allowing you to run everything locally, or even use your own cloud service. No lockdowns, your printer is YOURS.
