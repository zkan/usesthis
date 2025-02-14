---
title: Stefano Zacchiroli
summary: Computer science researcher, teacher, developer (Debian)
date: 2015-03-03
categories:
- developer
- linux
- teacher
---

### Who are you, and what do you do?

My name is [Stefano Zacchiroli](http://upsilon.cc/ "Stefano's website."), but I usually go by the nickname "Zack." I'm a computer science researcher and teacher at [University Paris Diderot](http://www.univ-paris-diderot.fr/ "The University Paris Diderot."), as well as a [Free Software](https://www.gnu.org/philosophy/free-sw.html "GNU's free software definition.") developer and activist. I'm a [Debian][] Developer, former three-time Debian Project Leader, and Board Director at the [Open Source Initiative](http://opensource.org/ "A non-profit supporting open source software.") (OSI)</a>.

### What hardware do you use?

My main hardware is my laptop, which I always carry with me. I'm now at my third iteration of (Lenovo) ThinkPads over a period of more than seven years and, overall, I'm a satisfied customer. As a geek I mostly interact with my OS by typing, and ThinkPad's keyboards are just unparalleled. My current ThinkPad is a [T440s][thinkpad-t440s], i7 CPU, 12GB RAM, 512GB SSD, and a Full HD display (not touchscreen, as I don't see the point of it).

When at the office I connect my laptop to an external LCD monitor and the best mechanical keyboard I've ever used: a [Das Keyboard Model S Ultimate][model-s-ultimate]. To ease the connection I rely on a basic Lenovo docking station, and I also have many (five or more, I think) Lenovo-ish AC adapters: one for the office, one near the couch at home, one for each backpack, etc.

As I believe in [autonomy](http://autonomo.us/2008/07/14/franklin-street-statement/ "An article about freedom in network services.") on the net, I also own various server-like machines. I run a virtual family server on a bare metal physical server which I rent from [So you Start](http://www.soyoustart.com/en/essential-servers/ "A dedicated server hosting service.") and share with a few close geek friends. At home I have a [Raspberry Pi][raspberry-pi] for home automation and a [QNAP TS-420 NAS][ts-420] with 4x 1TB disks (in RAID 5) for data storage. I also have a [Squeezebox 3][squeezebox] as music network player.

### And what software?

I run Debian wherever I can, and that includes all the machines mentioned above (most of them have in fact been chosen precisely for that reason).

In terms of Debian variants, I run Debian stable on server machines, except the Raspberry Pi that runs a dedicated Debian variant called [Raspbian][]. On desktops and laptops I run Debian testing, which is just the best (not to mention the first) "rolling-release" operating systems out there: a great trade-off between software freshness and not being too bleeding edge for use on your productivity machine.

As desktop environment I use [GNOME 3][gnome] with [GNOME Shell][gnome-shell]. Philosophically, I really like the GNOME project, their vision, and the courage they have had to reinvent the desktop after many years in which nobody was innovating. But I'm also technically quite happy about GNOME Shell. I love full-text searching for applications, the big switch to mute notifications, the no-frills approach, and the well-rounded app integration.

The only feature I miss in off-the-shelf GNOME Shell is [tiling window management](http://en.wikipedia.org/wiki/Tiling_window_manager "The Wikipedia entry for timing window managers.") (there is some tiling support in GNOME Shell, like splitting the screen in half with two main windows, but I do use more complex window arrangements than that). To fill that gap I'm using the [Shellshape][] extension; the result is good enough for my needs.

To give a general idea about my work flow, here is a list of tools that I use on a daily basis (in no particular order):

- [Mutt][] for email, with [Notmuch][] for indexing (the two [work quite well together][notmuch-mutt])
- [GNU Emacs][emacs] for all sorts of text editing, including coding
- [Git][] for versioning all sorts of text files
- [git-annex][] for sharing large files (e.g., backups, music, movies, pictures, etc) among computers. In my setup git-annex really shines at home, to share files between the NAS and other machines.
- [Org-mode][] as note tracker and TODO list manager (again, with [mutt integration](https://upsilon.cc/~zack/blog/posts/2010/02/integrating_Mutt_with_Org-mode/ "Stefano's article on using Mutt with Org-mode."))
- [Chromium][] for Web browsing (although I'm considering switching back to [Firefox][])
- [Pidgin][] and [irssi][] for chatting
- [OpenSSH][] (and more and more often [Mosh][]) to work remotely
- [Ikiwiki][] (with Git) for Web publishing
- [Ledger][] for accounting (again, with Git)

### What would be your dream setup?

Hardware-related dreams first.

I dream of a ThinkPad that doesn't need [non-free firmware](http://en.wikipedia.org/wiki/Binary_blob "The Wikipedia entry for Binary blob.") to get the Intel Wi-Fi working. Dear Intel, would you please give up on that, liberate your firmware, finally setting your users free?

The QNAP is a great NAS that is serving me well, but it is starting to feel slow for today's standards. I dream of a NAS in the same price range, with the same support for Debian, but [faster](https://wiki.debian.org/ArmHardFloatPort "A wiki entry about an ARM port of Debian."), without having to switch to more expensive server-grade machines like the great [HP's micro servers][proliant-microserver].

I dream of someone resurrecting the Squeezebox 3 line of products. Shame on Logitech for discontinuing them.

On the software side, I dream of the day I won't be "strongly encouraged" by my peers to run non-free software to interact with them. Currently the worst offenders in my social circle are [Skype][], centralized social network services (which not only exist primarily to eat your personal data, but also push loads of non-free software to your browser when you visit their websites), and [Flash][]. I dream of [better Free replacements](http://www.fsf.org/campaigns/priority-projects/ "A list of ongoing work to replace high priority software with free versions.") for all of those.

I dream of common keybindings throughout all the applications I use on a daily basis.

As a citizen of a [fairly accent-full country](http://en.wikipedia.org/wiki/France "The Wikipedia entry for France."), I also dream of accent-insensitive (or, more precisely: [diacritic](http://en.wikipedia.org/wiki/Diacritic "The Wikipedia entry for Diacritic.")-insensitive) text-search capabilities everywhere. It really is surprising to me how few applications are capable of returning as hits both "àéiôü" and "aeiou", when searching for the latter. Come on fellow software developers, it is not *that* difficult!

[chromium]: https://www.chromium.org/ "Open-source builds of the Chrome web browser."
[debian]: https://www.debian.org/ "A Linux distribution."
[emacs]: http://www.gnu.org/software/emacs/ "A free open-source text editor."
[firefox]: https://www.mozilla.org/en-US/firefox/new/ "A cross-platform open-source web browser."
[flash]: https://en.wikipedia.org/wiki/Adobe_Flash "A software and animation editor."
[git-annex]: https://git-annex.branchable.com/ "A tool for tracking the details of large files in git."
[git]: https://git-scm.com/ "A version control system."
[gnome-shell]: https://wiki.gnome.org/Projects/GnomeShell "A graphical interface for the GNOME desktop environment."
[gnome]: https://www.gnome.org/ "A desktop system for *nix operating systems."
[ikiwiki]: http://ikiwiki.info/ "A wiki tool based around a revision control system."
[irssi]: https://irssi.org/ "A CLI irc client."
[ledger]: https://ledger-cli.org/ "A command-line accounting system."
[model-s-ultimate]: http://web.archive.org/web/20170508162607/https://shop.daskeyboard.com/products/das-keyboard-ultimate-model-s "A USB keyboard with mechanical clicks."
[mosh]: https://mosh.org/ "A remote terminal shell system."
[mutt]: http://www.mutt.org/ "A command-line email client."
[notmuch-mutt]: https://notmuchmail.org/notmuch-mutt/ "A tool for using Notmuch with Mutt."
[notmuch]: https://notmuchmail.org/ "An email index and search tool."
[openssh]: http://www.openssh.com/ "A popular collection of SSH tools."
[org-mode]: https://orgmode.org/ "An Emacs mode for notes and to-do items."
[pidgin]: https://www.pidgin.im/ "An open-source multi-protocol chat client."
[proliant-microserver]: https://www.pcmag.com/archive/hp-proliant-microserver-256252 "A server."
[raspberry-pi]: https://en.wikipedia.org/wiki/Raspberry_Pi "A single-board hackable computer."
[raspbian]: http://www.raspbian.org/ "A version of Debian optimised for Raspberry Pi."
[shellshape]: https://github.com/timbertson/shellshape "A tiling window manager for GNOME Shell."
[skype]: https://www.skype.com/en/ "Voice and video chat software."
[squeezebox]: https://en.wikipedia.org/wiki/Squeezebox_(network_music_player) "A digital home audio server."
[thinkpad-t440s]: https://www.lenovo.com/us/en/ "A 14 inch PC laptop."
[ts-420]: http://web.archive.org/web/20160509091508/http://www.amazon.com/QNAP-TS-420-All-one-4-bay/dp/B00D2Y1EHE "A four-bay NAS."
