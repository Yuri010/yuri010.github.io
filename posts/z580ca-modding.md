<!-- THIS SITE IS LICENSED UNDER THE CIR-LICENSE. FOR MORE INFO VISIT https://github.com/Yuri010/CIR-License/
ORIGINAL CAN BE FOUND AT https://github.com/Yuri010/CIR-License/blob/main/License.md -->

# Z580CA Modding

### DISCLAIMER: I AM NOT RESPONSIBLE FOR BRICKED DEVICES OR ANYTHING LIKE THAT, ALL CREDITS GO TO THE ORIGINAL CONTENT OWNERS
### WITH GREAT POWER COMES GREAT RESPONSIBILITY, PROCEED AT YOUR OWN RISK
The Asus Zenpad S 8.0 had a bunch of trouble finding a way to be unlocked let alone rooted.\
When the FOTA servers went down, this was even harder as these were normally needed for the unlock process.\
The Android 6.0.1 firmware wasn't even unlockable! The bootloader would spit out an error that you need to enable the "Enable OEM Unlocking" option within the Android OS Developer Options. But that toggle doesn't even exist!

After contacting Asus I got the info that:
 - The FOTA servers were down
 - They won't be working on an unlock app like the newer Android devices have
 - I would just have to search the XDA forum for a solution\

Now that may not sound so hard, right? Wrong.. There isn't even a Device forum for this Zenpad.\
Though after just searching for a few months, I finally found the way, finally the 1 post.

### The Post
Credits to [@shakalaca](https://github.com/shakalaca) for [that one post everyone was looking for](https://forum.xda-developers.com/t/zenpad-s-root-achieved.3160422/page-66#post-75242374).
The post explains what their script will do and how to use it:
> I've build a package for the whole complicated process, so here you go:
> https://mega.nz/#F!F1FlzAoY!u6zR1Y14xvqoSbz-YQGFrw
>
> It will flash V4.x bootloader (ifwi) to ZenPad and set the unlock flag, then update the *correct* version of V5.x bootloader (ifwi) and do the unlock process. As far as I know the bootloader (ifwi) from V5.5.7 considers unlocked ZenPad as "device with corrupted software" and won't boot up. So we have to use the bootloader (ifwi) come from V5.4.3 (which is the same with V5.5.1)
>
> If your ZenPad is on V4.x, or just want a rooted ZenPad with latest firmware:
> 1. grab the files under folder "For_ZenPad_with_V4.x"
> 2. extract the split archive 'FreeMyZenPad.7z'
> 3. put libwinpthread-1.dll, mke2fs.conf and mke2fs.exe into "files" folder
> 4. click "Root.bat" and minutes later your'll get a rooted ZenPad. Please install 'MagiskManager-v5.5.5.apk' manually since I left the system.img clean.
>
> If your ZenPad is on V5.x and want to stay with current version
> 1. grab files under folder "For_ZenPad_with_V5.x"
> 2. extract FreeMyZenPadLite.zip
> 3. click Unlock.bat to unlock your ZenPad.
> 4. Grab the stock ROM with the same version in your ZenPad, extract boot.img and put into your device
> 5. Install 'MagiskManager-v5.5.5.apk' and then patch the boot.img
> 6. Fastboot flash boot patched_boot.img and you'll have root now.

Big shoutout to them! Honestly great work!

# Great! But what can you do with it?
That, will be explained in a following article :)
