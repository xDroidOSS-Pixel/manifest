<p align="center">
<img src="https://github.com/xDroidOSS-Pixel/manifest/blob/udc/banner.png">
</p>

# xdroidOSS | Only for Pixel Devices
a android based on AOSP with Minimalist UI Design.

# Getting Started
---------------
To get started with the xdroidOSS sources, you'll need to get
familiar with [Git and Repo](https://source.android.com/setup/build/downloading).

Minimum Build Requirements : Linux OS with 8 core or more and 32 GB RAM (Swap Memory if RAM is not enough).

### Sync source ###
To initialize your local repository, use command:

```bash
repo init -u https://github.com/xdroidOSS-Pixel/manifest -b udc_qpr1
```

Then sync up:

```bash
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags --optimized-fetch --prune
```

### Build source ###
Initialize the ROM environment with the envsetup.sh script.

```bash
. build/envsetup.sh
```

Lunch your device after cloning all device sources if needed.

```bash
lunch xdroid_$devicecodename-userdebug or user
```

Start compilation
```bash
make xd -j$(nproc --all)
```

### Special Credits ###
 * [**xdroidOSS**](https://github.com/xdroid-oss)

### Credits ###
 * [**AOSP**](https://android.googlesource.com)
 * [**AOSPA**](https://github.com/AOSPA)
 * [**CAF**](https://source.codeaurora.org)
 * [**crDroid**](https://github.com/crdroidandroid)
 * [**Evolution X**](https://github.com/Evolution-X)
 * [**HentaiOS**](https://github.com/hentaiOS)
 * [**LineageOS**](https://github.com/LineageOS)
 * [**StatixOS**](https://github.com/StatiXOS)
 * [**PixelOS**](https://github.com/PixelOS-AOSP)
 * [**PixelExperience**](https://github.com/PixelExperience)
 * [**RisingOS**](https://github.com/RisingTechOSS)
 * [**Project Kaleidoscope**](https://github.com/Project-Kaleidoscope)

 * and tons of other ROMs not mentioned above