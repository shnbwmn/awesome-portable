
# Awesome Portable [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> Curated list of awesome portable apps.

*More to come! It will take a while!*

Create a [pull request](https://github.com/shnbwmn/awesome-portable/pulls) to add programs | Start an [issue](https://github.com/shnbwmn/awesome-portable/issues) for corrections or discussions

_See also:_ [**Awesome Portable Games**](https://github.com/shnbwmn/awesome-portable-games), [**Awesome Online**](https://github.com/shnbwmn/awesome-online), [**Awesome Mobile**](https://github.com/shnbwmn/awesome-mobile)

**_Portability:_** [*tpfc*](https://www.portablefreeware.com/about.php), [*paf*](http://portableapps.com/about/what_is_a_portable_app)
* **No installation required** / can be unzipped | [extracted](https://www.portablefreeware.com/faq.php#extract) | files copied from an installation
* Runs **self-contained** / makes no changes to host computer outside of program folder
* Saves **main settings to program directory** / not home directory | AppData | registry
* **No third-party dependencies** / with some exceptions, like [.NET](https://www.microsoft.com/net/download/framework) | [Visual C++](https://support.microsoft.com/en-za/kb/2977003) | admin rights where necessary
* [**Stealth:**](https://www.portablefreeware.com/faq.php#stealth) no registry or filesystem items left on the host PC after program exit / ideal

**_Testing for portability:_**
* [Windows portability testing environment](https://www.portablefreeware.com/forums/viewtopic.php?t=21885)
* [**Dependency Walker**](http://www.dependencywalker.com/) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?p=28309), [*thumb*](http://www.thumbapps.org/2015/03/Dependency-Walker-Depends-portable.html), [*sf*](https://sourceforge.net/projects/thumbapps/files/Development/Dependency%20Walker/), [*wiki*](https://en.wikipedia.org/wiki/Dependency_Walker) / also known as *depends.exe*
* [**Primo**](http://members.tripod.com/~randy_hall/download.htm) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?t=8164)
* [**Sandboxie**](http://www.sandboxie.com/) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?t=4130) / isolate a running program to show files | registry entries created / install programs requiring installation inside a sandbox
* [**Virtualbox**](https://www.virtualbox.org/) / [*vbox*](http://www.vbox.me/) / run programs in a clean Windows installation to check for dependencies

**_Tools:_**
* [**LessMSI**](http://lessmsi.activescott.com/) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?p=30045) / extracts MSI installers
* [**Universal Extractor**](http://www.lupopensuite.com/db/universalextractor.htm) | [**Bioruebe**](http://bioruebe.com/dev/uniextract/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=2764) / extracts most program installers
* [**JPortable**](http://portableapps.com/apps/utilities/java_portable) | [**Launcher**](http://portableapps.com/apps/utilities/java_portable_launcher) / run JAR executables portably
* [**Adobe Flash Portable**](https://rejzor.wordpress.com/portable-adobe-flash/) | [**Alt**](http://notepad.patheticcockroach.com/4029/flash-player-12-for-portable-browsers-32-and-64-bits/) / latest Flash DLLs for portable browsers
* [**SmallestDotNET**](http://smallestdotnet.com/) / to get .NET installed quickly
* [**WinPCap**](http://www.winpcap.org/) / required, via installation or `wpcap` | `Packet` DLLs, by some network programs

**_Portabilisation projects:_**
* [**PortableApps**](http://portableapps.com/) / [*paf*](http://portableapps.com/development/portableapps.com_format)
* [**ThumbApps**](https://sourceforge.net/projects/thumbapps/)
* [**WinPenPack**](http://www.winpenpack.com/en/index.php)
* [**yaP**](http://rolandtoth.hu/yaP/) / [*tpfc*](http://www.portablefreeware.com/forums/viewtopic.php?f=6&t=22138)

**_Sites:_**
* [**TPFC**](http://www.portablefreeware.com/) / [*subs*](https://www.portablefreeware.com/forums/viewforum.php?f=4), [*res*](https://www.portablefreeware.com/resources.php)
* [**PenDriveApps**](http://www.pendriveapps.com/)

## Contents

* [*Development*](#development)
> [*res*](#resource-editors), [*source*](#source-control), [*text*](#text-editors)

* [*Education*](#education)
> [*religion*](#religion), [*stats*](#statistics)

* [*Graphics*](#graphics)
> [*3d*](#3d), [*art*](#art), [*cad*](#cad), [*pick*](#colour-pickers), [*raw*](#raw), [*cap*](#screen-capture), [*view*](#viewers)

* [*Internet*](#internet)
> [*browse*](#browsers), [*im*](#instant-messaging), [*dl*](#download-managers), [*mail*](#email), [*torrent*](#torrents), [*voice*](#voice-chat)

* [*Multimedia*](#multimedia)
> [*musicplay*](#music-players), [*pod*](#podcasts), [*rec*](#screen-recording), [*vidplay*](#video-players)

* [*Office*](#office)
> [*diary*](#diary), [*notes*](#notetaking), [*proj*](#project-management), [*suite*](#suites), [*wiki*](#wiki)

* [*Utilities*](#utilities)
> [*arch*](#archivers), [*backup*](#backup), [*calc*](#calculators), [*char*](#characters), [*clip*](#clipboard), [*fileman*](#file-managers), [*font*](#fonts), [*launch*](#launchers), [*pass*](#passwords), [*proc*](#processes), [*search*](#search), [*time*](#time)

## Development

[*contents*](#contents), [*top*](#awesome-portable-)

[![Computer](img/computer.jpg)](https://pixabay.com/en/computer-computer-keyboard-gaming-1844996/)

### Resource Editors
* [**ResEdit**](http://www.resedit.net/) / [*tpfc*](https://www.portablefreeware.com/?id=1675) 
* [**Resource Hacker**](http://www.angusj.com/resourcehacker/) / [*tpfc*](https://www.portablefreeware.com/?id=289)
* [**XN Resource Editor**](https://stefansundin.github.io/xn_resource_editor/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=407), [*paf*](http://portableapps.com/apps/utilities/xn_resource_editor_portable)

### Source Control
* [**Git**](https://git-scm.com/) / [*paf*](https://github.com/sheabunge/GitPortable)

### Text Editors
* [**Atom**](https://atom.io/) / [*tpfc*](https://www.portablefreeware.com/?id=2793), [*paf*](https://github.com/garethflowers/atom-portable)
* [**Brackets**](http://brackets.io/) / [*tpfc*](https://github.com/sagiegurari/brackets-portable) / geared toward web development
* [**CuteMarkEd**](https://cloose.github.io/CuteMarkEd/) / [*paf*](http://portableapps.com/apps/office/cutemarked-portable)
* [**EditBone**](http://www.bonecode.com/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=2706)
* [**Haroopad**](http://pad.haroopress.com/user.html) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?p=81239), [*yap*](http://rolandtoth.hu/yaP/#examples/Haroopad.ini)
* [**MarkdownEdit**](http://markdownedit.com/) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?p=81353)
* [**Notepad++**](https://notepad-plus-plus.org/) / [*tpfc*](https://www.portablefreeware.com/?id=539), [*paf*](http://portableapps.com/apps/development/notepadpp_portable)
* [**RJ TextEd**](http://www.rj-texted.se/) / [*tpfc*](https://www.portablefreeware.com/?id=2206)
* [**Sublime Text**](https://www.sublimetext.com/) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?t=16943) / not free, but unlimited evaluation
* [**SynWrite**](http://www.uvviewsoft.com/synwrite/) / [*tpfc*](https://www.portablefreeware.com/?id=2375)
* [**Visual Studio Code**](https://code.visualstudio.com/) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?p=82783), [*paf*](https://github.com/garethflowers/vscode-portable)

## Education

[*contents*](#contents), [*top*](#awesome-portable-)

[![Alms](img/alms.jpg)](https://pixabay.com/en/asia-burma-faith-boy-buddha-1807519/)

### Religion
* [**Bible Analyzer**](http://www.bibleanalyzer.com/) / [*tpfc*](https://www.portablefreeware.com/?id=2704)
* [**Bible Lightning**](http://www.softpedia.com/get/PORTABLE-SOFTWARE/Education/BibleLightning-Portable.shtml) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?p=79666) / fast KJV lookup
* [**BPBible**](https://github.com/bpbible/bpbible) / [*tpfc*](https://www.portablefreeware.com/?id=1597), [*paf*](http://portableapps.com/apps/education/bpbible_portable)
* [**Davar4**](http://www.davar3.net/) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?p=79667)
* [**Ready Bible Study and Reference**](http://michaels-tech-notes.weebly.com/blog/category/religion) / settings saved to INIs within program directory
* [**The Word**](http://www.theword.net/index.php?) / [*tpfc*](https://www.portablefreeware.com/?id=1248)

### Statistics
* [**R**](https://www.r-project.org) / [*paf*](http://portableapps.com/node/32898), [*sf*](https://sourceforge.net/projects/rportable/files/R-Portable/)
* [**RStudio**](https://www.rstudio.com) / [*paf*](https://sourceforge.net/projects/rportable/files/R-Studio/)
* [**Tinn-R**](https://sourceforge.net/projects/tinn-r/) / [*paf*](http://portableapps.com/node/52078), [*sf*](https://sourceforge.net/projects/tinn-r/files/)

## Graphics

[*contents*](#contents), [*top*](#awesome-portable-)

[![Cactus](img/cactus.jpg)](https://pixabay.com/en/cactus-orange-view-perspective-1873977/)

### 3D
* [**Blender**](https://www.blender.org/) / [*tpfc*](https://www.portablefreeware.com/?id=660), [*paf*](http://portableapps.com/apps/graphics_pictures/blender_portable), [*blend*](https://www.blender.org/manual/getting_started/installing/configuration/directories.html)
* [**MagicaVoxel**](https://ephtracy.github.io/index.html?page=mv_main) | [**Viewer**](https://ephtracy.github.io/index.html?page=mv_renderer) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?p=84300)

### Art
* [**Krita**](https://krita.org/en/) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?p=82550), [*paf*](http://portableapps.com/apps/graphics_pictures/krita-portable), [*yap*](http://rolandtoth.hu/yaP/#examples/Krita.ini), [*thumb*](http://www.thumbapps.org/2016/05/Krita-digital-painting-32-64-bit-portable.html) / yaP launcher, as well as `KDEHOME` method, works with Krita versions up to `2.9.11` / best to use the PAF
* [**MyPaint**](http://mypaint.org/) / [*tpfc*](https://www.portablefreeware.com/?id=2088), [*paf*](http://portableapps.com/apps/graphics_pictures/mypaint-portable)
* [**Pixia**](http://www.ne.jp/asahi/mighty/knight/) / [*tpfc*](https://www.portablefreeware.com/?id=26)

### CAD
* [**OpenSCAD**](http://www.openscad.org/) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?p=80983), [*yap*](http://rolandtoth.hu/yaP/#examples/OpenSCAD.ini)
* [**Sweet Home 3D**](http://www.sweethome3d.com/) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?p=79756)

### Colour Pickers
* [**ColorCop**](http://colorcop.net/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=617), [*wpp*](http://www.winpenpack.com/en/download.php?view.1070)
* [**ColorPic**](https://www.iconico.com/colorpic/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=1225)
* [**Instant Eyedropper**](http://instant-eyedropper.com/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=1856)
* [**Just Color Picker**](http://annystudio.com/software/colorpicker/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=2712)
* [**Pixie**](http://www.nattyware.com/pixie.php) / [*tpfc*](https://www.portablefreeware.com/?id=1558)

### RAW
* [**Photivo**](http://photivo.org/start) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?p=81038), [*site*](http://photivo.org/download/windows)
* [**RawTherapee**](http://rawtherapee.com/) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?p=6669), [*paf*](http://portableapps.com/apps/graphics_pictures/rawtherapee-portable), [*rawpedia*](http://50.87.144.65/~rt/w/index.php?title=Making_a_Portable_Installation)

### Screen Capture
* [**Greenshot**](http://getgreenshot.org/) / [*tpfc*](https://www.portablefreeware.com/?id=2340), [*site*](http://getgreenshot.org/faq/will-there-ever-be-a-portable-apps-version-of-greenshot/) / dev distributes PAF version as well / not on PortableApps site due to .NET 2 requirement
* [**Lightscreen**](https://lightscreen.com.ar/) / [*tpfc*](https://www.portablefreeware.com/?id=1959), [*paf*](http://portableapps.com/apps/utilities/lightscreen_portable)
* [**PicPick**](http://ngwin.com/picpick) / [*tpfc*](https://www.portablefreeware.com/index.php?id=1496), [*paf*](http://portableapps.com/apps/graphics_pictures/picpick-portable) / pixel ruler, magnifier, whiteboard, etc
* [**Screenshot Captor**](https://www.donationcoder.com/Software/Mouser/screenshotcaptor/) / [*tpfc*](https://www.portablefreeware.com/?id=2412)
* [**ShareX**](https://getsharex.com/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=2409) / multiple image capture and sharing methods
* [**Snipaste**](https://www.snipaste.com/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=2801)

### Viewers
* [**Faststone Viewer**](http://faststone.org/FSViewerDetail.htm) / [*tpfc*](https://www.portablefreeware.com/index.php?id=207)
* [**HoneyView**](http://www.bandisoft.com/honeyview/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=2497)
* [**Imagine**](http://www.nyam.pe.kr/blog/entry/Imagine) / [*tpfc*](https://www.portablefreeware.com/?id=1819)
* [**Irfanview**](http://www.irfanview.com/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=49), [*paf*](http://portableapps.com/apps/graphics_pictures/irfanview_portable)
* [**XnView**](http://www.xnview.com/en/xnview/) | [**MP**](http://www.xnview.com/en/xnviewmp/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=30), [*mp*](https://www.portablefreeware.com/forums/viewtopic.php?p=35220), [*paf*](http://portableapps.com/apps/graphics_pictures/xnview_portable)

## Internet

[*contents*](#contents), [*top*](#awesome-portable-)

[![Smartphone](img/smartphone.jpg)](https://pixabay.com/en/google-on-your-smartphone-search-1796337/)

### Browsers
* [**Google Chrome**](https://www.google.com/chrome/browser/desktop/index.html) / [*tpfc*](https://www.portablefreeware.com/index.php?id=2074), [*paf*](http://portableapps.com/apps/internet/google_chrome_portable), [*thumb*](https://sourceforge.net/projects/thumbapps/files/Internet/Google%20Chrome/)
* [**Mozilla Firefox**](https://www.mozilla.org/en-US/firefox/new/) / [*tpfc*](https://www.portablefreeware.com/?id=132), [*paf*](http://portableapps.com/apps/internet/firefox_portable), [*thumb*](https://sourceforge.net/projects/thumbapps/files/Internet/Firefox/)
* [**SlimJet**](http://www.slimjet.com/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=2633)
* [**Vivaldi**](https://vivaldi.com/) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?p=73125), [*thumb*](http://www.thumbapps.org/2015/02/vivaldi-108338-tech-preview-portable.html), [*sf*](https://sourceforge.net/projects/thumbapps/files/Internet/Vivaldi/)

### Download Managers
* [**Advanced Wget GUI**](https://github.com/Nenirey/AWGG) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?p=77772), [*sp*](http://www.softpedia.com/get/PORTABLE-SOFTWARE/Internet/Others/Portable-AWGG.shtml), [*vh*](http://www.videohelp.com/software/AWGG)
* [**EagleGet**](http://www.eagleget.com/) / [*tpfc*](https://www.portablefreeware.com/?id=2597)
* [**WinWGet**](http://winwget.sourceforge.net/) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?t=20900), [*paf*](http://portableapps.com/apps/internet/winwget_portable), [*astatix*](http://www.astatix.com/tools/winwget.php)

### Email
* [**Sylpheed**](http://sylpheed.sraoss.jp/en/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=1112), [*paf*](http://portableapps.com/apps/internet/sylpheed-portable), [*wpp*](http://www.winpenpack.com/en/download.php?view.1113)
* [**Mozilla Thunderbird**](https://www.mozilla.org/en-US/thunderbird/) | [**Lightning**](https://addons.mozilla.org/en-US/thunderbird/addon/lightning/) / [*tpfc*](https://www.portablefreeware.com/?id=133), [*paf*](http://portableapps.com/apps/internet/thunderbird_portable), [*wpp*](http://www.winpenpack.com/en/download.php?view.1277) / Lightning extension adds calendar and to-do list functionality

### Instant Messaging
* [**BeeBeep**](http://beebeep.sourceforge.net/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=2783) / p2p, no server required / secure file sharing as well
* [**Pidgin**](https://www.pidgin.im/) / [*tpfc*](https://www.portablefreeware.com/?id=1345), [*paf*](http://portableapps.com/apps/internet/pidgin_portable)

### Torrents
* [**PicoTorrent**](http://www.picotorrent.org/) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?p=79128)
* [**qBittorrent**](http://qbittorrent.sourceforge.net/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=2406), [*paf*](http://portableapps.com/apps/internet/qbittorrent_portable)
* [**Transmission-Qt**](https://sourceforge.net/projects/trqtw/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=2725), [*paf*](http://portableapps.com/apps/internet/transmission-portable), [*thumb*](https://sourceforge.net/projects/thumbapps/files/Internet/Transmission/)

### Voice Chat
* [**Mumble**](http://wiki.mumble.info/wiki/Main_Page) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?p=9770), [*paf*](http://portableapps.com/apps/internet/mumble-portable)

## Multimedia

[*contents*](#contents), [*top*](#awesome-portable-)

[![Microphone](img/microphone.jpg)](https://pixabay.com/en/microphone-mic-mike-voice-audio-1246057/)

### Music Players
* [**1by1**](http://mpesch3.de1.cc/1by1.html) / [*tpfc*](https://www.portablefreeware.com/?id=90)
* [**AIMP**](http://www.aimp.ru/index.php) / [*tpfc*](https://www.portablefreeware.com/index.php?id=1444), [*paf*](http://portableapps.com/apps/music_video/aimp-portable)
* [**Audacious**](http://audacious-media-player.org/) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?p=81470), [*yap*](http://rolandtoth.hu/yaP/#examples/Audacious.ini)
* [**Foobar2000**](http://www.foobar2000.org/) / [*tpfc*](https://www.portablefreeware.com/?id=184)

### Podcasts
* [**gPodder**](http://gpodder.org/) / [*tpfc*](https://www.portablefreeware.com/?id=1673), [*paf*](http://portableapps.com/apps/internet/gpodder_portable)

### Screen Recording
* [**OBS**](https://obsproject.com) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?p=80343), [*paf*](http://portableapps.com/node/53266), [*thumb*](http://www.thumbapps.org/2015/08/OBS-Open-Broadcaster-Software-32-64-bit-portable.html), [*obs*](https://obsproject.com/forum/resources/obs-and-obs-studio-portable-mode-on-windows.359/)
* [**oCam**](http://ohsoft.net/eng/ocam/download.php) / [*yap*](http://rolandtoth.hu/yaP/#examples/oCam.ini)

### Video Players
* [**HamMultiPlayer**](http://hammultiplayer.org/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=2791) / view multiple media files at the same time
* [**Light Alloy**](http://www.light-alloy.ru/) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?p=46371)
* [**MPC-HC**](https://mpc-hc.org/) | [**BE**](https://sourceforge.net/projects/mpcbe/) / [*tpfc*](https://www.portablefreeware.com/?id=2054), [*be*](https://www.portablefreeware.com/forums/viewtopic.php?p=60655), [*paf*](http://portableapps.com/apps/music_video/mpc-hc-portable)
* [**PotPlayer**](http://potplayer.daum.net/) / [*tpfc*](https://www.portablefreeware.com/?id=2483), [*paf*](http://portableapps.com/node/41287)
* [**SMPlayer**](http://smplayer.sourceforge.net/) | [**SMTube**](http://www.smtube.org/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=1358), [*paf*](http://portableapps.com/apps/music_video/smplayer_portable), [*wpp*](http://www.winpenpack.com/en/download.php?view.1245), [*7z*](http://smplayer.sourceforge.net/en/download-smplayer-portable) / use SMTube to browse and play YouTube videos
* [**VLC Media Player**](http://www.videolan.org/vlc/) / [*tpfc*](https://www.portablefreeware.com/?id=599), [*paf*](http://portableapps.com/apps/music_video/vlc_portable)

## Office

[*contents*](#contents), [*top*](#awesome-portable-)

[![Register-Box](img/registerbox.jpg)](https://pixabay.com/en/back-to-school-registerbox-1538863/)

### Diary
* [**RedNotebook**](http://rednotebook.sourceforge.net/) / [*tpfc*](https://www.portablefreeware.com/?id=2086), [*paf*](http://portableapps.com/apps/office/rednotebook_portable)

### Notetaking
* [**Cherrytree**](http://www.giuspen.com/cherrytree/) / [*tpfc*](https://www.portablefreeware.com/?id=2790), [*paf*](http://portableapps.com/apps/office/cherrytree-portable)
* [**KeyNote**](https://sourceforge.net/projects/keynote/) | [**NF**](https://github.com/dpradov/keynote-nf) / [*tpfc*](https://www.portablefreeware.com/?id=755), [*sf*](https://sourceforge.net/projects/keynote-newfeat/) / KeyNote NF is an active fork of the dead KeyNote with extended features
* [**Laverna**](https://laverna.cc/) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?p=82446)
* [**QOwnNotes**](http://www.qownnotes.org/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=2816)

### Project Management
* [**DevProject Manager**](http://www.gaijin.at/en/dldevproject.php) / [*tpfc*](https://www.portablefreeware.com/index.php?id=1273)
* [**Task Coach**](http://www.taskcoach.org/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=2113), [*paf*](http://portableapps.com/apps/office/task_coach_portable)
* [**ToDoList**](http://abstractspoon.weebly.com/) | [**Alt**](https://www.codeproject.com/Articles/5371/ToDoList-An-effective-and-flexible-way-to-keep-on) / [*tpfc*](https://www.portablefreeware.com/index.php?id=816), [*paf*](http://portableapps.com/apps/office/todolist_portable) / was removed from PortableApps at the dev's request
* [**Todomoo**](http://todomoo.sourceforge.net/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=2486)

### Suites
* [**LibreOffice**](https://www.libreoffice.org/) / [*tpfc*](https://www.portablefreeware.com/?id=2055), [*paf*](http://portableapps.com/apps/office/libreoffice_portable)
* [**OpenOffice**](https://www.openoffice.org/) / [*tpfc*](https://www.portablefreeware.com/?id=212), [*paf*](http://portableapps.com/apps/office/openoffice_portable)
* [**SoftMaker FreeOffice**](http://www.freeoffice.com/en/) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?t=20457), [*site*](http://www.freeoffice.com/en/tips-and-tricks-portable-installation)

### Wiki
* [**DokuWiki**](https://www.dokuwiki.org/dokuwiki#) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?p=83274), [*site*](https://www.dokuwiki.org/install:dokuwiki_on_a_stick) / self-hosted wiki software run on a portable MicroApache server
* [**TiddlyWiki**](http://tiddlywiki.com/) | [**Classic**](http://classic.tiddlywiki.com/) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?t=2031), [*git*](https://github.com/Jermolene/TiddlyWiki5) / single HTML opened with a browser / not a program, per se, but certainly portable
* [**WikidPad**](http://wikidpad.sourceforge.net/) / [*tpfc*](https://www.portablefreeware.com/?id=1099), [*site*](http://wikidpad.sourceforge.net/help/ConfigurationFiles.html)
* [**Zim**](http://www.zim-wiki.org/) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?p=56775), [*paf*](http://portableapps.com/node/29350), [*site*](http://www.glump.net/software/zim-windows) / PAF available from dev

## Utilities

[*contents*](#contents), [*top*](#awesome-portable-)

[![Yamaha](img/yamaha.jpg)](https://pixabay.com/en/yamaha-motorcycle-details-1653663/)

### Archivers
* [**7-Zip**](http://www.7-zip.org/) / [*tpfc*](https://www.portablefreeware.com/?id=796), [*paf*](http://portableapps.com/apps/utilities/7-zip_portable)
* [**Bandizip**](http://www.bandisoft.com/bandizip/) / [*tpfc*](https://www.portablefreeware.com/?id=2397)
* [**Peazip**](http://www.peazip.org/) / [*tpfc*](https://www.portablefreeware.com/?id=1048), [*paf*](http://portableapps.com/apps/utilities/peazip_portable), [*thumb*](https://sourceforge.net/projects/thumbapps/files/Utilities/Bandizip/)

### Backup
* [**Back4Sure**](http://www.ukrebs-software.de/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=1684)
* [**jaBuT Backup**](http://jabut.de/en) / [*tpfc*](https://www.portablefreeware.com/?id=2812)
* [**Personal Backup**](http://personal-backup.rathlev-home.de/index-e.html) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?p=28563), [*yap*](http://rolandtoth.hu/yaP/#examples/Personal%20Backup.ini)
* [**ZBack**](http://titan.fsb.hr/~dzorc/zback.html) / [*tpfc*](https://www.portablefreeware.com/index.php?id=1683)

### Calculators
* [**RedCrab**](http://www.redchillicrab.com/en/redcrab/index.html) / [*tpfc*](https://www.portablefreeware.com/index.php?id=2095)
* [**SpeedCrunch**](http://speedcrunch.org/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=1547), [*paf*](http://portableapps.com/apps/office/speedcrunch_portable)

### Characters
* [**WinCompose**](https://github.com/SamHocevar/wincompose) / [*tpfc*](https://www.portablefreeware.com/index.php?id=2615)

### Clipboard
* [**ArsClip**](http://www.joejoesoft.com/vcms/97/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=734)
* [**CopyQ**](http://hluk.github.io/CopyQ/) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?p=69636)
* [**Ditto**](http://ditto-cp.sourceforge.net/index.php) / [*tpfc*](https://www.portablefreeware.com/index.php?id=1361), [*paf*](http://portableapps.com/apps/utilities/ditto_portable)

### File Managers
* [**Double Commander**](http://doublecmd.sourceforge.net/) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?t=4648)
* [**FileVoyager**](http://www.filevoyager.com/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=2826)
* [**Free Commander XE**](http://freecommander.com/en/summary/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=291), [*paf*](http://portableapps.com/apps/utilities/freecommander_portable) / 64-bit version is donationware
* [**MultiCommander**](http://multicommander.com/) / [*tpfc*](https://www.portablefreeware.com/?id=2304)
* [**NexusFile**](http://www.xiles.net/) / [*tpfc*](https://www.portablefreeware.com/?id=1419)
* [**Q-Dir**](http://www.softwareok.com/?seite=Freeware/Q-Dir) / [*tpfc*](https://www.portablefreeware.com/?id=1431), [*paf*](http://portableapps.com/apps/utilities/q-dir-portable/)
* [**Tablacus Explorer**](http://www.eonet.ne.jp/~gakana/tablacus/explorer_en.html) / [*tpfc*](https://www.portablefreeware.com/index.php?id=2781), [*thumb*](http://www.thumbapps.org/2016/09/Tablacus-Explorer-portable-multi-tab-Windows-file-explorer.html) / addon support via built-in addon manager
* [**Total Commander**](https://www.ghisler.com) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?p=527), [*paf*](http://portableapps.com/node/14220), [*totalcmd*](https://www.ghisler.com/usbinst.htm) / not free, but certainly very good

### Fonts
* [**NexusFont**](http://www.xiles.net/) / [*tpfc*](https://www.portablefreeware.com/?id=731)

### Launchers
* [**FARR**](https://www.donationcoder.com/Software/Mouser/findrun/) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?p=6848)
* [**LiberKey**](http://www.liberkey.com/en.html) / [*tpfc*](https://www.portablefreeware.com/?id=2306)
* [**LupoPenSuite**](http://www.lupopensuite.com/) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?p=78512)
* [**PortableApps Platform**](http://portableapps.com/download) / [*tpfc*](https://www.portablefreeware.com/index.php?id=1056)
* [**Qsel**](http://www.horstmuc.de/wqsel.htm) / [*tpfc*](https://www.portablefreeware.com/?id=1133)
* [**Quick Access Popup**](http://www.quickaccesspopup.com/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=2765)
* [**SyMenu**](http://www.ugmfree.it/) / [*tpfc*](https://www.portablefreeware.com/?id=2394)
* [**XVA Assistant**](http://www.idesktop.me/) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?p=83028)

### Passwords
* [**KeePass**](http://keepass.info/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=2829), [*classic*](https://www.portablefreeware.com/index.php?id=194), [*paf*](http://portableapps.com/apps/utilities/keepass_portable)
* [**Password Safe**](https://pwsafe.org/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=1197), [*paf*](http://portableapps.com/apps/security/password-safe-portable)

### Processes
* [**Process Explorer**](https://technet.microsoft.com/en-us/sysinternals/bb896653) / [*tpfc*](https://www.portablefreeware.com/index.php?id=32), [*paf*](http://portableapps.com/apps/utilities/process-explorer-portable)
* [**Process Hacker**](https://wj32.org/processhacker/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=1934), [*paf*](http://portableapps.com/apps/utilities/process-hacker-portable)

### Renamers
* [**Bulk Rename Utility**](http://www.bulkrenameutility.co.uk/) / [*tpfc*](https://www.portablefreeware.com/?id=1008)

### Search
* [**Everything**](http://www.voidtools.com/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=1479)
* [**Listary**](http://www.listary.com/) / [*tpfc*](https://www.portablefreeware.com/?id=1680), [*paf*](http://portableapps.com/apps/utilities/listary_portable) / Pro version available

### Time
* [**Titlebar Date-Time**](http://www.whisperingpinessoftware.com/tbdt.html) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?p=84159)

### Uninstallers
* [**Bulk Crap Uninstaller**](http://klocmansoftware.weebly.com/) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?p=77953)
* [**IObit Uninstaller**](http://www.iobit.com/en/advanceduninstaller.php) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?p=30919), [*paf*](http://portableapps.com/apps/utilities/iobit_uninstaller_portable)

## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, Shane Bowman has waived all copyright and related or neighbouring rights to this work.

*Images courtesy [Pixabay](https://pixabay.com/), `CC0`*.


