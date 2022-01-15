# device_xiaomi_cactus
## How to build TWRP from official repo?
1) mkdir shrp && cd shrp
2) https://github.com/minimal-manifest-twrp/platform_manifest_twrp_omni
3) git clone git clone https://github.com/minimal-manifest-twrp/platform_manifest_twrp_omni -b twrp-9.0
4) export ALLOW_MISSING_DEPENDENCIES=true
5) . build/envsetup.sh
6) lunch omni_cactus-eng
7) mka recoveryimage
### Out file shrp/out/target/product/cactus/recovery.img
