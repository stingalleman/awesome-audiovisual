
# Awesome Audiovisual [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Curated list of awesome audiovisual projects

Want to add something? Just make a pull request, but be sure to follow the [contributing guidelines!](./contributing.md) (Also, if you don't have a github account, feel free to [email me.](mailto:stingalleman@icloud.com?subject=Awesome-Audiovisual%20contribution))
Question? Leave it in the [General Discussion issue.](https://github.com/stingalleman/awesome-audiovisual/issues/2)

## Contents

- [Lighting](#Lighting)
  - [Lighting Software](#Lighting-Software)
- [Audio](#Audio)
  - [Audio Software](#Audio-Software)
  - [Audio tools](#Audio-tools)
- [Video](#Video)
  - [Video Software](#Video-Software)
    - [Playout And Switching](#Playout-And-Switching)
    - [Control and Orchestration](#Control-and-Orchestration)
  - [Protocols](#Protocols)
  - [Video Tools](#Video-Tools)
- [Tools](#Tools)
  - [Timecode](#Timecode)
  - [Monitoring](#Monitoring)
- [Libraries](#Libraries)
  - [ArtNet Libraries](#ArtNet-Libraries)
- [Hardware](#Hardware)
- [IP-Audio + IP-Video](#IP-Audio-+-IP-Video)
- [Tutorials](#Tutorials)
  - [GrandMA2 tutorials](#GrandMA2-tutorials)
- [Blogs and other resources](#Blogs-and-other-resources)
- [Graphics](#Graphics)
- [Misc/other](#Misc/other)

## Lighting

### Lighting Software

- [Chamsys MagicQ](https://chamsyslighting.com/) - MagiQ is a professional lighting software providing up to 64 Artnet universes for free. It includes powerful features like 2D/3D pixel mapping, effect generator, media server and visualizer.
- [Dot2 software](https://www.malighting.com/downloads/products/dot2/) - Free, offline software for the Dot2 consoles. Inclused Dot2 onPC and Dot2 3D.
- [GrandMA2 software](https://www.malighting.com/downloads/products/grandma2/) - Free, offline software for the GrandMA2 lighting console. Inclused GrandMA2 OnPC and MA3D.
- [GrandMA3 software](https://www.malighting.com/downloads/products/grandma3/) - Free, offline software for the **new** GrandMA3 lighting console. Inclused GrandMA3 OnPC.
- [Open Lighting Architecture](https://www.openlighting.org/ola/) - A framework for lighting control information. Supports a range of protocols and over a dozen of USB devices.
- [QLC+](https://www.qlcplus.org/) - QLC+ is a free and cross-platform software to control DMX or analog lighting systems like moving heads, dimmers, scanners etc.
- [xLights](https://xlights.org/) - Meant for home Christmas light shows but is a great way to sync lights to music on a budget.

## Audio

### Audio Software

- [Audacity](https://www.audacityteam.org/) - Audio file editor and analysis tool, great for cropping down sound effects and music tracks.
- [Ardour](https://ardour.org/) - A full realtime audio recording and editing suite
- [da-Share MultiPlay](https://www.da-share.com/software/multiplay/) - MultiPlay is a Windows based program designed to play audio cues for theatre or corporate use. It is free to use.
- [Linux Show Player](https://www.linux-show-player.org/) - Free cue player designed for stage productions.
- [QLab](https://qlab.app/) - QLab is sound, video, and lighting control for macOS.
- [REAPER](https://www.reaper.fm/) - REAPER is a complete digital audio production application for computers, offering a full multitrack audio and MIDI recording, editing, processing, mixing and mastering toolset. 

### Audio tools

- [REW](https://www.roomeqwizard.com/) - REW is free room acoustics analysis software for measuring and analysing room and loudspeaker responses. Free SMAART alternative.

## Video

### Video Software

- [Blender](https://www.blender.org/) - Blender is the free and open source 3D creation suite. It supports the entirety of the 3D pipeline—modeling, rigging, animation, simulation, rendering, compositing and motion tracking, video editing and 2D animation pipeline.

#### Playout And Switching

- [CasparCL](https://github.com/Streampunk/casparcl) - Implementing the features of CasparCG with Node.JS and OpenCL.
- [CasperCG](https://github.com/CasparCG) - CasparCG Server is a Windows and Linux software used to play out professional graphics, audio and video to multiple outputs as a layerbased real-time compositor.
- [OBS Studio](https://github.com/obsproject/obs-studio) - Free and open source software for live streaming and screen recording
- [VLC Media Player](https://www.videolan.org/vlc/index.html) - Simple to use video player packed with features and plays almost every file type with no need to install codecs.

#### Control and Orchestration

- [Bitfocus Companion](https://github.com/bitfocus/companion) - Bitfocus Companion enables the reasonably priced Elgato Streamdeck to be a professional shotbox surface for an increasing amount of different presentation switchers, video playback software and broadcast equipment.
- [Director](https://github.com/borealsystems/Director) - Facility scale media orchestration and automation.

### Protocols

- [OBS Websocket](https://github.com/Palakis/obs-websocket) - WebSocket API for OBS Studio.

### Video tools

- [OBS-VirtualCam](https://github.com/CatxFish/obs-virtual-cam) - OBS-VirtualCam is a plugin for obs-studio , transforming the output video to a virtual directshow device.
- [StreamSizeCalculator](https://github.com/fschoett/2110-20-stream-size-calculator) - This is a tool to calculate network requirements for streaming 2110-20 video.

## Tools

- [Livescript](https://github.com/Netlob/livescript) - Insert a musical/theatre-script from Google Docs and use this for a live "autocue" and scroller with everyone on the site
- [StageClock](http://notelek.com/StageClock/) - StageClock is a Java based graphical timekeeping application. It outputs a clean feed from an attached monitor, and has time/date, timer, and show information.

### Timecode

- [TCgenerator](https://github.com/dimitriCGNL/TCGenerator) - Reaper time marker to GrandMA2 TC Generator
- [Timecode](https://github.com/MrExplode/Timecode) - ArtNet and LTC timecode generator, made with Java.
- [M2Q](https://github.com/lorenzofattori/M2Q) - Python application capable to trigger Chamsys Consoles/Software via MIDI for advanced synchronized shows.

### Monitoring

- [AES67 WebMeter](https://github.com/zjstraus/AES67-WebMeter) - Server that receives an AES67 audio stream and presents a webpage with meters
- [meters.lv2](https://github.com/x42/meters.lv2) - meters.lv2 is a collection of audio-level meters with GUI in LV2 plugin format.

## Libraries

- [node-dmx](https://github.com/node-dmx/dmx) - DMX controller library for node.js

### ArtNet Libraries

- [artnet](https://github.com/hobbyquaker/artnet) - Node.js module that can be used to send ArtDMX packages to an Art-Net node.
- [artnet4j](https://github.com/cansik/artnet4j) - Art-Net DMX over IP library for Java and Processing

## Hardware

See [HARDWARE.md](./HARDWARE.md)

## IP-Audio + IP-Video

- [AES67 Linux Daemon](https://github.com/bondagit/aes67-linux-daemon) - AES67 Linux Daemon is a Linux implementation of AES67 interoperability standard used to distribute and synchronize real time audio over Ethernet.
- [AES67 SAP nmos gateway](https://github.com/yboujraf/AES67_SAP_nmos_gateway) - An NMOS IS-04 implementation built around discovering AES67 streams announced with SAP (dante devices in AES67 mode).
- [OBS-ndi](https://github.com/Palakis/obs-ndi) - Network A/V in OBS Studio with NewTek's NDI technology.
- [SAP Receiver](https://github.com/jonasohland/sap-receiver) - Receive and store SDPs for AES67 SAP announcements
- [ST-2110 software toolkit](https://github.com/pkeroulas/st2110-toolkit) - This toolkit provides scripts and config to test, monitor and transcode SMPTE ST 2110 streams

## Tutorials

### GrandMA2 tutorials

- [GMA2 colour picker tutorial](https://www.youtube.com/watch?v=lhYDUzWKz3M) - a tutorial for how to add a colour picker in GrandMA2

## Blogs and other resources

- [Chamsys Programmers and Users facebook group](https://www.facebook.com/groups/chamsys.users/) - The best place to find information about Chamsys consoles and software.
- [Christian Jackson](https://www.youtube.com/channel/UCdLor-EVzOjOY7OZNXt8eIw) - YouTube channel about concert lighting. Also has great MA tutorials.
- [Geezers of Gear](https://geezersofgear.libsyn.com/) - Entertainment Production Industry veteran talking about pro-audio, lighting, staging, video + the people and companies who work in this great industry.
- [@limelightwired](https://www.instagram.com/limelightwired/) - Lighting production community on Instagram.
- [mikewoodld.com/blog/](https://www.mikewoodld.com/blog/) - Blog of Lighting Designer Mike Wood.
- [notelek.com/blog/](http://notelek.com/blog/) - LXR Stage Technology Blog.
- [QLab Cookbook](https://qlab.app/cookbook/) - The cookbook is a collection of projects, examples, and experiments using a broad range of QLab programming techniques including AppleScript, OSC, external control using QLab Remote, third-party MIDI and OSC controllers, and other software.
- [/r/lightingdesign](reddit.com/r/lightingdesign/) - The Reddit community for lighting designers worldwide.
- [/r/techtheatre](reddit.com/r/techtheatre/) - The reddit community for all production designers and technicians!

## Graphics

- [GIMP](https://www.gimp.org/) - GIMP is a cross-platform image editor available for GNU/Linux, OS X, Windows and more operating systems.
- [Inkscape](https://inkscape.org/) - Inkscape is a professional vector graphics editor for Linux, Windows and macOS.

## Misc/other

- [Blender ArtNet](https://github.com/BryanCrotaz/blender-artnet) - Blender script to push ArtNet data to Evee lights. Runs at 30fps with Evee rendering in the viewport.
- [Linux](https://en.wikipedia.org/wiki/Linux) - A free operating system that can run on pretty much every kind of computer and is great for breathing new life into old computers that aren't supported by the newer Windows editions. There's tons of different distributions to choose from, each have their own benefits and drawbacks. The most common one for general computer stuff is [Ubuntu](https://ubuntu.com/).
- [tonsofpcs/gvg110](https://github.com/tonsofpcs/gvg110)

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, Sting Alleman has waived all copyright and related or neighboring rights to this work.
