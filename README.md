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

1. Unpack the ```.tar.gz``` file you downloaded to an appropriate location for your applications, such as within ```/usr/local/``` for your user profile or ```/opt/``` for shared users.
For a 64-bit version of Linux, first install the required libraries for 64-bit machines.

2. To launch Android Studio, open a terminal, navigate to the ```android-studio/bin/``` directory, and execute ```studio.sh```.
3. Select whether you want to import previous Android Studio settings, then click **OK**.
4. Complete the Android Studio Setup Wizard, which includes downloading the Android SDK components that are required for development.

หากต้องการติดตั้ง Android Studio บน Linux ให้ทำตามขั้นตอนต่อไปนี้

1. แตกไฟล์ ```.tar.gz``` ที่คุณดาวน์โหลดไปยัง ตำแหน่งที่เหมาะสมสำหรับแอปพลิเคชันของคุณ เช่น ภายใน ```/usr/local/```สำหรับโปรไฟล์ผู้ใช้ของคุณหรือ ```/opt/``` สำหรับผู้ใช้ที่แชร์
สำหรับ Linux เวอร์ชัน 64 บิต ก่อนอื่นให้ติดตั้ง ไลบรารีที่จำเป็นสำหรับเครื่อง 64 บิต

2. หากต้องการเปิดใช้งาน Android Studio ให้เปิดเทอร์มินัล ไปที่ไดเรกทอรี ```android-studio/bin/``` และเรียกใช้ ```studio.sh```
3. เลือกว่าต้องการนำเข้าการตั้งค่า Android Studio ก่อนหน้าหรือไม่ แล้วคลิก **ตกลง**
4. ทำตามวิซาร์ดการตั้งค่าของ Android Studio ซึ่งรวมถึงการดาวน์โหลด คอมโพเนนต์ Android SDK ที่จำเป็นสำหรับการพัฒนา

**ไลบรารีที่จำเป็นสำหรับเครื่อง 64 บิต** 
หากคุณใช้ Ubuntu เวอร์ชัน 64 บิต คุณจำเป็นต้องติดตั้ง Ubuntu แบบ 32 บิต ที่มีคําสั่งต่อไปนี้
```
sudo apt-get install libc6:i386 libncurses5:i386 libstdc++6:i386 lib32z1 libbz2-1.0:i386
```

