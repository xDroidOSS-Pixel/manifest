![banner](https://raw.githubusercontent.com/xdroidOSS-Pixel/.github/55654e4a1b88977f60e2116d7cbeed17e87f450b/banner.png)

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

![footer](https://github.com/xdroidOSS-Pixel/.github/raw/main/footer.png)
