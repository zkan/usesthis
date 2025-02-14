---
title: Aaron Boodman
summary: Developer (Greasemonkey, Google Chrome)
date: 2010-12-26
categories:
- developer
- linux
- mac
- windows
---

### Who are you, and what do you do?

I'm [Aaron Boodman](http://www.aaronboodman.com/ "Aaron's website."), a software engineer. I am probably best-known for having created [Greasemonkey][]. I currently work on Google Chrome. In particular, I lead development of its [extension system](http://code.google.com/chrome/extensions/index.html "Information on Chrome's extension system.").

### What hardware do you use?

I have kind of an embarrassing amount of hardware.
 
Though Chrome is known for feeling fast and light to run, it's quite tubby to build. You need a lot of computer to work on it effectively. Luckily, uncle Goog keeps us well-provisioned.
 
My main setup at work is:
 
*  Linux: HP [Z600][] running Lucid Lynx. 2x Quad-core Xeon @ 2.27 GHz, 12 Gb RAM.
*  Windows: HP [Z600][] running [Vista][windows-vista]. 2x Quad-core Xeon @ 2.27 GHz, 12 Gb RAM.
*  OS X: [Mac Pro][mac-pro] running Snow Leopard. 2x Quad-core Xeon @2.26 GHz, 12 Gb RAM.
 
My main workstation is the Linux box. But since Chrome has native UI on each of its platforms, I do need to work and test on all three of these machines regularly.
 
I have a single 30" flat-screen monitor and a generic keyboard/mouse that I share between all three systems.
 
I went through a number of 3-port KVMs and they all sucked. I finally gave up and have a Belkin 2-port that I used to switch between Linux and Mac. I use Microsoft Remote Desktop to reach the Windows machine using the Linux rdesktop client.
 
I like to work from home a fair amount. For that, I have a [Levono T61][thinkpad-t61] running Lucid that I use as a dumb terminal to my Linux and Windows workstations. I have found that remoting into Mac is too slow and crappy to be worthwhile. If I need to do mac work, I go into the office.
 
I have the usual nerd collection of phones, iPods, Kindles, etc. I have a [Cr48][cr-48].

### And what software?

The constraints that have shaped my software setup are:
 
*  I learn my tools deeply, so I want to use the same ones on all my machines. I don't like having to switch between different sets of tools when I switch machines.
*  I like being able to work remotely, from home, a coffee shop, or wherever else. When I do this, I want to use the same setup I use at work.
*  I can't stand slow software. Anything that takes a while to boot, or has unresponsive UI gets weeded out of my setup quickly.
 
Over time, those constraints have whittled my work environment down to the following simple tools:
 
*  [Ubuntu Linux][ubuntu]
*  [emacs][] -nw (terminal mode)
*  [Screen][]
*  [Irssi][]
*  [Git][]
 
I like Linux because it's a fast, reliable, and stays out of my way. Also, because the rest of the tools I like work best on it.
 
I use emacs -nw because it is faster than the GUI verison, particularly when used remotely. Also, I rarely use my mouse, so I don't miss the GUI.
 
I run my sessions under screen so that I can connect to them remotely and resume where I left off. If you are from a non-unix background like me, you might not be familiar with the [wonders of screen](http://lizzie.spod.cx/screenirssi.shtml "A tutorial for using irssi with screen."). I highly recommend investing some time in learning it.
 
I tried many linux IRC clients, and they were all terrible. The worst problem was that I would miss conversations while I was offline. When I realized I could run a text-mode IRC client under screen, it changed my life. Now I just leave it running on my workstation, and connect to it from anywhere. I never miss anything.
 
Finally, I list Git here because it is my favorite new tool. It is so fast, reliable, and flexible. I love working on bunches of different things at once, and using branches to switch between them. When I have to test something on Mac or Windows, I love being able to [pull](http://www.kernel.org/pub/software/scm/git/docs/git-pull.html "Docs for the git-pull command.") my work from my Linux machine with a single command, then [push](http://www.kernel.org/pub/software/scm/git/docs/git-push.html "Docs for the git-push command.") it back with changes later.
 
Git also has great features for understanding your work's history. For example, I frequently reach for [pickaxe](http://gitfu.wordpress.com/2008/06/03/the-pickaxe-finding-changes-was-never-easier/ "Docs for the pickaxe command in git.") to understand when a particular change was introduced, even if it has moved around a lot.
 
I've used more complex tools like visual IDEs in the past. They have some nice features, but they tend to be slower, more crashy, require extensive setup, and not work well remotely. Over time, I realized they are a net loss to my time and energy.

### What would be your dream setup?

I'm pretty happy with what I have, within the constraints of reality.
 
If we're willing to throw that out, I'd love to be able to work on Chrome for Windows, Mac, and Linux all from a lightweight netbook. The compiles would be happening on some remote cluster somewhere.
 
And if we're talking super crazy, I'll take the [thought-controlled software and wireless brain connection](http://chris.wanstrath.usesthis.com/ "Our interview with Chris Wanstrath."), too, please.

[cr-48]: https://en.wikipedia.org/wiki/Chromebook "Google's first Chrome OS netbook."
[emacs]: http://www.gnu.org/software/emacs/ "A free open-source text editor."
[git]: https://git-scm.com/ "A version control system."
[greasemonkey]: https://addons.mozilla.org/en-US/firefox/addon/greasemonkey/ "A Firefox add-on to inject Javascript into sites for customisation."
[irssi]: https://irssi.org/ "A CLI irc client."
[mac-pro]: https://www.apple.com/mac-pro/ "The Intel-based Mac tower computer."
[screen]: http://www.gnu.org/software/screen/ "Think of it as tabs for your *nix terminal."
[thinkpad-t61]: https://www.cnet.com/reviews/lenovo-t61-review/ "A 14 inch PC laptop."
[ubuntu]: https://ubuntu.com/ "A Unix distribution."
[windows-vista]: https://en.wikipedia.org/wiki/Windows_Vista "A desktop operating system."
[z600]: https://www.amazon.com/HP-Z600-Workstation-Quad-2-13GHz/dp/B003H0KZ6E "A powerful PC workstation."
