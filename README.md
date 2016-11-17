
# Awesome Portable [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> Curated list of awesome portable apps.

*More to come! It will take a while! :bowtie:*

Create a [pull request](https://github.com/shnbwmn/awesome-portable/pulls) to add links | Start an [issue](https://github.com/shnbwmn/awesome-portable/issues) for corrections or discussions | [Contribution Guidelines](https://github.com/shnbwmn/awesome-portable/blob/master/Contribute.md)

**_See also:_** [**Awesome Portable Games**](https://github.com/shnbwmn/awesome-portable-games)

**_Portability:_** [:package:](https://www.portablefreeware.com/about.php) [:floppy_disk:](http://portableapps.com/about/what_is_a_portable_app)
* No installation required (can be unzipped/[extracted](https://www.portablefreeware.com/faq.php#extract) or files copied from an installation).
* Runs self-contained (makes no changes to host computer outside of program folder).
* Saves main settings to program directory (not user/home directory, AppData or registry).
* Doesn't require third-party dependencies (with some exceptions, like .NET or Visual C++, or admin rights).
* *[Stealth:](https://www.portablefreeware.com/faq.php#stealth)* leaves nothing behind in the registry or filesystem (no leftovers/clutter on the PC - ideal).
* Due to the nature of some programs and their core functionality, they might be considered portable despite breaking a few of the above.

**_Testing for portability:_**
* [Windows portability testing environment](https://www.portablefreeware.com/forums/viewtopic.php?t=21885)
* [Sandboxie](http://www.sandboxie.com/) - [:package:](https://www.portablefreeware.com/forums/viewtopic.php?t=4130) - isolate a running program to show files/registry entries created, or install programs requiring installation inside a sandbox
* [Virtualbox](https://www.virtualbox.org/) - [:gear:](http://www.vbox.me/) - run programs in a clean Windows installation to check for dependencies
* *Remember:* just because a program comes in a ZIP/RAR, etc or says "standalone/portable" doesn't mean it's truly portable.
* The crucial question is: *Where are the settings saved to?* - this is the core of testing.

**_Tools:_**
* [LessMSI](http://lessmsi.activescott.com/) - [:package:](https://www.portablefreeware.com/forums/viewtopic.php?p=30045) - extracts MSI installers
* [Universal Extractor 2](http://bioruebe.com/dev/uniextract/) - [:package:](https://www.portablefreeware.com/index.php?id=2764) - extracts most program installers

**_Note on icons:_**
> I consider TPFC and PA to be the foremost authorities on portability. 

* **[TPFC](http://www.portablefreeware.com/)** :package: - either a database entry or often a thread in the [submissions subforum](https://www.portablefreeware.com/forums/viewforum.php?f=4).
* **[PortableApps](http://portableapps.com/)** :floppy_disk: - either packaged in [PAF format](http://portableapps.com/development/portableapps.com_format), often in addition to native portability, or a link to PA forum.
* **[yaP](http://rolandtoth.hu/yaP/)** :file_folder: - has a [yaP config](http://www.portablefreeware.com/forums/viewtopic.php?f=6&t=22138) available.
* **[ThumbApps](https://sourceforge.net/projects/thumbapps/)** :cyclone: - TA PAF available (they package programs that PortableApps won't for licencing reasons).
* **Other** :gear: - portability instructions provided from the program site or another source.
* **Commercial** :moneybag: - costs money, or compulsory donationware. I prefer to list freeware though as much as possible.

**_Other sites:_**
* [LiberKey](http://www.liberkey.com/en.html)
* [LupoPenSuite](http://www.lupopensuite.com/)
* [PenDriveApps](http://www.pendriveapps.com/)
* [SyMenu](http://www.ugmfree.it/)
* [WinPenPack](http://www.winpenpack.com/en/index.php)

## Contents

* [*Education*](#education)
> [*religion*](#religion), [*stats*](#statistics)

* [*Graphics*](#graphics)
> [*cap*](#screen-capture), [*view*](#viewers)

* [*Internet*](#internet) 
> [*browse*](#browsers), [*dl*](#download-managers), [*mail*](#email), [*torrent*](#torrents)

* [*Multimedia*](#multimedia) 
> [*musicplay*](#music-players), [*pod*](#podcasts), [*rec*](#screen-recording), [*vidplay*](#video-players)

* [*Office*](#office)
> [*suite*](#suites), [*text*](#text-editors)

* [*Utilities*](#utilities) 
> [*zip*](#archivers), [*backup*](#backup), [*fileman*](#file-management), [*launch*](#launchers), [*search*](#search)

### Education

#### Religion
* [Bible Analyzer](http://www.bibleanalyzer.com/) - [:package:](https://www.portablefreeware.com/?id=2704)
* [Bible Lightning](http://www.softpedia.com/get/PORTABLE-SOFTWARE/Education/BibleLightning-Portable.shtml) - [:package:](https://www.portablefreeware.com/forums/viewtopic.php?p=79666) - fast KJV lookup
* [BPBible](https://github.com/bpbible/bpbible) - [:package:](https://www.portablefreeware.com/?id=1597) [:floppy_disk:](http://portableapps.com/apps/education/bpbible_portable)
* [Davar4](http://www.davar3.net/) - [:package:](https://www.portablefreeware.com/forums/viewtopic.php?p=79667)
* [Ready Bible Study and Reference](http://michaels-tech-notes.weebly.com/blog/category/religion) - settings saved to INIs within program directory
* [The Word](http://www.theword.net/index.php?) - [:package:](https://www.portablefreeware.com/?id=1248)

#### Statistics
* [R](https://www.r-project.org) - [:floppy_disk:](http://portableapps.com/node/32898) [:gear:](https://sourceforge.net/projects/rportable/files/R-Portable/)
* [RStudio](https://www.rstudio.com) - [:gear:](https://sourceforge.net/projects/rportable/files/R-Studio/)
* [Tinn-R](
http://nbcgib.uesc.br/lec/software/editores/tinn-r/en) - [:floppy_disk:](http://portableapps.com/node/52078) [:gear:](https://sourceforge.net/projects/tinn-r/files/)

### Graphics

#### Screen Capture
* [Greenshot](http://getgreenshot.org/) - [:package:](https://www.portablefreeware.com/?id=2340) - dev distributes PAF version as well
* [Lightscreen](https://lightscreen.com.ar/) - [:package:](https://www.portablefreeware.com/?id=1959) [:floppy_disk:](http://portableapps.com/apps/utilities/lightscreen_portable)
* [PicPick](http://ngwin.com/picpick) - [:package:](https://www.portablefreeware.com/index.php?id=1496) [:floppy_disk:](http://portableapps.com/apps/graphics_pictures/picpick-portable) - a lot more than just a screenshot tool
* [ShareX](https://getsharex.com/) - [:package:](https://www.portablefreeware.com/index.php?id=2409) - like PicPick, has many diverse features beyond screenshotting
* [Snipaste](https://www.snipaste.com/) - [:package:](https://www.portablefreeware.com/index.php?id=2801)

#### Viewers
* [Faststone](http://faststone.org/FSViewerDetail.htm) - [:package:](https://www.portablefreeware.com/index.php?id=207)
* [HoneyView](http://www.bandisoft.com/honeyview/) - [:package:](https://www.portablefreeware.com/index.php?id=2497)
* [Imagine](http://www.nyam.pe.kr/blog/entry/Imagine) - [:package:](https://www.portablefreeware.com/?id=1819)
* [XnView](http://www.xnview.com/en/xnview/) - [:package:](https://www.portablefreeware.com/index.php?id=30) [:floppy_disk:](http://portableapps.com/apps/graphics_pictures/xnview_portable)
* [XnView MP](http://www.xnview.com/en/xnviewmp/) - [:package:](https://www.portablefreeware.com/forums/viewtopic.php?p=35220)

### Internet

#### Browsers
* [Chrome](https://www.google.com/chrome/browser/desktop/index.html) - [:package:](https://www.portablefreeware.com/index.php?id=2074) [:floppy_disk:](http://portableapps.com/apps/internet/google_chrome_portable) [:cyclone:](https://sourceforge.net/projects/thumbapps/files/Internet/Google%20Chrome/)
* [Firefox](https://www.mozilla.org/en-US/firefox/new/) - [:package:](https://www.portablefreeware.com/?id=132) [:floppy_disk:](http://portableapps.com/apps/internet/firefox_portable) [:cyclone:](https://sourceforge.net/projects/thumbapps/files/Internet/Firefox/)

#### Download Managers
* [EagleGet](http://www.eagleget.com/) - [:package:](https://www.portablefreeware.com/?id=2597)

#### Email
* [Thunderbird](https://www.mozilla.org/en-US/thunderbird/) - [:package:](https://www.portablefreeware.com/?id=133) [:floppy_disk:](http://portableapps.com/apps/internet/thunderbird_portable)

#### Torrents
* [PicoTorrent](http://www.picotorrent.org/) - [:package:](https://www.portablefreeware.com/forums/viewtopic.php?p=79128)
* [qBittorrent](http://qbittorrent.sourceforge.net/) - [:package:](https://www.portablefreeware.com/index.php?id=2406) [:floppy_disk:](http://portableapps.com/apps/internet/qbittorrent_portable)
* [Transmission-Qt](https://sourceforge.net/projects/trqtw/) - [:package:](https://www.portablefreeware.com/index.php?id=2725) [:floppy_disk:](http://portableapps.com/apps/internet/transmission-portable) [:cyclone:](https://sourceforge.net/projects/thumbapps/files/Internet/Transmission/)

### Multimedia

#### Music Players
* [1by1](http://mpesch3.de1.cc/1by1.html) - [:package:](https://www.portablefreeware.com/?id=90)
* [AIMP](http://www.aimp.ru/index.php) - [:package:](https://www.portablefreeware.com/index.php?id=1444) [:floppy_disk:](http://portableapps.com/apps/music_video/aimp-portable)
* [Audacious](http://audacious-media-player.org/) - [:package:](https://www.portablefreeware.com/forums/viewtopic.php?p=81470) [:file_folder:](http://rolandtoth.hu/yaP/#examples/Audacious.ini)

#### Podcasts
* [gPodder](http://gpodder.org/) - [:package:](https://www.portablefreeware.com/?id=1673) [:floppy_disk:](http://portableapps.com/apps/internet/gpodder_portable)

#### Screen Recording
* [OBS](https://obsproject.com) - [:package:](https://www.portablefreeware.com/forums/viewtopic.php?p=80343) [:floppy_disk:](http://portableapps.com/node/53266) [:cyclone:](http://www.thumbapps.org/2015/08/OBS-Open-Broadcaster-Software-32-64-bit-portable.html) [:gear:](https://obsproject.com/forum/resources/obs-and-obs-studio-portable-mode-on-windows.359/)

#### Video Players
* [Light Alloy](http://www.light-alloy.ru/) - [:package:](https://www.portablefreeware.com/forums/viewtopic.php?p=46371)
* [MPC BE](https://sourceforge.net/projects/mpcbe/) - [:package:](https://www.portablefreeware.com/forums/viewtopic.php?p=60655)
* [MPC HC](https://mpc-hc.org/) - [:package:](https://www.portablefreeware.com/?id=2054) [:floppy_disk:](http://portableapps.com/apps/music_video/mpc-hc-portable)
* [Potplayer](http://potplayer.daum.net/) - [:package:](https://www.portablefreeware.com/?id=2483) [:floppy_disk:](http://portableapps.com/node/41287)
* [VLC]

### Office

#### Suites
* [LibreOffice](https://www.libreoffice.org/) - [:package:](https://www.portablefreeware.com/?id=2055) [:floppy_disk:](http://portableapps.com/apps/office/libreoffice_portable)
* [OpenOffice](https://www.openoffice.org/) - [:package:](https://www.portablefreeware.com/?id=212) [:floppy_disk:](http://portableapps.com/apps/office/openoffice_portable)
* [SoftMaker FreeOffice](http://www.freeoffice.com/en/) - [:package:](https://www.portablefreeware.com/forums/viewtopic.php?t=20457) [:gear:](http://www.freeoffice.com/en/tips-and-tricks-portable-installation)

#### Text Editors
* [Atom]
* [Brackets] - - geared toward web development
* [EditBone](http://www.bonecode.com/) - [:package:](https://www.portablefreeware.com/index.php?id=2706)
* [Notepad++]
* [RJ TextEd]
* [SynWrite](http://www.uvviewsoft.com/synwrite/) - [:package:](https://www.portablefreeware.com/?id=2375)
* [Visual Studio Code]

### Utilities

#### Archivers
* [7-Zip](http://www.7-zip.org/) - [:package:](https://www.portablefreeware.com/?id=796) [:floppy_disk:](http://portableapps.com/apps/utilities/7-zip_portable)
* [Bandizip]
* [Peazip]

#### Backup
* [jaBuT Backup](http://jabut.de/en) - [:package:](https://www.portablefreeware.com/?id=2812)

#### File Management
* [Double Commander](http://doublecmd.sourceforge.net/) - [:package:](https://www.portablefreeware.com/forums/viewtopic.php?t=4648)
* [Free Commander XE](http://freecommander.com/en/summary/) - [:package:](https://www.portablefreeware.com/index.php?id=291) [:floppy_disk:](http://portableapps.com/apps/utilities/freecommander_portable) - 64-bit version is donationware
* [MultiCommander](http://multicommander.com/) - [:package:](https://www.portablefreeware.com/?id=2304)
* [NexusFile]
* [Q-Dir](http://www.softwareok.com/?seite=Freeware/Q-Dir) - [:package:](https://www.portablefreeware.com/?id=1431) [:floppy_disk:](http://portableapps.com/apps/utilities/q-dir-portable)

#### Launchers
* [FARR](https://www.donationcoder.com/Software/Mouser/findrun/) - [:package:](https://www.portablefreeware.com/forums/viewtopic.php?p=6848)
* [Qsel](http://www.horstmuc.de/wqsel.htm) - [:package:](https://www.portablefreeware.com/?id=1133)
* [Quick Access Popup](http://www.quickaccesspopup.com/) - [:package:](https://www.portablefreeware.com/index.php?id=2765)
* [SyMenu](http://www.ugmfree.it/) - [:package:](https://www.portablefreeware.com/?id=2394)
* [XVA Assistant](http://www.idesktop.me/) - [:package:](https://www.portablefreeware.com/forums/viewtopic.php?p=83028)

#### Search
* [Everything](http://www.voidtools.com/) - [:package:](https://www.portablefreeware.com/index.php?id=1479)
* [Listary](http://www.listary.com/) - [:package:](https://www.portablefreeware.com/?id=1680) [:floppy_disk:](http://portableapps.com/apps/utilities/listary_portable) - Pro version available

## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, Shane Bowman has waived all copyright and related or neighbouring rights to this work.

