![Styx](https://github.com/StyxProject/manifest/raw/R/StyxBanner.png)

Styx is a simple, clean, beautiful Android based custom ROM that strives to provide a stable and fluid experience, with minimal enhancements and features to bring out the most out of your Android device.

To get started with Styx, you'll need to get
familiar with [Repo](https://source.android.com/source/using-repo.html) and [Version Control with Git](https://source.android.com/source/version-control.html).

### Build Environment.

**Initializing the manifest**
```
repo init -u https://github.com/StyxProject/manifest -b S
```

**Syncing the source**
```
repo sync -j$(nproc --all) --force-sync --no-tags --no-clone-bundle --prune --optimized-fetch
```

**Building**
```
source build/envsetup.sh
lunch styx_device-buildtype
m styx-ota
```

### Credits.
 * [**Paranoid Android**](https://github.com/AOSPA)
 * [**ProtonAOSP**](https://github.com/ProtonAOSP)
 * [**PotatoProject**](https://github.com/PotatoProject)
 * [**LineageOS**](https://github.com/LineageOS)
 * [**StormbreakerOSS**](https://github.com/StormbreakerOSS)
 * And the list never ends.
