<p align="center"> <img src="https://github.com/sahad-mk/FireVu/blob/master/Images/Firevu_Splash.png" height="25%" width="50%"></p>
<p align="center"><b><i> FireVu - Intentionally Vulnerable Android Application </i> </b> </p>

## FireVu

![SH.an](https://img.shields.io/badge/version-1.0-success)  ![Android](https://img.shields.io/badge/Android%209(Pie)-important)   ![Tested](https://img.shields.io/badge/Tested%20On-Mi%20A1-green) [![Linkedin](https://img.shields.io/badge/Linkedin-/Sahadmk-blue)](https://www.linkedin.com/in/sahadmk)

## Introduction
FireVu is an intentionally vulnerable Android application developed for Android open source security. The initial goal was to demonstrate the misconfigured Firebase database of mobile apps. I have added a few more vulnerabilities for learning purpose.

###### Vulnerabilities of this app:

1. Misconfigured Firebase Database.
2. Misconfigured Firebase Storage.
3. Vulnerable Exported content provider.
4. Vulnerable Exported activities.
5. Insecure data storage.
6. Insecure logging.
7. Android Backup vulnerability.
8. Application Debuggable.

For finding the Misconfigured Firebase vulnerability in FireVu,Check my ![Misconfigured Firebase Writeup](https://github.com/sahad-mk/FireVu/blob/master/Documents/Misconfigured%20Firebase%20Database.pdf)

## Prerequisites

     1. Supported Version: Android 9 (pie) device or use genymotion android 9 emulator.

     2. Supported(Tested) screen sizes :1080*1920 and 1080*2010.
 
     3. Install Open GApps and ARM translation in genymotion.

     5. App requires internet for user login (Firebase Authentication).

## Installation
     
        1. Download the FireVu.apk file.
        
        2. Open apk file and tap 'Install'.
        
        3. Enable Install Unknown apps.
        
        4. Drag and drop the FireVu.apk file into genymotion emulator.
        
        5. Disable verify apps over USB.
 
## Screenshots

1. Attack suraface of the application.

   ![Firevu attack_surface](https://github.com/sahad-mk/FireVu/blob/master/Images/attack_suraface.png)
   

2. User Registration (Enable Internet Access).

   <img src=https://github.com/sahad-mk/FireVu/blob/master/Images/register.png height="250" width="200">
   
   You can use any random email id.There is no email verification (But you can't register with an email which is already in use).
   
   
3. User Login (Enable Internet Access)

   
   <img src="https://github.com/sahad-mk/FireVu/blob/master/Images/login.png" height="250" width="200">
   
   Login with your registered account or use the default [Credentials](https://github.com/sahad-mk/FireVu/blob/master/credentials.txt).
        
        
      
