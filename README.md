# Awesome Android Reverse Engineering with stars

<p align="center">
   <img width=100% src="assets/cover.gif">
 </a>
</p>

<p align="center">
 <b>A curated list of awesome Android Reverse Engineering training, resources, and tools.</b>

<div align="center">

[![Awesome](https://awesome.re/badge.svg)](https://github.com/MarketingPipeline/Awesome-Repo-Template/) ⭐ 211 | 🐛 0 | 🌐 HTML | 📅 2023-03-03
![GitHub contributors](https://img.shields.io/github/contributors/user1342/Awesome-Android-Reverse-Engineering)
![GitHub Repo stars](https://img.shields.io/github/stars/user1342/Awesome-Android-Reverse-Engineering?style=social)
![GitHub watchers](https://img.shields.io/github/watchers/user1342/Awesome-Android-Reverse-Engineering?style=social)
![GitHub last commit](https://img.shields.io/github/last-commit/user1342/Awesome-Android-Reverse-Engineering) <br>

</div>

# How to Use

Awesome-Android-Reverse-Engineering is an amazing list for people who work in taking apart Android applications, systems, or components. Simply press `ctrl + F` to search for a keyword, go through our Contents Menu, or lookout for a '☆' indicating some great and up-to-date resources.

# Contents

* [Training](#training)
  * [Courses and Material](#courses-and-material)
  * [Videos](#videos)
  * [Books](#books)
* [Tools](#tools)
  * [Static Analysis Tools](#static-analysis-tools)
  * [Dynamic Analysis Tools](#dynamic-analysis-tools)
  * [Decompilers](#decompilers)
  * [Malware Analysis](#malware-analysis)
* [Resources](#resources)
  * [Documentation](#documentation)
  * [Case Studies](#case-studies)
* [CTFs and CrackMes](#ctfs-and-crackmes)
* [Misc](#misc)
* [Obfuscation & Anti-Reversing](#obfuscation--anti-reversing)
* [Firmware & Kernel Analysis](#firmware--kernel-analysis)
* [Cloud API & Web Services Reversing](#cloud-api--web-services-reversing)

## Training

### Courses and Material

* [☆ Maddie Stone's Android Reverse Engineering Training](https://www.ragingrock.com/AndroidAppRE/) - A comprehensive online training course on Android reverse engineering by Maddie Stone.
* [Introduction to Assembly from Azeria Labs](https://azeria-labs.com/writing-arm-assembly-part-1/) - Covering everything from data types, registers, the ARM instruction set, memory instructions, and more.

### Videos

* [Kristina Balaam Android Reverse Engineering](https://www.youtube.com/@chmodxx) - A video series on reverse engineering basics and reverse engineering Android malware.
* [LaurieWired Android Reverse Engineering videos](https://www.youtube.com/@lauriewired) - A YouTube channel focusing on Android reverse engineering.
* [Using Frida To Modify Android Games | Mobile Dynamic Instrumentation](https://www.youtube.com/watch?v=BXtAujoPhQw) - Focusing on reverse engineering Android applications and on using Frida to dynamically modify Android games.

### Books

* [☆ Android Internals: A Confectioner's Cookbook](http://newandroidbook.com/) - An in-depth exploration of the inner-workings of Android.
* [Blue Fox: Arm Assembly Internals and Reverse Engineering](https://www.amazon.co.uk/dp/1119745306) - Provides a solid foundation in ARM assembly internals.
* [Android Software Internals Quick Reference](https://www.amazon.co.uk/Android-Software-Internals-Quick-Reference/dp/1484269136) - Techniques in Java and Android system internals.
* [☆ Mobile Offensive Security Pocket Guide](https://www.amazon.co.uk/Mobile-Offensive-Security-Pocket-Guide/dp/1399921959) - Key information, approaches, and tooling for mobile penetration testers.
* [Android Security Internals](https://nostarch.com/androidsecurity) - Detailed look into Android security architecture.
* [Android Malware Detection with Machine Learning](https://nostarch.com/androidmalwaredetection) - Machine learning techniques for detecting malicious apps.
* [Android Hacker's Handbook](https://www.amazon.com/Android-Hackers-Handbook-Joshua-Drake/dp/111860864X/) - A deep dive into Android exploitation and forensics.
* [Practical Reverse Engineering](https://www.amazon.com/Practical-Reverse-Engineering-Reversing-Obfuscation/dp/1118787315/) - Covers low-level reverse engineering concepts, including ARM assembly.
* [The IDA Pro Book](https://nostarch.com/idapro2.htm) - Essential for advanced IDA Pro techniques.

## Tools

### Static Analysis Tools

* [MobSF](https://github.com/MobSF/Mobile-Security-Framework-MobSF) ⭐ 21,592 | 🐛 19 | 🌐 JavaScript | 📅 2026-08-10 - Supports both static and dynamic analysis for Android app security testing.
* [QARK](https://github.com/linkedin/qark) ⭐ 3,378 | 🐛 79 | 🌐 Python | 📅 2024-01-16 - An open-source tool for automatic Android app vulnerability scanning.
* [Quark Engine](https://github.com/quark-engine/quark-engine) ⭐ 1,710 | 🐛 77 | 🌐 Python | 📅 2026-08-11 - Integrates various tools as Quark Script APIs for mobile security research.
* [AndroBugs Framework](https://github.com/AndroBugs/AndroBugs_Framework) ⚠️ Archived - Analyzes and scans Android apps for security issues.
* [Dexcalibur](https://github.com/FrenchYeti/dexcalibur) ⭐ 1,167 | 🐛 36 | 🌐 TypeScript | 📅 2026-08-11 - Automated tool for analyzing and instrumenting Android applications.
* [☆ APK Dependency Graph](https://github.com/alexzaitsev/apk-dependency-graph) ⭐ 760 | 🐛 7 | 🌐 Java | 📅 2021-05-25 - Visualizes APK class dependencies.
* [DIS{integrity}](https://github.com/user1342/DISintegrity) ⭐ 81 | 🐛 1 | 🌐 Python | 📅 2024-04-13 - Analyzes APKs for root, integrity, and tamper detection.
* [COVA](https://github.com/secure-software-engineering/COVA) ⭐ 41 | 🐛 4 | 🌐 Python | 📅 2026-03-02 - Computes path constraints based on user-defined APIs.
* [☆ imjtool](http://newandroidbook.com/tools/imjtool.html) - Firmware unpacking tool for various vendors and formats.
* [Android Studio](https://developer.android.com/studio) - Useful for analyzing decompiled apps via an IDE.
* [disarm](http://newandroidbook.com/tools/disarm.html) - Command line utility for parsing ARM-64 instructions.

#### De-Obfuscation

* [simplify](https://github.com/CalebFenton/simplify) ⭐ 4,657 | 🐛 32 | 🌐 Java | 📅 2022-04-30 - Android virtual machine and deobfuscator.
* [deoptfuscator](https://github.com/Gyoonus/deoptfuscator) ⭐ 478 | 🐛 11 | 🌐 C++ | 📅 2022-06-16 - Tool for deobfuscating apps using control-flow obfuscation.
* [☆ Obfu\[DE\]scate](https://github.com/user1342/Obfu-DE-Scate) ⭐ 198 | 🐛 1 | 🌐 Python | 📅 2024-04-13 - De-obfuscation tool that uses fuzzy comparison logic.
* [TinySmaliEmulator](https://github.com/amoulu/TinySmaliEmulator) ⭐ 104 | 🐛 0 | 🌐 Python | 📅 2017-07-12 - Minimalist smali emulator for "decrypting" obfuscated strings.

### Dynamic Analysis Tools

* [Drozer](https://github.com/WithSecureLabs/drozer) ⭐ 4,590 | 🐛 9 | 🌐 Python | 📅 2026-04-08 - Framework for Android security testing with dynamic analysis features.
* [AutoDroid](https://github.com/user1342/AutoDroid) ⭐ 165 | 🐛 0 | 🌐 Python | 📅 2024-04-14 - Mass APK gathering and analysis tool.
* [jtrace](http://newandroidbook.com/tools/jtrace.html) - Similar to strace, but for Android system calls.
* [sesearch](https://linux.die.net/man/1/sesearch) - Command line tool for querying SELinux policies.
* **Networking:**
  * [apk-mitm](https://github.com/shroudedcode/apk-mitm) ⭐ 5,079 | 🐛 83 | 🌐 TypeScript | 📅 2024-07-24 - Prepares APKs for HTTPS inspection.
  * [SSLsplit](https://github.com/droe/sslsplit) ⭐ 1,875 | 🐛 76 | 🌐 C | 📅 2025-10-27 - Intercepts and manipulates SSL/TLS encrypted traffic.
  * [☆ Burp Suite](https://portswigger.net/burp) - Commercial tool for analyzing network traffic of Android apps.
  * [Wireshark](https://www.wireshark.org/) - Open-source network protocol analyzer.
  * [MITMProxy](https://mitmproxy.org/) - Man-in-the-middle proxy for analyzing network traffic.
* **Dynamic Instrumentation:**
  * [☆ Objection](https://github.com/sensepost/objection) ⭐ 9,313 | 🐛 55 | 🌐 Python | 📅 2026-07-23 - Runtime exploration tool to bypass app security controls.
  * [RMS Runtime Mobile Security](https://github.com/m0bilesecurity/RMS-Runtime-Mobile-Security) ⭐ 3,065 | 🐛 6 | 🌐 JavaScript | 📅 2026-08-03 - Frida web interface.
  * [jnitrace](https://github.com/chame1eon/jnitrace) ⭐ 1,856 | 🐛 20 | 🌐 TypeScript | 📅 2023-07-18 - Frida-based JNI API tracer.
  * [☆ FriDump](https://github.com/Nightbringer21/fridump) ⭐ 856 | 🐛 26 | 🌐 Python | 📅 2024-08-07 - Uses Frida to dump memory of running apps.
  * [☆ Binder Trace](https://github.com/foundryzero/binder-trace) ⭐ 766 | 🐛 11 | 🌐 Python | 📅 2025-09-11 - Intercepts and parses Android Binder messages.
  * [☆ Frida](https://frida.re/) - Dynamic instrumentation toolkit for runtime manipulation.
  * **Xposed Framework** - For hooking and modifying app behavior at runtime.

### Decompilers

* [☆ JADX](https://github.com/skylot/jadx) ⭐ 50,045 | 🐛 442 | 🌐 Java | 📅 2026-08-05 - Decompiles APKs into Java source code.
* [FernFlower](https://github.com/JetBrains/intellij-community/tree/master/plugins/java-decompiler/engine) ⭐ 20,443 | 🐛 152 | 🌐 Java | 📅 2026-08-13 - Analytical decompiler for Java.
* [DEX2JAR](https://github.com/pxb1988/dex2jar) ⭐ 13,133 | 🐛 379 | 🌐 Java | 📅 2024-07-21 - Converts DEX files to JAR files.
* [Cfr](https://github.com/leibnitz27/cfr) ⭐ 2,659 | 🐛 150 | 🌐 Java | 📅 2026-06-04 - Supports decompilation of Android APK files.
* [Procyon](https://github.com/mstrobel/procyon) ⭐ 1,209 | 🐛 59 | 🌐 Java | 📅 2022-06-12 - Suite of Java decompilation tools.
* [☆ Apktool](https://ibotpeaches.github.io/Apktool/) - Popular tool for decompiling/recompiling APK files.
* [JDGui](http://java-decompiler.github.io/) - Graphical utility to view Java source from class files.
* [IDA Pro](https://hex-rays.com/ida-pro/) - Commercial disassembler and debugger.
* [☆ Ghidra](https://ghidra-sre.org/) - Free and open-source SRE framework.
* **Additional Decompilers:**
  * [Androguard](https://github.com/androguard/androguard) ⭐ 6,192 | 🐛 46 | 🌐 Python | 📅 2026-06-05 - Analyzes and reverse engineers Android apps.
  * [APK Studio](https://github.com/vaibhavpandeyvpz/apkstudio) ⭐ 4,603 | 🐛 3 | 🌐 C++ | 📅 2026-01-05 - Qt-based IDE for reverse-engineering APKs.
  * [show-java](https://github.com/niranjan94/show-java) ⭐ 789 | 🐛 53 | 🌐 Kotlin | 📅 2023-01-04 - APK, JAR & Dex decompiler.
  * [apk2gold](https://github.com/lxdvs/apk2gold) ⭐ 699 | 🐛 19 | 🌐 Shell | 📅 2024-03-05 - Decompiles Android apps to Java (note: may be outdated).
  * [AndroidProjectCreator](https://github.com/ThisIsLibra/AndroidProjectCreator) ⭐ 392 | 🐛 8 | 🌐 Java | 📅 2023-09-18 - Converts APKs to Android Studio projects.
  * JEB Decompiler - Commercial decompiler for Android apps.
  * [Radare2](https://rada.re/n/) - Reverse engineering framework with disassembly and debugging.
  * [☆ APKLab](https://marketplace.visualstudio.com/items?itemName=Surendrajat.apklab) - VS Code extension integrating multiple tools.

### Malware Analysis

* [androwarn](https://github.com/maaaaz/androwarn) ⭐ 532 | 🐛 22 | 🌐 HTML | 📅 2020-01-21 - Static code analyzer for malicious Android applications.
* [DroidDetective](https://github.com/user1342/DroidDetective) ⭐ 142 | 🐛 0 | 🌐 Python | 📅 2024-04-14 - Machine learning malware analysis for Android apps.
* [Cuckoo Droid](https://github.com/idanr1986/cuckoodroid-2.0) ⭐ 115 | 🐛 7 | 🌐 Python | 📅 2017-08-07 - Automated Android malware analysis with Cuckoo Sandbox.

## Resources

### Documentation

* [Android Security Documentation](https://source.android.com/docs/security) - Official Google documentation on Android security.
* [Android Reverse Engineering Challenges](https://github.com/apsdehal/awesome-ctf#reverse-engineering) ⭐ 11,750 | 🐛 64 | 🌐 JavaScript | 📅 2024-07-22 - Curated list of reverse engineering challenges and CTFs.
* [AndroidXref](http://androidxref.com/) - Open code search for Android source.
* [APKMirror](https://www.apkmirror.com/) - Repository of APKs from the Play Store and user uploads.
* [APKPure](https://m.apkpure.com/) - Repository of APKs for testing and research.

### Case Studies

* [A Reverse Engineer’s Post-mortem Of The Houseparty Video Chat App](https://www.jamesstevenson.me/a-reverse-engineers-post-mortem-of-the-houseparty-video-chat-app/)
* [SharkBot: a “new” generation Android banking Trojan being distributed on Google Play Store](https://research.nccgroup.com/2022/03/03/sharkbot-a-new-generation-android-banking-trojan-being-distributed-on-google-play-store/)
* [In-the-Wild Series: Android Exploits](https://googleprojectzero.blogspot.com/2021/01/in-wild-series-android-exploits.html)

## CTFs and CrackMes

* [☆ UnCrackable Mobile Apps](https://github.com/OWASP/owasp-mastg/tree/master/Crackmes) ⭐ 13,109 | 🐛 227 | 🌐 Python | 📅 2026-08-03 - OWASP Android app CrackMes.
* [KGB Messenger](https://github.com/tlamb96/kgb_messenger) ⭐ 120 | 🐛 0 | 🌐 Java | 📅 2019-07-04 - CTF challenge for learning Android reverse engineering.
* [CyberTruckChallenge19](https://github.com/nowsecure/cybertruckchallenge19) ⚠️ Archived - Security workshop material from CyberTruck Challenge 2019.
* [Flare-On Challenge](https://www.fireeye.com/services/flare-on.html) - High-level reverse engineering CTF with Android challenges.
* [OverTheWire Narnia](http://overthewire.org/wargames/narnia/) - Not Android-specific but excellent for binary exploitation practice.

## Misc

* [uber-apk-signer](https://github.com/patrickfav/uber-apk-signer) ⭐ 2,706 | 🐛 11 | 🌐 Java | 📅 2023-10-30 - CLI tool for signing and zip aligning APKs.
* [LADB](https://github.com/tytydraco/LADB) ⭐ 2,374 | 🐛 53 | 🌐 Kotlin | 📅 2026-07-26 - Local ADB shell for Android.
* [Broken Droid Factory](https://github.com/user1342/Broken-Droid-Factory) ⭐ 50 | 🐛 0 | 🌐 Python | 📅 2024-04-14 - Generates pseudo-random vulnerable Android apps for training.
* [RUNIC tamper detection demo](https://github.com/user1342/RUNIC) ⭐ 17 | 🐛 0 | 🌐 Java | 📅 2024-04-13 - Demo for understanding Android tamper detection and integrity systems.

## Obfuscation & Anti-Reversing

* **Obfuscation Tools:**
  * [ProGuard](https://www.guardsquare.com/manual/configuration/usage) - Code shrinker, optimizer, and obfuscator.
  * [R8](https://developer.android.com/studio/build/shrink-code) - Google’s code shrinker and obfuscator.
  * [DexGuard](https://www.guardsquare.com/dexguard) - Commercial tool for advanced app obfuscation.
* **Anti-Reversing Techniques:**
  * [Android Tamper Detection Framework (ATDF)](https://github.com/Fuzion24/AndroidTamperDetection) - Implements tamper detection.
  * [Paranoid](https://github.com/sundaysec/Paranoid) - Detects root and tampering.
  * [libhooker](https://github.com/hluwa/libhooker) - Detects hooking frameworks like Frida and Xposed.

## Firmware & Kernel Analysis

* [Binwalk](https://github.com/ReFirmLabs/binwalk) ⭐ 14,223 | 🐛 91 | 🌐 Rust | 📅 2026-08-11 - Analyze, extract, and reverse engineer firmware images.
* [FirmWire](https://github.com/FirmWire/FirmWire) ⭐ 874 | 🐛 17 | 🌐 Python | 📅 2026-07-11 - Dynamic analysis platform for baseband firmware.
* [AFLSmart](https://github.com/aflsmart/aflsmart) ⭐ 521 | 🐛 7 | 🌐 C | 📅 2022-01-18 - Fuzzer optimized for firmware image analysis.
* [Android Kernel Exploits](https://github.com/saelo/android_kernel_exploitation) - Collection of kernel vulnerabilities and exploit techniques.

## Contributing

Your contributions are always welcome! Please read the contribution guidelines first. We follow the Contributor Covenant Code of Conduct, so please review and adhere to it when contributing.

## Licence

![GitHub](https://img.shields.io/github/license/user1342/Awesome-Android-Reverse-Engineering)\
This project is licensed under the MIT License - see the LICENSE.md file for details.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-13._
