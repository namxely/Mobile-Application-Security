# Resources for Mobile Application Testing

> 🌐 **Languages:** **English** | [Tiếng Việt](README.vi.md)

Curated collection of mobile application security testing guides, vulnerable labs, tools, and cheatsheets for Android and iOS penetration testing.

<img src="https://th.bing.com/th?id=OIP.xWR1nJNsf9n31VJFkk4A5wHaHa&w=250&h=250&c=8&rs=1&qlt=90&o=6&pid=3.1&rm=2" width="150px"> <img src="https://th.bing.com/th/id/OIP.X1UEJtsTvV8kqfrdosWfdAHaHY?w=173&h=180&c=7&r=0&o=5&pid=1.7" width="145px">

## Table of Contents

- [Essential Mobile Pentesting Tools](#essential-mobile-pentesting-tools)
- [Local Cheatsheets & Checklists](#local-cheatsheets--checklists)
- [Android](#android)
  - [Android Blogs & Guides](#android-blogs--guides)
  - [Android Labs](#android-labs)
  - [Android Tools & Misc](#android-tools--misc)
- [iOS](#ios)
  - [iOS Blogs, Papers & Guides](#ios-blogs-papers--guides)
  - [iOS Labs](#ios-labs)
- [Credits & References](#credits--references)

## Essential Mobile Pentesting Tools

* [OWASP MAS (MASTG & MASVS)](https://mas.owasp.org/) - Official OWASP Mobile Application Security standard and testing guide
* [MobSF (Mobile Security Framework)](https://github.com/MobSF/Mobile-Security-Framework-MobSF) - Automated all-in-one static & dynamic mobile app security analysis framework (Android/iOS)
* [Frida](https://github.com/frida/frida) - Dynamic instrumentation toolkit for hooking functions, bypassing SSL pinning & root/jailbreak detection
* [Objection](https://github.com/sensepost/objection) - Runtime mobile exploration toolkit powered by Frida (no root/jailbreak required)
* [JADX](https://github.com/skylot/jadx) - Dex-to-Java decompiler for analyzing Android APK source code
* [HTTP Toolkit Frida Unpinning](https://github.com/httptoolkit/frida-interception-and-unpinning) - Actively maintained Frida scripts for Android HTTPS interception and certificate unpinning
* [apkleaks](https://github.com/dwisiswant0/apkleaks) - Scan APK files for hardcoded endpoints, URIs, and secrets

## Local Cheatsheets & Checklists

* [iOS Pentesting Cheatsheet](./i0s-cheatsheet.md)
* [Mobile Penetration Testing Checklist (MPTC)](./MPTC.md)
* [Mobile App Security Checklist v1.2 (.xlsx)](./Mobile_App_Security_Checklist-English_1.2.xlsx)
* [Mobile App Checklist 2017 (.xlsx)](./MobileApp_Checklist_2017.xlsx)

## Android

### Android Blogs & Guides

* [Android Pentesting Lab Setup – Android Studio](https://pentestguy.com/android-pentesting-lab-setup-android-studio/)
* [iOS SSL Pinning Bypass using Frida](https://pentestguy.com/ios-ssl-pinning-bypass-using-frida/)
* [SSL Pinning Bypass Using Frida and Objection](https://pentestguy.com/ssl-pinning-bypass-using-frida-and-objection/)
* [How to Jailbreak iOS 15 & Setup for Pentesting](https://pentestguy.com/how-to-jailbreak-ios-15-setup-for-pentesting/)
* [Secure an Android Device](https://source.android.com/security)
* [Android Security Tips](https://developer.android.com/training/articles/security-tips)
* [OWASP Mobile Security Testing Guide (MASTG)](https://mas.owasp.org/MASTG/)
* [OWASP Mobile Security Testing Guide (Legacy Wiki)](https://www.owasp.org/index.php/OWASP_Mobile_Security_Testing_Guide)
* [Security Testing for Android Cross Platform Application](https://3xpl01tc0d3r.blogspot.com/2019/09/security-testing-for-android-app-part1.html)
* [Dive deep into Android Application Security](https://blog.0daylabs.com/2019/09/18/deep-dive-into-Android-security/)
* [Pentesting Android Apps Using Frida](https://www.notsosecure.com/pentesting-android-apps-using-frida/)
* [Mobile Application Penetration Testing Cheat Sheet](https://github.com/sh4hin/MobileApp-Pentest-Cheatsheet)
* [Android Applications Reversing 101](https://www.evilsocket.net/2017/04/27/Android-Applications-Reversing-101/#.WQND0G3TTOM.reddit)
* [Android WebView Vulnerabilities](https://pentestlab.blog/2017/02/12/android-webview-vulnerabilities/)
* [OWASP Mobile Top 10](https://www.owasp.org/index.php/OWASP_Mobile_Top_10)
* [Practical Android Phone Forensics](https://resources.infosecinstitute.com/practical-android-phone-forensics/)
* [Mobile Reverse Engineering Unleashed](http://www.vantagepoint.sg/blog/83-mobile-reverse-engineering-unleashed)
* [quark-engine - An Obfuscation-Neglect Android Malware Scoring System](https://github.com/quark-engine/quark-engine)
* [Application and Network Usage in Android](https://www.sans.org/cyber-security-summit/archives/file/summit-archive-1528491463.pdf)
* [GEOST BOTNET - the discovery story of a new Android banking trojan](http://public.avast.com/research/VB2019-Garcia-etal.pdf)
* [Mobile Pentesting With Frida](https://drive.google.com/file/d/1JccmMLi6YTnyRrp_rk6vzKrUX3oXK_Yw/view)
* [Magisk Systemless Root - Detection and Remediation](https://www.mobileiron.com/en/blog/magisk-android-rooting)
* [AndrODet: An adaptive Android obfuscation detector](https://arxiv.org/pdf/1910.06192.pdf)
* [Hands On Mobile API Security](https://hackernoon.com/hands-on-mobile-api-security-get-rid-of-client-secrets-a79f111b6844)
* [Zero to Hero - Mobile Application Testing - Android Platform](https://nileshsapariya.blogspot.com/2016/11/zero-to-hero-mobile-application-testing.html)
* [How to use FRIDA to bruteforce Secure Startup with FDE-encryption on a Samsung G935F running Android 8](https://github.com/Magpol/fridafde)
* [Android Malware Adventures](https://docs.google.com/presentation/d/1pYB522E71hXrp4m3fL3E3fnAaOIboJKqpbyE5gSsOes/edit)

### Android Labs

* [DIVA (Damn Insecure and Vulnerable App)](https://github.com/payatu/diva-android)
* [SecurityShepherd](https://github.com/OWASP/SecurityShepherd)
* [Damn Vulnerable Hybrid Mobile App (DVHMA)](https://github.com/logicalhacking/DVHMA)
* [OWASP-mstg Crackmes](https://github.com/OWASP/owasp-mstg/tree/master/Crackmes)
* [VulnerableAndroidAppOracle](https://github.com/dan7800/VulnerableAndroidAppOracle)
* [Android InsecureBankv2](https://github.com/dineshshetty/Android-InsecureBankv2)
* [Purposefully Insecure and Vulnerable Android Application (PIIVA)](https://github.com/htbridge/pivaa)
* [Sieve app](https://github.com/mwrlabs/drozer/releases/download/2.3.4/sieve.apk)
* [DodoVulnerableBank](https://github.com/CSPF-Founder/DodoVulnerableBank)
* [Digitalbank](https://github.com/CyberScions/Digitalbank)
* [OWASP GoatDroid](https://github.com/jackMannino/OWASP-GoatDroid-Project)
* [AppKnox Vulnerable Application](https://github.com/appknox/vulnerable-application)
* [Vulnerable Android Application](https://github.com/Lance0312/VulnApp)
* [Hackme Bank](http://www.mcafee.com/us/downloads/free-tools/hacme-bank-android.aspx)
* [Android Security Labs](https://github.com/SecurityCompass/AndroidLabs)
* [Android-security](https://github.com/rafaeltoledo/android-security)
* [VulnDroid](https://github.com/shahenshah99/VulnDroid)

### Android Tools & Misc

* [Android-Reports-and-Resources](https://github.com/B3nac/Android-Reports-and-Resources/blob/master/README.md)
* [android-security-awesome](https://github.com/ashishb/android-security-awesome)
* [android-device-check - scripts to check Android device security configuration](https://github.com/nelenkov/android-device-check)
* [apk-mitm - CLI to prepare Android APK files for HTTPS inspection](https://github.com/shroudedcode/apk-mitm)
* [Andriller - software utility with a collection of forensic tools for smartphones](https://github.com/den4uk/andriller)
* [Dexofuzzy: Android malware similarity clustering method](https://www.virusbulletin.com/virusbulletin/2019/11/dexofuzzy-android-malware-similarity-clustering-method-using-opcode-sequence/)
* [Chasing the Joker](https://docs.google.com/presentation/d/1sFGAERaNRuEORaH06MmZKeFRqpJo1ol1xFieUa1X_OA/edit#slide=id.p1)
* [Side Channel Attacks in 4G and 5G Cellular Networks - Slides](https://i.blackhat.com/eu-19/Thursday/eu-19-Hussain-Side-Channel-Attacks-In-4G-And-5G-Cellular-Networks.pdf)
* [Shodan.io-mobile-app for Android](https://github.com/PaulSec/Shodan.io-mobile-app)

## iOS

### iOS Blogs, Papers & Guides

* [iOS Security](https://www.cse.wustl.edu/~jain/cse571-14/ftp/ios_security/index.html)
* [IOS Application security – Setting up a mobile pentesting platform](https://resources.infosecinstitute.com/ios-application-security-part-1-setting-up-a-mobile-pentesting-platform/#gref)
* [Collection of the most common vulnerabilities found in iOS applications](https://github.com/felixgr/secure-ios-app-dev)
* [IOS_Application_Security_Testing_Cheat_Sheet](https://www.owasp.org/index.php/IOS_Application_Security_Testing_Cheat_Sheet)
* [OWASP iOS Testing Guide (MASTG)](https://mas.owasp.org/MASTG/)
* [iOS Application Injection](https://arjunbrar.com/post/ios-application-injection)
* [Low-Hanging Apples: Hunting Credentials and Secrets in iOS Apps](https://spaceraccoon.dev/low-hanging-apples-hunting-credentials-and-secrets-in-ios-apps)
* [Checkra1n Era - series](https://blog.digital-forensics.it/)
* [BFU Extraction: Forensic Analysis of Locked and Disabled iPhones](https://blog.elcomsoft.com/2019/12/bfu-extraction-forensic-analysis-of-locked-and-disabled-iphones/)
* [HowTo-decrypt-Signal.sqlite-for-IOS](https://github.com/Magpol/HowTo-decrypt-Signal.sqlite-for-IOS)
* [Can I Jailbreak?](https://canijailbreak.com/)
* [How to Extract Screen Time Passcodes and Voice Memos from iCloud](https://blog.elcomsoft.com/2019/10/how-to-extract-screen-time-passcodes-and-voice-memos-from-icloud/)
* [Reverse Engineering Swift Apps](https://github.com/iOS-Reverse-Engineering-Dev/Swift-Apps-Reverse-Engineering/blob/master/Reverse%20Engineering%20Swift%20Applications.pdf)
* [Mettle your iOS with FRIDA](https://sensepost.com/blog/2019/mettle-your-ios-with-frida/)
* [A run-time approach for pentesting iOS applications](https://blog.securelayer7.net/a-run-time-approach-for-pen-testing-ios-applications-part-ii-objection-in-action/)
* [iOS Internals vol 2](http://newosxbook.com/bonus/iBoot.pdf)
* [A Deep Dive into iOS Code Signing](https://blog.umangis.me/a-deep-dive-into-ios-code-signing/)
* [AirDoS: remotely render any nearby iPhone or iPad unusable](https://kishanbagaria.com/airdos/)
* [How to access and traverse a checkra1n jailbroken iPhone filesystem using SSH](https://aboutdfir.com/jailbreaking-checkra1n-configuration/)

### iOS Labs

* [OWASP iGoat](https://www.owasp.org/index.php/OWASP_iGoat_Tool_Project)
* [Damn Vulnerable iOS App (DVIA) v2](https://github.com/prateek147/DVIA-v2)
* [Damn Vulnerable iOS App (DVIA) v1](https://github.com/prateek147/DVIA)
* [iPhoneLabs](https://github.com/SecurityCompass/iPhoneLabs)

## Credits & References

- **Original Repository**: [0xSojalSec/Mobile-Application-Security](https://github.com/0xSojalSec/Mobile-Application-Security)
- **Original Author**: [@0xSojalSec](https://github.com/0xSojalSec)
- **Curated & Updated**: Organized Table of Contents, deduplicated entries, updated OWASP MAS/MASTG references, removed unreachable/dead links, added essential mobile pentesting tools (OWASP MAS, MobSF, Frida, Objection, JADX, HTTP Toolkit Frida Unpinning, apkleaks), and added Vietnamese translation ([README.vi.md](README.vi.md)).
- **License**: No upstream `LICENSE` file was included in the original repository; attribution and original links are preserved above.
