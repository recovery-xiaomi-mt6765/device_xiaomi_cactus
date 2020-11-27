# device_xiaomi_cactus
## How to build OrangeFox from official repo?
1) mkdir of && cd of
2) repo init -u repo init -u https://gitlab.com/OrangeFox/Manifest.git -b fox_9.0
3) repo sync
4) git clone https://github.com/recovery-xiaomi-mt6765/device_xiaomi_cactus -b orangefox-pie device/xiaomi/cactus
5) export ALLOW_MISSING_DEPENDENCIES=true
6) . build/envsetup.sh
7) lunch omni_cactus-eng
8) mka recoveryimage
### Out file twrp/out/target/product/cactus/recovey.img
