---
title: Marius Eriksen
summary: Software developer (Twitter)
date: 2014-02-20
categories:
- developer
- mac
---

### Who are you, and what do you do?

My name is [Marius Eriksen](http://monkey.org/~marius/ "Marius' website.") ([@marius](https://twitter.com/marius "Marius' Twitter account.")) and I write software. My formative years were spent at [CITI](http://www.citi.umich.edu/ "The Center for Information Technology's website.") at the University of Michigan, hacking on [operating systems][openbsd], [distributed file systems](http://datatracker.ietf.org/wg/nfsv4/charter/ "Version 4 of the NFS file system standard."), and [various](http://static.usenix.org/event/usenix05/tech/freenix/full_papers/eriksen/eriksen.pdf "Marius' article on Trickle.") [networking][nylon] and [computer](http://monkey.org/~marius/tmp/fsraces.pdf "Marius' article on preventing file system races.") [security][systrace] related projects.

Since then, I've spent time working on infrastructure at Google and Twitter. Recently, I've spent most of my time on what might properly be called the connective tissue of our distributed systems: our RPC system, [Finagle][finagle], and our [libraries for writing safe and performant concurrent programs][util]. I try to push the boundaries of [higher level techniques in systems programming](http://plosworkshop.org/2013/preprint/eriksen.pdf "Marius' post on your server as a function."). I'm currently working on a new system for composing distributed systems; details are forthcoming soon.

I also help organize the annual [CUFP](http://cufp.org/ "The Commercial Users of Functional Programming website.") workshop.

### What hardware do you use?

I'm using a [Retina MBP 13"][macbook-pro]. As with any new-ish computer, it's the best one I've had. It's light & compact -- this is important to me as I drag it along on my commute -- but also packs enough hardware that I am rarely in want of more power. And that display. It is gorgeous. When I get to work, I hook it up to a 27" Dell display, and use a wireless [Evoluent VerticalMouse][verticalmouse] (I do a lot of mousing. See below.) together with an [Apple Wireless Keyboard][keyboard].

I have a beefy (headless) Linux box underneath my desk (running [Ubuntu][]). It mostly does builds, benchmarking, and other periodic tasks. Twitter's compute clusters are always at my avail.

I use an [iPhone 5][iphone-5], and also an iPad.

Also: lots of notebooks and paper. I tend to write things down on whatever is available. (To borrow an old adage: the best notebook is the one you have with you.) Most of the time, I write things down just to help me think -- a veritable [Waste Book](http://www.amazon.com/Waste-Books-York-Review-Classics/dp/0940322501 "Amazon's page for 'The Waste Books' by Georg Christoph Lichtenberg.") -- and only occasionally for posterity.

To get around I use a homemade fixed-gear bicycle with a [Raleigh Rush Hour][rush-hour-2008] steel frame and wheels made using [Velocity Deep-V rims][deep-v-700c] and Wheelsmith spokes. I have a Bakfiets cargo bike for hauling groceries and kids around. I take Caltrain to work. (Now that's [real hardware](http://en.wikipedia.org/wiki/MPI_MP36PH-3C "The Wikipedia entry for the MPXpress locomotive.").)

At work, I listen to music with headphones: [Beyerdynamic DR-1350s][dt-1350] when it's quiet enough; otherwise a pair of [Bose QC-15s][quietcomfort-15].

### And what software?

I used to be quite exacting of my software environment. I went to great lengths to make it just-so: I even wrote a window manager -- [cwm][], it survives to this day, and ships in the base OpenBSD distribution -- to escape the tyranny of having an environment designed by others. (A fun story: When I was at Google, Sergey Brin once rollerskated -- yes, rollerskated -- into my office, spotted my strange windowing system, and proceeded to debate me about the merits of tiling vs. floating window management.)

Now, I try to use whatever is available, whatever is easy, whatever is default. For one, I use [OS X][macos]. Despite what others say, my experience is that it keeps getting better with each release: more stable, more performant, more energy-efficient. I use [Safari][] (and I make frequent use of its Reading List feature), [Calendar.app][ical], [Notes.app][notes], [Reminders.app][reminders]. (Reminders.app runs my life; I am very forgetful.) I use Apple's [Mail.app][mail] for email, and I try to keep it unsophisticated: I quell the flood of emails by subscribing only to mailing lists where I'm reasonably sure most emails are of direct interest to me. I use Apple's [Photo Streams][icloud] to share images with my family.

I use [Pinboard][] to catalog my web excursions. I use Twitter's [Mac app][twitter-mac] as well as [our website][twitter] to keep up with what's happening. We use [Review Board][review-board] to do code reviews, the [pants][commons] build system to build software, and [Mesos][]/[Aurora][] to run programs on our clusters. Along with Twitter, [iMessages][imessage] and [Flint.app][flint] keeps me connected to my colleagues. The [Scala][] compiler continually taunts me with type-checking failures.

I have a rule I try to abide by: it should take no more than 30 minutes to set up a new device. That means no elaborate setup, not too much software, and most importantly, keeping as much state as possible in the cloud.

For that, I use Benjamin Pierce's excellent [Unison][]. You can use it like a more sophisticated and private [Dropbox][]. I have a simple script that synchronizes the pieces of my home directory that I care about. A new machine is bootstrapped with the same script.

I spend most of my time in a rather peculiar environment: Rob Pike's [Acme][] editor, courtesy of Russ Cox's [Plan 9 from User Space][plan-9-user-space]. It's a text editor, but it's really much more. You can think of it as an IDE, but that doesn't quite capture it either. I think of it as a work environment in harmony with Unix: You can extend it by writing small programs that compose well; it has a few well-defined and orthogonal mechanisms for interaction (the [plumber](http://plan9.bell-labs.com/sys/doc/plumb.html "An article about the plumbing architecture in Plan 9."), [9P](http://en.wikipedia.org/wiki/9P "The Wikipedia entry for 9P."), [mouse chording](http://en.wikipedia.org/wiki/Mouse_chording "The Wikipedia entry for mouse chording.")). It's also what I like to think of as a system with a high power-to-weight ratio: It's a relatively small and simple program, but it wields a lot of power. You could make it a little more powerful, but not without adding a lot of complexity. Acme is very mouse heavy: it doesn't have keyboard shortcuts for complex navigation, or to invoke functionality. It means you do a lot of mousing. Initially that can be daunting, but you get used to it really quickly; in fact, I've come to prefer it.

On iOS I use the stock apps, and [Twitter][twitter-ios] of course; [Reeder][reeder-ios] for reading RSS feeds, [Rdio][rdio-ios] for music, the [New York Times app][nytimes-ios] for reading news, and [Audible][audible-ios] for listening to audio books. I share short videos with [Vine][vine-ios]. I use the [Kindle][kindle-ios] app for reading. (Since Amazon bought Audible, you can now sync positions in audiobooks and Kindle books. Great when you're commuting or running.)

The [Duo Security][duo] app helps me access both [monkey.org](http://monkey.org/ "Marius' shared website.") and Twitter's internal networks securely.

### What would be your dream setup?

Instead of answering your question directly, let me instead wax philosophical.

I'd like my tools -- hardware and software both -- to be more like [Leica][m6] film cameras: Using a Leica really requires you to pay attention to your environment. (Where is the light coming from? Where are the shadows? How contrastful is your environment? How far away is my subject? Watch [James Nachtwey](http://www.jamesnachtwey.com/ "James' website.") in "[War Photographer](http://www.war-photographer.com/en/ "The site for 'War Photographer.'")": here is someone completely immersed in his environment. Attuned, aware, attentive.) This is something I try to bring to my work: choose simple, barren tools, eschew sophisticated ones that blind you to your environment. Work with what you've got. Be resourceful. Pay attention.

A Leica is fundamentally simpler than a modern camera, but everything on it serves a purpose. You can't remove anything from it without compromising its functionality, but it's only slightly less "powerful".

Unfortunately, the tyranny of consumer software is that it is marketed based on "features" without paying attention to what it is these features add. Accidental complexity abound, and we end up with software that is very powerful but also much too complex. You have no hope of understanding how it all works. Such software also tends to be monolithic: a big giant ball of features, all inconsistently tangled together. This makes it difficult to combine with other software. Put another way, consumer software tends to lack that wonderful combinatorial explosion you get when you put a few simple and well-thought-out abstractions together.

That is what I want: more thoughtful, composable software; fewer monolithic behemoths; less "weight," and only slightly less power. It's probably a losing proposition, but we can hope.

[acme]: https://en.wikipedia.org/wiki/Acme_(text_editor) "A text editor and graphical shell for Plan 9."
[audible-ios]: https://apps.apple.com/us/app/audible/id379693831 "An app for the audio book service."
[aurora]: https://aurora.apache.org/ "Job scheduling software."
[commons]: https://github.com/twitter-archive/commons "Twitter's common Python/JVM libraries."
[cwm]: http://man.openbsd.org/cgi-bin/man.cgi/OpenBSD-current/man1/cwm.1?query=cwm%26sec=1 "A simple OpenBSD window manager."
[deep-v-700c]: https://www.velocityusa.com/index.php/product/rims/deep-v-622 "Bike rims."
[dropbox]: https://www.dropbox.com/ "Online syncing and storage."
[dt-1350]: http://north-america.beyerdynamic.com/ "Over the ear headphones."
[duo]: https://duo.com/ "A two-factor authentication service."
[finagle]: https://twitter.github.io/finagle/ "Twitter's RPC software."
[flint]: http://giantcomet.com/flint/mac/ "A Campfire client for the Mac."
[ical]: https://en.wikipedia.org/wiki/Calendar_(Apple) "The calendar software included with macOS."
[icloud]: https://www.apple.com/icloud/ "A cloud service."
[imessage]: https://en.wikipedia.org/wiki/IMessage "A messaging platform."
[iphone-5]: https://en.wikipedia.org/wiki/IPhone_5 "A smartphone."
[keyboard]: https://www.apple.com/us/shop/goto/mac/accessories "The keyboard."
[kindle-ios]: https://apps.apple.com/gb/app/kindle/id302584613 "An iPhone app for accessing Kindle content from Amazon."
[m6]: https://en.wikipedia.org/wiki/Leica_M6 "A film camera."
[macbook-pro]: https://www.apple.com/macbook-pro/ "A laptop."
[macos]: https://en.wikipedia.org/wiki/MacOS "An operating system for Mac hardware."
[mail]: https://en.wikipedia.org/wiki/Mail_(application) "The default Mac OS X mail client."
[mesos]: https://mesos.apache.org/ "Distributed cluster management software."
[notes]: https://en.wikipedia.org/wiki/Notes_(Apple) "A note-taking application included with Mac OS X."
[nylon]: http://web.archive.org/web/20190506110412/https://packages.gentoo.org/packages/net-proxy/nylon "A proxy server."
[nytimes-ios]: https://apps.apple.com/us/app/nytimes/id284862083 "An iPhone app to grab the latest news from the newspaper."
[openbsd]: http://www.openbsd.org/ "An open-source operating system emphasising security and cryptography."
[pinboard]: http://pinboard.in/ "A bookmarking web service."
[plan-9-user-space]: https://swtch.com//9fans.github.io/plan9port/ "A port of Plan 9 programs to *nix."
[quietcomfort-15]: https://www.bose.com/controller?url=%2Fshop_online%2Fheadphones%2Fnoise_cancelling_headphones%2Fquietcomfort_15%2Findex.jsp "Noise-cancelling headphones."
[rdio-ios]: https://apps.apple.com/us/app/rdio/id335060889 "An Rdio client for iOS."
[reeder-ios]: https://reederapp.com "A Google Reader client for iOS."
[reminders]: https://support.apple.com/guide/icloud/mmc0cd794a/ "A to-do list included with Mac OS X."
[review-board]: https://www.reviewboard.org/ "A web-based code review system."
[rush-hour-2008]: http://web.archive.org/web/20160502145117/http://archive.raleighusa.com:80/archive/2008-road/rush-hour-2008/ "A bike."
[safari]: https://www.apple.com/safari/ "A fast web browser."
[scala]: https://www.scala-lang.org/ "A compiled programming language."
[systrace]: http://www.citi.umich.edu/u/provos/systrace/ "Software for enforcing system call policies."
[twitter-ios]: https://apps.apple.com/app/twitter/id333903271 "A Twitter client."
[twitter-mac]: https://apps.apple.com/us/app/twitter/id409789998 "A Mac client for Twitter."
[twitter]: http://web.archive.org/web/20230525035323/https://twitter.com/ "An online micro-blogging platform."
[ubuntu]: https://ubuntu.com/ "A Unix distribution."
[unison]: https://www.cis.upenn.edu/~bcpierce/unison/ "A file syncing tool."
[util]: https://github.com/twitter/util/ "Twitter's reusable code library."
[verticalmouse]: http://evoluent.com/products/vm4rw/ "A unique wireless mouse."
[vine-ios]: https://apps.apple.com/us/app/vine/id592447445 "A short looping video app."
