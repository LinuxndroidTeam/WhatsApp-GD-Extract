# WhatsApp Google Drive Extractor
===============================

Allows WhatsApp users on Android to extract their backed up WhatsApp data
from Google Drive. Anytime, Anywhere

## Requirements 

1. [Python 3](https://www.python.org/downloads/)
 2. Android device with WhatsApp installed and the Google Drive backup
    feature enabled.
 3. Find The One-Time device's Android ID Using Adb.
 ```shell
adb shell settings get secure android_id
```
 4. Google account login credentials (username and password). App password
    when using 2-factor authentication.
 5. Must Use Windows 10, 11

 ## Youtube Video

[![Watch Video](https://img.youtube.com/vi/Hqnalf3fQms/0.jpg)](https://youtu.be/Hqnalf3fQms)
    
 ## How To Use
------------

 1. Extract `WhatsApp-GD-Extract-master.zip`.
 2. Install dependencies: 
 ```shell
python -m pip install -r requirements.txt
```
 3. Update Some dependencies:
 ```shell
pip install gpsoauth && pip install requests==2.23.0
```
 4. Paste Google Login & Android_id in `settings.cfg`.
 5. Run Command and Extract All data from Google Drive.
 ```shell
python WhatsAppGDExtract.py sync
```

## Checkout More Advanced [Hacking Courses](https://shop-linuxndroid.in/)
  

<br>
<p align="center">Love ❤️ By <a href="https://shop-linuxndroid.in">Linuxndroid</a></p>


## Follow Me on :

[![Instagram](https://img.shields.io/badge/IG-linuxndroid-yellowgreen?style=for-the-badge&logo=instagram)](https://www.instagram.com/linuxndroid)

[![Youtube](https://img.shields.io/badge/Youtube-linuxndroid-redgreen?style=for-the-badge&logo=youtube)](https://www.youtube.com/channel/UC2O1Hfg-dDCbUcau5QWGcgg)

[![Browser](https://img.shields.io/badge/Website-linuxndroid-yellowred?style=for-the-badge&logo=browser)](https://shop-linuxndroid.in)
