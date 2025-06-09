---
layout: default
title: Week 1
parent: Weekly Progress
nav_order: 3
---
---
# Week 1
June 2 – June 8

---

![Setup](/assets/images/setup.jpg)

- I have started writing project progress blog posts to [Debian Outreach Team pages](https://outreach-team.pages.debian.net/) and added entry for Debian Outreach Team pages to [Debian Planet](https://planet.debian.org/) as most of the community is unaware of the work GSoC Contributors/Interns doing and also I will be writing Bi-Weekly reports which can be published in Debian Planet will have wide reach.
- Tested U-Boot package: u-boot-rpi (2023.01+dfsg-2+deb12u1) current version stable/bookworm on  Raspberry Pi Zero 2 W & 4 Model B
   -  Created a bootable SD Card with u-boot-rpi, raspi-firmware used Debian's multiarch functionality to install the u-boot-rpi:arm64 package on a amd64 system and copied the appropriate u-boot image and edited config.txt to match.
- Commit [bb6c5faa Fix: machine entries ordering in db/all.db to pass sort check](https://salsa.debian.org/installer-team/flash-kernel/-/commit/bb6c5faa9cf772f2b3978e3d307273e4cb20b5b9?merge_request_iid=71)
- Tested flash-kernel on a Raspberry Pi Zero 2 W Rev 1.0 running [Bookworm / Raspberry Pi family 3 tested Image](https://raspi.debian.net/tested/20231109_raspi_3_bookworm.img.xz). 
- Filed a bug report to see support for Raspberry Pi Zero 2 W ([#1107524](https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1107524))



### Merge Requests

- opened [!73: Add: Support for Raspberry Pi Zero 2 W](https://salsa.debian.org/installer-team/flash-kernel/-/merge_requests/73) 
- opened and merged [!48: Add: config for Debian Outreach Team Pages](https://salsa.debian.org/planet-team/config/-/merge_requests/48)
- opened [!5: Fix: Jekyll build and HTML-Proofer errors](https://salsa.debian.org/outreach-team/outreach-team.pages.debian.net/-/merge_requests/5)
- opened [!6:  GSoC2025: Introduction blog post](https://salsa.debian.org/outreach-team/outreach-team.pages.debian.net/-/merge_requests/6)


### Ending Thoughts

That’s all for the week! Hopefully, this weekly progress logs keeps everyone updated on my progress and attract potential contributors.

### Helpful Links
- [https://wiki.debian.org/U-boot/Status](https://wiki.debian.org/U-boot/Status)
- [https://wiki.debian.org/Multiarch/HOWTO](https://wiki.debian.org/Multiarch/HOWTO)
- [https://manpages.debian.org/bookworm/flash-kernel/flash-kernel.8.en.html](https://manpages.debian.org/bookworm/flash-kernel/flash-kernel.8.en.html)
- [https://manpages.debian.org/bookworm/u-boot-tools/mkimage.1.en.html](https://manpages.debian.org/bookworm/u-boot-tools/mkimage.1.en.html)
- [https://manpages.debian.org/bookworm/u-boot-menu/u-boot-update.8.en.html](https://manpages.debian.org/bookworm/u-boot-menu/u-boot-update.8.en.html)


