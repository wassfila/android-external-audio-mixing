# HowTo
[vendor\genivi\modules\audiorelay\README.md](vendor\genivi\modules\audiorelay\README.md)

# Test on Virtual machine
* copy repo content over AOSP rpoject

```bash
    source build/envsetup.sh
    lunch genivi_car_x86_64-userdebug
    m -j4
```

* emulater probably not supported from virtual machine

```console
    ~/work$ emulator
    emulator: WARNING: Couldn't find crash service executable /home/wass/work/prebuilts/android-emulator/linux-x86_64/emulator64-crash-service
    emulator: WARNING: system partition size adjusted to match image file (3083 MB > 800 MB)
    emulator: ERROR: x86_64 emulation currently requires hardware acceleration!
    Please ensure KVM is properly installed and usable.
    CPU acceleration status: KVM requires a CPU that supports vmx or svm
```
