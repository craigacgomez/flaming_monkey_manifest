Flaming Monkey Manifest
=======================

Manifest file for Flaming Monkey

- **Get the source:**
        $ mkdir FLAMING_MONKEY
        $ cd FLAMING_MONKEY
        $ repo init -u https://android.googlesource.com/platform/manifest-b android-4.3_r2.1
        $ repo sync

- **Update the source:**
        $ cd FLAMING_MONKEY
        $ repo sync

- **Building**
        $ source build/envsetup.sh
        $ lunch full_<device>-userdebug (e.g. full_manta-userdebug)
        $ make -j8 otapackage

- **Cleaning**
        $ source build/envsetup.sh
        $ make clean
