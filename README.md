# Build<br></br>
repo init -u git://github.com/ziprom/android.git -b lineage-14.1-mtk<br></br>
repo sync<br></br>
git clone https://github.com/Shivom007/Test-Nougat-Device-Tree-Panasonic-P55-Novo.git -b cm-14.1 device/Panasonic/P55Novo<br></br>
git clone https://github.com/Shivom007/Test-Nougat-Vendor-Tree-Panasonic-P55-Novo.git -b cm-14.1 vendor/Panasonic/P55Novo<br></br>
source build/envsetup.sh<br></br>
brunch P55Novo<br></br>
Done :)
