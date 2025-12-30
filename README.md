## Welcome to Qubes Users Berlin!

We are a group of [Qubes OS](https://www.qubes-os.org) users who meet monthly in Berlin. 

# 30.1.2026 Qubes OS meetup

**Next meetup is scheduled for Friday, the 30.1.2026 from 6 till 8 p.m. at [x-hain](https://x-hain.de/).

Some topics for the meetup:

- TBD
- Whatever you would like to share and discuss! Bring your own

![Q](./qubes-logo-grain2.png) uestions!

All creatures welcome! <3

Please consult the calendar of x-hain for further information.

# Future meetups

In future meetups we want to discuss

- OpSec strategies with Qubes OS - Join us for practical discussion, insights and strategies to safeguard your digital activities!
- Android in Qubes OS cont'd


# Past meetups

## 29.12.2025

The meetup was led by @marmarek and @marmarta <3 with interesting discussions:

- Overview of Qubes OS
- Diving into the features of Qubes OS 4.3, as well as useful tooling:
 - Preloaded disposable VMs
 - QWT support
 - Seamless mode supported for Windows 10
 - Forensics in disposabe qubes: setting the `ephemeral` config option using

   ```
   Command 'config':
  usage: qvm-volume config [--verbose] [--quiet] [--help]
                           VM:VOLUME property value
   ```

   you can run the specific dispvm exclusively in RAM.

   `rw` config option for a specific volume is also useful:

   ```
   Command 'config':
  usage: qvm-volume config [--verbose] [--quiet] [--help]
                           VM:VOLUME property value
   ```
  You can verify with `qvm-volume info`, and the default config value for the particular lvm thin pool, f.ex. `qvm-pool info <LVM_THIN_POOL>`

 - Ansible support and future development planned
 - Continued Salt support for Qubes retained
- [wyng-util-qubes](https://codeberg.org/tasket/wyng-util-qubes) also for 4.3
- [Qubes Video Companion](https://github.com/QubesOS/qubes-video-companion)
- On the question of how to help out <3:
 - A good starting point would be testing, reviewing and/or [fixing minor issues](https://github.com/QubesOS/qubes-issues/issues?q=state%3Aopen%20label%3A%22good%20first%20issue%22)
 - For more advanced contributors, perhaps [this](https://github.com/QubesOS/qubes-issues/issues/6661) will be of interest :)
 - Or look at the `Backlog` or `Ready` columns of [Current team tasks](https://github.com/orgs/QubesOS/projects/19/views/2) and leave a comment if you are interested
 - Improve and/or write [documentation](https://github.com/QubesOS/qubes-doc/), ([usefule guidelines](https://doc.qubes-os.org/en/latest/developer/general/how-to-edit-the-rst-documentation.html))
 - General [contributing guidelines](https://doc.qubes-os.org/en/latest/introduction/contributing.html)
- "modern" suspend (S0ix, s2idle) debugging hint: look at `/sys/kernel/debug/pmc_core/substate_requirements`; enable `s2idle` via `qvm-features dom0 suspend-s0ix 1` and reboot

## 27.6.2025


Some of the topics include:

- Deep dive into **preloaded disposable qubes** with a demo of the development environment by Ben
- With two new issues raised following the discussion and conversation:
  - [Issue 10026](https://github.com/QubesOS/qubes-issues/issues/10026)
  - [Issue 10027](https://github.com/QubesOS/qubes-issues/issues/10027)
- Exploring **Qubes RPC policies** and **qrexec source code**
- Background and refresher on **Qubes RPC policies** and **Qubes Admin API**:
  - [Qrexec: secure communication across domains](https://www.qubes-os.org/doc/qrexec/)
  - [Qrexec: Qubes RPC internals](https://www.qubes-os.org/doc/qrexec-internals/)
  - [Qubes Admin API](https://www.qubes-os.org/doc/admin-api/)
  - [Forum Thread](https://forum.qubes-os.org/t/how-to-use-the-qubes-admin-polcies-api-despite-the-lack-of-documentation-wip/29863)

and some useful tools like:

  - qubes-policy-editor
  - qubes-policy-editor-gui (dom0)
  - [vim-qrexec plugin](https://github.com/ben-grande/vim-qrexec)

## 27.5.2025

- Give i3 a try with an example setup 

Sinni talked about their setup with a follow up discussion <3 !


## 25.4.2025

We did discuss some pretty cool topics: preloaded disposable qubes, salted site-specific browser qubes & Android in Qubes OS:

1. We got a peak into a very exciting Qubes OS feature in development by [Ben](https://github.com/ben-grande) - [preloaded disposable qubes](https://github.com/QubesOS/qubes-issues/issues/1512)
2. Salted site-specific browser qubes revisited by Corey [see](https://github.com/coyotebush/qubes-salt/tree/web) 
3. Discussion & further collaborations on site regarding Android on Qubes OS inspired by the forum [post](https://forum.qubes-os.org/t/use-android-apps-in-qubesos/32971) by norkelcake and bae9e4f7 
4. GrapheneOS - apart from syncing the repo and building for emulator nothing much :) wip - play with kernel parameters with the notable warning that this disregards security features. GrapheneOS Team has [plans](https://grapheneos.social/@GrapheneOS/113185686714810236) though :)

## 28.3.2025

We looked at some Salt and Android use cases in Qubes OS:

- Salted site-specific browser qubes!
  - Corey talked about salting a web qube and also shared his [repo](https://github.com/coyotebush/qubes-salt)! We will continue the discussion in April!
- Android Use Cases in Qubes OS
  - We continued the engaging discussion from our last meetup. snorkelcake and bae9e4f7 wrote a guide for how to setup an android qube which is available on the [forum](https://forum.qubes-os.org/t/use-android-apps-in-qubesos/32971).

# Monthly meetings

**Qubes Users Berlin monthly meetings are currently every last Friday of each month!**

We will meet every **last** Friday of each month at [xHain](https://x-hain.de/de/participate/#content), a hackerspace at **Grünberger Str. 16** in Friedrichshain. We abide by xHain's [hygiene concept](https://wiki.x-hain.de/de/xHain/hygiene-konzept).

We look forward to discussing topics related to Qubes OS with you! :) 

A small presentation/discussion on different topics is planned for every meeting. As well as snacks! :)

If you are interested and want to present something related to Qubes OS yourself,
please don't hesitate and write us an email! 

Stay tuned! 

## Mailing list

You are welcome to join our [mailing list](https://www.autistici.org/mailman/listinfo/qub), where we announce meetings and discuss items.

## Social media

If you wish, you can connect with us on [bluesky](https://bsky.app/profile/qubes-users-berlin.bsky.social) and [mastodon](https://mastodon.social/@qubes_users_berlin).

## Code of conduct

The meeting is covered by Qubes OS [Code of Conduct](https://qubes-os.org/code-of-conduct) and [Berlin Code of Conduct](https://berlincodeofconduct.org/). 

<img src="https://github.com/QubesOS/qubes-attachment/raw/master/icons/qubes-community-event/qubes-community-event.png" align="center" width="200">
