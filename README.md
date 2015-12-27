Small adjustments to make build possible on OSX. Verified on OSX 10.11.1.

[FFmpeg-Android](http://hiteshsondhi88.github.io/ffmpeg-android/) [![Android Arsenal](https://img.shields.io/badge/Android%20Arsenal-FFmpeg--Android-brightgreen.svg?style=flat)](https://android-arsenal.com/details/1/925)
==============

* FFmpeg for Android compiled with x264, libass, fontconfig, freetype and fribidi
* Supports Android L
* [FFmpeg Android Library](https://github.com/hiteshsondhi88/ffmpeg-android-java)

Supported Architecture
----
* armv7
* armv7-neon
* x86

Instructions
----
* Set environment variable
  1. export ANDROID_NDK={Android NDK Base Path}
* Run following commands to compile ffmpeg
  1. Somehow install (Most are available in Homebrew) :
    - build-essential 
    - git 
    - autoconf 
    - libtool 
    - pkg-config 
    - gperf 
    - gettext 
    - yasm
  2. ./init_update_libs.sh
  3. ./android_build.sh
* To update submodules and libraries you can use ./init_update_libs.sh command
* Find the executable binary in build directory.
* If you want to use FONTCONFIG then you need to specify your custom fontconfig config file (e.g - "FONTCONFIG_FILE=/sdcard/fonts.conf ./ffmpeg --version", where /sdcard/fonts.conf is location of your FONTCONFIG configuration file).
* You can also download [prebuilt-binaries.zip](https://github.com/hiteshsondhi88/ffmpeg-android/releases/download/v0.3.3/prebuilt-binaries.zip) [prebuilt-binaries.tar.gz](https://github.com/hiteshsondhi88/ffmpeg-android/releases/download/v0.3.3/prebuilt-binaries.tar.gz) here.

License
----
  check files LICENSE.GPLv3 and LICENSE

HIRE US
--------
Get in touch with us - http://www.writingminds.com


[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/hiteshsondhi88/ffmpeg-android/trend.png)](https://bitdeli.com/free "Bitdeli Badge")

