## Hackintosh macOS Sonoma : Avita-Liber-v14

I removed the USBMap Kext; strangely things are more stable when not using it. I will stick to not using it...

> Opencore version: 1.0.1
> macOS version: *14.6.1*
> Processor: *intel i5 10210u*
> Ram: *8gb DDR4*
> Storage: *256GB ssd (non-nvme, 6gbps sata link)*

### What Works:

1. Full QE/CI support
2. USB-C HDMI dongles
3. microhdmi-hdmi dongles
4. battery status, etc.
5. multitouch trackpad / gestures / etc
6. Bluetooth
... mostly everything works

### What does not work (should work in the future):

1. Brightness keys
2. Lid status (no automatic sleep when lid is closed)
3. Hibernation ??!!
... small things, nothing major, system is stable enough

What will not work, ever.

1. wifi, qca9377 is unsupported by macos
