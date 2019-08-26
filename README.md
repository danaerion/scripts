# Scripts
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/93a7e7b65a7d4d6fa440a9851bf110b2)](https://www.codacy.com/manual/iamsaalim/script?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=iamsaalim/script&amp;utm_campaign=Badge_Grade)

## A useful script for building custom kernel for Android Devices
###### This is a script which I use to compile custom kenel for my devices. It was written keeping in mind about compiling a standalone kernel in CI Deployments. 

**Features of this script :**
  ~~~
  1. Device Specific Configuration
  2. Fetching the most needed stuffs like Toolchains(clang, gcc-arm64-4.9, gcc-arm-4.9) and Flasher(AnyKernel)(Device Specific)
  3. Integrate with Telegram
  4. Notifies when compilation starts with some useful informations
  5. Uploads build to Telegram
  ~~~
