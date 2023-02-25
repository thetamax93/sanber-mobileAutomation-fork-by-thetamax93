# sanber-mobileAutomation-fork-by-thetamax93

Script ini adalah fork dari sanber-mobileAutomation by alvintrianto
https://github.com/alvintrianto/sanber-mobileAutomation

Script specs yang digunakan untuk Tugas Akhir Mobile Automation adalah dietmeal.automation.js
Dengan apk Diet_meal.apk

Prasyarat:

1. Bikin Folder di desktop: C:\Users\Desktop\Workdocs\TOOL QA\Abbtools\android-sdk-windows
2. Copas isian android sdk dari android studio dan java JRE ke folder android-sdk-windows diatas:
    C:\Users\Username\AppData\Local\Android\Sdk > android
    C:\Program Files\Java\jre1.8.0_231
   Jika belum ada SDK/JRE silahkan download java dan android studio terbaru terlebih dahulu
3. Jangan run appium dan appium inspector, karena appium akan jalan sendiri dari command 'npm run wdio'

Script ini sudah dimodifikasi sedemikian rupa sehingga user hanya perlu run:

```
  npm run wdio
```

----------------------------------------------------

How to Start

Install 
1. Node JS
2. Java SDK & JAVA_HOME
3. Android Studio & ANDROID_HOME
4. Appium Desktop
5. Install package.json with command

```
  npm install
```

How to run
1. Connect to your device android or IOS
2. Setup desired capabilities in file wdio.conf.js
3. Run test
```
  npm run wdio
```
