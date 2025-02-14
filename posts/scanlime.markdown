---
title: Micah Elizabeth Scott
summary: Hardware and software hacker
date: 2012-12-20
categories:
- developer
- hacker
- mac
---

### Who are you, and what do you do?

My name is [Micah Elizabeth Scott](http://scanlime.org/ "Micah's website."). I've been doing unconventional things with technology for as long as I can remember, often exploring the boundaries between software and hardware. I've built satellites, robots, virtual machines, graphics drivers, CPU emulators, networking stacks, USB controllers, reverse engineering tools, and pretty much everything in-between.

I worked at VMware for six years, doing mostly USB and [GPU virtualization](http://scanlime.org/2008/12/gpu-virtualization-at-wiov-08/ "Micah's post on GPU virtualisation."). For about the last year, I've been at [Sifteo](https://www.sifteo.com/ "Sifteo's website.") building a new kind of video game console. Now I'm following my own path for a while, exploring ways to mix software, hardware, and art.

### What hardware do you use?

I have a strange relationship with hardware. My hobbies and career tend to revolve around using tools and producing things, but I tend towards minimalism in my own life. So, my favorite hardware is whatever can follow me around when I need it to, and stay out of the way otherwise.

These days I do nearly all of my design and coding work on a 13" [MacBook Air][macbook-air] from 2010. The CPU certainly isn't the fastest thing ever, but the SSD still makes it feel fast, at least when it comes to compiling code or editing photos. It's really important to me that I have a computer that I can carry anywhere. I live in San Francisco, and I often feel like the whole city is my living room and office. Keeping the scenery fresh helps me feel less disconnected from the world when I'm deep inside my work.

Depending on how much I need to carry, I'll pack the lappy in either a small [Tom Bihn Ristretto][ristretto-13-inch] bag or my custom [Chrome Citizen][custom-citizen] bag. The latter has plenty of room for a few extra layers of clothing, all of the laptop accessories I could want, a sketchbook, and whatever random hardware I'm tinkering on.

When I do work from my own desk, I dock the laptop with a [Dell U2711][u2711]. I see it as an alternative to the Apple 27" [Cinema Display][cinema-display], but with more than one input. I like inputs. Also, pixels.

The monitor feels like a nice luxury, but really the most important reason to have a work bench is for the bench-top power supply. I have a [BK Precision 1621A][1621a], which is rated for up to 15V and 5A. Before I owned a proper bench-top supply, I thought it was just a nice-to-have. I was content to power my projects off of wall-warts or [hacked up ATX power supplies](http://www.wikihow.com/Convert-a-Computer-ATX-Power-Supply-to-a-Lab-Power-Supply "An article on converting an ATX power supply to a lab power supply."). But seriously, current limiting rocks. It's not just for charging batteries or smoke-testing a new PCB. It's confidence. If your current limit is set properly, it is _much_ harder to accidentally fry whatever circuit you're working on. Just like revision control and unit test suites can give me more confidence to take risks and get messy with software, a good power supply is a safety net that gives me more confidence to experiment with hardware.

I'm a visual learner, and I get the most out of my experiments if I can see the results in real-time. So, I'm a bit of a test equipment junkie. I love a good oscilloscope and logic analyzer. My current setup compromises quality for portability, though. I've [been using](http://scanlime.org/2008/08/new-oscilloscope/ "Micah's post on using the BS100U.") a [BitScope BS100U][bs100u] for the past four years. It has two analog channels, 8 digital channels, and 50 MSPS capture. I like the small size and the ability to work with analog and digital signals simultaneously. But really, I'm ready for an upgrade.

My multimeter is a [Fluke 179][179], and I'm extremely happy with it. I think I've managed to convince most of my employers to buy these meters for the office too, because they're just so reliable. A multimeter is something I prefer to put some trust into, and this is a meter that hasn't let me down yet.

My two favorite hand tools have got to be my [Weller WES51][wes51] soldering station and a really sharp X-Acto knife. For surface mount work, I have an [Atten 850B][850b] rework station, and for the really tiny [PCB surgery](http://www.flickr.com/photos/micahdowty/3894260058/ "A photo of Micah's PCB surgery work.") work I bought a 7X-45X stereo zoom microscope. This has become one of my favorite tools. For me, owning a microscope that you can use hand tools under has been a really amazing enabler, allowing me to work at much smaller scales than I could otherwise.

I own several pairs of tweezers, with various levels of sharpness. I have an extremely fine-point pair with ESD protection, for doing the most delicate SMT work. I have two general-purpose pairs, and another slightly less delicate pair that still has an extremely sharp point. When working at a small scale, these are my hands. I'll often use two pairs of tweezers or one tweezer and one X-Acto knife to manipulate small parts under the microscope. The general-purpose tweezers find uses ranging from pulling jumpers out of breadboards to pulling plastic scraps out of my 3D printer.

For "rapidly" prototyping plastic parts, I've been experimenting with DIY 3D printers for a while. I bought a [MakerBot Thing-o-Matic][thing-o-matic] when they were new, but I immediately ran into trouble with the unreliable extruder motors on that first manufacturing run. I made several upgrades to the printer, most importantly replacing the extruder with a MakerGear stepper extruder and a 0.25mm nozzle. After all of this upgrading, my printer has a pretty respectable resolution at 150 microns per layer. On the downside, it's an incredibly slow, noisy, and unreliable machine.

### And what software?

I find it really hard to get attached to software. I've seen how the sausage is made, and my tenure at VMware has shown me the ugliest sides of every operating system. I've had brief stints of using Windows. I used to use Linux almost exclusively. Now I've been mostly using [Mac OS][macos]. But really, I see all operating systems as a necessary annoyance.

I have fewer opinions on text editors than most software engineers I know. I used to use [emacs][] for coding but [vim][] for most other tasks. Nowadays, I tend to use [Sublime Text 2][sublime-text] for nearly everything. What can I say, I'm a sucker for the mini-map.

For 3D illustration and solid modeling, I've mostly been using [Blender][] and [OpenSCAD][], though I've been wanting to learn [Rhino][] and [SolidWorks][] too.

For 2D illustration, I'll use some combination of [Inkscape][], [OmniGraffle][], and [Adobe Illustrator][illustrator]. I'm most familiar with Inkscape, but I've found OmniGraffle to be fantastic for [illustrating software documentation](https://developers.sifteo.com/docs/SifteoSDK/0.9.8/gfx.html "Some of Sifteo's SDK documentation.").

For pixel graphics, I've had the most experience with [GIMP][], but I've largely switched from GIMP to [Photoshop][] recently. I use [Aperture][] to develop and organize my photos.

I won't hesitate to drop down to [C++][c-plusplus] or assembly language when it's necessary, but when I can pull it off, I have the most fun writing [Python][]. Lately I've been enjoying [Lua][] too, mostly for its stellar embedding API.

I like building my own tools, and a lot of my favorites are data visualization and simulation tools I've built for specific purposes. As a really visual person, I love creating new ways to see inside of complex systems in real-time.

I find [Evernote][] to be highly useful for keeping my life organized. I use it for todo lists, nascent ideas, travel plans, and anything else I want to be able to edit and see on any device.

### What would be your dream setup?

My dream setup would really be more of an anti-setup. I'd love to have a community space full of great tools that I don't own. More storage space, nicer test equipment, and other like-minded creative folks to bounce ideas off of.

Of course I'd love to have a faster and higher quality 3D printer that breaks less, a faster oscilloscope, access to a fast laser-cutter. A spectrum analyzer and software defined radio would be really indispensable for working on wireless electronics.

I'd love a laptop that's faster and has more pixels. Perhaps a [MacBook Pro][macbook-pro] with retina display, but I feel like portability is still by far the most important factor for me. My ideal laptop would be a 13" MacBook Air with a retina display, built-in LTE wireless, and the fastest CPU and biggest SSD I could get. It would also be great to have a really low-latency way of offloading big jobs to the cloud.

Really I'd love to work from a cafe/warehouse/beach/desert, on battery power, with a server elsewhere running my giant render or compile.

[1621a]: http://web.archive.org/web/20220923142045/https://www.bkprecision.com/products/power-supplies/1621A-0-to-18v-0-to-5a-digital-display-dc-power-supply.html "A DC power supply."
[179]: https://www.fluke.com/en-us/product/electrical-testing/digital-multimeters/fluke-179 "A digital multimeter."
[850b]: http://web.archive.org/web/20190506101255/https://www.amazon.com/850B-SMT-REWORK-STATION-SOLDER/dp/B000E14FJW "A soldering station."
[aperture]: https://en.wikipedia.org/wiki/Aperture_(software) "Photo editing and management software for Mac OS X."
[blender]: https://www.blender.org/ "A free, open-source 3D renderer."
[bs100u]: http://www.brilldea.com/product_BS100U.html "A USB oscilloscope."
[c-plusplus]: https://en.wikipedia.org/wiki/C%2B%2B "A compiled programming language."
[cinema-display]: https://en.wikipedia.org/wiki/Apple_Cinema_Display "An LCD display."
[custom-citizen]: https://chromeindustries.com/us/en/customs "A bike bag."
[emacs]: http://www.gnu.org/software/emacs/ "A free open-source text editor."
[evernote]: https://evernote.com/ "Online software for capturing notes."
[gimp]: https://www.gimp.org/ "An open-source image editor."
[illustrator]: https://www.adobe.com/products/illustrator.html "A vector graphics editor."
[inkscape]: https://inkscape.org/ "An open-source vector graphics program."
[lua]: http://www.lua.org/ "An interpreted scripting language."
[macbook-air]: https://www.apple.com/macbook-air/ "A very thin laptop."
[macbook-pro]: https://www.apple.com/macbook-pro/ "A laptop."
[macos]: https://en.wikipedia.org/wiki/MacOS "An operating system for Mac hardware."
[omnigraffle]: https://www.omnigroup.com/omnigraffle/ "Diagramming software for the Mac."
[openscad]: http://openscad.org/ "Open-source 3D CAD software."
[photoshop]: https://www.adobe.com/products/photoshop.html "A bitmap image editor."
[python]: https://www.python.org/ "An interpreted scripting language."
[rhino]: https://www.rhino3d.com/ "3D modelling software."
[ristretto-13-inch]: http://transportr.io/redirect/f17f9280-18af-4999-afb4-994230ba9768 "A laptop bag."
[solidworks]: https://www.3ds.com/products/solidworks "Modelling/CAD software."
[sublime-text]: http://www.sublimetext.com/ "A coder's text editor."
[thing-o-matic]: https://www.makerbot.com/stories/2010/09/25/announcing-makerbots-new-3d-printer-the-thing-o-matic/ "A 3D printer."
[u2711]: http://web.archive.org/web/20221206090348/http://www.amazon.com/Dell-UltraSharp-U2711-27-inch-Widescreen/dp/B0039648BO "A 27 inch widescreen LCD monitor."
[vim]: https://www.vim.org/ "A command-line text editor."
[wes51]: http://web.archive.org/web/20230315042353/https://www.amazon.com/Weller-WES51-Analog-Soldering-Station/dp/B000BRC2XU/ "A soldering station."
