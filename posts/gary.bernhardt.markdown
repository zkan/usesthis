---
title: Gary Bernhardt
summary: Software developer, screencaster (Destroy All Software)
date: 2014-04-08
categories:
- developer
- mac
- screencaster
---

### Who are you, and what do you do?

I'm mostly a programmer. For two years, I published screencasts on various software development topics at [Destroy All Software](http://www.destroyallsoftware.com/ "Developer screencasts."). It was very popular, but I got tired of talking to myself in a recording studio. I'm now working on an unannounced product related to finance (for good, not evil). I also speak at a lot of conferences: about 25 in the last three years, although I'm trying to reduce that significantly.

### What hardware do you use?

Not much. There's no version control for hardware failures, and I don't have the patience to deal with that. I use a late-2011 13" [MacBook Air][macbook-air] as my only computer. At my office, I use it with a [Thunderbolt Display][thunderbolt-display].

In the summer of 2013, I became afraid of RSI and preventatively switched to an [Evoluent vertical mouse][verticalmouse], which I've been pretty happy with (though I wish I'd gotten the wired version). I also switched both my keyboard geometry and my keyboard layout, which is a much more extreme change.

My keyboard is a full-hand [ErgoDox][]. It looks roughly like the one on the [Massdrop assembly page](https://www.massdrop.com/ext/ergodox/assembly.php "A guide to assembling an ErgoDox.") except that my case is longer, extending down from the bottom to form a built-in wrist rest. It has the notoriously clicky Cherry blue switches. I assembled it myself, which required a couple hundred solder joints. You can buy them pre-assembled now, I think, but I enjoyed the process (and I'm now confident that I can repair any problem with it).

The Norman keyboard layout was a bigger switch, although not as big as some other layouts. QWASZXCV are all in their QWERTY positions, so many common keyboard shortcuts are unchanged. Most other keys are on the same finger as QWERTY, just moved up or down. Norman on an ErgoDox is very comfortable and I was at 70 WPM after a month or so. I'm around 90 WPM now, and still around 120 on QWERTY. I've never used QWERTY on my ErgoDox or Norman on a normal keyboard; I suspect this helps with keeping both sets of muscle memory in place.

I have an [iPhone 4][iphone-4], but find it frustrating. Every action is awkward and slow (and not because it's three generations old, although that doesn't help). I type about 60 WPM on an iPhone and have always used QWERTY there. My phone has been muted with vibration turned off for a year or so, so it has no way to alert me of anything. I'll let the computer know when I need it.

For screencasting, I used a [Rode Podcaster mic][podcaster] and a pair of inconsequential in-ear headphones for monitoring. Towards the end, I was recording in a professional studio here in Seattle. Before that, I had a cobbled-together home studio. And before that, I recorded in my living room because I didn't know what I was doing.

### And what software?

For programming, I use [Vim][] (but I used [Emacs][] years ago). Most code that I write is in [Python][] or [Ruby][]. Other than that, it's just [Unix](http://web.mit.edu/~simsong/www/ugh.pdf "A PDF of the Unix-Haters Handbook."), mostly unchanged from what it was in the year I was born. My terminal is [iTerm 2][iterm2] with the pastel color scheme and the [Inconsolata-g font][inconsolata-g].

I track tasks with [OmniFocus][], both on my Mac and my iPhone. When I first drafted this six months ago, I praised it very highly because it was the only thing that never broke. In the meantime, it's broken a few times, losing some of my data. Support told me that this is a known possibility. All software will destroy your data.

My passwords are in [1Password][]; most of them are unique strings of 24-32 random characters. It's a very solid product. Everyone should use 1Password or something like it.

I use [Mutt][] to read mail, with [OfflineIMAP][] syncing from [Fastmail's][fastmail] IMAP servers to my local maildir. The syncing is managed by a still-unpublished custom script that commits to git before and after every sync. That's right: my email is in a git repository, and it's committed dozens of times per day. As I write this, there are 1,701 commits; 131,097 mail messages; 3.4 GB of mail; and 3.5 GB of git repo (that should be much smaller but isn't for reasons that would put you to sleep).

Backup is a little complicated. I back up to Amazon S3/Glacier using [Arq][] and to a local [Time Capsule][time-capsule] using [Time Machine][time-machine]. Both of those run hourly and store backup history.

I also make two clones of my full drive: one to a bootable USB drive, and another to the Time Capsule (separate from the Time Machine history). Both are done using [SuperDuper][]. Then, just for good measure, I clone the entire 1.5 GB Time Capsule to another USB drive via [rsync][]. The whole SuperDuper/rsync process happens every two weeks.

The "why" of all of that is a long story, but that's roughly the minimum configuration that I consider fairly safe and easily recoverable after catastrophic failure. The two hourly backup systems involved -- Arq and Time Machine -- have failed completely multiple times, losing or, in Time Machine's cases, corrupting all of my backups without alerting me. The causes of those failures remain uncorrected, so they will surely happen again. SuperDuper hasn't failed, but it's also not a storage system itself and its backups have no history.

I suspect that many people will skip past that backup stuff. Backup is boring, which is why everyone loses their data.

### What would be your dream setup?

If I can only have things that exist, then pretty much what I have now. I'd swap my Air for the newest model; maybe try one of those new [Mac Pros][mac-pro]; maybe try two 24" monitors instead of my 27". But I don't want more or fancier things; I just want the computer to actually work.

If I don't have to stick to things that exist, though...

A MacBook air, but with a fast E Ink display that uses all of the bezel space (so roughly 14.5"; the current display is about 13.25"). I don't care that it's grayscale; I just want pixel density and low power consumption.

A modal editor, roughly keystroke compatible with Vim's normal and visual modes, but with an entirely new ex mode. It's scriptable in some reasonable modern language that fails early and loudly in the face of error or ambiguity. Python, but with "end" markers added, blocks added, and `__builtins__` removed, would be a good start. I gave a whole [conference talk](https://www.destroyallsoftware.com/talks/a-whole-new-world "Gary's talk about his ambitious software project.") about this.

All data that I create stored locally, on my machine, in a file system where everything from the full disk state down has a hash and all change history is stored. If it runs out of space and needs to delete history, it will ask me first, blocking the entire machine if necessary. (This is just Stanislav's [second law of sane personal computing](http://www.loper-os.org/?p=284 "An article descripting the Seven Laws of Sane Personal Computing.")).

Online continuous synchronization of all local data changes to a remote storage system. This provides backup that I might actually trust: every change to the disk goes to the network as soon as possible; you know that nothing was lost or corrupted because it's all hashed from "/" down; and you can recover from arbitrary mistakes because you have full change history.

Of course, everything encrypted on-disk via a reasonable current algorithm. All network storage encrypted via a half dozen or so reasonable current algorithms with different design lineages, onion style, using a key that isn't stored anywhere. It'll be fine; my CPU is faster than my network connection.

I think I'll cut it off there and avoid the temptation to talk about my ideal kernel. ;)

[1password]: https://1password.com "Password management software for Mac OS X."
[arq]: https://www.arqbackup.com/ "S3-based backup for the Mac."
[emacs]: http://www.gnu.org/software/emacs/ "A free open-source text editor."
[ergodox]: https://www.ergodox.io/ "A buildable split ergonomic keyboard."
[fastmail]: https://www.fastmail.com/ "An email hosting service."
[inconsolata-g]: https://leonardo-m.livejournal.com/77079.html "A font."
[iphone-4]: https://en.wikipedia.org/wiki/IPhone_4 "A smartphone."
[iterm2]: https://iterm2.com/ "An alternative terminal application for Mac OS X."
[mac-pro]: https://www.apple.com/mac-pro/ "The Intel-based Mac tower computer."
[macbook-air]: https://www.apple.com/macbook-air/ "A very thin laptop."
[mutt]: http://www.mutt.org/ "A command-line email client."
[offlineimap]: https://www.offlineimap.org/ "A tool for syncing mail from an IMAP server."
[omnifocus]: https://www.omnigroup.com/omnifocus/ "Task management software for the Mac."
[podcaster]: http://www.rode.com/microphones/podcaster "A USB microphone."
[python]: https://www.python.org/ "An interpreted scripting language."
[rsync]: https://rsync.samba.org/ "An open-source file transfer/syncing tool."
[ruby]: https://www.ruby-lang.org/en/ "An interpreted scripting language."
[superduper]: https://shirt-pocket.com/SuperDuper/SuperDuperDescription.html "An excellent Mac backup/cloning application."
[thunderbolt-display]: https://www.apple.com/displays/ "A Thunderbolt-powered monitor."
[time-capsule]: https://www.apple.com/mac/ "A WiFi access point and backup system."
[time-machine]: https://en.wikipedia.org/wiki/Time_Machine_(Mac_OS) "Backup software for the masses, included with Mac OS X 10.5."
[verticalmouse]: http://evoluent.com/products/vm4rw/ "A unique wireless mouse."
[vim]: https://www.vim.org/ "A command-line text editor."
