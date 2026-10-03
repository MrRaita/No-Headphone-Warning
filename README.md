# Disable Headphone Safety Warning

A minimal systemless module for Android devices that disables Android's safe headphone volume warning and safe-volume enforcement.

## AI Disclosure

That headphone safety warning was annoying the hell out of me, so I had AI make this module for me.

Yep, I had AI do pretty much all of it because my coding skills are basically nonexistent. I have no idea why I'm sharing this here either, but hey, maybe someone else will find it useful. :)

## What it changes

The module adds the following system properties:

\`\`\`properties
audio.safemedia.bypass=true
audio.safemedia.force=false
audio.safemedia.csd.force=false
\`\`\`

## Compatibility

- KernelSU
- APatch
- Magisk

## Installation and removal

### Installation

1. Download the module ZIP from the project's Releases page.
2. Install it through KernelSU Manager, APatch, or Magisk.
3. Reboot the device.

### Removal

1. Open KernelSU Manager, APatch, or Magisk.
2. Find the module in the installed modules list.
3. Uninstall the module.
4. Reboot the device.
