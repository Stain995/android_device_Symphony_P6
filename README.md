# android_device_Symphony_P6

- **AICP 12.1**  For Symphony P6

Basic   | Spec Sheet
-------:|:-------------------------
CPU     | mt6582 1.3GHz 
Kernel  | 3.10.54
GPU     | Mali-400MP
Memory  | 1GB/2GB RAM
Shipped Android Version | 5.0
Storage | 8GB/16GB
Display | 5.3" 720 x 1280 px
Camera  | 13mp Rear, 5mp front




# Build Commands :-

  * repo init -u https://github.com/Stain995/platform_manifest.git -b n7.1
  * repo sync -f --force-sync --no-clone-bundle
  * source build/envsetup.sh
  * lunch aicp_P6-userdebug
  * brunch P6

#[ Note: all device and vendor tree is included in platform manifest so no need to clone it again and again! ]

# Credits/Thanks to:-

 * tribetmen
 * mehanic6
 * manjotsidhu
 * StainYY
 * SamSanuch
 * a7raj
