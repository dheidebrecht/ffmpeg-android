Get Android NDK from:

http://dl.google.com/android/ndk/android-ndk-r10e-linux-x86_64.bin

Extract and place in directory as indicated in the Extraction instructions: https://developer.android.com/ndk/downloads/index.html#extract

export ANDROID_NDK variable pointing to directory extracted to above.

clone https://github.com/dheidebrecht/ffmpeg-android

cd to ffmpeg-android directory

execute ./init_update_libs.sh

execute ./android_build.sh

after build finishes, copy build/armeabi-v7a-neon/bin/ffmpeg to app/src/main/res/raw/ffmpeg in unclip-android project.