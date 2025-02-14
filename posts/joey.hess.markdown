---
title: Joey Hess
summary: Software developer (Debian, git-annex)
date: 2012-10-30
categories:
- developer
- linux
---

### Who are you, and what do you do?

I'm [Joey Hess](http://joeyh.name/ "Joey's website.") and I write programs.

Lately I've been focusing on programs that encourage broader use of version control systems, like [git][]. The goal is to harness all the power that's been developed by developers for developers for managing source code, and redirect it to other purposes. So I've built [etckeeper][] (managing /etc with git, for sysadmins), [ikiwiki][] (wikis and blogs in git), and [git-annex][] (applying git to very large files). I'm funded by a Kickstarter project in 2012-2013 to build something not unlike [DropBox][], based on git-annex, that automatically version controls and syncs files between computers.

I'm also a long-time [Debian][] developer, having been involved in building the Debian installer, and I run a 30-year delayed Usenet feed at [olduse.net](http://olduse.net/ "A time-delayed Usenet feed.").

### What hardware do you use?

I do everything on a netbook, a [Dell Mini 9][inspiron-mini-9]. I've been using it since 2008, and have worn out two keyboards. (The down arrow key is always the first to go.) I like the Mini's small size, easy access to expansion slots, and lack of any breakable moving parts other than the keyboard and hinge. I particularly need my laptop to be silent; no fan become a requirement for me years ago, around the time I stopped using desktop computers.

I've upgraded the netbook's SSD, of course, and recently had to upgrade from 1 GB to 2 GB of memory because the linker needed more. Otherwise, my needs are modest, and if I need a faster computer I'll log into one remotely. I have three remote servers of my own (most of them are really virtual machines), as well as access to quite a lot of others for various projects.

I don't use a desk. I work in five or six different places and postures around the house. When the weather's good, I'm outside, or on the porch. My preferred "desktop background" is some interesting view in back of my netbook's rather small screen.

I don't habitually use any cell phones or tablets. If it doesn't have a keyboard, I feel that my thoughts are being forced out through a straw. The only other active computer in the house is my home server and internet gateway; a [Sheevaplug][] with a wireless dongle and a dialup modem.

This place is nicely remote, and off the grid, relying on solar power. I only get 50 amp-hours of juice on a sunny day, and often less than 15 amp-hours on a bad day. So the whole house runs on 12 volt DC power to avoid the overhead of an inverter; my laptop is powered through a succession of cheap vehicle power adapters, and my home server runs on 5 volt power provided by a USB adapter.

When power is low, I often hack in the evenings by lantern light.

### And what software?

I run Debian unstable on my laptop and most of my servers. I have one production web server that runs Debian stable instead, but mostly I can deal with any day-to-day glitches that come up using Debian unstable. I've used nothing else since 1996.

I use the [XFCE desktop environment][xfce], with the [Xmonad][] window manager. My editor is [vim][], and my web browser is [chromium][]. I mostly use a bunch of terminal emulators, of course, although my netbook's low screen resolution limits me to seeing one full-size terminal, and two reduced size ones at one time. I struggled with finding window layouts that work in this low screen resolution, but eventually [developed several](http://joeyh.name/blog/entry/xmonad_layouts_for_netbooks/ "Joey's post on xmonad layouts.") and am rarely bothered by it now.

These days I'm mostly programming in [Haskell][], having spent the past 5 years going through that painful but eye-opening learning curve. Most of the code I maintain is [Perl][], [C][], and shell script, but I'd just as soon use Haskell for anything new. I've gradually became a big fan of Haskell; I feel it makes me write much more solid code that is much easier to maintain and refactor. But the best part is there are seemingly no end of things to learn in the Haskell space.

I seem to live half the time out of range of broadband, and still use dialup since bouncing the internet off a satellite has too much latency, and no better total aggregate bandwidth. So I'm fully adapted to asynchronous communication. I download my mail with [offlineimap][], as well as blogs converted to mail with [rss2email][] I use distributed version control extensively, and use my git-annex to maintain large quantities of local data and queue up large files to transfer in the rare times when I'm around fast internet.

Other notable software includes the [Music Player Daemon][mpd], which runs on my netbook and also my home server. And the excellent [Redshift](https://launchpad.net/redshift) application, which adjusts the screen color temperature depending on the time of day and preserves my night vision. And I should mention that I'm using [Obnam][] for backups lately.

### What would be your dream setup?

I dream of a ARM-based netbook with exceptionally good battery life, an E-ink display, and fully open and non-proprietary hardware. I've put off upgrading for years since this seems such an obvious thing for the market to produce, but the market is fascinated with locked-down tablets instead.

[c]: https://en.wikipedia.org/wiki/C_(programming_language) "A compiled programming language."
[chromium]: https://www.chromium.org/ "Open-source builds of the Chrome web browser."
[debian]: https://www.debian.org/ "A Linux distribution."
[dropbox]: https://www.dropbox.com/ "Online syncing and storage."
[etckeeper]: http://joeyh.name/code/etckeeper/ "A tool for managing /etc with git."
[git-annex]: https://git-annex.branchable.com/ "A tool for tracking the details of large files in git."
[git]: https://git-scm.com/ "A version control system."
[haskell]: https://wiki.haskell.org/Haskell "A functional programming language."
[ikiwiki]: http://ikiwiki.info/ "A wiki tool based around a revision control system."
[inspiron-mini-9]: https://outlet.us.dell.com/ARBOnlineSales/Online/InventorySearch.aspx?brandid=2201&c=us&cs=22&l=en&s=dfh&frid=127 "A 9 inch netbook."
[mpd]: https://mpd.fandom.com/wiki/Music_Player_Daemon_Wiki "A music playing server."
[obnam]: https://liw.fi/obnam/ "A backup tool."
[offlineimap]: https://www.offlineimap.org/ "A tool for syncing mail from an IMAP server."
[perl]: https://www.perl.org/ "An interpreted scripting language."
[rss2email]: http://web.archive.org/web/20221113013814/http://www.allthingsrss.com/rss2email/ "A tool for delivering news from RSS feeds to an email address."
[sheevaplug]: https://en.wikipedia.org/wiki/SheevaPlug "A plug computer with a tiny footprint."
[vim]: https://www.vim.org/ "A command-line text editor."
[xfce]: https://www.xfce.org/ "A lightweight UNIX-like desktop environment."
[xmonad]: https://xmonad.org/ "A tiling window manager for X11."
