# test-gsi-rom-and-roms-links
### rom links i found:

## OxygenOS
**OxygenOS 15 [fuxi] (testoos_gsi_rom):**
https://mysticcloud.hpdevfox.ru/fb2dfce0a24ddc666b1b0916c969f53d9bdd8e4318e3395e/oostest.zip

[❌] Not tested

------

### gsi links i found:

## FlymeOS
> [!WARNING]
> FASTBOOT ONLY!

**FlymeOS-10 [any] (gsi):**
https://sourceforge.net/projects/mystic-gsi-updates/files/Flyme/Flyme-meizu18X-13-1686879531-AB-20240526-MysticGSI.zip/download


[✅] Tested on Samsung A53 5G

in order to boot flymeos on a53:


flash [android_kernel_samsung_a53x-FireAsf/releases/tag/5.1](https://github.com/Ksawlii/android_kernel_samsung_a53x-FireAsf/releases/tag/5.1) and then file `FireAsf-5.1-Vanilla-StableAsf-00.20.tar` via odin3 i recommend [Odin3_v3.13.1_3B_Patched_Samfw.com.rar](https://samfw.com/Odin/Odin3_v3.13.1_3B_Patched_Samfw.com.rar) then use [TWRP-a53x](https://twrp.me/samsung/samsunggalaxya53.html) to flash the rom via Fastboot

> [!Note]
> i'm working on patching this gsi for a53, so the phone would work normally.

-------

**FlymeOS 10 (umi-mi11):**
https://drive.google.com/drive/folders/1gHP2qhMndr2Me5eosMuSczJEm0UPj_jP?usp=sharing

Tested, works fine.
> [!Warning]
> FLASH THIS WITH YOUR OWN RISK

Bugs i noticed:
- fingerprint
- NFC

this rom is made by a chinese dev named youlinw or youlinw233, all credits go to him

**Flashing:**
Flyme OS 10 for Mi 11 (Android 13)

(must be installed in fastboot)



Instructions:

Run the included install_ROM.bat file (press Y and Y for root or Y and N for no root)

If it fails at the last step just flash super.img manually

Boot into recovery and format data (any recovery works)
