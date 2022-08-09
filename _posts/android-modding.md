---
layout: post
title: "Android Modding, What? Why? How?"
date: 2022-08-08
categories: android
description: "Post explaining around Android modding, What? Why? How? Pros and Cons."
published: true
canonical_url: https://yuri010.github.io/android/2022/06/28/android-modding.html
---

<!-- THIS SITE IS LICENSED UNDER THE CIR-LICENSE. FOR MORE INFO VISIT https://github.com/Yuri010/CIR-License/
ORIGINAL CAN BE FOUND AT https://github.com/Yuri010/CIR-License/blob/main/License.md -->

# Android Modding

### DISCLAIMER: I AM NOT RESPONSIBLE FOR BRICKED DEVICES OR ANYTHING LIKE THAT
### WITH GREAT POWER COMES GREAT RESPONSIBILITY, PROCEED AT YOUR OWN RISK
### UNLOCKING YOUR DEVICE COMPLETELY FACTORY RESETS IT, AND WIPES ANY DATA TO DIGITAL HEAVEN

Modding Android, it may be the most normal thing for superusers, others have never heard of it. This post will explain a bunch of the basic things.

### 1. Terminology
There are a lot of things and words that you might not understand in this post, that is why it begins with this part, the terminology :)\
Here there will be list of some things discussed:
 - ``ADB`` and ``Fastboot``, they are tools provided by Google to both debug but also modify your Android device.
 - ``Custom Recovery`` and ``TWRP``, A custom recovery can be used to install custom software on your device, from just a small modification, or maybe a handy systemwide equalizer you were looking for, to a whole different operating system. TWRP is an example of a custom recovery.
 - ``Bricked`` device, A bricked device just means that it doesn't boot / start.\
There are 3 forms: 
   - soft-bricked (Just doesn't start the OS, can be fixed most of the time)
   - hard-bricked (The bootloader or a critical Android component doesn't work anymore, can't access Fastboot or the recovery, harder to fix)
   - and hardware-bricked (hardware component doesn't work, can't really be fixed)
 - ``Unlocking``, the process of ``unlocking`` your device to allow flashing of custom firmware (for example a custom recovery)
 - ``Rooting``, the process of obtaining ``root`` access, allows you to modify system files.

### 2. Unlocking
Unlocking your phone opens the possibility of flashing custom firmware onto the device. With an unlocked device, you can install a custom recovery, custom ROM, all kinds of stuff like that.

### 3. The custom recovery
A custom recovery replaces the normal phone's recovery and gives you even more control over the device. Some modifications need to be installed through a custom recovery as they either need to modify the system or can't be installed while the system is running.\
You can also back-up your entire device from there, including your system, vendor and all stuff like that, this is also known as a NANDroid backup. In that case, if something goes wrong irrecursively, but you can still access your recovery, you can just flash a backup where you still had everything working like a charm!\
But you can also install a custom ROM from here (with all sorts of customization goodies, better privacy or just a higher Android version).
Or simple modifications like a system-wide equalizer, as most devices don't come with that out of the box.

### 4. The custom ROM
A custom ROM is a customized operating system for your device, it can have a lot of improvements! For example:
 - A newer Android version than the stock
   - (Which may also improve app compatibility :))
 - Better privacy
 - Improved customization\
Though it can also have their downsides:
 - Less stable system
 - Certain device features may not work
 - You might miss features of your stock OS

### Rooting
Some people may confuse rooting with unlocking, though they are 2 completely different things.\
Rooting is the process of aquiring "root access" on your device, this allows you to modify system files you previously weren't able to. Apps can use these permissions to get even more advanced customization and you can get more control over your privacy!
Though more access isn't always good. If you give access to the wrong app, then stuff can go very bad!

### Pros **VS** Cons
After all this info, should you consider going through the hastle?\
Just go through these quick pros and cons and consider for yourself :)

**Pros**:
 - More Customization, with potentially more privacy
 - Can breathe life into an old device by refreshing its software to a newer Android version

**Cons**:
 - Can leave your device more vulnerable
 - Some apps (like banking apps) can detect if your device has been unlocked and / or rooted and block the usage based on that
 - Can leave your device less stable due to running not officially supported software
   - Especially when the Android version is too new to run on your device, it can get very slow and instable

In my opinion: It is fine, it has its pros for powerusers like me, but if you're just a normal user and happy with what you currently have- then what are you doing here?\
Please just read the disclaimer again at the top of this page and you can choose for yourself :)
