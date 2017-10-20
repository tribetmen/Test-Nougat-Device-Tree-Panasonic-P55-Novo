# Test-Nougat-Device-Tree-Panasonic-P55-Novo



Build

repo init -u git://github.com/LineageOS/android.git -b cm-13.0
repo sync
git clone https://github.com/Shivom007/Device-Tree-Panasonic-P55-Novo.git -b cm-14.1 device/Panasonic/P55Novo
git clone https://github.com/Shivom007/Vendor-Tree-Panasonic-P55-Novo.git -b cm-14.1 vendor/Panasonic/P55Novo
cd device/Panasonic/P55Novo/patches
source apply.sh
source build/envsetup.sh
brunch P55Novo
Done :)
