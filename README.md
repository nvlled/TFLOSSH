# TFLOSSH: *Towards* Free/Libre and Open Source Software and Hardware

This repository is intended to be a non-exhaustive source of information on devices and software that are part of a journey towards Free/Libre Open Source Software and Hardware.

# Contents

- [Terminology](#terminology)
- [Why free/libre and open source is needed](#why-freelibre-and-open-source-is-needed)
    - [Intel Management Engine](#intel-management-engine)
    - [AWS Elemental PLA chips](#aws-elemental-pla-chips)
- [Priority free/libre and open projects](#priority-freelibre-and-open-projects)
- [Why GNU/Linux on mobile devices is needed](#why-GNU/Linux-on-mobile-devices-is-needed)
- [Why Google is dangerous](#why-google-is-dangerous)
- [FOSS laptops](#foss-laptops)
    - [System76](#system76)
- [FOSS mobile devices](#foss-mobile-devices)
    - [LineageOS](#lineageos)
        - [LineageOS devices comparison](#lineageos-devices-comparison)
        - [Reddit thread 2019-06-30](#reddit-thread-2019-06-30)
        - [Asus ZenFone Max Pro M1 (X00TD)](#asus-zenfone-max-pro-m1-x00td)
        - [Samsung Galaxy Note 3 (hlte)](#samsung-galaxy-note-3-hlte)
        - [General setup](#lineageos-general-setup)
    - [Librem PureOS](#librem-pureos)
        - [Librem 5](#librem-5)
    - [UBports Ubuntu Touch](#ubports-ubuntu-touch)
        - [UBports Ubuntu Touch devices](#ubports-ubuntu-touch-devices)
        - [Meizu PRO 5 (turbo)](#meizu-pro-5-turbo)
        - [BQ Aquaris E4.5 (krillin)](#bq-aquaris-e4.5-krillin)
    - [Applications solutions for LineageOS and Ubuntu Touch](#applications-solutions-for-lineageos-and-ubuntu-touch)
- [Libreboot](#libreboot)
- [Other](#other)

# Terminology

|**term**                                                           |**expansion**                                             |**comments**                                                                                                                                                                                                                      |
|-------------------------------------------------------------------|----------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|TFLOSSH                                                            |*Towards* Free/Libre and Open Source Software and Hardware|"Towards" implies incomplete. It implies that this is a journey.                                                                                                                                                                  |
|[FOSS](https://en.wikipedia.org/wiki/Free_and_open-source_software)|Free and open source software                             |Ideally, this implies *all* **software** of the machine being free and open source and verifiably so. So, this would include chipset microcode, operating systems, applications etc.                                              |
|FOSH                                                               |Free and open source hardware                             |Ideally, this implies *all* **hardware** of the machine being free and open source and verifiably so. So, this would include all chip architectures and all other hardwares such as main system boards and communciations devices.|

# Why free/libre and open source is needed

- [*Philosophy of the GNU Project*](https://www.gnu.org/philosophy/philosophy.html) -- [Richard Stallman](https://en.wikipedia.org/wiki/Richard_Stallman)
- [*Lithuania says throw away Chinese phones due to censorship concerns*](https://www.reuters.com/business/media-telecom/lithuania-says-throw-away-chinese-phones-due-censorship-concerns-2021-09-21)

## Intel Management Engine

- [Intel x86s hide another CPU that can take over your machine (you can't audit it)](https://boingboing.net/2016/06/15/intel-x86-processors-ship-with.html) -- Damien Zammit (2016-06-15)
- [Intel's Management Engine is a security hazard, and users need a way to disable it](https://www.eff.org/deeplinks/2017/05/intels-management-engine-security-hazard-and-users-need-way-disable-it) - Erica Portnoy and Peter Eckersley (Electronic Frontier Foundation) (2017-05-08)

## AWS Elemental PLA chips

- [*The Big Hack: How China Used a Tiny Chip to Infiltrate U.S. Companies*](https://www.bloomberg.com/news/features/2018-10-04/the-big-hack-how-china-used-a-tiny-chip-to-infiltrate-america-s-top-companies) -- Jordan Robertson
and Michael Riley (Bloomberg) (2018-10-04)
- [*Vodafone Found Hidden Backdoors in Huawei Equipment*](https://www.bloomberg.com/news/articles/2019-04-30/vodafone-found-hidden-backdoors-in-huawei-equipment) -- Daniele Lepido (2019-04-29)

## Priority free/libre and open projects

- [High Priority Free Software Projects](https://www.fsf.org/campaigns/priority-projects) -- Free Software Foundation

## Why GNU/Linux on mobile devices is needed

- The 2018-12-30 state of GNU/Linux on mobile devices and the threats of Android and iOS: [*Why we need GNU/Linux on mobile devices (now more than ever)*](https://c3lt.de/35c3/talk/BRKHHG) -- [Jan Sprinz](https://github.com/neothethird) (35th Chaos Communication Congress (35C3) Lightning Talks) (2018-12-30)

## Why Google is dangerous

- [*I Cut Google Out Of My Life. It Screwed Up Everything*](https://gizmodo.com/i-cut-google-out-of-my-life-it-screwed-up-everything-1830565500) -- Kashmir Hill (2019-01-29)
- [*Degoogling LineageOS in 2019*](https://old.reddit.com/r/LineageOS/comments/ccs5wy/degoogling_lineageos_in_2019)

# FOSS laptops

## System76

- Warning: They feature no nipple.
- [System76](https://system76.com/laptops)
- [System76 Bonobo WS 17' (featuring GPU Nvidia 10-series)](https://system76.com/laptops/bonobo)

# FOSS mobile devices

- [*Why we need GNU/Linux on mobile devices (now more than ever)*](https://c3lt.de/35c3/talk/BRKHHG) -- [Jan Sprinz](https://github.com/neothethird)

## LineageOS

### LineageOS devices comparison

- [LineageOS devices comparison notebook](devices.ipynb)
- [Unofficial List and Spec Sheet of Officially Supported LineageOS devices](https://docs.google.com/spreadsheets/d/1swcOWw_KcSaE8otSa-1rthq7bLLmfsNZMWnVF5XCd1o/edit#gid=0)
    - [Reddit](https://www.reddit.com/r/LineageOS/comments/7w6nl3/unofficial_list_and_spec_sheet_of_officially/)

### Reddit thread 2019-06-30

- <https://old.reddit.com/r/LineageOS/comments/c7dnax/what_phone_do_you_use_for_los>

### Asus ZenFone Max Pro M1 (X00TD)

- [Asus ZenFone Max Pro M1 (X00TD) device setup documentation](X00TD.md)

### Samsung Galaxy Note 3 (hlte)

- [Samsung Galaxy Note 3 (hlte) device setup documentation](hlte.md)

### General setup

- Unlock the device and the bootloader.
- Install TWRP and LineageOS.
- Install [F-Droid](https://f-droid.org/FDroid.apk).
- Install [Aurora Store](https://f-droid.org/en/packages/com.aurora.store).
- Install [applications](applications.md).

## Librem PureOS

PureOS is a GNU/Linux distribution based on Debian. [Phosh](https://developer.puri.sm/Librem5/Software_Reference/Environments/Phosh.html) is the PureOS GTK-compliant default user interface for phone-like devices. It uses [a fork](https://source.puri.sm/Librem5/wlroots) of [wlroots](https://github.com/swaywm/wlroots) as a Wayland compositor.

- upcoming documentation

### Librem 5

- [Librem 5](https://puri.sm/products/librem-5)

- upcoming documentation

## UBports Ubuntu Touch

- [Ubuntu Touch documentation](Ubuntu_Touch.md)

### UBports Ubuntu Touch devices

- [UBports Ubuntu Touch devices](https://devices.ubuntu-touch.io)

### Meizu PRO 5 (turbo)

This is a device capable of running UBports Ubuntu Touch 16.04 LTS with Anbox for Android applications.

- [Meizu PRO 5 (turbo) device setup documentation](turbo.md)

### BQ Aquaris E4.5 (krillin)

This was the first commercially available phone to feature Ubuntu Touch.

- [BQ Aquaris E4.5 (krillin) device setup documentation](krillin.md)

## Applications solutions for LineageOS and Ubuntu Touch

- [Applications solutions for LineageOS and Ubuntu Touch](applications.md)

# Libreboot

Libreboot is a free and open source BIOS or UEFI replacement.

- [Libreboot](https://libreboot.org)

# Other

## VPNs

![](https://raw.githubusercontent.com/wdbm/TFLOSSH/master/media/2018-11-10T184615.png)

## setup of NordVPN via APK 2018-11-11T0252Z

- <https://nordvpn.com/tutorials/android/apk>

## browser extensions

- [browsers_config](https://github.com/wdbm/browsers_config)
