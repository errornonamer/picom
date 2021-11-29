[**Click here for the official picom README**](https://github.com/yshui/picom)

![picom.png](https://github.com/ibhagwan/picom/raw/next/picom.png)

## Why another picom fork?

**TL;DR:** rounded corners, dual_kawase blur and window animations on all backends.

### This fork contains:

- Dual kawase blur method from [tryone144](https://github.com/tryone144/compton) as well as his new [feature/dual_kawase branch](https://github.com/tryone144/compton/tree/feature/dual_kawase) which implements the dual kawase blur method on the experimental glx backend.

- Rounded corners code from [sdhand](https://github.com/sdhand/picom) which is also ported to the experimetnal XRender backend.

- New code for rounded corners (+borders) on the glx backend using GLSL fragment shader for both legacy and experimental backends

- Window animations code from [dccsillag](https://github.com/dccsillag/picom/tree/implement-window-animations)

## Known issues

- xrandr backend is broken (low performance, no rounded corners)

## How to install

### Build from source

Clone this repo and follow the [build instructions of the official picom README](https://github.com/yshui/picom/blob/next/README.md#build)

