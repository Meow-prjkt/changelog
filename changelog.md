# Changelog 12/03/2026
- munch: Import vibrator effects
- CameraProvider: set saner values
- Migrate libcameraservice ext to soong_config_set
- camera: Add enabled bool for finished workarounds
- camera: Implement setTorchModeExt
- camera: Implement supportsSetTorchModeExt
- Implement torch light control

# Changelog 07/03/2026
- remove default Pocket Mode from source
- Set BOARD_USES_ADRENO to true
- Fix voip incall mic
- dolby: Update dolby blobs from pdx237
- parts: Move to SwitchPreferenceCompat for Bypass Charging
- libinit: Drop fingerprint override
- fix auto brightness issues
- rootdir: Remove IO read_ahead_kb tune
- parts: Implement Pocket Detection service
- Enable Remote Key Provisioning (RKPD) support

# Changelog 25/02/2026
- Allow mi_thermald read/write access to HBM sysfs
- Properly disable phantom process killing
- init: Give proper permissions for /dev/diag
- props: enable_camera_smooth
- Fix touch thermal profile cant turned on

# Changelog 22/02/2026
- Uprev vendor.qti.hardware.bluetooth_audio to 2.1
- Allow toolbox to manage resourcecache_data_file
- Import 64 bit vendor.qti.hardware.bluetooth_audio@2.1-impl.so
- Enable QCRIL radio power saving
- Add Gryphline games to unity boosting
- Disable GPU protected composition
- Limit dex2oat cpu utilization
- Disable WiFi Multi-STA

# Changelog 14/02/2026
- Update some Prebuilts from HyperOS 1.0.5.0 Mi
- Disable MTE on system_server and apps
- Override kernel BPF version
- wifi: Add parameters for Hotspot 2.0
- Allow devicesettings_app to access LiveDisplay tuneables
- Label expressive design and skia renderthread properties
- Allow vendor_init to tune kernel scheduler interfaces
- Label libgpudataproducer.so to address denial

# Changelog 10/02/2026
- Fixup Add more reserve space for vanilla builds (can flash Full GApps packages)
- Set ro.netflix.bsp_rev
- Improve surfaceflinger Service 

# Changelog 09/02/2026
- Set frame rate multiple threshold to 120
- Reduce blur radius
- HBM: Change default threshold to 7000
- Enable AOSP surfaceflinger
- Enable ScrollOptimizer
- Build libusbhost to vendor
- Reduce aod brightness value
- Add android.hardware.drm@1.4 and libcrypto_shim
- Build libhidltransport and libhwbinder
- Build Graphics Allocator HAL service and implement it
- Build gralloc.qcom
- Explicitly disable SF layer cache
- Set systemui/server dex profiles to performance
- Boost gpu on LAUNCH
- Bump little cluster boost upon INTERACTION
- Bump kernel clang to r563880
- Force device to treat 170M as sRGB in SF
- config.fs: Add new AID
- config.fs: Adding GIDs for SSGTZD process
- config.fs: Define new AID for qcc-trd
- Update sepolicy properties
- Prepend soong ns to lib_driver_cmd_qcwcn
- RefreshRateTile: Seperate min & max refresh rate

# Changelog 06/02/2026
- Update a650_sqe from linux-firmware
- Sync/update blobs from pipa OS2.0.10.0.UMZCNXM
- Update Graphics blobs from ishtar OS2.0.105.0.VMAMIXM
- Fix imsrcsd/init_thermal-engine rc
- Configure custom thermal
- Set thermal data path for xiaomi mi_thermald

# Changelog 04/02/2026
- Use 4G instead of LTE icon for save statusbar space
- Add a property to enable prefetching video
- allow the linux kernel to access /vendor/firmware

# Changelog 29/01/2026
- Enable doze auto brightness on AOD
- Enable WFD property "persist.debug.wfd.enable".
- Disable HWC for VDS except WFD
- Allow HWC path for WFD
- alioth: overlay: Configure display cutout
- Update WFD system blobs to dada OS3.0.3.0.WOCMIXM

# Changelog 26/01/2026
- Defer applying divider
- remove default Pocket Mode from source
- Add XML files for dEQP feature flags
- Add OpenGL ES and update Vulkan dEQP feature flags
- Add camera.concurrent into supported feature
- Fix HBM Issue brightness
- Add Battery Friendly Pocket Mode
- Dropped Devicewebcam
- Implement usb fast charge mode

# Changelog 19/01/2026
- alioth: Update blobs from OS1.0.6.0.TKHCNXM
- Add overlay to improve signal reception
- Configure turbo charging
- Build DeviceAsWebcam service
- Enable Volte for Argentine networks
- Enable HDR10 GPU target property
- Add RmNet Data props
- Shim WFD with libinput_shim
- opt-out of dialer's incoming call proximity sensor check
- Explicitly disable "Enable GL comp backpressure"
- Enable apk fs-verity
- Mlock limited to 64 KB
- Allow hal_wifi_default to manage firmware tombstones
- Remove unnecessary wcnss-service start
- Fix hal_power_default denial
- Import pinned service libs from AOSPA
- Update some patch on Lunaris Dolby
---

# Changelog 15/01/2026
- Address more XiaomiParts denials
- Make ramdisk compressed by lz4
- Use lower streaming bandwidth for USB 2.0 for UVC
- Opt out of VIDEO_ENCODE flag for DeviceAsWebcam
- Setup DeviceAsWebcam
- Set config_use16BitTaskSnapshotPixelFormat to true
- Enable new network selection UI
- Drop force triple frame buffers
- Update Lunaris Dolby

# QPR 2 Changes
- Patch some blobs to depend on libtinyxml2-v34.so
- Add com.android.bluetooth context to seapp_contexts
---
