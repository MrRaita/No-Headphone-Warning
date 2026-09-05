# Disable Headphone Safety Warning

A minimal systemless module for Android devices that disables Android's safe headphone volume warning and safe-volume enforcement.

## What it changes

The module adds the following system properties:

```properties
audio.safemedia.bypass=true
audio.safemedia.force=false
audio.safemedia.csd.force=false
```

## Installation

1. Download the module ZIP from the project's Releases page.
2. Install it through KernelSU Manager, APatch, or Magisk.
3. Reboot the device.

## Uninstallation

Disable or remove the module from KernelSU Manager, APatch, or Magisk and reboot.

## Important

This module does more than hide the warning dialog. It disables Android's safe-media volume enforcement as well.

Listening to headphones at excessive volume can cause permanent hearing damage. Use this module at your own risk.

## Compatibility

- KernelSU
- APatch
- Magisk
- Android versions where these `audio.safemedia.*` properties are honored by the audio stack

## AI Disclosure

That headphone safety warning was annoying the hell out of me, so I had AI make this module for me.

Yep, I had AI do pretty much all of it because my coding skills are basically nonexistent. I have no idea why I'm sharing this here either, but hey, maybe someone else will find it useful :)
