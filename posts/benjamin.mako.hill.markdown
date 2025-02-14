---
title: Benjamin Mako Hill
summary: Social scientist, free software hacker (MIT)
date: 2012-04-11
categories:
- hacker
- linux
- social
---

### Who are you, and what do you do?

I'm [Benjamin Mako Hill](http://mako.cc/ "Benjamin's website.") and I'm a rebel with rather too many causes. I'm a social scientist and PhD student at MIT studying [free culture](http://freedomdefined.org/Definition "The definition of 'free culture'.") and [free software](https://www.gnu.org/philosophy/free-sw.html "The definition of 'free software'.") communities: my dissertation is on the sociology of attracting contributors to free culture projects. I'm also a hacker on a bunch of free software projects, a writer, and a [blogger](http://mako.cc/copyrighteous/ "Benjamin's weblog."). In various ways, I've been involved with [Debian][], [Ubuntu][], [Wikipedia](https://en.wikipedia.org/wiki/User:Benjamin_Mako_Hill "Benjamin's Wikipedia user page."), [One Laptop per Child](http://one.laptop.org/ "The One Laptop Per Child project."), and the [Free Software Foundation](http://www.fsf.org/ "The Free Software Foundation.").

### What hardware do you use?

My laptop is the venue for most of my work, most of my hobbies, and (on many days) most of my social life. At the moment, I use a [Lenovo Thinkpad X201][thinkpad-x201]. Before that, it was a X61s, an X40, an X31, and an X20. See the pattern?

My laptop needs to be lightweight because I carry it everywhere. It needs to be rugged because I throw it in my backpack without one of those laptop wetsuits or other padding. It needs to have [hardware with Linux drivers](http://www.thinkwiki.org/wiki/ThinkWiki "A wiki based on installing *nix on a ThinkPad.") because I don't use anything else. It needs to have a solid keyboard because I type quickly and only rarely use a pointing device. In terms of these requirements, the Thinkpad X-series are the only laptops I've ever been completely happy with.

When I need a new laptop, I buy the fastest X-series laptop available (my current laptop is an i5 M540) and max out the RAM (currently 8GB). I have a solid state drive and it is the best change to my computing hardware I've made in a decade in terms of speed, ruggedness, and reliability. I can't imagine going back. I'm rough on my hardware so I usually have major repairs once or twice before Lenovo's 3-year warranty expires. After the warranty expires, I watch for sales and buy a new one when I see a good deal. I buy directly from Lenovo, pay the [Windows Tax](https://en.wikipedia.org/wiki/Windows_refund#The_.22Windows_tax.22 "A Wikipedia entry on the 'Windows Tax.'"), and am deeply annoyed by the fact that I am forced to repeatedly buy a proprietary operating system I do not boot even once.

At my desk, I've got a docking station, a 27-inch [Dell Ultrasharp U2711][u2711] monitor and a pair of old [Bose MediaMate][mediamate] speakers; I own two sets, love their sound for classical and jazz, and can put up with it for everything else.

At home, I have a special edition [Model M][model-m] keyboard with a trackpoint. I love that keyboard and don't know where to get a new one. It's on my list of things to carry out of my burning house. I've used Model Ms for 20 years now and I type harder than anyone else I know. The college police department once showed up at my dorm room to investigate a noise complaint at 4AM. It was me typing. No joke. On the road, I sometimes use a [Happy Hacking keyboard][happy-hacking-keyboard] to allow for better posture.

The computer in my pocket is currently an [HTC Sensation][sensation]. It it is the latest in a series of [Android][] developer phones by HTC I've moved through. I don't find it particularly sensational but I primarily use my phone as a place to tether my laptop and, believe it or not, make phone calls, and it does that just fine.

I carry around a hacked [Kindle DX][kindle] (graphite) I use exclusively for reading academic papers as PDFs. I am very worried about Amazon's apparent plan to repurpose Stallman's dystopian short story The Right to Read as a business model and have not (and will not) buy a book that is [defective by design](http://www.defectivebydesign.org/ "A site about the drawbacks of DRM."). But although I don't want to support Amazon, I'm also worried about the cost and environmental impact of printing 7000+ pages of papers a year (which I did before I got the Kindle). On the bright side, it seems that buying the Kindle, turning off the Whispernet, and then never buying a book from Amazon, is a great way to make sure that Amazon loses money and that the battery only needs to be recharged once a month.

I execute most CPU cycles on a cluster at the [Harvard MIT Data Center](http://hmdc.harvard.edu/ "The data analysis center for MIT.") where I burn 60 kilograms of coal running statistical jobs overnight. I feel quite bad about this and try not to do it often. Because I outsource most CPU and memory intensive jobs to Harvard and MIT clusters, the power of the computers I actually sit in front of does not matter much to me.

### And what software?

My laptop runs [Debian][] "sid" (i.e., unstable). With a two year break around 2004 when I used (and helped start) [Ubuntu][] -- and an ill-conceived 1-month tryst with [the HURD][hurd] in college -- I've been using Debian on the desktop since the early nineties when I graduated from both [Slackware][] and middle school. To the extent that Ubuntu is Debian, I've never even seriously considered using anything else since.

I actively maintain and use three servers: two run Debian stable and one Ubuntu LTS (all are now [Xen][] VMs). I'm both a Ubuntu Core Developer and a Debian Developer and I think it's important to actively use software you maintain so I want to keep machines running both operating systems around. I keep development and stable chroots of both Debian and Ubuntu on my laptop to build and test packages.

In terms of my desktop software, I've used [FVWM][], [AfterStep][], [WindowMaker][window-maker], [Enlightenment][], [BlackBox][], [FluxBox][], and [GNOME][] before realizing that all I ever wanted was a tiling window manager. In my experience, the ability to not use a mouse as one navigates between terminals is a path to less sore wrists, a deep personal happiness, and fundamental increase in quality of life. I highly recommend it.

In my impetuous youth, I fell in love with [Ion][]. But when its author pulled support for multiple monitors because he felt that wanting to plug in a second display was a form of consumerism and "penis enlargement", I saw the writing on the wall. After deciding to avoid the competitor whose name, while we're on the subject, [rhymes with gonad][xmonad], I settled on [Awesome][] and, over time, have become very content with it. I use Awesome primarily as a way of launching menubar-less, black-background, [GNOME Terminals][gnome-terminal] running [zsh][].

Back in 2003, I realized that I had two types of fonts, three non-Latin [text][scim] [input][uim] [method][mule] frameworks (with bindings to each other!), a handful of different text-rendering systems, [and][ispell] [four][aspell] [different][myspell] [spellcheckers][hunspell]. GNOME seemed like the best framework to bring the free world out of that swamp and I've tried to support and use as much GNOME infrastructure as possible from within my "awesome", if idiosyncratic, desktop. In addition to GNOME terminal, I use [Network Manager][network-manager], [GNOME Settings Daemon][gnome-settings-daemon], [Update Notifier][update-notifier] and [GNOME Power Manager][gnome-power-manager].

The other piece of software I abandoned in my 2003 purge was [Emacs][] ([XEmacs][], specifically). Despite its reputation as the kitchen sink, the last decade has seen Emacs become less of an island in the free software desktop: it now uses [GTK+][gtk-plus], standard input management systems, Παν語 ([Pango][pango]), and more. [vim][] -- which I had switched to -- seems to be trying to occupy the space Emacs has vacated. For example, vim added its own integrated spellchecker, something Emacs has never done. Increasingly annoyed, I switched back to GNU Emacs after nearly five years of weening myself off and two-years of Emacs sobriety.

Although I still have mixed feelings, and while I appreciate and am proficient in vim, I *love* modern Emacs. My decision to switch back was also motivated by [ESS][] (the Emacs R mode, which is incredible), [AUCTeX][] (the Emacs TeX/LaTeX mode), and [Org-Mode][]. None existed in their current form a decade ago and I use all extensively today.

These days, I do most of my programming in [R][] within ESS. As I've become a sociologist and statistician, I've moved from [Python][], [Ruby][], [Perl][], [C++][c-plusplus], and [C][] to R. R is slow and using it with big datasets gives one plenty of time to reflect on this fact. But R is also expressive, elegant, and concise for numerical and statistical work so I happily suffer through it. I make my graphs in [ggplot2][] which is so trendy that I feel that mentioning this is a sort of R-hipster confession.

I read my email in [Mutt][] and write it in Emacs. I feel like my Mutt configuration is one of my major projects over the last decade; it is extensive and contains large chunks of configuration generated in Perl at startup. I run my own mail server (using [Postfix][]) and sync mail locally using [Dovecot][] on my server and [OfflineIMAP][] on my laptop. Mutt operates directly on local MailDirs which are synced with the server every few minutes. I search my mail locally using [notmuch][] and [mairix][] with [some glue I've borrowed](http://upsilon.cc/~zack/blog/posts/2011/01/how_to_use_Notmuch_with_Mutt/ "A post on using Notmuch with Mutt.") that makes for quite a nice user experience.

I use [Irssi][] running in [screen][] on a server for IRC. I've never found an IM/XMPP/Jabber client I liked, so I run [Bitlbee][] which represents my IM client as a IRC channel full of my contacts.

I browse the web in [FireFox][] and rely so heavily on a series of extensions that I find it very hard to imagine switching to Chrome or anything else. The most critical extensions are [Zotero][] which I use for bibliography management, [Tree Style Tab][tree-style-tab] to save horizontal screen real estate, [AdBlock Plus][adblock-plus] to make the web bearable, and [NoScript][] to keep my browser from running random code from websites I don't realize I'm visiting.

My browser is often pointed at [NewsBlur][] (an incredible RSS feed reader), [Scuttle][] (social bookmarking software I run a patched instance of), and [Identi.ca][identi.ca] (a microblogging service). All three are free software and [free network services](http://autonomo.us/2008/07/franklin-street-statement/ "A post on what defines a free network service.").

I think Google has too much data about me and I generally try to avoid using their services. Even then, I use them all the time. I frequently search using [DuckDuckGo][] and I refuse to use [GMail][] because I don't want Google to have my email. That said, looking through email headers, it's clear that because nearly all of the people I email with do use Gmail, Google has my email anyway. On a related note, I use the [GNU Privacy Guard][gnupg] and wish more people did too.

I have yet to find a music player that I like, so I tend to just run [mplayer][] from the shell, usually pointed at a [Icecast][]/[Shoutcast][] stream, usually [soma.fm][somafm].

All of [my code](http://mako.cc/software/ "Benjamin's software."), most of [my writing](http://mako.cc/writing/ "Benjamin's published books and articles."), my blog, my website, and nearly any other project I work on on more than on occasion goes into [git][]. I've recently started using [magit][] to manipulate git from within Emacs and I love it. I find something unbearably ironic about [GitHub][]'s model of building [a proprietary centralized service](http://mako.cc/writing/hill-free_tools.html "Benjamin's post on hosted source code services.") around a a tool designed to be decentralized and free. As a result, I try to publish all my own branches using an instance of gitweb I run myself.

### What would be your dream setup?

I want a laptop with no moving parts that is not unusably slow. The last four times I had to get my laptop repaired it was for failed hard disks and fans -- the only components in my whole computing set-up with bearings. Solid states drives are the first step but fans don't seem to be going anywhere. Modern fans are loud even when they are quiet. They get filled with lint and dirt and string. They break.

I desperately want a laptop with a less wide aspect ratio although I realize I am destined for disappointment. The shift from 4:3 to 16:10 and now 16:9 (have mercy, please) is [a swindle](http://mako.cc/copyrighteous/20111207-00 "Benjamin's post on widescreen ratios."). My X-series laptops' screens have all had the same diagonal length (12.1 inches). However, because the aspect ratio has changed, my 12.1" X201 screen has 28 square centimeters less physical area than the my 12.1" X61 screen. I'm ready to conclude that either this a conspiracy to sell me less screen for the same amount of money (see, [shrinking packages sizes for food](http://www.nytimes.com/2011/03/29/business/29shrink.html?_r=1 "A NYTimes article on shrinking food packages.")) or I'm being held hostage by consumers who think their computers are tiny wide screen televisions and not, y'know, computers. Or both.

I want a Kindle DX that is not part of a DRM-based plan to make books expire, disappear, and become dependent on proprietary hardware and software. There are now some alternative devices with the similarly large E Ink screens necessary to read two-column scientific paper PDFs. But they all came out after I bought the Kindle. If I had known they were coming, I might have waited. That said, they all use proprietary firmware and implement DRM too, as far as I can tell.

As a horrible speller, I want to have one excellent spellchecker, one spell checking dictionary and one list of the words I've whitelisted. I still have four installed and it makes me die a little every time I confront this. I once supervised a [Google Summer of Code](https://code.google.com/soc/ "Google's student coding program.") student who tried to fix this issue -- and failed.

People [complain](http://kieran.healy.usesthis.com/ "Kieran's Setup interview.") about Emacs but I'm actually pretty happy with it. The most annoying thing to me about Emacs is how long it takes to start. I get around this by running an Emacs Server and then launching emacsclient which simply provides alternate interfaces to an already running editor. My default editor is a tiny shellscript that looks for a running version of Emacs and, if it can't find it, launches vim instead (basically `emacsclient $@ || vim $@`). That's an ugly arrangement I'd prefer to avoid.

While I'm dreaming:

I want 100% free software operating systems and applications for my computer, my phone, my ebook reader, and every other piece of technology I use.

I wish everyone else used my setup because I think they would benefit from using free software -- and, as a side effect, they would be unlikely to create Flash websites, assume that I use [Microsoft Office][office], or send me non-text/plain email. Most of my corner of academia uses [Stata][] and [Word][] and my divergence from this orthodoxy leads to all kinds of headaches when I collaborate and publish. I could live without that.

I want a version of Debian unstable that I can recommend to people that do not write Debian.

I want every programming language I use to be as fast as C.

I want every program to have clear and well documented source code available in a programming language that I know so that I can take advantage of the freedoms that the majority of my software gives me.

*Benjamin now keeps a [changelog of his latest computer setup](http://wiki.mako.cc/TheSetup_Changelog "Benjamin's setup changelog.").*

[adblock-plus]: https://adblockplus.org/ "Browser extensions for blocking ad content."
[afterstep]: http://www.afterstep.org/ "An X window manager inspired by NeXTStep's interface."
[android]: https://developers.google.com/android/?csw=1 "A mobile phone platform."
[aspell]: http://aspell.net/ "A spell checking system."
[auctex]: http://www.gnu.org/software/auctex/ "An Emacs package for TeX support."
[awesome]: https://awesomewm.org/ "A window manager for X."
[bitlbee]: https://www.bitlbee.org/main.php/news.r.html "An IM to IRC proxy server."
[blackbox]: https://blackboxwm.sourceforge.net/ "A lightweight window manager for X."
[c-plusplus]: https://en.wikipedia.org/wiki/C%2B%2B "A compiled programming language."
[c]: https://en.wikipedia.org/wiki/C_(programming_language) "A compiled programming language."
[debian]: https://www.debian.org/ "A Linux distribution."
[dovecot]: https://dovecot.org/ "A secure IMAP server."
[duckduckgo]: https://duckduckgo.com/ "A new search engine."
[emacs]: http://www.gnu.org/software/emacs/ "A free open-source text editor."
[enlightenment]: https://www.enlightenment.org/ "A window manager for X."
[ess]: https://ess.r-project.org/ "An Emacs package for statistical analysis program support."
[firefox]: https://www.mozilla.org/en-US/firefox/new/ "A cross-platform open-source web browser."
[fluxbox]: http://fluxbox.org/ "A lightweight window manager for X."
[fvwm]: https://www.fvwm.org/ "A window manager for X."
[ggplot2]: http://web.archive.org/web/20180506153516/http://ggplot2.org:80/ "A plotting system for the R language."
[git]: https://git-scm.com/ "A version control system."
[github]: https://github.com/ "A Git code repository service."
[gmail]: https://mail.google.com/mail/u/0/ "Web-based email."
[gnome-power-manager]: https://packages.debian.org/stable/gnome-power-manager "A power management daemon for GNOME."
[gnome-settings-daemon]: https://packages.debian.org/stable/gnome-settings-daemon "A daemon for controlling settings in a GNOME session."
[gnome-terminal]: https://en.wikipedia.org/wiki/GNOME_Terminal "A terminal application."
[gnome]: https://www.gnome.org/ "A desktop system for *nix operating systems."
[gnupg]: https://www.gnupg.org/ "Encryption and signing software."
[gtk-plus]: https://www.gtk.org/ "A multi-platform GUI toolkit."
[happy-hacking-keyboard]: https://en.wikipedia.org/wiki/Happy_Hacking_Keyboard "A computer keyboard."
[hunspell]: http://hunspell.github.io/ "A spell checking system."
[hurd]: https://www.gnu.org/software/hurd/hurd.html "A replacement OS for UNIX."
[icecast]: https://www.icecast.org/ "Software for streaming media."
[identi.ca]: https://identi.ca/ "An online micro-blogging platform."
[ion]: https://tuomov.iki.fi/software/ "A window manager for X11."
[irssi]: https://irssi.org/ "A CLI irc client."
[ispell]: https://www.cs.hmc.edu/~geoff/ispell.html "A spell checking system."
[kindle]: http://web.archive.org/web/20230315012831/http://www.amazon.com/Kindle-Ereader-ebook-reader/dp/B007HCCNJU/ "A digital book reader."
[magit]: https://github.com/magit/magit "A git mode for Emacs."
[mairix]: http://www.rpcurnow.force9.co.uk/mairix/ "An email index and search tool."
[mediamate]: https://www.bose.com/en_us/support/products/computer_speakers_support/computer-musicmonitor.html "Computer speakers."
[model-m]: https://en.wikipedia.org/wiki/Model_M_keyboard "A keyboard."
[mplayer]: http://www.mplayerhq.hu/ "Movie viewing software."
[mule]: https://en.wikipedia.org/wiki/MULE/Emacs "A multilingual editor."
[mutt]: http://www.mutt.org/ "A command-line email client."
[myspell]: https://en.wikipedia.org/wiki/MySpell "A spell checking system."
[network-manager]: https://wiki.gnome.org/Projects/NetworkManager "A network manager for GNOME."
[newsblur]: https://www.newsblur.com/ "An online feed reader."
[noscript]: https://noscript.net/ "A Firefox extension for whitelisting scripting content."
[notmuch]: https://notmuchmail.org/ "An email index and search tool."
[office]: https://www.microsoft.com/en-us/microsoft-365 "An office productivity suite."
[offlineimap]: https://www.offlineimap.org/ "A tool for syncing mail from an IMAP server."
[org-mode]: https://orgmode.org/ "An Emacs mode for notes and to-do items."
[pango]: https://pango.gnome.org "A library for rendering multilingual text."
[perl]: https://www.perl.org/ "An interpreted scripting language."
[postfix]: http://www.postfix.org/ "Mail server software."
[python]: https://www.python.org/ "An interpreted scripting language."
[r]: http://www.r-project.org/ "Software for statistical computing and graphics."
[ruby]: https://www.ruby-lang.org/en/ "An interpreted scripting language."
[scim]: https://www.scim-im.org/ "A multilingual input system/development framework."
[screen]: http://www.gnu.org/software/screen/ "Think of it as tabs for your *nix terminal."
[scuttle]: https://sourceforge.net/projects/scuttle/ "Web-based bookmarking software."
[sensation]: https://en.wikipedia.org/wiki/HTC_Sensation "An Android-powered smartphone."
[shoutcast]: https://www.shoutcast.com/ "Software for streaming media."
[slackware]: http://www.slackware.com/ "A Linux distribution."
[somafm]: https://somafm.com/ "An online radio station."
[stata]: https://www.stata.com/ "Data analysis and statistical software."
[thinkpad-x201]: http://web.archive.org/web/20160511173457/http://shop.lenovo.com:80/us/notebooks/thinkpad/x-series/x201 "A 12.1 inch lightweight laptop."
[tree-style-tab]: https://addons.mozilla.org/en-US/firefox/addon/tree-style-tab/ "A Firefox extension for organising tabs in a tree layout."
[u2711]: http://web.archive.org/web/20221206090348/http://www.amazon.com/Dell-UltraSharp-U2711-27-inch-Widescreen/dp/B0039648BO "A 27 inch widescreen LCD monitor."
[ubuntu]: https://ubuntu.com/ "A Unix distribution."
[uim]: https://code.google.com/archive/p/uim "A multilingual input system/development framework."
[update-notifier]: https://packages.debian.org/stable/update-notifier "A GNOME daemon that alerts a user to available updates."
[vim]: https://www.vim.org/ "A command-line text editor."
[window-maker]: http://www.windowmaker.org/ "An X window manager inspired by NeXTStep's interface."
[word]: https://www.microsoft.com/en-us/microsoft-365/word "A document editor."
[xemacs]: https://en.wikipedia.org/wiki/XEmacs "A version of Emacs."
[xen]: https://xenproject.org/ "Virtualisation software."
[xmonad]: https://xmonad.org/ "A tiling window manager for X11."
[zotero]: https://www.zotero.org/ "A research tool."
[zsh]: https://www.zsh.org/ "An interactive shell and scripting language."
