# xdroidOSS | Pixel 2 & Pixel 3

### Sync source ###
```bash
repo init -u https://github.com/xdroidOSS-Pixel/manifest -b thirteen
```
```bash
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

### Build source ###
```bash
. build/envsetup.sh
lunch xdroid_$devicecodename-userdebug
make xd -j$(nproc --all)
```
### Credits ###
 * [**xDroidOSS**](https://github.com/xdroid-oss)
