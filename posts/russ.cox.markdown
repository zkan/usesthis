---
title: Russ Cox
summary: Software developer (Plan 9, RE2, Go)
date: 2011-04-09
categories:
- developer
- mac
- windows
---

### Who are you, and what do you do?

[I](http://swtch.com/~rsc/ "Russ' website.") write programs. For about a decade I worked on the operating system [Plan 9 from Bell Labs][plan-9]. I now work at Google, where I created [Google Code Search](http://codesearch.google.com/ "Google's Code Search.") and along with it the [RE2 regular expression library][re2]. For the last two and a half years I've been one of the core developers of the [Go programming language][go]. In free time outside of work, I wrote the last two major versions of the software behind the [Online Encyclopedia of Integer Sequences](http://oeis.org/ "The On-Line Encyclopedia of Integer Sequences.").

I also write about programs. The writing I'm most known for is my series about [how to implement regular expressions](http://swtch.com/~rsc/regexp/regexp1.html "Russ' series on Regular Expressions.") and my construction of [a zip file that contains itself](http://research.swtch.com/2010/03/zip-files-all-way-down.html "Russ' article on a zip file that contains itself.").

### What hardware do you use?

I lost interest in having the new shiny a long time ago. I like to find things that work for me and stick with them. I also rarely bother to pay for something new when I can get the previous model for less.

At home that means a refurbished [Mac Mini][mac-mini] from 2006, a used [Dell 2001FP 20" LCD][2001fp] from 2004, and a [Samsung ML-1750 laser printer][ml-1750] from 2004. More recent additions include an [Apple Time Capsule][time-capsule] for backing up the Mac and running the home network, a [Netgear ReadyNAS Duo][readynas-duo] (with mirrored disks) for networked storage, and a [Fujitsu ScanSnap S510][scansnap-s510]. I swear by the [small Apple keyboard][keyboard] (in stores they have one that size with a USB cable too) and the [Evoluent mouse][verticalmouse]. They all continue to serve me very well. The only thing I might replace if I were starting over would be the ReadyNAS box. The low-end model I have runs Linux on what appears to be a [SPARC simulated by an FPGA](http://www.readynas.com/forum/viewtopic.php?f=7&t=48124 "A thread about ReadyNAS and SPARC."); saying it's slow is an understatement, but it's only a disk. The printer and the scanner both seemed extravagant at the time, but they have been absolute workhorses and well worth the money.

When I'm not at home, and even often when I am, I work on my laptop. I used an [IBM Thinkpad X40][thinkpad-x40] running Linux from 2004 until very recently. It was small, light, sturdy, and had three mouse buttons. What more could you want? I recently replaced my X40 with a refurbished [Lenovo Thinkpad X201s][thinkpad-x201s], which is also small, light, sturdy, and has three mouse buttons. On top of that, it has a gorgeous high-resolution screen, an SSD, 4 cores, and 4 GB of RAM. I know it won't seem like much in a few years, but right now it sure feels like I'm living in the future.

As far as gadgets, the ones that have lasted are my [Bose QC2 headphones][quietcomfort-2] (the [QC15][quietcomfort-15] are just as nice), [Nexus One phone][nexus-one], [Nikon D90][d90] with [18-200mm AF-S lens][af-s-dx-nikkor-18-200mm-f3.5-5.6g-ed-vr-ii]. I bought a [Kindle 3][kindle] recently, and I like it, but it hasn't stood the test of time yet.

I also use a lot of pens and 8.5x11 paper pads. I scribble constantly when I'm trying to work things out. I don't save any of it, but it helps me think.

### And what software?

I ran [Plan 9 from Bell Labs][plan-9] as my day to day work environment until around 2002. By then two facts were painfully clear. First, the Internet was here to stay; and second, Plan 9 had no hope of keeping up with web browsers. Porting Mozilla to Plan 9 was far too much work, so instead I ported almost all the Plan 9 user level software to FreeBSD, Linux, and OS X. The result is called [Plan 9 from User Space][plan-9-user-space] and is probably much more widely used today than Plan 9 ever was.

I run [_acme_][acme] full screen as my day to day work environment. It serves the role of editor, terminal, and window system. It's hard to get a feel for it without using it, but [this video](http://www.youtube.com/watch?v=dopu3ZtdCsg "A video of acme in action.") helps a little.

[Rob Pike](http://herpolhode.com/rob/ "Rob's website.")'s [_sam_][sam] editor deserves special mention too. From a UI standpoint, it's a graphical version of [_ed_][ed], which you either love or hate, but it does two things better than any other editor I know. First, it is a true multi-file editor. I have used it to edit thousands of files at a time, interactively. Second, and even more important, it works insanely well over low-bandwidth, high-latency connections. I can run sam in [Boston](http://www.google.com/intl/mn/jobs/uslocations/boston/index.html "Google in Boston.") to edit files in [Sydney](http://www.google.com.au/intl/en/jobs/sydney/ "Google in Sydney.") over ssh connections where the round trip time would make vi or emacs unusable. Sam runs as two halves: the UI half runs locally and knows about the sections of the file that are on or near the screen, the back end half runs near the files, and the two halves communicate using a well-engineered custom protocol. The original target environment was 1200 bps modem lines in the early 1980s, so it's a little surprising how relevant the design remains, but in fact, it's the same basic design used by any significant [JavaScript][] application on the web today. Finally, sam is the editor of choice for both [Ken Thompson](http://plan9.bell-labs.com/who/ken/ "Ken's website.") and [Bjarne Stroustroup](http://www.research.att.com/~bs/ "Bjarne's website."). If you can satisfy both of them, you're doing something right.

Aside from the Plan 9 tools, I live mostly in Google software. I use [Google Chrome][chrome] to get at my Gmail on my vanity domain [swtch.com](http://swtch.com/unix "Rob's website."), I use [Blogger][] to manage my [blog posts](http://research.swtch.com/ "Rob's research posts.") (but I write them in acme), I use [Google Reader][google-reader] to follow sites on the web, I use [Google Voice][google-voice] to direct my phone calls.

I use [Picasa][] to manage photos on my Mac and upload them to [SmugMug][] for sharing with friends, and then I use [SmugFolio][smugfolio-android] to sync them nicely onto my Android phone. When I'm traveling, I'm a big fan of [TripIt][] and their [Android app][tripit-android]. I'm excited about being able to run Android apps like SmugFolio on my [Google TV box][nsz-gt1].

I use [Unison][] to sync files between my various computers. [Dropbox][] seems to be the hot new thing, but I like that Unison doesn't ever store my files on someone else's computers.

### What would be your dream setup?

The thing I miss most about Plan 9 was the way that no matter which computer you sat down at, you had the same environment. Because we were working off a shared file server - there were no local disks on the Plan 9 workstations - you could go home and log in and all your work was there waiting. Of course, it only worked because we had good, fast connectivity to the file server, and only file state - not application state - transferred, but it was still a huge win.

Today it's taken for granted that everyone has local files on disk and you need programs like Unison or Dropbox (or for the power users, Mercurial or Git) to synchronize them, but what we had in Plan 9 was completely effortless, and my dream is to return to that kind of environment. I want to be working on my home desktop, realize what time it is, run out the door to catch my train, open my laptop on the train, continue right where I left off, close the laptop, hop off the train, sit down at work, and have all my state sitting there on the monitor on my desk, all without even thinking about it.

Moving everything into "The Cloud" may be a path to that dream, but we are definitely not there yet.

[2001fp]: http://web.archive.org/web/20210415151948/http://www.amazon.com/Dell-UltraSharp-2001FP-20-1-inch-Monitor/dp/B000BMBUAQ "A 20.1 inch LCD screen."
[acme]: https://en.wikipedia.org/wiki/Acme_(text_editor) "A text editor and graphical shell for Plan 9."
[af-s-dx-nikkor-18-200mm-f3.5-5.6g-ed-vr-ii]: https://www.nikonusa.com/en/Nikon-Products/Product/Camera-Lenses/2192/AF-S-DX-NIKKOR-18-200mm-f%252F3.5-5.6G-ED-VR-II.html "A lens for DSLR cameras."
[blogger]: https://en.wikipedia.org/wiki/Blogger_(service) "A weblog publishing system."
[chrome]: https://www.google.com/intl/en/chrome/ "A WebKit-based browser, where each tab runs in its own thread."
[d90]: https://www.nikonusa.com/en/Nikon-Products/Product-Archive/Digital-SLR-Cameras/D90.html "A 12.3 megapixel digital SLR camera."
[dropbox]: https://www.dropbox.com/ "Online syncing and storage."
[ed]: https://en.wikipedia.org/wiki/Ed_(text_editor) "A line text editor for Unix."
[go]: https://go.dev/ "A compiled programming language."
[google-reader]: https://en.wikipedia.org/wiki/Google_Reader "A web-based feed reader."
[google-voice]: https://en.wikipedia.org/wiki/Google_Voice "A phone number and online voicemail system."
[javascript]: https://en.wikipedia.org/wiki/JavaScript "An interpreted scripting language."
[keyboard]: https://www.apple.com/us/shop/goto/mac/accessories "The keyboard."
[kindle]: http://web.archive.org/web/20230315012831/http://www.amazon.com/Kindle-Ereader-ebook-reader/dp/B007HCCNJU/ "A digital book reader."
[mac-mini]: https://www.apple.com/mac-mini/ "A small desktop computer."
[ml-1750]: http://web.archive.org/web/20190508180021/https://www.amazon.com/Samsung-ML-1750-XAA-Laser-Printer/dp/B00008XOKW "A laser printer."
[nexus-one]: https://en.wikipedia.org/wiki/Nexus_One "An Android-based smartphone."
[nsz-gt1]: http://web.archive.org/web/20210129235350/http://www.amazon.com/Sony-NSZ-GT1-Wi-Fi-Enabled-Blu-ray-Featuring/dp/B004D4917W "A Blue-ray player powered by Google TV."
[picasa]: http://picasa.google.com/ "A photo client and web service."
[plan-9-user-space]: https://swtch.com//9fans.github.io/plan9port/ "A port of Plan 9 programs to *nix."
[plan-9]: https://en.wikipedia.org/wiki/Plan_9_from_Bell_Labs "A distributed operating system."
[quietcomfort-15]: https://www.bose.com/controller?url=%2Fshop_online%2Fheadphones%2Fnoise_cancelling_headphones%2Fquietcomfort_15%2Findex.jsp "Noise-cancelling headphones."
[quietcomfort-2]: https://www.amazon.com/Bose-QuietComfort-Acoustic-Canceling-Headphones/dp/B000AP05BO "Noise-cancelling headphones."
[re2]: https://github.com/google/re2 "A regular expression engine."
[readynas-duo]: https://www.readynas.com/?p=1514 "A network backup/storage solution."
[sam]: https://en.wikipedia.org/wiki/Sam_(program) "A multi-file text editor."
[scansnap-s510]: https://www.fujitsu.com/us/products/ "A sheet-fed scanner."
[smugfolio-android]: https://play.google.com/store/apps/details?id=com.snapwood.smugfolio "A SmugMug offline viewer and uploader for Android."
[smugmug]: https://www.smugmug.com/ "A photo sharing website."
[thinkpad-x201s]: https://www.thinkwiki.org/wiki/Category:X201s "A 12.1 inch PC laptop."
[thinkpad-x40]: https://www.thinkwiki.org/wiki/Category:X40 "A 12.1 inch PC laptop."
[time-capsule]: https://www.apple.com/mac/ "A WiFi access point and backup system."
[tripit-android]: https://play.google.com/store/apps/details?id=com.tripit "A TripIt client for Android."
[tripit]: https://www.tripit.com/web "A travel planning web service."
[unison]: https://www.cis.upenn.edu/~bcpierce/unison/ "A file syncing tool."
[verticalmouse]: http://evoluent.com/products/vm4rw/ "A unique wireless mouse."
