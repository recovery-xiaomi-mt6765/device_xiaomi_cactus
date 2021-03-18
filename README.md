# device_xiaomi_cactus
## How to build TWRP from official repo?
1) mkdir shrp && cd shrp
2) https://shrp.github.io/#/guide
3) export ALLOW_MISSING_DEPENDENCIES=true
4) . build/envsetup.sh
5) lunch omni_cactus-eng
6) mka recoveryimage
### Out file shrp/out/target/product/cactus/recovery.img
