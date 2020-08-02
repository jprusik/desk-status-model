# Desk Status Device

One common issue, especially in large office layouts and locations utilizing hot-desking, is the difficulty employees navigating their workplaces. In particular, tracking down the right desk can be tricky, even with proper space mapping.

Expensive commercial solutions provide desk signage to help workers find the right desk, but for businesses that can't afford these or prefer not to be locked into a proprietary hardware ecosystem, there's an alternative: self-assembled, low-cost devices capable of a robust feature set.

![Desk status (front-right, available state)](media/right-front-available.jpg)

This project aims to make it easy for anyone with a little technical inclination to build smart signage for their office desks in a cheap and scalable way. This particular configuration makes use of the [Robin platform](https://robinpowered.com/), which offers a myriad of office enhancements.
| | | | |
| --- | --- | --- | --- |
| ![front view, powered off](media/front-off.jpg) | ![left view, powered off](media/left-off.jpg) | ![back view, powered off](media/back-off.jpg) | ![right-back view, powered off](media/back-right-off.jpg) |
| ![front view, desk unavailable state](media/front-unavailable.jpg) | ![right-front view, desk unavailable state](media/left-front-unavailable.jpg) | ![left-front view, desk available state](media/left-front-available.jpg) | |

## Features

- A small physical footprint means your device won't compete for desk space.
- An OLED screen allows for simple or dense information display with sharp clarity, without being distracting. Desk assignment and reservation details are easy to check without maps or apps.
- An onboard multicolor LED allows for a variety of RGB lighting blends, with smooth crossfading and color mixing capabilities. Signal statuses or temporary beacons for at-a-glance information nearby or at a distance.
- The entire configuration can be powered by the USB port of a computer or monitor - no special adapters or power units needed.

### Seat status changes with your management platform

![Desk status change](media/desk-status-change.gif)

### Use beacon signals let employees increase their desk's visibility as they search for it

![Beacon signal](media/beacon-signal.gif)

### Shutdown sequence ensures no out-of-date information is provided when the device or desk is not active

![Shutdown sequence](media/shutdown-sequence.gif)

## Components

These are the components used in the configuration shown above, but there's a lot of flexibility, depending on the features you'd like.

- 1x Enclosure (models are included in this project for 3D printing)
- 1x 0.96 inch OLED (128x64 resolution)
- 1x Raspberry Pi Zero (wifi variant means one less cable to worry about)
- (optional) 1x micro USB LAN adapter (required for the non-wireless Raspberry Pi Zero variant)
- (optional) 1x RGB LED (required for status light features)
- 1x microSD card (4GB or more is sufficient)
- 8x Jumper cables
- 4x M2.5 screws
- 1x set of header pins

## Model versions

If you are printing your own enclosure, there are a few different models available, based on your components and desired configuration:

## Assembly

This project covers the physical construction of your desk status device. For software installation and set up, see the [desk-status](https://github.com/jprusik/desk-status) project.
