# HoRaApp

Install the following packages: curl, git, unzip, xz-utils, zip, libglu1-mesa

```
sudo apt-get update -y && sudo apt-get upgrade -y;

sudo apt-get install -y curl git unzip xz-utils zip libglu1-mesa
```

Install the following prerequisite packages for Android Studio

``` 
sudo apt-get install \
    libc6:amd64 libstdc++6:amd64 \
    libbz2-1.0:amd64 libncurses5:amd64
```
Install [Android Studio](https://developer.android.com/studio)

To install Android Studio on Linux, follow these steps:

1. Unpack the .tar.gz file you downloaded to an appropriate location for your applications, such as within ```/usr/local/``` for your user profile or ```/opt/``` for shared users.
For a 64-bit version of Linux, first install the required libraries for 64-bit machines.

2. To launch Android Studio, open a terminal, navigate to the android-studio/bin/ directory, and execute studio.sh.
3. Select whether you want to import previous Android Studio settings, then click OK.
4. Complete the Android Studio Setup Wizard, which includes downloading the Android SDK components that are required for development.
