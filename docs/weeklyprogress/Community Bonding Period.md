---
layout: default
title: Community Bonding Period
parent: Weekly Progress
nav_order: 2
---
---
# Community Bonding Period
May 8 – June 1

---
- GSoC 2025 accepted Contributors announced and my GSoC proposal [Make Debian for Raspberry Pi Build Again](https://summerofcode.withgoogle.com/programs/2025/projects/JvTO8QWv) accepted.
- Community Bonding period begined and had a face-to-face talk over Jitsi with mentor Gunnar Wolf and also stayed in touch through Telegram DMs.
- Created this project web page.
- [[Pkg-raspi-maintainers] Request: Debian Raspberry Pi Team membership](https://alioth-lists.debian.net/pipermail/pkg-raspi-maintainers/Week-of-Mon-20250505/001271.html)
- Attended GSoC Contributor Welcome Session - Wednesday, May 14th
- Familiarized with `vmdb2` documentation, Debian ARM architecture ports and `debian-installer` tools.
- Understood what differs between Raspberry Pi families, looked at Cyril Brulebois generate-recipe (in the repo `Raspberry Pi image specs`).
- Filed a bug report to see support for Raspberry Pi 4 Model B ([#1106381](https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=1106381))
- Prepared test hardware environment and tested existing daily  auto-built images on Raspberry Pi 0 & 4 and also setuped a Debian unstable environment with schroot and sbuild for Debian packaging.
- Reached out to mentor to get access to the [raspi.debian.net](http://raspi.debian.net/) existing build infrastructure and tried initially setting up on my local machine to get familiar with it and then to start migrating it to Debian infrastructure and also fixed build errors and warnings caused by Ruby version upgrades and deprecated methods, which prevented the website from building on unstable.
- I already have Raspberry Pi zero 2w, 4 and 5 devices and DPL approved amount to buy the rest hardware. I sent mentor the actual prices close to my home of the most convienient seller.


### Merge Requests

| MR | Status |
| ------ | ------ |
| Boot Media (Software Image): Flashing Instructions using Raspberry Pi Imager  ([MR #21](https://salsa.debian.org/raspi-team/web-raspi-img/-/merge_requests/21))      |  Pending      |
|  Add: Support for Raspberry Pi 4 Model B ([MR #71](https://salsa.debian.org/installer-team/flash-kernel/-/merge_requests/71)) | Pending |
| Fix: build errors and Ruby 3.3+ compatibility issues ([MR #22](https://salsa.debian.org/raspi-team/web-raspi-img/-/merge_requests/22)) | Accepted    |
|  RaspberryPi: enable repository for trixie  ([MR #361](https://salsa.debian.org/extrepo-team/extrepo-data/-/merge_requests/361)) | Accepted |

### Ending Thoughts

That’s all for the Community Bonding Period! Hopefully, this weekly progress logs keeps everyone updated on my progress and attract potential contributors. Moreover, I’m organizing my daily life for this new exciting period. 


---
### Misc 😉

<div onclick="window.open('https://www.linkedin.com/posts/krvprashanth_debian-welcomes-the-2025-gsoc-contributors-activity-7333572570056638483-tGwn?utm_source=share&utm_medium=member_android&rcm=ACoAADTOmc0BYyaYJOAQcIQUWM0yICwTivv98XE', '_blank')" style="cursor: pointer; border: 1px solid #ddd; padding: 1em; border-radius: 8px; background: #f9f9f9; margin-top: 2em;">
  <div style="display: flex; justify-content: space-between; align-items: center; margin-bottom: 0.5em;">
    <div style="display: flex; align-items: center;">
      <img src="https://static.licdn.com/scds/common/u/images/logos/favicons/v1/favicon.ico" alt="LinkedIn" width="20" height="20" style="margin-right: 0.5em;">
      <strong>LinkedIn Post</strong>
    </div>
    <span style="font-size: 0.9em; color: #555;">May 28, 2025</span>
  </div>
  <blockquote style="margin: 0; font-style: italic;">
    This summer, I'm excited to start contributing and developing with this great community.<br><br>
    Looking forward to new connections and learning opportunities :)
  </blockquote>
</div>


