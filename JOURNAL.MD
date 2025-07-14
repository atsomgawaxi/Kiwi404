---
title: "Kiwi404"
author: "AtsomGawaxi"
description: "This is an addition to my KiwiVerse, this is a pentesting tool based on the FlipperZero platform"
created_at: "2025-07-11"
---

# July 11 (Official Start)
Started making the schematic today, i'm using EasyEDA since i find it easier to upload everything to JLCPCB when i'm done, plus, it has the built-in LCSC page.
Since i'm doing a project similar to the Flipper, i thought of using a stronger MCU (the MCU it comes with is the STM32WB55RG). But the "strongest" thing i found, was a different package with more pins than the RG (the VG package). But since i'm doing my own kind of spin-off of it, i'm planning on adding it's original features, plus some features that aren't on the normal flipper that are nice to have, without relying on a external module, that is. So it is nice having extra pins.
I don't really plan on doing my own firmware for it though, i just plan on making a build of it's original open-sourced firmware that is compatible with my hardware. Since it's a lot of modules to code in, and there probably aren't many code libraries for them. So it's way more viable (and faster) to reuse the Flipper's original firmware.
**I also need to do this FAST, since Highway ends in the 31st.**

This was mostly a research day, since i needed to know about the original Flipper's specs and properties, so i didn't do much on the schematics.

**Time spent: 3h**

# July 12 
God, how i hate and love EasyEDA at the same time, it has some weird controls and lack of keyboard shortcuts, like, what do you mean i have to go out of my way to the top toolbar to simply rotate a component instead of just pressing R? Anyways, i'm planning to do most stuff like the original Flipper, things like power, some of the MCU wiring, that sort of stuff.
[Here's my current reference.](https://docs.flipper.net/development/hardware/schematic)

**Time spent: 2h**

# July 13
*Fuuuuuuuuuuuuuuuuuuuuck.* Depending on how this goes, i might aswell have to switch back to the original Flipper's hardware, since i discovered that the stock firmware is really weird with different components, even if they're slightly different. If i can't work around something with the stock firmware, i might just use Momentum Firmware, which is a lot more portable.
I also probably won't replicate the power schematics and that sort of stuff, since it's probably overcomplicated for what i'm doing, and can probably be dumbed down a LOT.
[MonkaS](https://docs.flipper.net/development/hardware/schematic#tAW55)

**Time spent: 2h**

# July 14
The STM32WB55VG will HAVE to do, since there's LITERALLY NO AVAILABLE PINS besides the ones for module boards, look at this:

<img src="https://media.discordapp.net/attachments/1385442305632112694/1394396898047299584/image.png?ex=6876a8cf&is=6875574f&hm=41b0e5fda9c368e3e9c25c36a8711c148d393df2d6227419506b7c3e35a4f4ff&=&format=webp&quality=lossless">
