---
title: Ed Finkler
summary: Web developer (Gimme Bar, Spaz)
date: 2011-10-05
categories:
- developer
- linux
- mac
credits:
  name: Chris Shiflett
  url: http://www.flickr.com/photos/shiflett/4022501283/
---

### Who are you, and what do you do?

I'm Ed Finkler, but you may also know me as [funkatron](http://funkatron.com/ "Ed's website."). I've been a web developer for about 15 years now. Primarily I work in PHP, but most of my career I've been a one-man web team, so I have dabbled in everything from DB administration to backend dev to design. In the past few years I've gotten heavily into desktop and mobile application with [JavaScript][]. Four years ago I started a successful open source microblogging project called [Spaz][], for desktop and mobile. My day job is making awesome stuff at [FictiveKin](http://fictivekin.com "The company that makes Gimme Bar"), primarily on [Gimme Bar][gimme-bar].

### What hardware do you use?

I actually just bought a new 13-inch, Mid 2011 [MacBook Air][macbook-air]. It's probably the best laptop I've ever used: extremely light and quite fast (it has the 1.8Ghz i7 CPU). The problem is OS X 10.7: I don't think it's quite fully baked at this point, so I haven't transitioned it to being my main work machine (one of our team members had to downgrade back to OS X 10.6 because of this). A few minutes ago I kernel-panicked the machine by switching spaces. That, and the RAM is limited to 4GB, which does make a diff when you use virtual machines a lot.

My workhorse is a Mid 2010 15" [MacBook Pro][macbook-pro]:

- i7 2.66 Ghz
- 8GB RAM
- 256GB SSD
- 1680 x 1050 screen

For Gimme Bar we use a VM in [VirtualBox][] to act as our local development server. This makes the 8GB of RAM really, really useful, because that seems to be the threshold where you can run a reasonable VM and not notice performance degradation in your other apps. I've tried it at 4GB and it works, but you can notice issues. So I strongly recommend putting at least 8GB of RAM in your dev machine, especially since RAM is quite cheap. Best $100 you can spend.

The SSD has proven to be a major performance boost for the machine, especially on startup and initial login. I have a 2007 8-core [Mac Pro][mac-pro], and it is *exponentially* slower on startup. That's not just the CPU -- the disks (7200RPM SATA) are just far, far slower. If you can afford an extra $500 on your machine, I highly recommend getting an SDD. It makes things much more pleasant.

As I get old and my eyes start to crap out, I'm sorta less into high-res screens, but getting the higher-resolution screen on the 15" MacBook Pro was a really good idea. Most of my time is spent editing code, and I can reasonably open two windows of code next to each other. At the lower res (1440x900) you can't quite pull that off.

At home I have an aforementioned Mac Pro that is primarily involved in serving up video files to the HTPCs in the house, and a [Mac Mini][mac-mini] that acts as a backup server. I have a few large HDs hanging off the Mini to store backups. At some point I'd like to get a good NAS, but I struggle with spending $600+ for a pure backup box. This is probably stupid, I know.

Apple seems more and more douchebaggy as the years go on (maybe it was just easier to root for an underdog), so I am not necessarily excited about using their hardware anymore. Still, I find their combination of great build quality and an easy to use UNIX OS the recipe that makes me as productive as possible. I can't run OS X on anything else, and I can't stand postage stamp-sized trackpads anymore.

I do have a Lenovo [Thinkpad x201][thinkpad-x201] that I mess with from time to time. It has Ubuntu 11.04 on it right now. It's a very light, nice little machine that I'd probably take with me on trips if I could put OS X on it. Also the trackpad is atrocious, and the "nub" is a lot less versatile (no gestures). Alas.

My main phone is a [Palm Pre 2][pre-2]. I also have an [iPhone 4][iphone-4] that I don't use much, an [iPad 2][ipad-2], and a couple [HP TouchPads][touchpad]. I'm a big webOS fan.

I also collect old computers and game consoles, but this interview is already longer than it should be.

### And what software?

In the past 6 months, [Sublime Text 2][sublime-text] has become my primary code editor. It has a lot of similarities to TextMate, but it's being actively developed so it has some really nice additional features, like split windows, much better large file handling, and faster search across files.

[TextMate][] still has a bit more polish in some areas that I appreciate (especially the [JavaScript][] Tools bundle), and I do use it for a few tasks here and there.

I do a lot of still in the CLI, and [iTerm2][iterm2] is a great replacement for the standard Terminal. Split windows, hotkey bring-to-front, Quake-style drop down console, and [Growl][] support are all things I get a lot of use out of with iTerm2.

For both my personal projects and work, I use [git][] for version control almost exclusively. I try to convince you it's the best -- it's frequently a matter of finding the right incantation to do a particular thing -- but [GitHub][] is kind of a killer app, and so many others know how to use Git that it's a defacto standard. I do most of my git stuff in the CLI, but I do use the [brotherbard fork](https://github.com/brotherbard/gitx "A fork of GitX") of [GitX][] to do more complex commits.

We use [VirtualBox][] on Gimme Bar for setting up a common development environment, and it works really well. I also use VB for webOS virtual machines when developing Spaz. I do also use [Parallels Desktop][parallels-desktop] some, mainly so I can play Windows games (it's much faster than other VM options for this).

[Fake][] is a really great tool for automating browser activity -- sorta like having automator built into Safari, with a bunch of browser-specific actions. This makes it really good for building functional tests of web sites. This is how functional web testing should be done.

I use IRC a lot for collaboration and general buffoonery. [Linkinus][] is my preferred IRC client. It's not perfect, and the support is kinda weak in my experience, but it works pretty well and lets me navigate with the keyboard between channels. I've gotten so used to this that other clients drive me nuts.

We have daily stand-up meetings on Gimme Bar, and [Skype][] is pretty essential for this. We also use it for spot one-on-one meetings to hash out stuff. I've found voice communication really valuable when working remotely (our whole team is remote), so Skype is pretty key. If it wasn't available we'd probably use soothing else, but it works well enough. It's helpful to be able to forward calls to my mobile phone as well when I'm not near a computer.

I'm a paying [Dropbox][] customer (50GB), and while I don't use it all, I use it enough to make it really valuable. I sync all my project data between my machines with it, and being cross-platform really is helpful -- I can have my code on Linux, Windows and OS X machines. It also have served me well to fix stupid mistakes I make in-between git commits -- like blowing away a few hours of work. I do that too often.

For email I started using [Sparrow][] recently, because I really really love how it can take up far less space than most email apps. As I get older and more easily distracted, I find screen real estate to be more and more expensive.

I still use IM a lot, and [Adium][] has been my mainstay client for years. It's also an extremely good example of a successful open source application for end users.

For Twitter and Identi.ca, I of course use Spaz most of the time, but I'd be remiss in not mentioning [ttytter][], a terminal-based client written in Perl. I will often fire it up when I need a simpler, calmer interface for Twitter.

I'm writing the responses for this interview in [Notational Velocity][notational-velocity], which is a really nice, simple text editor for OS X. The SimpleNote-based syncing is killer for me, so I can read and edit documents on my Pre 2 with an app called Noted!.

I do less design work than I used to, because I realize on a daily basis how much I suck at it. However, when I was still kidding myself, I used [Adobe Fireworks][fireworks] for almost everything. I actually have been a user since 1.0, back when it was a Macromedia app. I don't know that it got better with Adobe, but at least they didn't kill it off. Lately I've been messing around with [Acorn][] to do some work, and it's a pretty solid tool.

For backups, I use [CrashPlan][], both for local LAN backups and online backups.

### What would be your dream setup?

I'm not sure that exists right now. The MacBook Air would be pretty unbeatable if it could take 8GB of RAM and had a larger HD -- I find 256GB *just* a little too small to carry everything I want with me. As it is, it's still the best laptop I've ever used -- probably the best computer I've ever used period. Stupid Apple.

If the MacBook Air could somehow also run Windows and play games really well, that would be pretty killer, because I like to game some and it doesn't really cut it for the stuff I'd like to play (mostly the Bioware RPGs and modern Fallout games). A nice dock-like thing with a big pretty screen and a keyboard/mouse would work well when I want to sit down and play on a bigger screen, but mostly I prefer to be on the couch or recliner when I am doing computer stuff. I've thought about buying a dedicated Windows box just for gaming, but that seems like a lot to spend on something I might not use very much.

In the end, it's really the dream of having one machine to rule them all, isn't it? And that just doesn't exist. Alas.

Actually, I just realized what my dream is: current Apple hardware (including phones and tablets) with the openness and easy-of-hackery that webOS devices provides (or provided). That's really not ever gonna happen, is it?

[acorn]: https://flyingmeat.com/acorn/ "An image editor for the Mac."
[adium]: https://en.wikipedia.org/wiki/Adium "A multi-protocol chat application for the Mac."
[crashplan]: https://www.crashplan.com/en-us/ "An online backup service."
[dropbox]: https://www.dropbox.com/ "Online syncing and storage."
[fake]: https://fakeapp.com/ "A web browser for the Mac designed for automation."
[fireworks]: https://creative.adobe.com/products/fireworks "A graphics and work tool for the Mac."
[gimme-bar]: http://web.archive.org/web/20180518235129/https://gimmebar.com/ "A web service for storing collections of things from the web."
[git]: https://git-scm.com/ "A version control system."
[github]: https://github.com/ "A Git code repository service."
[gitx]: https://gitx.frim.nl/ "A git GUI for Mac OS X."
[growl]: https://growl.github.io/growl/ "A notification system for Mac OS X."
[ipad-2]: https://www.apple.com/ipad/ "A tablet device."
[iphone-4]: https://en.wikipedia.org/wiki/IPhone_4 "A smartphone."
[iterm2]: https://iterm2.com/ "An alternative terminal application for Mac OS X."
[javascript]: https://en.wikipedia.org/wiki/JavaScript "An interpreted scripting language."
[linkinus]: https://en.wikipedia.org/wiki/Linkinus "An IRC client for Mac OS X."
[mac-mini]: https://www.apple.com/mac-mini/ "A small desktop computer."
[mac-pro]: https://www.apple.com/mac-pro/ "The Intel-based Mac tower computer."
[macbook-air]: https://www.apple.com/macbook-air/ "A very thin laptop."
[macbook-pro]: https://www.apple.com/macbook-pro/ "A laptop."
[notational-velocity]: https://notational.net/ "A clever note-taking app for the Mac."
[parallels-desktop]: https://www.parallels.com/products/desktop/ "A PC emulator for the Mac."
[pre-2]: https://en.wikipedia.org/wiki/Palm_Pre_2 "A webOS smartphone."
[skype]: https://www.skype.com/en/ "Voice and video chat software."
[sparrow]: http://www.gmail.com/intl/en/mail/help/sparrow.html "A mail client for the Mac with a funky UI."
[spaz]: https://getspaz.com/ "A microblogging client for Twitter, Identi.ca and Laconica."
[sublime-text]: http://www.sublimetext.com/ "A coder's text editor."
[textmate]: https://macromates.com/ "A text editor for the Mac."
[thinkpad-x201]: http://web.archive.org/web/20160511173457/http://shop.lenovo.com:80/us/notebooks/thinkpad/x-series/x201 "A 12.1 inch lightweight laptop."
[touchpad]: http://web.archive.org/web/20141217142055/http://www.hp.com/united-states/webos/us/en/tablet/touchpad.html "A webOS tablet."
[ttytter]: http://web.archive.org/web/20220813100822/https://www.floodgap.com/software/ttytter/ "A command-line Twitter client."
[virtualbox]: https://www.virtualbox.org/ "Open-source virtualisation software."
