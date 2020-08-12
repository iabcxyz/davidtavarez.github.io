---
layout: post
title: "Troubleshooting Grin++"
date: 2020-08-12 23:59:00 -0400
keywords: "grin++, grin, tor, onion, sending, receiving"
comments: true
description: "Fixing common issues with Grin++"
---

Grin++ is a, I'm sorry, the best [Grin](http://grin.mw/) Wallet. Grin++ runs on Windows, Linux and macOS, probably soon on Android, who knows... also Grin++ is multi-language, Grin++ has been translated into 12 differrent languages: Chinese, German, Spanish, Arabic, Italian, Polish, Portuguese, Russian, Ucranian, Russian, Turkish and, recently, Slovenian, it doesn't matter if you don't speak English, Grin++ got you covered 💕. If you're not using Grin++ yet, you should, go to [grinplusplus.github.io](https://grinplusplus.github.io/) and download it, I'll wait for you ⌚. Thanks.

But life isn't perfect 😞; sometimes, some few users face some small tiny issues, and today I will explain to you how to fix these tiny issues 😁👍.

# Windows.

## Node isn't installed

![Node isn't installed](https://raw.githubusercontent.com/davidtavarez/davidtavarez.github.io/master/_images/posts/NodeIsntInstalled.png)

Well, this can be easly fixed by making sure our Antivirus is not deleting neither putting into quarantine the Backend: **GrinNode.exe**. In order to confirm that, we need to make sure the file named as **GrinNode.exe** is located inside the `bin` folder at `C:\Users\admin\AppData\Local\Programs\GrinPlusPlus\resources\app.asar.unpacked\` as it's showed in the next picture:

![bin](https://raw.githubusercontent.com/davidtavarez/davidtavarez.github.io/master/_images/posts/GrinNodeBin.png)