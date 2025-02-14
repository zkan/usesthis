---
title: Daniel Cid
summary: Security researcher, developer (OSSEC)
date: 2012-12-06
categories:
- bsd
- developer
- linux
- security
---

### Who are you, and what do you do?

I am [Daniel Cid](http://dcid.me/ "Daniel's website."). I am current the CTO of a security company called [Sucuri](http://sucuri.net/ "Sucuri's website."). But don't let the title fool you, since we are a small company, I do real work and I spend most of my time doing malware analysis, security research and trying to recover compromised servers for our clients.

In the past, I founded the [OSSEC][] project (an intrusion detection system) and was the lead developer there for many years (2003-2011). In the meantime the project was acquired by Trend Micro in 2008 and I joined them and kept working solely on OSSEC until last year (2011).

### What hardware do you use?

I am well known for not using any fancy hardware (yes, people make fun of me because of that). For many years (until 2010), my main development server was a very old PIII with very little memory that I just used to [SSH][] in and do most of my work. It worked well and I took pride on being so backwards in time. I also had a SPARC server sitting under my feet that I used to help my posture and keep my feet up. It once got to more than 1,000 days without being shut down.

Unfortunately, the PIII died, so I had to buy a new one. The SPARC was very noisy and heavy, so I had to let it go.

Lately, I do all my work on my laptop (cheap HP Pavilion g) with 4G of ram. I don't even use desktops anymore and I store all my work on a remote dedicated server.

Another important part of my hardware setup is my keyboard and chair. I avoid using the mouse as much as possible and since I have back/neck problems, I use that funny looking kneeling chair and it helps tremendously with my posture. For my keyboard, I can't use anything but the [Apple keyboard][keyboard] (even though I don't use a Mac).

I am very lean in terms of hardware, and I don't even use a watch or cell phone or any of the fancy new tools that most tech people like. If you checked my site a week ago, it would still be all in ASCII.

### And what software?

I always ran [OpenBSD][] on both my servers and desktop, but when my old PIII died, I got lazy and just installed [Xubuntu][] on my laptop and have been using and enjoying it since. Very lightweight and simple. For my servers I have been using [Linux CentOS][centos].

Most of my development work is done in [C][], so I use the best combination that there is: terminal ([xterm][]) + [vim][] + [gcc][]. Even when I need to do [PHP][] work, I still use vim via the terminal.

For my servers, I keep the minimalistic setup, installing only the necessary. [Apache][] for web (using [Nginx][] as a proxy when necessary), PHP for dynamic content and [qmail][] for email serving. I also (obviously) run OSSEC every where and love to monitor and watch all the logs coming through.

I store every thing remotely and I use [sshfs][] (SSH file system) to access it and HG ([mercurial][]) for source control. That allows me to easily switch laptops without losing any data.

### What would be your dream setup?

I don't have much of a dream setup as long as everything works. But I would certainly like to have a more lightweight laptop that I could still use Xubuntu in there. Something like the [MacBook Air][macbook-air], but without the Mac :)

[apache]: https://www.apache.org/ "Web server software."
[c]: https://en.wikipedia.org/wiki/C_(programming_language) "A compiled programming language."
[centos]: https://www.centos.org/ "A Linux distribution."
[gcc]: http://gcc.gnu.org/ "Code compiler frontends."
[keyboard]: https://www.apple.com/us/shop/goto/mac/accessories "The keyboard."
[macbook-air]: https://www.apple.com/macbook-air/ "A very thin laptop."
[mercurial]: https://www.mercurial-scm.org/ "A version control system."
[nginx]: http://nginx.org/ "A very fast web/mail server."
[openbsd]: http://www.openbsd.org/ "An open-source operating system emphasising security and cryptography."
[ossec]: http://www.ossec.net/ "An open-source intrusion detection system."
[php]: https://www.php.net/ "An interpreted scripting language."
[qmail]: http://web.archive.org/web/20220803223549/http://qmail.org/top.html "An SMTP server."
[ssh]: https://en.wikipedia.org/wiki/Secure_Shell "A command-line tool for secure remote connections."
[sshfs]: https://code.google.com/archive/p/macfuse/wikis/MACFUSE_FS_SSHFS.wiki "An SSH file system for MacFUSE."
[vim]: https://www.vim.org/ "A command-line text editor."
[xterm]: https://en.wikipedia.org/wiki/Xterm "Terminal software for the X Window System."
[xubuntu]: https://xubuntu.org/ "A lightweight version of the Ubuntu distribution."
