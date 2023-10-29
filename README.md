# This project is no longer maintained

Issues will not be attended, the code is provided as is for anyone who wants to try and improve it themselves

# Joystick Visualizer
[![GitHub release](https://img.shields.io/github/release/mdjarv/joystickvisualizer.svg)](https://github.com/mdjarv/JoystickVisualizer/releases/latest)
[![Donate](https://img.shields.io/badge/Tip%20Jar-PayPal-green.svg)](http://paypal.me/mdjarv)
[![Discord](https://img.shields.io/badge/Discord-Chat-blue.svg)](https://discord.gg/4nc3XtQ)

Show your stick and throttle movement as an overlay while streaming or recording videos.

### **[Download latest release here](https://github.com/mdjarv/JoystickVisualizer/releases/latest)**

This software will read buttons and axis input from supported devices and visualize them using 3D models on top of a flat colored background making it easy to apply chroma key and placing them as overlays using streaming software like OBS or XSplit

![Preview of Joystick Visualizer](https://raw.githubusercontent.com/mdjarv/JoystickVisualizer/master/preview_image.png)

### Supported Devices

* CH Pro Pedals
* Logitech 3D Pro
* MFG Crosswind
* Saitek Rudder Pedals
* Saitek Combat Rudder Pedals
* Saitek X45 HOTAS (Using Warthog 3D model)
* Saitek X52 Throttle
* Saitek X52 Joystick (Using Warthog 3D model)
* Saitek X52 Pro HOTAS (Using Warthog 3D model)
* Saitek X55 Throttle
* Saitek X55 Joystick
* Saitek Pro Flight Throttle Quadrant
* Thrustmaster Warthog Joystick
* Thrustmaster Warthog Throttle
* Thrustmaster T.Flight Rudder
* Thrustmaster T16000M
* Thrustmaster T.Flight HOTAS X (Using Warthog 3D model)
* VKB Gunfighter (Using Warthog 3D model)
* Virpil Mongoos T-50 (Using Warthog 3D model)

If you want to get in contact with me hop on my [Discord](https://discord.gg/4nc3XtQ) server and say hello or tweet me [@papapiishu](https://twitter.com/papapiishu)

## Setting it up

### Start the Software

* Start `JoystickProxy.exe`, you will see a list of found devices. If your device is in the [Supported Devices](#supported-devices) list but does not show, check the "`Show all devices`" checkbox and contact me so that we can figure out what the issue is.

![Proxy Window](https://raw.githubusercontent.com/mdjarv/JoystickVisualizer/master/proxy_window.png)

* Start `JoystickVisualizer.exe`, select your resolution and make sure to run in Windowed Mode

![Visualizer Window](https://raw.githubusercontent.com/mdjarv/JoystickVisualizer/master/visualizer_window.png)

Your devices should show up in the Visualizer when you start moving them

### Configure OBS

1. In OBS add a `Game Capture` source, give it a useful name like "Joystick Visualizer"
2. Make sure you select `JoystickVisualizer.exe` and you can also uncheck `Capture Cursor`
3. `Allow Transparency` should also be checked

### Controlling the camera

The camera in the Visualizer can be moved around by right-clicking and dragging, and the view can be zoomed using the mouse wheel.

There are also three camera presets that can be accessed with the `1`, `2` and `3` keys on the keyboard.

## Credits

The Visualizer was created in Unity3D, and the Proxy is a normal C# application that is using the SharpDX library for capturing the USB controllers.

3D model of the Thrustmaster Warthog Joystick was made by Daniel S. and can be found on 3D Warehouse:

* https://3dwarehouse.sketchup.com/model.html?id=u688a84e3-d0f0-4e07-aed1-0715d11dd8f5
* https://3dwarehouse.sketchup.com/model.html?id=ue4b69784-5c08-4753-9d72-5cee5e6e5882

3D model of the Thrustmaster Warthog Throttle was made by Oliver G. and can be found on 3D Warehouse:

* https://3dwarehouse.sketchup.com/model.html?id=1870c8e3d1267a38c023ee32d47e2fa9

3D model by By-Jokese (https://byjokese.com)

* Saitek X55 RHINO stick and throttle
* Saitek Rudder Pedals
* Saitek Combat Rudder Pedals

## Contact

You can find me on:

* Discord: https://discord.gg/4nc3XtQ
* GitHub: https://github.com/mdjarv
* Twitter: [@papapiishu](https://twitter.com/papapiishu "@papapiishu on twitter")
* Twitch: [papapiishu](http://www.twitch.tv/papapiishu "papapiishu on Twitch")
