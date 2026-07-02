\---Changelogs---



**02-07-2026:**



* Fixed OOS-CAM (Introduced separate builds for oos-cam)
* Fixed system updater not built with the rom due to weird logic in source (from this build, both local and OTA update should work fine)
* Fixed few sepolicy violation
* Fixed NPE crash in oplus-fwk (oos-cam)
* Rebased device specific source to latest
* Upstream updates from PixelOS team



**23-06-26:**



* HOTFIX: Fixed broken recovery due to change in kernel (thanks @madara273)
* Switch to Sakura Kernel by @madara273
* Updated KernelSU Next to v3.2.0 with SUSFS integrated
* Switched to Pixel AIDL Thermal HAL v3

&#x20;  → Shows warning when skin temp reaches 52 °C

&#x20;  → Automatically drops FPS to 60 Hz on thermal throttle

* Removed OOS Camera (temporary)
* Aperture (LoS Camera) can now record up to 4K60 and 120 FPS (Thanks to @thuryn - Unofficial EvoX Dev!)



**Initial Public Build:**



* switched to Sakura kernel
* upstream PixelOS changes
* fixed some selinux denials
* adjusted status bar height
* raise to wake fixed
* ambient display/AOD brightness fixed and new logic applied
* low mic issue fix applied(thanks @SuperJammy)
* OOS cam included(thanks @Flashedfiber for help)
* Switched to userdebug signed build
* Fixed stock pixel ringtone issue
* Switched to libpermgr
* Fixed various selinux denials
* KSU Next 3.2.0 with susfs
* New alert slider animation(credits (https://github.com/lemonadep-crd/pos\_hardware\_oplus/commit/688e167a3d2fcefc371f11d07fe9958e05371b87))
* Disabled FRP lock
* Fixed mic issue on voip like WhatsApp
* Implemented torchlight intensity control
* and many more
