---
layout: default
title: Week 3 & 4
parent: Weekly Progress
nav_order: 5
---
---
# Week 3 & 4
June 16 – June 29

---
- Created a Debian bookworm virtual machine using debvm to use as a test server on my local machine to test Ansible playbook to build Raspberry Pi Debian images.
- Raspberry Pi Debian Images Build Farm [https://salsa.debian.org/krvprashanth/raspi-debian-build-farm](https://salsa.debian.org/krvprashanth/raspi-debian-build-farm)
    - Commit [5cf4a9fc Refactor: move scripts to build_env; add inventory and playbook](https://salsa.debian.org/krvprashanth/raspi-debian-build-farm/-/commit/5cf4a9fc91d6d8c6750c7d2ed9d37d07046b8b00)
- Filed a bug report to see support for Raspberry Pi Compute Module 4 ([#1108236](https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1108236))
- Had meeting with mentor Gunnar Wolf on Monday, 26 June, 9:30 pm IST and shared the work done over the past week.
- Tried building (initial workaround of armhf) architecture-specific Raspberry Pi Debian using vmdb2, flash-kernel, and u-boot.
    - [https://salsa.debian.org/krvprashanth/raspi-arch-image-specs](https://salsa.debian.org/krvprashanth/raspi-arch-image-specs)


### Merge Request
- opened [!74: Add: machine db entry for Raspberry Pi Compute Module 4](https://salsa.debian.org/installer-team/flash-kernel/-/merge_requests/74)

### Ending Thoughts
That’s all for the past two weeks! Hopefully, this bi-weekly progress log keeps everyone updated on my progress and helps attract potential contributors.

### Helpful Links
- [https://dyn.manpages.debian.org/bookworm-backports/debvm/debefivm-create.1.en.html](https://dyn.manpages.debian.org/bookworm-backports/debvm/debefivm-create.1.en.html)


