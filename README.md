## IL.P1S / IL.X1C

<!--
![Klipper Logo](/images/logo_new.png)
## Join the [**Community Discord!**](https://discord.gg/W6B5mBejuC)

## Support me on [**Ko-Fi**](https://ko-fi.com/chazmakes). It's not necessary, but if you want to help out at all then all support is greatly appreciated!
-->

> [!Caution]
> This is a fork of a beta project. Chaz and I are not responsible for anything done to your machine.
> 
> Be brave enough to sacrifice your warranty, or think again.
> 
> Stay ready to print a replacement part AT ALL TIMES. You may break something.

Welcome to IL.P1S! This fork is based on Chaz's effort; consider [**buying him a few V6 nozzles. (Ko-Fi)**](https://ko-fi.com/chazmakes)

<!-- The project is STILL in beta, with 2 working P1K in the wild. This is a **non-destructive (PCB Only)**, or **destructive** upgrade path to [**Klipper**](https://www.klipper3d.org/), on a Bambu Lab P1 or X1. This means replacing the existing electronics with OSHW. A custom PCB has been designed to make everything plug and play with the fans, heatbed etc. BLKC runs on a fork of Klipper known as [**Kalico**](https://github.com/KalicoCrew/kalico). Make sure to get yourself familiarized with [**The Klipper Docs**](https://www.klipper3d.org/) or [**The Kalico Docs**](https://github.com/KalicoCrew/kalico/tree/main/docs) -->

If you wish to re-use your AMS 1, please check out [OpenAMS](https://openams.si-forge.com/).

Find extensive documentation, including a BOM and lots more [**here**](https://docs.chazmakes.com/)!

The current release is <ins>**0.1**</ins>, updates coming soon (pinky promise)

## What works?
- ✓ The full hotend and extruder assembly
- ✓ Heatbed control with the Stock SSR
- ✓ The entire motion system is unchanged
- ✓ All fans work if wired correctly (PWM and Tach control needs to be added)
- ✓ Bambu Lab AMS does work via the [**OpenAMS project**](https://github.com/OpenAMSOrg)
- ✓ Piezoelectric Probing was proven to work, check out [the docs](https://docs.chazmakes.com/piezoelectric-sensors.html)

- [?] Webcam (Standard USB layout, but I don't know what is what. GG for now)
- [?] Toolhead boards: I'm working hard to make EBB-36 work
- [?] Cartographer V4 / Beacon Rev.H
- [?] Filament runout detection (I think I found it?!)
- [?] Same thing, but on X1C

- ✖ Stock display (NEVER!)
- ✖ A few stock fans
- ✖ You must EXPLICITLY generate a new printer on OrcaSlicer. I'll try my best to erase this issue from existence.

## Literally why, what is the damn point.. my Bambu works fine!!!!????

At first, this was entirely just a joke. More of a "why not" sort of thing. But as time went on the benefits outweighed the drawbacks. It provides a great platform for modding and gives you full control. Most importantly, having the heatbed capable of running at 110 [degree symbol]C! Whatever you can think of, you can do it with this platform. Another upside is it also completely eliminates the Bambu Cloud, allowing you to run everything locally, or even use your own cloud service. No lockdowns, **your printer is YOURS.**
