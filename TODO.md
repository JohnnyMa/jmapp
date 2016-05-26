TODO:

http://gmirror.org/#android-sdk-tools-only

http://www.cnblogs.com/sink_cup/archive/2011/10/31/ubuntu_x64_android_sdk_java.html


for ubuntu 32bit:
https://dl-ssl.google.com/android/repository/platform-tools_r23.0.1-linux.zip



echo 'export ANDROID_HOME="'$HOME'/workspace/android-sdk-linux"' >> ~/.bashrc

echo 'export PATH="$PATH:$ANDROID_HOME/tools:$ANDROID_HOME/platform-tools"' >> ~/.bashrc

echo 'export JAVA_CMD="/usr/lib/jvm/java-7-openjdk-amd64/bin/java"' >> ~/.bashrc
