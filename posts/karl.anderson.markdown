---
title: Karl Anderson
summary: Software engineer, phone hardware hacker
date: 2015-02-17
categories:
- developer
- linux
- mac
---

### Who are you, and what do you do?

I'm [Karl Anderson](http://monkey.org/~kra/ "Karl's website."). I help run [Futel](http://futel.net/ "A free phone company."), a free phone company. I'm a software engineer for [Duo Security][duo]. I make post-apocalyptic training installations with members of [Dorkbot PDX](http://dorkbotpdx.org/ "A group of people having fun with electricity.").

### What hardware do you use?

I use a 12.5" [ThinkPad X220 laptop][thinkpad-x220]. It's small and it has a full-size mechanical keyboard, and it's underpowered and not too valuable. The important feature is that I can throw it in my backpack and pull it out on the couch or a dark corner of the bar, so it gives me time to work. Nothing special. I love it like I love my bike and my space heater (which are similarly covered with stickers). It's a tool that's very familiar to my hands. It's a mistake to get sentimental about a computer. At work I get to use a sweet large [MacBook Pro][macbook-pro] with a lot of memory so I can do things in several virtual machines at once and talk with my co-workers at the same time. I'm not sentimental about it, not sure why. I lose myself in it as much as I lose myself in my own laptop.

This means that I'm usually lugging around two laptops, a book, a newspaper, and a toolkit, raincoat, and extra layers, because I get around by bike or motorcycle. I sometimes feel like a dork because I don't travel light.

I have some desktop computers and disks to do long-running tasks like serve files, backup my laptop, and scrape the web. I'm just glad that I can put it in the closet and interface with a quiet laptop that doesn't involve a CRT and spinning drives.

I have an obsolete [Android][] phone that I don't use much because it's horribly slow and I don't trust it anyway, but I can't justify spending hundreds of dollars on whatever phone is current these days. The phone doesn't really matter, I mention it because I use it for two-factor authentication. They don't let me use it to authenticate at work, because it's too old, so I use a [Yubikey][] for that. I keep it in my work laptop, so the laptop is basically a dongle. I respect it and treat it securely. I don't respect my phone, it has apps on it that I can't uninstall. It's trying to tell me what I should be thinking about. I should probably get a phone I can root.

When I'm at the office, which is most of my screen time, or working for a while at home, I use a second monitor, a Goldtouch split keyboard, a thin keyboard tray with negative tilt, a [GeekDesk][] sit-stand desk, and a Steelcase chair. A setup that fits me is the most important thing about my hardware, because I have to be careful about RSI. I'm supposedly overdue for carpal tunnel surgery, and a doctor also said I'll want to have my neck sawed open someday, probably because I've crashed into too many things on my bike. I should use my laptop a lot less.

Futel runs on payphones we get off Craigslist, [Linksys WRT54G routers][wrt54g] and Linksys SIP adapters we get off eBay and thrift stores, and old laptops, as well as cables, conduit, hardware, and concrete, and lots of other scrounged crap. We're cheap. And rented cloud machines, I assume those run on enslaved human brains or something.

The hardware hacking I do mostly runs on the [Teensy][], an [Arduino][]-compatible platform, and various bent devices and other junk. I know hardly anything about hardware. This is a great time for people like me to mess around with it, because it's so easy to do jump in and start with simple things.

### And what software?

I spend most of my screen time in [Emacs][], in terminal and editor buffers, whether on my host OS or a virtual box. My personal laptop is an [Ubuntu][] box, which I don't like that much, but I spent too much time in my youth figuring out what OS to run and how I wanted to configure it. Seriously, I used to make my own menu bars, now I wonder why I bothered. My work Mac is set up however my co-workers tell me to, because they're more paranoid and knowledgeable than I am. The Mac constantly annoys me for different reasons than the Ubuntu box, but so long as I the important setup is in a VM, I don't have to worry about it much.

Futel is basically a VoIP service implemented with [Asterisk][] and [OpenVPN][] and a lot of scripts. We use [DD-WRT][] on routers because we can use cheap hardware, and because we can put an OpenVPN client directly on the router. We want to expose as little Asterisk as possible. When we put an Asterisk box directly on the net, kids immediately start trying to break in and make toll calls or resell service or DDOS numbers or whatever they want to do with VoIP services these days. We can't re-flash the SIP boxes, so we're at the mercy of whatever firmware they have, and they're often carrier-locked, so we have to be careful when buying them. It's evil, a lot of energy went into making those chips, and now they're worthless because some defunct corporation didn't want us to use their hardware long after they were dead.

### What would be your dream setup?

I want to answer this question with some Stanisław Lem scenario. Interacting with computers is the dreamtime, because people are on the other side of that abstract space, and we're letting that space change how we interact with them. It's made out of words, it's poetry. But it's a stupid dream, because the real world is out there too, with real people to interact with.

It's the same nightmare I have once in a while when I'm asleep, where I'm moving in slow motion, or I'm building towers and then the plot changes and I need to be digging ditches. Forget the hardware, I'll fall out of love with it tomorrow. The only feelings I have for the hardware come from how it gets out of my way. I just want to work towards achieving my objectives. In my dreams, I'm twenty-three again, stronger and less wise. I used to be able to hack for seventeen hours straight, and in my dreams I can do that again.

[android]: https://developers.google.com/android/?csw=1 "A mobile phone platform."
[arduino]: https://www.arduino.cc/ "Open-source prototyping hardware."
[asterisk]: https://www.asterisk.org/ "An open source VoIP framework."
[dd-wrt]: https://dd-wrt.com/site/index "A alternative Linux-based firmware for routers."
[duo]: https://duo.com/ "A two-factor authentication service."
[emacs]: http://www.gnu.org/software/emacs/ "A free open-source text editor."
[geekdesk]: https://www.geekdesk.com/ "An electronic, height-adjustable desk."
[macbook-pro]: https://www.apple.com/macbook-pro/ "A laptop."
[openvpn]: https://openvpn.net/community/ "Open source VPN software."
[teensy]: https://www.pjrc.com/teensy/ "A USB microcontroller board."
[thinkpad-x220]: http://web.archive.org/web/20170206231919/http://shop.lenovo.com/us/laptops/thinkpad/x-series/x220 "A 12.5 inch PC laptop."
[ubuntu]: https://ubuntu.com/ "A Unix distribution."
[wrt54g]: https://www.linksys.com/support "A wireless router."
[yubikey]: https://www.yubico.com/setup/ "A USB-based tool for generating one-time passwords."
