# android_vendor_xiaomi_munch-firmware

Firmware images for Poco F4 (munch), to include in custom ROM builds.

**Current version**: fw_munch_miui_MUNCHGlobal_V14.0.2.0.TLMMIXM_e6ea0e8ca7_13.0

### How to use?

1. Clone this repo to `vendor/xiaomi/munch-firmware`

2. Include it from `BoardConfig.mk` in device tree:

```
# Firmware
include vendor/xiaomi/munch-firmware/BoardConfigVendor.mk
```