---
title: Greg Kroah-Hartman
summary: Linux kernel developer
date: 2012-11-15
categories:
- developer
- linux
- mac
---

### Who are you, and what do you do?

I'm [Greg Kroah-Hartman](http://www.kroah.com/log/ "Greg's website."). I am a Linux kernel developer working for [The Linux Foundation](http://www.linuxfoundation.org "The Linux Foundation's site.") as a Fellow. I'm responsible for different parts of the Linux kernel as a maintainer (USB, driver core, staging area, other various bits), and I do the Linux kernel stable releases every week or so, taking the bug fixes from the latest development tree and backporting them to the last released kernel for all to use. 

I started the [Linux Driver Project](http://www.linuxdriverproject.org "The Linux Driver Project's site.") many years ago while I was working at Novell/SuSE which provides free Linux drivers for any company that wants them. That project still continues today, writing a handful of new drivers every year.

### What hardware do you use?

My laptop is a [MacBook Pro][macbook-pro] Retina. My workstation is an old pieced-together Intel machine, the parts selected for the size and lack of noise more than anything else, with two large monitors connected. The laptop and the workstation all only have SSD drives in them. I have an old Dell workstation as a build machine for kernel testing, with an extremely fast Micron Flash PCI drive in it for building kernels. Thanks to Amazon's generosity, I've been doing a lot more kernel build testing on their AWS systems, utilizing a 32 processor, 64Gb virtual machine, allowing me to build multiple kernels at the same time all on a RAM disk in minutes. That has enabled me to be more productive while traveling.

I also have a few virtual and physical servers floating around the cloud that I use for email, [git][], and backup services.

For a phone I have a [Galaxy Nexus][galaxy-nexus]. I also have a [Nexus 7 tablet][nexus-7], which I'm finding I like more and more these days, and have given up my previous [Kindle][] and iPad for it.

### And what software?

Linux everywhere of course. On the desktop I am running the [openSUSE][] Tumbleweed distribution (a rolling version of openSUSE that provides the latest stable packages) as I'm the one responsible for that distribution. I run [Gentoo Linux][gentoo] on my servers and my build machine. I am trying out [Arch Linux][arch-linux] on my MacBook as I wanted to see how that distro was due to hearing good things about it. So far I'm impressed with it, and given that openSUSE doesn't work on the MacBook Pro yet, I'm sticking with it for now.

For daily use, I live in [mutt][] and [vim][] for email and editing. I use [offlineimap][] for syncing email around on all of the different systems I use. To send email I rely on [msmtp][] to be able to handle queueing of emails when I do not have any connectivity (like on airplanes). git for source code control in dealing with Linux kernel patches as well as other more mundane stuff (email archiving, configuration files, etc.) I use [quilt][] on top of git for handling the Linux kernel [stable patch set](http://git.kernel.org/?p=linux/kernel/git/stable/stable-queue.git;a=summary "A list of the stable patches for the Linux kernel.") as the workflow there does not lend itself to a pure git environment.

For desktop environment, on my workstation, I use [GNOME 3][gnome], despite me complaining about it all the time. On my laptop I've converted over to using the [i3][] window manager, on top of the GNOME 3 session handling logic. Give me a few more weeks and I might just move my desktop over to that environment as well - I'm finding that i3 is really good for my use cases (lots of terminal windows open, virtual screens, and fast keyboard navigation of everything.) For a web browser I switch between [Firefox][] and [Chrome][] every few weeks for no valid reason.

My Nexus 7 tablet is running the nightly [CyanogenMod][] releases and have had no problems at all with it. My Galaxy Nexus phone is running the stock Jelly Bean release from Google, no modifications.

### What would be your dream setup?

I spend most of my time reading and responding to email, and over the years, my combination of mutt, vim, offlineimap, and msmtp really work just about as good as I could ever imagine, synchronizing emails around different systems without any loss of data. So on that front, I do have my dream setup already. Combined with git, the best source code control tool I've ever used (and I've used them all), I can set up a bare machine in a matter of minutes and have full access to all of my kernel trees, emails, and development tools.

The hardware side of things could use some work. I spend too much time waiting for kernel builds to complete. Right now I've gotten a full kernel build, with all options enabled, down to about 5 minutes on a cloud computing platform, and 4 minutes on my local build system. I know this can go faster, and even waiting that long feels unacceptable at times. Now that disk speeds have gone through the roof with the advent of flash-based storage, our bottlenecks are at other areas of the hardware stack, mostly still CPU power. Our bus speeds (PCI / Thunderbolt, Ethernet, etc.) keep increasing and hopefully CPU speeds keep up with them in order to keep the buses busy, otherwise in a few years we are going to be in trouble.

I want to be able to do a full kernel build in less than a minute, on a machine that doesn't require me wiring it to my home dryer power outlet and doesn't sound like a small airplane is taking off in the basement. The Linux kernel code base keeps growing at a constant rate, so over time, kernel build times should decrease with new CPU releases, but in the past few years, that hasn't seemed to happen.

On a portability front, if my Nexus 7 had 4g connectivity, I'd drop my cell phone in an instant. That machine has turned out to be very useful for handling email, reading books, planing trip schedules, and other mundane tasks. Given that it is a Linux machine underneath, I also have access to my normal range of command line tools I am used to. I have hope that someday I can get rid of my laptop for something in that form factor as long as it still has the horsepower to do kernel development tasks I need to do. Combine it with a faster cloud-based build environment, and I might be there in a few years.

[arch-linux]: https://archlinux.org/ "A Linux distro."
[chrome]: https://www.google.com/intl/en/chrome/ "A WebKit-based browser, where each tab runs in its own thread."
[cyanogenmod]: http://web.archive.org/web/20161225043707/https://www.cyanogenmod.org/ "A custom ROM for Android phones."
[firefox]: https://www.mozilla.org/en-US/firefox/new/ "A cross-platform open-source web browser."
[galaxy-nexus]: http://web.archive.org/web/20210205175044/http://www.google.com/nexus/ "An Android-based smartphone."
[gentoo]: https://www.gentoo.org/ "A Linux distribution."
[git]: https://git-scm.com/ "A version control system."
[gnome]: https://www.gnome.org/ "A desktop system for *nix operating systems."
[i3]: https://i3wm.org/ "An X window manager."
[kindle]: http://web.archive.org/web/20230315012831/http://www.amazon.com/Kindle-Ereader-ebook-reader/dp/B007HCCNJU/ "A digital book reader."
[macbook-pro]: https://www.apple.com/macbook-pro/ "A laptop."
[msmtp]: https://msmtp.sourceforge.net/ "An SMTP client."
[mutt]: http://www.mutt.org/ "A command-line email client."
[nexus-7]: http://web.archive.org/web/20210205175044/http://www.google.com/nexus/ "An Android tablet."
[offlineimap]: https://www.offlineimap.org/ "A tool for syncing mail from an IMAP server."
[opensuse]: https://en.wikipedia.org/wiki/OpenSUSE "A Linux distribution."
[quilt]: http://savannah.nongnu.org/projects/quilt "A patch tracking system."
[vim]: https://www.vim.org/ "A command-line text editor."
