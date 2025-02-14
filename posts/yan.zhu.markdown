---
title: Yan Zhu
summary: Staff Technologist (Electronic Frontier Foundation)
date: 2014-06-24
categories:
- developer
- linux
---

### Who are you, and what do you do?

Hi, I'm Yan. My current title is Staff Technologist at the [Electronic Frontier Foundation](https://www.eff.org/ "The EFF's website.") in San Francisco. This means I write code and sometimes words to protect Internet users from corruptible entities, such as corporations and governments. I like information freedom, the right to privacy, theoretical physics, cryptography, free software, and an Internet that respects humans. I dislike consentless power structures.

As part of the [Tor Project][tor], I maintain a browser security and privacy extension called [HTTPS Everywhere][https-everywhere] that forces encrypted connections to websites. Lately I've also been writing a Firefox extension called [Privacy Badger][privacy-badger] to block invisible third-party trackers on the web. Sometimes I push code to [SecureDrop][], an anonymous document submission platform for whistleblowers.

All of my work is free and open-source.

In past lives, I've been a writer, a freelance composer/arranger, a web security auditor, and an engineer of various things (batteries, rockets, telescopes, websites, immense vegan dinners). I got my B.S. from MIT in Physics and briefly worked on experimental tests of quantum gravity at Stanford for my (unfinished) PhD.

### What hardware do you use?

Ownership, particularly when it involves attaching emotion to physical objects, frequently strikes me as weird. As a remedy, I optimize for hardware that falls just a hair short of inspiring joy.

My work laptop is a [ThinkPad X1 Carbon][thinkpad-x1-carbon]. I maxed out the RAM to 8GB but overall it's just your average ThinkPad X1 Carbon. My other laptop is a memory-starved, glacierlike [ThinkPad X220][thinkpad-x220] from college, which I still love for its delightfully percussive keyboard and resilience to physical brutality. People often underappreciate the charm of a laptop that will survive a rappel down the side of a 20-story building if one is required.

Until last summer, I refused to own a smartphone. Then the pressures of ambulatory navigation in unfamiliar geography convinced me to purchase a secondhand [Galaxy Nexus][galaxy-nexus] from a friend. At this point, the screen has suffered enough damage that I am frequently offered new smartphones as a charity service.

I found a [ZTE Open][open.2] phone running [Firefox OS][firefox-os] in my office the other day. After charging it and turning it on, I crashed it twice in five minutes. It's definitely a candidate for future frustration - I mean exploration.

About a year ago, someone convinced me to buy a [Kindle Paperwhite][kindle-paperwhite]. As I was flying into SFO last week, I accidentally left it as a sacrificial offering to the Gods of Air Travel on their favorite shrine, the Seatback Pocket. I expect to never see it again, which is just as well for fighting DRM.

I don't have much else. A couple USB sticks for encrypted backups, a borrowed Bluetooth dongle for traffic sniffing, a server in Iceland, and a large monitor that currently lives at a friend's house down the street. I move around a lot and was nomadic for most of the past year, so I've tried to keep my possessions minimal.

A couple other things perpetually near my body that are not-technically hardware but certainly integral for making life not suck are (1) [a folding bike][mu-p8] that serves as my main form of transportation in San Francisco, (2) [a durable backpack][the-rambler] that fits a laptop + climbing gear + extra clothes + groceries, and (3) [a multitool][skeletool] for those unexpected situations that call for superb mechanical advantage.

### And what software?

My main laptop runs [Debian][] Testing ("Jessie"); as a result, I have gotten really good at ignoring lack of functionality that laptops generally have.

For years, I refused to use any window manager except [xmonad][]. A few months ago, after 45 minutes of failure to achieve a usable state with it on Debian Testing, I switched over to [Awesome][] with custom keybindings to make it behave like vanilla xmonad. So far, I'm satisfied.

I use [urxvt][rxvt-unicode] as my terminal emulator, [tmux][] for multiplexing, and [fish][] for my shell. I do all my coding and text editing in [Vim][]; if you're curious, you can find my configurations in [https://github.com/diracdeltas/dotfiles](https://github.com/diracdeltas/dotfiles "Yan's dotfiles on GitHub."). As someone who writes a lot of [JavaScript][], I find [JSHint][] invaluable. I like looking at colors, and the [Solarized][] theme for urxvt and vim has some nice ones.

For email, I primarily use [Thunderbird][] with [Enigmail][] configured to GPG-encrypt messages whenever possible. (I have used [Mutt][] on-and-off but am frankly intimidated by the Herculean configuration process.) I try to hand as little of my data over to Google as possible, so my [Gmail][] account mostly exists for collecting spam.

My phone runs [CyanogenMod][] without any Google applications, including the Google Play Store. As a result, it is not a very useful phone.

I do all of my web browsing in [Firefox][] unless I'm developing or testing something for [Chrome][]. I'm one of the more enthusiastic people you'll ever meet when it comes to talking about Firefox add-ons, so here's the ones that I use on a daily basis:

1. HTTPS Everywhere for improving web security and reducing the risk of governments passively collecting all my web traffic. Disclaimer: I make this.

2. Privacy Badger for automatically detecting and blocking requests from third parties that are tracking me on the web. Disclaimer: I make this too.

3. [NoScript][] for making XSS and malicious code execution from untrusted sites less likely. Incidentally, NoScript is also a great way to speed up page loads on sites that throw you a lot of gratuitous JavaScript when all you want is to read about how global warming is going to destroy us all in 30 years.

4. [Adblock Plus][adblock-plus] for hiding annoying ads.

5. [Vimperator][] so that Firefox behaves like Vim, of course.

6. [Firebug][] and [JS Deminifier][JavaScript-deminifier] for finding security holes in websites.

### What would be your dream setup?

Let's start with the easy ones. I would like (1) an e-book reader that has the portability and battery life of a Kindle, runs free software out-of-the-box, and doesn't support DRM; (2) an open-source maps application for [Android][]/CyanogenMod that can provide biking and public transit directions for any city that I happen to be in; and (3) a usable open-source password manager that syncs to mobile devices, integrates with browsers, and meets some set of minimum security requirements. (I'll work on the latter if someone else does the first two.)

Slightly more ambitious: every device should come with root access for the user if they want it. Going down the stack, it would be nice if all computing devices by default ran a [free BIOS](https://www.fsf.org/campaigns/free-bios.html "An article about the benefits of a free BIOS.") and other free firmware on top of easily-modifiable, open hardware.

Respecting the autonomy of users by allowing them to understand and modify their devices is crucial for creating widespread technical literacy and, subsequently, a world in which ordinary people can detect when their rights are being threatened by technology providers and governments. I have a crazy dream that, someday, ordinary families will sit down at their kitchen tables to install software updates together and read the change logs aloud over breakfast.

Shooting for the stars now: let's design computers so that software engineering doesn't force us to occupy constrained, mostly-immobile positions in florescent-lit rooms for 8+ hours every day. I'd like to code and go backpacking at the same time.

[adblock-plus]: https://adblockplus.org/ "Browser extensions for blocking ad content."
[android]: https://developers.google.com/android/?csw=1 "A mobile phone platform."
[awesome]: https://awesomewm.org/ "A window manager for X."
[chrome]: https://www.google.com/intl/en/chrome/ "A WebKit-based browser, where each tab runs in its own thread."
[cyanogenmod]: http://web.archive.org/web/20161225043707/https://www.cyanogenmod.org/ "A custom ROM for Android phones."
[debian]: https://www.debian.org/ "A Linux distribution."
[enigmail]: https://enigmail.net/index.php/en/ "An extension for Thunderbird that enables GPG-encrypted emailing."
[firebug]: https://getfirebug.com/ "A Firefox addon for web development."
[firefox-os]: https://support.mozilla.org/products/firefox-os "An OS for smartphones."
[firefox]: https://www.mozilla.org/en-US/firefox/new/ "A cross-platform open-source web browser."
[fish]: https://fishshell.com/ "A command-line shell."
[galaxy-nexus]: http://web.archive.org/web/20210205175044/http://www.google.com/nexus/ "An Android-based smartphone."
[gmail]: https://mail.google.com/mail/u/0/ "Web-based email."
[https-everywhere]: https://www.eff.org/https-everywhere/ "A browser extension for ensuring secure web browsing."
[javascript]: https://en.wikipedia.org/wiki/JavaScript "An interpreted scripting language."
[jshint]: https://jshint.com/ "A service for finding issues with your Javascript."
[kindle-paperwhite]: http://web.archive.org/web/20230502144520/https://www.amazon.com/Kindle-Paperwhite-Touch-light/dp/B007OZNZG0 "An e-book reader with a book-like screen."
[mu-p8]: https://dahon.com/?p=3111 "A foldable bicycle."
[mutt]: http://www.mutt.org/ "A command-line email client."
[noscript]: https://noscript.net/ "A Firefox extension for whitelisting scripting content."
[open.2]: https://en.wikipedia.org/wiki/ZTE_Open "A Firefox OS smartphone."
[privacy-badger]: https://privacybadger.org "A browser extension for blocking trackers and ads."
[rxvt-unicode]: http://web.archive.org/web/20170301142616/https://en.wikipedia.org/wiki/Rxvt-unicode "A colour terminal emulator for X Windows."
[securedrop]: https://securedrop.org "A submission system for whistleblowers."
[skeletool]: https://www.leatherman.com/skeletool-18.html "A stainless steel multi-tool."
[solarized]: https://ethanschoonover.com/solarized/ "A colour theme for text editors."
[the-rambler]: http://transportr.io/redirect/bd0c202b-d59c-45f4-b5ba-eb35e4f5f0e5 "A water-resistant backpack."
[thinkpad-x1-carbon]: https://www.lenovo.com/us/en/laptops/thinkpad/thinkpad-x/ThinkPad-X1-Carbon-5th-Generation/p/22TP2TXX15G "A lightweight PC laptop with a 14 inch screen."
[thinkpad-x220]: http://web.archive.org/web/20170206231919/http://shop.lenovo.com/us/laptops/thinkpad/x-series/x220 "A 12.5 inch PC laptop."
[thunderbird]: https://www.thunderbird.net/ "An open-source cross-platform mail client."
[tmux]: https://sourceforge.net/projects/tmux.mirror/ "A terminal multiplexer, similar to screen."
[tor]: https://www.torproject.org/ "A software and network package for protecting your anonymity."
[vim]: https://www.vim.org/ "A command-line text editor."
[vimperator]: http://vimperator.org/vimperator/ "A Firefox extension for adding vim-like keyboard shortcuts."
[xmonad]: https://xmonad.org/ "A tiling window manager for X11."
