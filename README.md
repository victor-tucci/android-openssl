# android-openssl

Android NDK openssl build script for original repository(https://www.openssl.org/)

modified version of setenv-android.sh and build script support all architectures in the android NDK

see details : http://wiki.openssl.org/index.php/Android

# Instructions
Clone this, then
```
wget https://github.com/openssl/openssl/archive/OpenSSL_1_0_2l.tar.gz
cd android-openssl
tar xfz ../OpenSSL_1_0_2l.tar.gz
./build-all-arch.sh
```
