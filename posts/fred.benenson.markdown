---
title: Fred Benenson
summary: Data researcher (Kickstarter)
date: 2013-03-14
categories:
- data
- developer
- mac
---

### Who are you, and what do you do?

I'm [Fred Benenson](http://www.fredbenenson.com/ "Fred's website."), I work at [Kickstarter][] on data. I split my time between research, engineering, and fixing the wifi. Previously I worked for [Creative Commons](http://creativecommons.org/ "A non-profit revolving around copyright licenses.") and helped start the [Students for Free Culture](http://freeculture.org/ "A movement promoting public interest in IP.") movement. I'm obsessed with emoji and currently have multiple Rubiks cubes of my desk.

### What hardware do you use?

At work I just upgraded to a 13" Retina [MacBook Pro][macbook-pro] from a 15" MBP from 2010. I had maxed out the new machine's RAM and got it with the SSD. If you haven't upgraded to an SSD, it's the single best upgrade you can possibly make. The 13" MBP Retina is a lot lighter to carry up and down stairs which I tend to do a lot of at Kickstarter HQ. I also have the ubiquitous Dell 24" LCD as an external monitor.

At home I have an [iMac][] with a Fusion drive that I like. Previously I had a [Mac Pro][mac-pro] but Apple seems like they've abandoned the line, and I got fed up with swapping out hard drives and new RAM. 

I also do a lot of computation in the "cloud" using an Amazon [EC2][] instance running [RStudio][]. This is a Webkit-interface for the open source data / stats language called [R][], and the machine it is running on in Amazon's cloud has 32GB of memory. This much RAM is necessary because you have to assume R is going to try to load everything into memory. Amazon recently announced even beefier instances (224GB RAM with an SSD, etc.), but I haven't run into any walls with this one yet so I'm sticking to it. I frequently load 5-10 million row datasets into memory on this machine without problem.

This isn't at all impressive if you're used to working with "big data" or parallelized computing, but being able to manipulate and analyze millions of rows of data in memory using R is pretty sweet.

I used to do some professional event photography in NYC, so I have a couple Canon SLRs, and my [5D MkII][eos-5d-mark-ii] is my favorite. I typically pair that with my [Canon 50mm f/1.2 L lens][ef-50mm-f1.2l-usm], which I think is possibly one of the greatest lenses ever made, and shoot using manual focus in low light. I hear the MkIII's autofocus is incredible, so I've been contemplating an upgrade.

### And what software?

I spend most of my time working with text and code, and since I'm a [vim][] guy, I use [Sublime Text 2][sublime-text] with vintage mode turned on. It isn't a perfectly faithful translation of vim, but it's good enough for most of my habits. Combining ST2's multi-cursor support with vim controls is mind-blowing if you haven't tried it before. Slicing and dicing code with a dozen cursors in realtime using vim commands is way more fun than writing regular expressions. It's revelatory, really, and allows me to look past all of ST2's other shortcomings (of which aren't all that many).

I recently switched to [oh-my-zsh][], which is a terrific "modern" shell that supports many wonderful helpers, conveniences, and themes. My current zsh theme is "crunch" which surfaces the status of the git repo I may be in, the [Ruby][] version I'm working with, and the current timestamp inside my shell prompt.

Aside from RStudio, Hadley Wickham's libraries for R are essential. I make all of Kickstarter's static graphs using [ggplot2][], but couldn't live without his [plyr][], [reshape][], or [lubridate][] packages.

Since a lot of my day-to-day data work begins with writing a SQL query, I use [Sequel Pro][sequel-pro] extensively. The new version's icon is excellent, but other good features include the ability to save and export query lists, and good CSV export control. If you're writing SQL frequently and not using Sequel Pro, you're crazy.

### What would be your dream setup?

If it existed (and it probably won't, ever), a 30" external retina screen driven by a 13" Macbook whose video card isn't underpowered and also has infinite system RAM.

Other than that, I'm pretty happy with my current setup.

[ec2]: https://aws.amazon.com/ec2/ "A web service for virtualised processing."
[ef-50mm-f1.2l-usm]: https://www.usa.canon.com/cusa/consumer/products/cameras/ef_lens_lineup/ef_50mm_f_1_2l_usm "A standard and medium telephoto camera lens."
[eos-5d-mark-ii]: http://web.archive.org/web/20151104220940/http://www.usa.canon.com/cusa/support/consumer/eos_slr_camera_systems/eos_digital_slr_cameras/eos_5d_mark_ii "A 21 megapixel DSLR."
[ggplot2]: http://web.archive.org/web/20180506153516/http://ggplot2.org:80/ "A plotting system for the R language."
[imac]: https://www.apple.com/imac-24/ "An all-in-one computer."
[kickstarter]: http://web.archive.org/web/20221227013734/https://www.kickstarter.com/ "A service for crowdfunding projects."
[lubridate]: https://github.com/tidyverse/lubridate "An R package for working with dates and time."
[mac-pro]: https://www.apple.com/mac-pro/ "The Intel-based Mac tower computer."
[macbook-pro]: https://www.apple.com/macbook-pro/ "A laptop."
[oh-my-zsh]: https://github.com/ohmyzsh/ohmyzsh "A framework of extensions and themes for the zsh shell."
[plyr]: http://plyr.had.co.nz/ "A split-apply-combine tool."
[r]: http://www.r-project.org/ "Software for statistical computing and graphics."
[reshape]: http://had.co.nz/reshape/ "An R package for munging and aggregating data."
[rstudio]: https://posit.co/ "An IDE for the R language."
[ruby]: https://www.ruby-lang.org/en/ "An interpreted scripting language."
[sequel-pro]: http://www.sequelpro.com/ "A MySQL GUI for the Mac."
[sublime-text]: http://www.sublimetext.com/ "A coder's text editor."
[vim]: https://www.vim.org/ "A command-line text editor."
