# Sidecar for Android & Mac Guide

Use Parsec, BetterDisplay and MouseHook to build your own portable "one more screen".
Tested on MacOS Sonoma. 
Latency is very low if you're in a local network. Otherwise you can also tether.

## BetterDisplay:
Project Download:
https://github.com/waydabber/BetterDisplay/releases

Better Display can create a virtual screen that supports retina resolution and suits your own device's screen ratio. It is much better than Parsec's bad implementation of virtual screen. 
And the features that we would be needing are free. Many thanks to the owner and maintainer of this project, @waydabber.

## MouseHook:
Parsec + Better Display can solve the issue of projecting the screen lag-free. But you would notice that you wouldn't be able to see your mouse, without our hero, MouseHook here.
I don't own this app and it's written by @brgj. Original project link is here: https://github.com/brgj/MouseHook
Many thanks @Brgj for sovling this issue!

## Parsec:
Simply download and install Parsec on your Mac and Android device.


# Setup and usage

- add a virtual screen in your BetterDisplay app. If you're using foldable devices, you can add a 4:3 screen. BD allows you to create custom virtual screen during your Pro license trial. You can disable license features afterwards but BD wouldn't remove your already added virtual screen. However, I strongly suggest you to donate/buy this app.
- set up MouseHook and enable it on the virtual screen. Simply click it's menubar icon and make sure the virtual screen has a tick on it.
- In Parsec Mac, start to share your screen.
- On Parsec Android, connect to your Mac, and click on the Parsec icon to switch to the correct display (virtual display).
- There's a bug on Parsec Android relating to its Vulkan renderer. You might see a green screen after switching virtual display, but that's normal. Simply disable Vulkan renderer, and restart it, then everything should be fine.
- Vulkan renderer is strongly suggested because it has a much lower latency.

# Example and Video Guide
- coming soon if i have nothing else to do.
