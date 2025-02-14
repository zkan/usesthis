---
title: Dave Jones
summary: Electrical engineer, video blogger (EEVblog)
date: 2013-05-09
categories:
- engineer
---

### Who are you, and what do you do?

I'm Dave Jones, and I'm a full time video blogger at the [EEVblog](http://www.eevblog.com/ "The EEVblog."). I live in Sydney, Australia, and record my shows in a purpose designed
lab (nerd cave!) a few minutes from home.

I make a living making niche Electronics Engineering [YouTube][] videos for other electronics nerds like me. I've been doing this video blog for 4 years, and now 2 years full time since the tech company I worked for packed up and moved to China. All of my video is non-scripted off-the-cuff. I don't know what I will say until I hit record.

I also host a weekly engineering internet podcast radio show called
[The Amp Hour](http://www.theamphour.com/ "Dave and Chris' podcast."). My co-host Chris Gammell is based in Cleveland, Ohio.

### What hardware do you use?

A [Canon HF G10 video camera][vixia-hf-g10] is my main blogging camera, with a mix of microphone solutions. One of the biggest things I have learned about video blogging is that audio can be more important than video. People will watch crap video quality with good audio, but they won't want to watch top quality video with crap audio. I have fallen back to using the internal mic in the HF G10 a lot now for close-up, behind the camera commentary. Usually internal mics in cameras are crap, but this Canon has done the audio right - the mics are first class.

An external [Rode VideoMic][videomic] pro shotgun mic (Australian made!) is used for interviews and other field work. And an [Audio Technica ATR-3350 lapel mic][atr-3350] is used for talking head work in front of the camera. Curiously, the shotgun mic doesn't work well in my lab/office environment. The aircon noise (peaks at 215Hz, based on the aircon ducting size and length!) in the ceiling from the other offices comes through too loud on the audio track and is distracting. The lapel mic works much better in this situation, even though I'm only 1m from the shotgun mic. The 6m cable on the lapel mic is really handy for moving around the lab while still wired up. 

For field work I also have a pair of [Audio Technica Pro 88W][pro-88w] wireless mics that go into an [Azden CAM-3 passive mixer][cam-3]. Two are useful for on-camera interviews. The Canon HF G10 can mix the internal mic with the external, and this comes in handy for field work as well.

Some bloggers will record audio separately with a handheld recorder, but this kills your editing productivity. Great for a Hollywood feature film, useless for regular blogging. You have to sync that audio for every clip, and try doing that for 200 clips in a 1hr video blog and it'll take you a week to edit one video! So I record all audio in-camera. I also try to get the audio levels right in-camera (using the on-camera VU meter), so I have very little levelling work to do in the editing process.

I shoot at a fixed bit rate of 12Mbps AVCHD in 1440 x 1080 in order to save on file space. The 1920x1080 at 24Mbps my camera is cable of is simply not needed when you are dealing with YouTube and mostly non-fast motion material.

Most video cameras are useless at really close macro shots, so I use an [Opteka x10 macro lens][10x-high-definition-ii] for this. Essential for close-up shots of electronics PCBs.

My B-Roll camera is a [Canon HF-M400][vixia-hf-m400], sometimes useful for cutaway shots. It's an older model that I had to deliberately get because the latest model used a different battery to my HF G10, and that simply wasn't acceptable. Nothing worse than having to manage two different sets of batteries and chargers.

My two tripods are both Manfrotto Modo Maxi 785B for compatibility with each other. I found that you can insert the camera stem upside down and turn this into an upside down microscope (with macro lens). Great for vertical close-up shots.

All of my video is shot in-sequence, even if I move the tripod 20 times, and attach and re-attach the macro lens a dozen times. You save a huge amount of time in the video editing process by doing this.

I use a [Samson C01U USB mic][c01u] for computer capture work, and also my radio show. With a pop filter of course. I have the same mic at home and the office so I can desktop record at both locations and have the same sound. I have [home-made acoustic absorption panels](http://www.youtube.com/watch?v=JQLDIrS8deU "Dave's YouTube video about DIY acoustic sound panels.") in my home recording studio to stop reflections.

### And what software?

Almost all my editing is done in Sony [Movie Studio Pro 12][vegas-pro]. It's cheap consumer-level editing software, but I don't do anything fancy. If you are doing fancy editing, then I think you are probably doing video blogging wrong! My workflow consists of taking the AVCHD files directly from the camera and dragging them onto my editing timeline. I then trim the dead space at the start and end of each video clip, and remove the occasional goofed clip. I might tweak the audio level of the odd clip, and occasionally add some text overlay explanations, but that's pretty much it for editing. Like I said, about as basic an editing requirement as you can get, and that's how I like it. And because I go to the trouble of shooting almost everything in sequence if possible, I don't have to spend hours figuring out which video clip goes in what order, I just drag all the clip to the timeline and the job is done in a few seconds. When some of my videos are over an hour long, with up to 200 clips, that's a HUGE deal!

I output from Sony Movie Studio in a matching fixed 12Mbps Sony AVC MP4 format that matches the input clip bitrate. Movie Studio (and most other editing software) is useless at outputting video in formats suitable for upload to YouTube, unless you have infinite upload Internet speed! They all lack a feature called Constant Quality, which changes the bitrate on a frame by frame basis based on the content in the frame. So fast-moving images take more space (less compression), and still images (like my talking head) take less space (more compression). Instead, they only offer fixed, and average/peak rates. So you usually end up with either a massively overkill output file size, or too heavy a compression that ruins moving image material.

So I render at a high bit rate in Sony and then use [Handbrake][] to convert this large output file into a Constant Quality H.264 MP4 file suitable for YouTube. I use a CQ setting of 22 for a 1920x1080 master I upload to YouTube. The Handbrake file is the same quality, but much smaller in file size - and that matters when you are uploading HD content to YouTube on a daily basis. I also use Handbrake to produce a smaller 640x360 H.264 [iTunes][]-compatible file (CQ=26) for a podcast version of my show (some people like to watch on their phones, etc.) I have some custom scripts to ensure that the same settings are used each time, and I can simply drag my file onto a desktop icon and it does the rest.

I occasionally use [Corel VideoStudio][videostudio-pro] for footage I need to speed up and/or do some fancy effect with that I can't do in Sony.

For computer tutorials I screen capture using [Camtasia][]. It's got a file compatibility issues with Sony, but otherwise works great. I ensure that I screen capture at precisely 1280x720 (16:9 aspect) so that there is no scaling required in the video editing software. That produces nice and sharp screen text when viewing the final video. This is a big mistake that screen capture noobs make. I've also found that full HD 1920x1080 screen capture is just too much - the text ends up being too small to view in standard definition 640x360 playback on YouTube. 1280x720 is the sweet spot.

For the podcast radio show we use [Audacity][], a free open source audio program. We used to use [Skype][] for real-time chatting during the show, but the quality just wasn't there. We now use [Mumble][] instead and the sound quality is a huge improvement over Skype or [Google Talk][google-talk]. We rent a small server for this for a few bucks a month, and it allows guests to join the show and we can record their audio directly from Mumble in great quality. This frees the host from having to know how to record locally. We record our own audio locally using Audacity, and just use Mumble as the communications medium. Each recording is put through [The Levelator][the-levelator], which automagically fixes all our audio issues. This is done before the two or three audio clips are merged in Audacity.

### What would be your dream setup?

A tribe of intelligent thought-reading monkeys to do everything for me!

People keep telling me to "step up" to DSLR for video, but the simple fact is that whilst they are great if you are shooting a documentary and have all the time in the world to shoot and edit it, DSLRs are simply not as convenient as a proper video camera for the video blogging work I do. The lack of good audio features, articulating screens, good auto focus while zooming, form factor, recording time limitations, and a host of other small things that you take for granted on even the cheapest video camera all add up to just annoyance. But most of my dream setup doesn't exist, regardless of price it seems, so this is just what I'd wish was available to tweak my setup and workflow.

I would love my video camera to have a tally light, and a really easy way to replay (and maybe delete) each clip. Most video cameras are so annoying at this, you end up not bothering to check anything until you go to edit it.

I would kill for video editing software that automagically trims the dead space of the start and end of each clip I drop into the timeline. That would save me 80% of my video editing work. It's technically possible (detect no audio and cut it out), it's just that no one seems to do it.

Purpose designed dolly camera rail on my bench, with an articulating arm so I can shoot footage from above the bench so the tripod doesn't get in the way. I have parts for this, I just need to build it...

Diffused lights that just float in mid air, and you can easily position them anywhere you want. Nothing more annoying than a reflection off your ceiling lights off the thing you are shooting.

Internet upload speed as fast as my download speed. I have the fastest cable home Internet in this country (100Mbps download, 3Mbps upload), and the upload speed is just ridiculously slow for HD video upload. Internet companies offer no options for content producers like me, they just assume that everyone wants to download everything. "Upload, why do you need that Sir?"

A super fast quadzillion-core PC that renders video super quick. My current rate is about real time, so a 1hr video takes an hour to render + Handbrake conversion + upload.

A video editor that auto-levelled each clip's audio seamlessly without any effort.

Infinite bandwidth between my office PC and home PC. At the moment my only option for HD video files is SneakerNet.

A software tool that allows me to easily respond to YouTube comments in a logical and quick manner. The YouTube comment system is nothing short of retarded.

An acoustically quiet and damped lab to work (and shout!) in. Preferably a huge separate garage out the back of my house.

[10x-high-definition-ii]: http://web.archive.org/web/20190730034302/http://opteka.com:80/10x.aspx "A macro lens for SLRs."
[atr-3350]: http://www.audio-technica.com/en-us/atr3350 "An omnidirectional microphone."
[audacity]: https://sourceforge.net/projects/audacity/ "An open-source, cross-platform audio editor."
[c01u]: https://www.samsontech.com/samson/products/microphones/usb-microphones/c01u/ "A studio condenser microphone."
[cam-3]: http://web.archive.org/web/20190506112032/https://www.amazon.com/AZDEN-CAM-3-On-Camcorder-Audio-Mixer/dp/B00006JPD1 "A mini audio mixer."
[camtasia]: https://www.techsmith.com/video-editor.html "Screencasting software."
[google-talk]: https://en.wikipedia.org/wiki/Google_Talk "Google's own audio/video/text chat system."
[handbrake]: https://handbrake.fr/ "Cross-platform, open source video encoding software."
[itunes]: https://www.apple.com/itunes/ "A jukebox application and online store."
[mumble]: https://wiki.mumble.info/wiki/Main_Page "Voice chat software."
[pro-88w]: http://www.audio-technica.com/en-us/microphones/wireless-systems/line-series/pro-88w "A wireless microphone system."
[skype]: https://www.skype.com/en/ "Voice and video chat software."
[the-levelator]: https://en.wikipedia.org/wiki/Levelator "Software for auto-adjusting the levels in audio."
[vegas-pro]: https://en.wikipedia.org/wiki/Sony_Vegas_Pro "A non-linear video editing suite."
[videomic]: http://www.rode.com/microphones/videomic "A condenser shotgun microphone."
[videostudio-pro]: https://www.videostudiopro.com/en/products/videostudio/pro/ "Video editing software."
[vixia-hf-g10]: http://web.archive.org/web/20230408022412/http://www.amazon.com/Canon-G10-Camcorder-Internal-Memory/dp/B004HW7DZM "An HD camcorder."
[vixia-hf-m400]: http://web.archive.org/web/20210419090101/http://www.amazon.com/Canon-M40-Camcorder-Internal-Memory/dp/B004HW7E3I/ "An HD camcorder."
[youtube]: https://www.youtube.com/ "A web site for watching 80's TV commercials and bad mashups."
