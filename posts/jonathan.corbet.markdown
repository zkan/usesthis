---
title: Jonathan Corbet
summary: Linux kernel contributor, editor (LWN)
date: 2012-05-28
categories:
- developer
- editor
- linux
---

### Who are you, and what do you do?

I am Jonathan Corbet, executive editor of [LWN.net](http://lwn.net/ "A Linux and free software news site."), occasional kernel contributor, lead author of Linux Device Drivers, member of the Linux Foundation's Technical Advisory Committee, and slave to the wife, two kids, and one golden retriever.

### What hardware do you use?

Looking most widely, my digital presence operates out of three dedicated systems at hosting facilities; two for LWN and one as a cooperative home for non-work stuff maintained with several friends.

My desktop is a fairly run-of-the-mill quad-core box, except that I did put a nice Intel SSD into it. Certain activities - starting [LibreOffice][], [git][] pulls, and kernel compiles, for example - are just way more tolerable on an SSD-based system; I'm not quite sure how I got by without it. It has mundane Intel graphics, but that's enough to drive two big monitors, both of which tend to be so cluttered that I've long since forgotten what my background image is.

One other nice touch is the [Logitech diNovo Edge keyboard][dinovo-edge]. I'm a fast typist but am very sensitive to the feel and layout of the keyboard; I've been using this one long enough that I've worn the lettering off the keycaps and I'm still pleased to have it.

The laptop is an [HP 2510p][compaq-2510p] with a nine-cell battery. I do a lot of traveling to conferences and such; the laptop is heavily optimized for light weight and long battery life. I've been pondering trading it in for something ultrabookish, but haven't made that move yet.

I also have a pile of early [OLPC XO][xo] 1.75 laptops around, useful for ARM development work.

The pockettop is my trusty [HTC Nexus One][nexus-one]. It's getting a little old and showing signs of use, but I've not really seen anything out there that looks so much shinier that I have to have it. It's running [CyanogenMod 7][cyanogenmod], of course; alas, it looks like an Android 4-based CM for the Nexus One isn't in the offering anytime real soon. So I may have to make a change at some point.

I do also have a [Nokia N9][n9] that I use sometimes. It's a very nice piece of hardware with software that showed a lot of promise. Once can only hope that, once it's gotten this Windows thing out of its system, Nokia will be able to return to Linux-based systems.

One shouldn't neglect the [Netgear WNDR3700v2][n600] router running [OpenWRT][]; I wouldn't dream of getting on the net without it.

Finally, alas, my [iRiver H340][h340] music player running [Rockbox][] died a definitive death a little while back. I've replaced it with a Cowon J3, which is an entirely nice piece of hardware, but I do miss Rockbox.

### And what software?

Linux on everything, of course.

The primary desktop machine is running the [Fedora Rawhide][fedora] distribution. Rawhide is not for the faint of heart; it has occasional tendency to explode at inopportune times. But it's one of the best ways I've found to keep right on the bleeding edge of software development in the Linux community without spending all my time building stuff. Besides, it's kind of fun to have a new and different operating system every day.

Even Rawhide doesn't have a sufficiently scary kernel, though, so, naturally, I build and run my own.

I tend to keep a variety of distributions around on other systems, just so I can keep up with what they're up to. The production systems are running [CentOS][], but we continually consider just biting the bullet and paying for an enterprise Linux distribution so we can legitimately gripe when the security updates are late.

When people ask about editors I don't know what to answer since I'm fluent in both emacs and vi. I tend to use emacs for article writing and software development; I've written some elisp code to interface it directly into the LWN content management system, which is really nice. I fire up vi when I need an editor quickly for something. The way it usually settles out is that I use emacs when I'm running as my self and vi when I'm doing stuff as root.

I write kernel code in [C][], naturally; almost anything else is done in [Python][]. Python is not without its warts, and I really dislike how obvious (in retrospect) errors can lurk until one particular code path is followed months in the future, but the language is a lot of fun and it's possible to get a lot done in a short period of time.

Email is handled with [Postfix][] and [Dovecot][] on the server and [Claws-mail][] on the desktop. All mail clients suck, but I've not found one that sucks less than Claws at the moment. It lets me do things like feed messages to scripts, has some nice message processing facilities, and I've never had to fight with it to get it to send patches without molesting them. I've been keeping an eye on [Notmuch][] but haven't been able to make that transition so far.

Needless to say, I would go insane without [SpamAssassin][]. I currently get 3-4,000 spams per day; if a dozen of them actually make it into my mailbox, I get really grumpy.

Other useful stuff includes [gnucash][] for personal finance management (though, alas, I've not yet found anything good enough to run a business with), [Firefox][] for the net (as much as anything because it has NoScript, which I'd hate to be without), and [rsync][] for managing directory trees and moving them around.

### What would be your dream setup?

Such things may be hard to explain to all you kids out there, but I started programming on a CDC mainframe using punched cards. When I got to use an early BSD release on a VAX - with a vt100 terminal, no less - it seemed like a dream setup. I am still getting over the fact that I can not only have a Unix-like system in my house; I can have one in my backpack and my pocket as well. It all seems like a dream.

But my real dream setup, I guess, is a setup where I am in control. That means open systems that I can hack, software that is free, and a community of developers keeping its eye on the whole thing. We are so very close now; if we choose carefully, we *can* hack our computers, our phones, and more. But we are also very far. Control over our hardware, our software, and our data has to be fought for and won, over and over again, and the stakes are high.

For a compelling explanation of how important this is, go have a look at Karen Sandler's [linux.conf.au keynote](http://mirror.internode.on.net/pub/linux.conf.au/2012/Keynote_Karen_Sandler.ogv "A link to an OGG video about free software.").

If you were to find yourself in a position where you needed a computer implanted into your chest, wired to your heart, and with wireless connectivity to the world, wouldn't you want a chance to look at the code? My dream setup, I guess, is one where that kind of access isn't something I have to explain to people and fight for.

[c]: https://en.wikipedia.org/wiki/C_(programming_language) "A compiled programming language."
[centos]: https://www.centos.org/ "A Linux distribution."
[claws-mail]: https://www.claws-mail.org/ "A GTK+ email client."
[compaq-2510p]: https://www.cnet.com/reviews/hp-compaq-2510p-review/ "A 12.1 inch PC laptop."
[cyanogenmod]: http://web.archive.org/web/20161225043707/https://www.cyanogenmod.org/ "A custom ROM for Android phones."
[dinovo-edge]: https://support.logitech.com/product/dinovo-edge/ "A rechargeable Bluetooth keyboard."
[dovecot]: https://dovecot.org/ "A secure IMAP server."
[fedora]: https://fedoraproject.org/ "A Linux distribution."
[firefox]: https://www.mozilla.org/en-US/firefox/new/ "A cross-platform open-source web browser."
[git]: https://git-scm.com/ "A version control system."
[gnucash]: https://www.gnucash.org/ "Open-source personal finance software."
[h340]: http://web.archive.org/web/20220905211217/https://www.amazon.com/iriver-H340-Digital-Player-Display/dp/B00065W74Q "A digital music player."
[libreoffice]: https://www.libreoffice.org/ "A free, open-source productivity suit."
[n600]: http://web.archive.org/web/20221206162148/http://www.amazon.com/NETGEAR-Wireless-Router-Gigabit-WNDR3700/dp/B002HWRJY4 "A dual-band wireless router."
[n9]: https://en.wikipedia.org/wiki/Nokia_N9 "A MeeGo-based smartphone."
[nexus-one]: https://en.wikipedia.org/wiki/Nexus_One "An Android-based smartphone."
[notmuch]: https://notmuchmail.org/ "An email index and search tool."
[openwrt]: https://openwrt.org/ "An embedded Linux distribution for wireless routers."
[postfix]: http://www.postfix.org/ "Mail server software."
[python]: https://www.python.org/ "An interpreted scripting language."
[rockbox]: https://www.rockbox.org/ "Replacement firmware for music players."
[rsync]: https://rsync.samba.org/ "An open-source file transfer/syncing tool."
[spamassassin]: https://spamassassin.apache.org/ "Server-side spam-fighting software."
[xo]: https://laptop.org/en/laptop/ "A laptop designed for children in developing countries."
