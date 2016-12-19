
# Awesome Portable [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> Curated list of awesome portable apps.

*More to come! It will take a while!*

[**Contents**](#contents) | Create a [**Pull Request**](https://github.com/shnbwmn/awesome-portable/pulls) to add programs | Start an [**Issue**](https://github.com/shnbwmn/awesome-portable/issues) for corrections or discussions

_See also:_ [**Awesome Portable Games**](https://github.com/shnbwmn/awesome-portable-games) | [**Awesome Online**](https://github.com/shnbwmn/awesome-online) | [**Awesome Mobile**](https://github.com/shnbwmn/awesome-mobile)

[![Elephant](img/elephant.jpg)](https://pixabay.com/en/elephant-animals-asia-large-bright-1822636/)

#### *Portability:*

[*tpfc*](https://www.portablefreeware.com/about.php), [*paf*](http://portableapps.com/about/what_is_a_portable_app)

* **No installation required** / can be unzipped, [extracted](https://www.portablefreeware.com/faq.php#extract), or files copied from an installation
* Runs **self-contained** / makes no changes to host computer outside of program folder
* Saves **main settings & extensions to program directory** / not home directory, AppData, or the registry
* **No third-party dependencies** / with some exceptions, like [.NET](https://www.microsoft.com/net/download/framework), [Visual C++](https://support.microsoft.com/en-za/kb/2977003), or admin rights where necessary
* [**Stealth**](https://www.portablefreeware.com/faq.php#stealth) / no registry or filesystem items left on the host PC after program exit / optional but ideal

#### *Testing for portability:*

[*methods*](https://www.portablefreeware.com/forums/viewtopic.php?t=21885), [*mindmap*](https://www.portablefreeware.com/forums/viewtopic.php?f=2&t=7718), [*v2*](https://www.portablefreeware.com/forums/viewtopic.php?p=82375#p82375)

* [**7-Zip**](http://www.7-zip.org/) / [*tpfc*](https://www.portablefreeware.com/?id=796), [*paf*](http://portableapps.com/apps/utilities/7-zip_portable) / can open installer archives / can act as rudimentary dual-pane file manager
* [**Dependency Walker**](http://www.dependencywalker.com/) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?p=28309), [*thumb*](http://www.thumbapps.org/2015/03/Dependency-Walker-Depends-portable.html), [*sf*](https://sourceforge.net/projects/thumbapps/files/Development/Dependency%20Walker/), [*wiki*](https://en.wikipedia.org/wiki/Dependency_Walker) / also known as *depends.exe*
* [**LessMSI**](http://lessmsi.activescott.com/) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?p=30045) / extracts MSI installers
* [**Process Monitor**](https://technet.microsoft.com/en-us/sysinternals/processmonitor.aspx) / [*tpfc*](https://www.portablefreeware.com/?id=1033), [*paf*](http://portableapps.com/apps/utilities/process-monitor-portable) / previously *RegMon* and *FileMon* / see all registry & filesystem writes in real-time
* [**Registry Viewer**](http://www.gaijin.at/en/dlregview.php) / [*tpfc*](https://www.portablefreeware.com/?id=1657) / view RegHives, eg, from Sandboxie
* [**RegShot**](https://sourceforge.net/projects/regshot/) | [**Primo**](http://members.tripod.com/~randy_hall/download.htm) / [*tpfc*](https://www.portablefreeware.com/?id=297), [*unicode*](https://www.portablefreeware.com/index.php?id=2505), [*primo*](https://www.portablefreeware.com/forums/viewtopic.php?t=8164), [*paf*](http://portableapps.com/apps/utilities/regshot_portable) / creates before and after snapshots of the registry & filesystem for comparison
* [**Sandboxie**](http://www.sandboxie.com/) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?t=4130) / isolate a running program to show files & registry entries created / install programs requiring installation inside a sandbox / my main testing tool / requires admin rights
* [**Universal Extractor**](http://www.lupopensuite.com/db/universalextractor.htm) | [**Bioruebe**](http://bioruebe.com/dev/uniextract/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=2764) / extracts most program installers
* [**VirtualBox**](https://www.virtualbox.org/) / [*vbox*](http://www.vbox.me/) / run programs in a clean Windows installation to check for dependencies / requires admin rights
* [**Windows Registry Recovery**](http://www.mitec.cz/wrr.html) / [*tpfc*](https://www.portablefreeware.com/index.php?id=1147) / alternative RegHive viewer

#### *Tools:*
* [**Adobe Flash**](http://www.adobe.com/software/flash/about/) | [**Portable**](https://rejzor.wordpress.com/portable-adobe-flash/) | [**Alt**](http://notepad.patheticcockroach.com/4029/flash-player-12-for-portable-browsers-32-and-64-bits/) / latest Flash DLLs for portable browsers
* [**Ghostscript**](http://www.ghostscript.com/) | [**Portable**](http://portableapps.com/apps/utilities/ghostscript_portable) / Postscript interpreter required by some PDF programs
* [**Java**](https://www.java.com/en/) | [**JPortable**](http://portableapps.com/apps/utilities/java_portable) | [**Launcher**](http://portableapps.com/apps/utilities/java_portable_launcher) / run JAR executables portably
* [**SmallestDotNET**](http://smallestdotnet.com/) / to get .NET installed quickly
* [**WinPCap**](http://www.winpcap.org/) / required via installation or `wpcap.dll`, `Packet.dll` by some network programs

#### *Important Sites:*
* [**LiberKey**](http://www.liberkey.com/en.html) / [*tpfc*](https://www.portablefreeware.com/?id=2306)
* [**LupoPenSuite**](http://www.lupopensuite.com/) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?p=78512)
* [**PenDriveApps**](http://www.pendriveapps.com/)
* [**PortableApps**](http://portableapps.com/) | [**Platform**](http://portableapps.com/download) / [*tpfc*](https://www.portablefreeware.com/index.php?id=1056), [*paf*](http://portableapps.com/development/portableapps.com_format), [*sf*](https://sourceforge.net/projects/portableapps/), [*ftp*](https://sourceforge.mirrorservice.org/p/po/portableapps/)
* [**ThumbApps**](http://www.thumbapps.org/) / [*sf*](https://sourceforge.net/projects/thumbapps/) / uses PortableApps format
* [**TPFC**](http://www.portablefreeware.com/) / [*subs*](https://www.portablefreeware.com/forums/viewforum.php?f=4), [*res*](https://www.portablefreeware.com/resources.php)
* [**winPenPack**](http://www.winpenpack.com/en/index.php) | [**Net Menu**](http://www.winpenpack.com/en/download.php?view.1303) / [*tpfc*](https://www.portablefreeware.com/index.php?id=2264)
* [**yaP**](http://rolandtoth.hu/yaP/) | [**crypt**](http://rolandtoth.hu/yaP/#yaPcrypt) / [*tpfc*](http://www.portablefreeware.com/forums/viewtopic.php?f=6&t=22138), [*examples*](http://rolandtoth.hu/yaP/#examples)

#### *Other Sites:*

[*control-panels*](#control-panels)

* [**DonationCoder**](https://www.donationcoder.com/) / Mouser, Skwire, one-hour software, NANY, etc
* [**joeware**](http://www.joeware.net/freetools/index.htm)
* [**MiTeC**](http://www.mitec.cz/index.html) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?p=81174)
* [**NirSoft**](http://www.nirsoft.net/) | [**NirLauncher**](http://launcher.nirsoft.net/) | [**Panel**](http://www.nirsoft.net/panel/) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?f=4&t=10706), [*paf*](http://portableapps.com/node/21347)
* [**NTCore**](http://www.ntcore.com/index.php)
* [**SysInternals**](https://technet.microsoft.com/en-us/sysinternals/bb545027.aspx) | [**Suite**](https://technet.microsoft.com/en-us/sysinternals/bb842062) | [**Live**](https://live.sysinternals.com/)

## Contents

[*top*](#awesome-portable-)

* [***Development***](#development)
> [*IDEs*](#ides) | [*Resource Editors*](#resource-editors) | [*Specialised Editors*](#specialised-editors) | [*Text Editors*](#text-editors) | [*Version Control*](#version-control) | [*Web Servers*](#web-servers)

* [***Education***](#education)
> [*Genealogy*](#genealogy) | [*Geography*](#geography) | [*Medical*](#medical) | [*Religion*](#religion) | [*Statistics*](#statistics)

* [***Graphics***](#graphics)
> [*3D*](#3d) | [*Animation*](#animation) | [*Art*](#art) | [*CAD*](#cad) | [*Colour Pickers*](#colour-pickers) | [*GIF*](#gif) | [*Image Editors*](#image-editors) | [*Image Compression*](#image-compression) | [*Image Viewers*](#image-viewers) | [*RAW*](#raw) | [*Screen Capture*](#screen-capture) | [*Vector Editors*](#vector-editors)

* [***Internet***](#internet)
> [*Browsers*](#browsers) | [*Download Managers*](#download-managers) | [*Email*](#email) | [*FTP*](#ftp) | [*Instant Messenging*](#instant-messaging) | [*Remote Access*](#remote-access) | [*RSS*](#rss) | [*Torrents*](#torrents) | [*VoIP*](#voip)

* [***Multimedia***](#multimedia)
> [*Audio Editors*](#audio-editors) | [*Disk Tools*](#disk-tools) | [*Media Conversion*](#media-conversion) | [*Music Players*](#music-players) | [*Podcasts*](#podcasts) | [*Scoring*](#scoring) | [*Screen Recording*](#screen-recording) | [*Tagging*](#tagging) | [*Video Editors*](#video-editors) | [*Video Players*](#video-players)

* [***Office***](#office)
> [*Calendar*](#calendar) | [*Diary*](#diary) | [*Desktop Publishing*](#desktop-publishing) | [*Document Scanning*](#document-scanning) | [*Document Viewers*](#document-viewers) | [*Finance*](#finance) | [*Mindmapping*](#mindmapping) | [*Notetaking*](#notetaking) | [*Office Suites*](#office-suites) | [*Outliners*](#outliners) | [*PIMs*](#pims) | [*Project Management*](#project-management) | [*TeX*](#tex) | [*Wiki*](#wiki) | [*Writing*](#writing)

* [***Security***](#security)
> [*Antivirus*](#antivirus) | [*Cleaners*](#cleaners) | [*Deletion*](#deletion) | [*Malware Scanners*](#malware-scanners) | [*Passwords*](#passwords)

* [***Utilities***](#utilities)
> [*Archivers*](#archivers) | [*Automation*](#automation) | [*Backup*](#backup) | [*Calculators*](#calculators) | [*Cataloguing*](#cataloguing) | [*Characters*](#characters) | [*Clipboard*](#clipboard) | [*Control Panels*](#control-panels) | [*Copiers*](#copiers) | [*Defragmentation*](#defragmentation) | [*Duplicates*](#duplicates) | [*File Managers*](#file-managers) | [*File Tagging*](#file-tagging) | [*Fonts*](#fonts) | [*Launchers*](#launchers) | [*Processes*](#processes) | [*Registry*](#registry) | [*Renamers*](#renamers) | [*Search*](#search) | [*Time*](#time) | [*Uninstallers*](#uninstallers) | [*Window Managers*](#window-managers)

## Development

[*contents*](#contents), [*top*](#awesome-portable-)

[![Computer](img/computer.jpg)](https://pixabay.com/en/computer-computer-keyboard-gaming-1844996/)

### IDEs
* [**Eclipse**](http://www.eclipse.org/) / [*paf*](http://portableapps.com/node/53284), [*wpp*](http://www.winpenpack.com/en/download.php?view.591), [*sf*](https://sourceforge.net/projects/eclipseportable/)
* [**Geany**](https://www.geany.org/) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?f=4&t=7645), [*paf*](http://portableapps.com/apps/development/geany_portable), [*sf*](https://sourceforge.net/projects/geanyportable/) / actually a text editor with basic IDE features
* [**Lazarus**](http://www.lazarus-ide.org/) | [**Alt**](https://sourceforge.net/projects/lazarus/) / [*paf*](http://portableapps.com/node/50162), [*sf*](https://sourceforge.net/projects/lazarusportable/), [*site*](http://wiki.freepascal.org/Installing_Lazarus#Installing_Lazarus_on_Portable_USB_Driver), [*forum*](http://forum.lazarus.freepascal.org/index.php?topic=31371.0), [*wpp*](http://www.winpenpack.com/main/download.php?view.727)

### Resource Editors
* [**ResEdit**](http://www.resedit.net/) / [*tpfc*](https://www.portablefreeware.com/?id=1675) 
* [**Resource Hacker**](http://www.angusj.com/resourcehacker/) / [*tpfc*](https://www.portablefreeware.com/?id=289)
* [**XN Resource Editor**](https://stefansundin.github.io/xn_resource_editor/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=407), [*paf*](http://portableapps.com/apps/utilities/xn_resource_editor_portable)

### Specialised Editors
* [**JSONedit**](http://tomeko.net/software/JSONedit/index.php) / [*tpfc*](https://www.portablefreeware.com/index.php?id=2393)
* [**MiTeC JSON Viewer**](http://mitec.cz/jsonv.html) / [*tpfc*](https://www.portablefreeware.com/index.php?id=2853)
* [**MiTeC XML Viewer**](http://mitec.cz/xmlv.html) / [*tpfc*](https://www.portablefreeware.com/index.php?id=2852)

### Text Editors
* [**AkelPad**](http://akelpad.sourceforge.net/en/index.php) / [*tpfc*](https://www.portablefreeware.com/?id=952), [*paf*](http://portableapps.com/apps/development/akelpad_portable), [*wpp*](http://www.winpenpack.com/en/download.php?view.700), [*plugins*](http://akelpad.sourceforge.net/en/plugins.php) / extremely lightweight
* [**Atom**](https://atom.io/) / [*tpfc*](https://www.portablefreeware.com/?id=2793), [*paf*](https://github.com/garethflowers/atom-portable) / by GitHub :)
* [**Brackets**](http://brackets.io/) / [*tpfc*](https://github.com/sagiegurari/brackets-portable), [*yap*](http://rolandtoth.hu/yaP/#examples/Brackets.ini) / geared toward web development
* [**CuteMarkEd**](https://cloose.github.io/CuteMarkEd/) / [*paf*](http://portableapps.com/apps/office/cutemarked-portable)
* [**EditBone**](http://www.bonecode.com/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=2706)
* [**Haroopad**](http://pad.haroopress.com/user.html) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?p=81239), [*yap*](http://rolandtoth.hu/yaP/#examples/Haroopad.ini)
* [**Komodo Edit**](http://www.activestate.com/komodo-edit) / [*paf*](https://sourceforge.net/projects/askomodoeditpaf/), [*yap*](http://rolandtoth.hu/yaP/#examples/Komodo%20Edit%209.3.ini), [*thumb*](http://www.thumbapps.org/2016/05/Komodo-Edit-text-editor-portable.html), [*site*](http://community.komodoide.com/t/is-there-a-portable-version-of-komodoedit/695)
* [**MarkdownEdit**](http://markdownedit.com/) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?p=81353), [*thumb*](http://www.thumbapps.org/2016/08/Markdown-Edit-portable-mardown-text-editor.html)
* [**Notepad++**](https://notepad-plus-plus.org/) / [*tpfc*](https://www.portablefreeware.com/?id=539), [*paf*](http://portableapps.com/apps/development/notepadpp_portable)
* [**Notepad2**](http://www.flos-freeware.ch/notepad2.html) | [**mod**](https://xhmikosr.github.io/notepad2-mod/) / [*tpfc*](https://www.portablefreeware.com/?id=649), [*tpfc-mod*](https://www.portablefreeware.com/forums/viewtopic.php?f=4&t=22433), [*paf*](http://portableapps.com/apps/development/notepad2_portable), [*paf-mod*](http://portableapps.com/apps/development/notepad2-mod_portable), [*sf*](https://sourceforge.net/projects/notepad2/), [*kliu*](http://code.kliu.org/misc/notepad2/)
* [**Notepad3**](https://www.rizonesoft.com/downloads/notepad3/) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?f=4&t=23090)
* [**Programmer's Notepad**](http://www.pnotepad.org/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=2109)
* [**RJ TextEd**](http://www.rj-texted.se/) / [*tpfc*](https://www.portablefreeware.com/?id=2206)
* [**SciTE**](http://www.scintilla.org/SciTE.html) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?t=1596), [*wpp*](http://www.winpenpack.com/en/download.php?view.659) / *Sc1* is a version with all the DLLs included in one EXE
* [**Sublime Text**](https://www.sublimetext.com/) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?t=16943) / not free, but unlimited evaluation
* [**SynWrite**](http://www.uvviewsoft.com/synwrite/) / [*tpfc*](https://www.portablefreeware.com/?id=2375)
* [**TextAdept**](https://foicica.com/textadept/) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?t=20636), [*yap*](http://rolandtoth.hu/yaP/#examples/TextAdept.ini)
* [**Visual Studio Code**](https://code.visualstudio.com/) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?p=82783), [*paf*](https://github.com/garethflowers/vscode-portable)

### Version Control
* [**Git**](https://git-scm.com/) | [**For Windows**](https://git-for-windows.github.io/) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?p=66571), [*paf*](https://github.com/sheabunge/GitPortable), [*stack*](http://stackoverflow.com/questions/22310007/differences-between-git-scm-msysgit-git-for-windows/22310210#22310210?newreg=4dd14f94819e4a60aa0d711f16c75bbd), [*choc*](https://chocolatey.org/packages/git)
* [**SmartGit**](http://www.syntevo.com/smartgit/) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?p=84327), [*avi*](http://aviaryan.in/blog/smartgit-portable-github-client.html)

### Web Servers
* [**EasyPHP**](http://www.easyphp.org/) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?t=2144), [*pen*](https://pendriveapps.com/easyphp-portable-wamp-web-server/) / available as [Devserver](http://www.easyphp.org/easyphp-devserver.php) and [Webserver](http://www.easyphp.org/easyphp-webserver.php) variants
* [**Laragon**](https://laragon.org/) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?p=82528), [*sf*](https://sourceforge.net/projects/laragon/), [*forum*](https://forum.laragon.org/), [*laravel*](https://laravel.com/) / focuses on Laravel PHP framework for webdev / available as stripped-down Lite version
* [**MicroApache**](https://custodesblog.wordpress.com/2013/03/25/microapache-2-0-64-with-php-5-2-17-for-windows/) / [*sf*](https://sourceforge.net/projects/microapache/) / [DokuWiki On A Stick](#wiki) version has up-to-date Apache and PHP
* [**Neard**](https://github.com/crazy-max/neard) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?p=82512) / very large in size / requires admin rights
* [**Uniform Server**](http://www.uniformserver.com/) / [*tpfc*](https://www.portablefreeware.com/?id=396), [*sf*](https://sourceforge.net/projects/miniserver/)
* [**XAMPP**](https://www.apachefriends.org/index.html) / [*tpfc*](https://www.portablefreeware.com/?id=1069), [*paf*](http://portableapps.com/apps/development/xampp), [*pen*](https://pendriveapps.com/xampp-portable-web-server/), [*sf*](https://sourceforge.net/projects/xampp/) / place at the root of the drive

## Education

[*contents*](#contents), [*top*](#awesome-portable-)

[![Alms](img/alms.jpg)](https://pixabay.com/en/asia-burma-faith-boy-buddha-1807519/)

### Genealogy
* [**Ahnenblatt**](http://www.ahnenblatt.com/index.html) / [*tpfc*](https://www.portablefreeware.com/index.php?id=2736) / PAF version distributed by developer
* [**Gramps**](https://gramps-project.org/) / [*paf*](http://portableapps.com/apps/education/gramps_portable), [*site*](https://gramps-project.org/wiki/index.php?title=Run_Gramps_from_a_portable_drive)
* [**ScionPC**](http://homepages.paradise.net.nz/scionpc/) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?f=4&t=22947)

### Geography
* [**Marble**](https://marble.kde.org/) / [*tpfc*](https://www.portablefreeware.com/?id=2326), [*paf*](http://portableapps.com/apps/education/marble_portable)
* [**Panoply**](http://www.giss.nasa.gov/tools/panoply/) / [*sp*](http://www.softpedia.com/get/Science-CAD/Panoply.shtml) / made by NASA / portable by running `Panoply.jar` through JPortable
* [**QGIS**](http://www.qgis.co.za/en/site/) / [*archgeek*](http://www.archaeogeek.com/portable-gis.html), [*docs*](http://portable-gis-docs.readthedocs.io/en/latest/index.html), [*stack*](http://gis.stackexchange.com/questions/176825/are-there-any-portable-versions-of-qgis), [*ground*](https://www.groundtruth.com.au/gis-on-a-stick), [*git*](https://github.com/groundtruth/GIS-on-a-Stick) / very large

### Medical

[*irfanview*](#image-viewers), [*techadvice*](http://technologyadvice.com/blog/healthcare/5-dicom-viewers/), [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?f=2&t=23227)

* [Gingo CADx]
* [Mango]

### Religion
* [**Bible Analyzer**](http://www.bibleanalyzer.com/) / [*tpfc*](https://www.portablefreeware.com/?id=2704)
* [**Bible Lightning**](http://www.softpedia.com/get/PORTABLE-SOFTWARE/Education/BibleLightning-Portable.shtml) | [**Console**](http://www.softpedia.com/get/PORTABLE-SOFTWARE/Education/Portable-BibleLightning-Console.shtml) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?p=79666), [*ff*](http://www.freewarefiles.com/BibleLightning_program_91140.html), [*pen*](https://pendriveapps.com/portable-bible-lightning/) / fast KJV lookup / [homepage](http://www.biblelightning.org/) offline
* [**BPBible**](https://github.com/bpbible/bpbible) / [*tpfc*](https://www.portablefreeware.com/?id=1597), [*paf*](http://portableapps.com/apps/education/bpbible_portable)
* [**Davar4**](http://www.davar3.net/) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?p=79667)
* [**Ready Bible Study and Reference**](http://michaels-tech-notes.weebly.com/blog/category/religion) / [*sp*](http://www.softpedia.com/get/Others/Home-Education/Ready-Bible-Study-and-Reference.shtml), [*ff*](http://www.freewarefiles.com/Ready-Bible-Study-and-Reference_program_107176.html) / settings saved to INIs within program directory
* [**The Word**](http://www.theword.net/index.php?) / [*tpfc*](https://www.portablefreeware.com/?id=1248)

### Statistics
* [**R**](https://www.r-project.org) / [*paf*](http://portableapps.com/node/32898), [*sf*](https://sourceforge.net/projects/rportable/files/R-Portable/)
* [**RStudio**](https://www.rstudio.com) / [*paf*](https://sourceforge.net/projects/rportable/files/R-Studio/)
* [**Tinn-R**](https://sourceforge.net/projects/tinn-r/) / [*paf*](http://portableapps.com/node/52078), [*sf*](https://sourceforge.net/projects/tinn-r/files/)

## Graphics

[*contents*](#contents), [*top*](#awesome-portable-)

[![Cactus](img/cactus.jpg)](https://pixabay.com/en/cactus-orange-view-perspective-1873977/)

### 3D
* [**Blender**](https://www.blender.org/) / [*tpfc*](https://www.portablefreeware.com/?id=660), [*paf*](http://portableapps.com/apps/graphics_pictures/blender_portable), [*blend*](https://www.blender.org/manual/getting_started/installing/configuration/directories.html), [*wpp*](http://www.winpenpack.com/main/download.php?view.41)
* [**MagicaVoxel**](https://ephtracy.github.io/index.html?page=mv_main) | [**Viewer**](https://ephtracy.github.io/index.html?page=mv_renderer) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?p=84300)

### Animation
* [**OpenToonz**](https://opentoonz.github.io/e/) / [*paf*](https://github.com/turtletooth/OpenToonzPortable), [*git*](https://github.com/opentoonz) / GTS, a scanning program, and a set of Dwango effect plugins are available from the main site

### Art
* [**Krita**](https://krita.org/en/) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?p=82550), [*paf*](http://portableapps.com/apps/graphics_pictures/krita-portable), [*yap*](http://rolandtoth.hu/yaP/#examples/Krita.ini), [*thumb*](http://www.thumbapps.org/2016/05/Krita-digital-painting-32-64-bit-portable.html) / yaP launcher, as well as `KDEHOME` method, works with Krita versions up to `2.9.11` / best to use the PAF for `3.0` onwards
* [**MyPaint**](http://mypaint.org/) / [*tpfc*](https://www.portablefreeware.com/?id=2088), [*paf*](http://portableapps.com/apps/graphics_pictures/mypaint-portable)
* [**Pixia**](http://www.ne.jp/asahi/mighty/knight/) / [*tpfc*](https://www.portablefreeware.com/?id=26)

### CAD

* [**KiCad**](http://kicad-pcb.org/) / [*paf*](http://www.cybercircuits.co.nz/web/KiCadPortable), [*sf*](https://sourceforge.net/projects/kicad4-portable/), [*d2k*](http://www.designer2k2.at/mods/elektronik/104-kicad-portable) / EDA PCB design suite
* [**OpenSCAD**](http://www.openscad.org/) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?p=80983), [*yap*](http://rolandtoth.hu/yaP/#examples/OpenSCAD.ini)
* [**SolveSpace**](http://solvespace.com/index.pl) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?p=46045), [*yap*](http://rolandtoth.hu/yaP/#examples/SolveSpace.ini)
* [**Sweet Home 3D**](http://www.sweethome3d.com/) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?p=79756)

### Colour Pickers
* [**ColorCop**](http://colorcop.net/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=617), [*wpp*](http://www.winpenpack.com/en/download.php?view.1070)
* [**ColorGrabber**](https://nur.gratis/software/colorgrabber-2-0-tool-zum-aufnehmen-picken-von-farben-von-der-desktop-oberflaeche-125.htm) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?p=84314) / homepage in German
* [**ColorPic**](https://www.iconico.com/colorpic/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=1225)
* [**Instant Eyedropper**](http://instant-eyedropper.com/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=1856)
* [**Just Color Picker**](http://annystudio.com/software/colorpicker/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=2712)
* [**Pixie**](http://www.nattyware.com/pixie.php) / [*tpfc*](https://www.portablefreeware.com/?id=1558)

### GIF
* [**GifCam**](http://blog.bahraniapps.com/gifcam/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=2541)
* [**GIF Viewer**](https://sourceforge.net/projects/gifviewer/) / [*yap*](http://rolandtoth.hu/yaP/#examples/GIF%20Viewer.ini)
* [**LICEcap**](http://www.cockos.com/licecap/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=2587)
* [**ScreenToGif**](http://www.screentogif.com/) | [**Alt**](http://screentogif.codeplex.com/) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?f=4&t=21813)

### Image Editors
* [**GIMP**](https://www.gimp.org/) / [*tpfc*](https://www.portablefreeware.com/?id=644), [*paf*](http://portableapps.com/apps/graphics_pictures/gimp_portable), [*wpp*](http://www.winpenpack.com/en/download.php?view.71), [*partha*](http://www.partha.com/)
* [**PhotoScape**](http://www.photoscape.org/ps/main/index.php) / [*tpfc*](https://www.portablefreeware.com/?id=1339), [*thumb*](http://www.thumbapps.org/2016/05/PhotoScape-photo-editor-portable.html), [*yap*](http://rolandtoth.hu/yaP/#examples/PhotoScape.ini)

### Image Compression
* [**Caesium**](https://saerasoft.com/caesium/) | [**Online**](https://saerasoft.com/caesium/online/) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?t=20757), [*paf*](http://portableapps.com/apps/graphics_pictures/caesium-portable), [*sf*](https://sourceforge.net/projects/caesium/), [*fosshub*](https://www.fosshub.com/Caesium-Image-Compressor.html) / CaesiumPH needs to be tested for portability
* [**FileOptimizer**](http://nikkhokkho.sourceforge.net/static.php?page=FileOptimizer) / [*tpfc*](https://www.portablefreeware.com/?id=2377) / does much more than images, eg PDFs
* [**PngOptimizer**](http://psydk.org/pngoptimizer) / [*tpfc*](https://www.portablefreeware.com/?id=1277), [*paf*](http://portableapps.com/apps/graphics_pictures/pngoptimizer-portable), [*pen*](https://pendriveapps.com/pngoptimizer-optimize-and-convert-png/)
* [**RIOT**](http://luci.criosweb.ro/riot/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=1821), [*thumb*](http://www.thumbapps.org/2015/08/Radical-Image-Optimization-Tool-RIOT-portable.html)
* [Romeolight tools]

### Image Viewers
* [**Faststone Viewer**](http://faststone.org/FSViewerDetail.htm) / [*tpfc*](https://www.portablefreeware.com/index.php?id=207)
* [**HoneyView**](http://www.bandisoft.com/honeyview/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=2497)
* [**Imagine**](http://www.nyam.pe.kr/blog/entry/Imagine) / [*tpfc*](https://www.portablefreeware.com/?id=1819)
* [**Irfanview**](http://www.irfanview.com/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=49), [*paf*](http://portableapps.com/apps/graphics_pictures/irfanview_portable)
* [**XnView**](http://www.xnview.com/en/xnview/) | [**MP**](http://www.xnview.com/en/xnviewmp/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=30), [*mp*](https://www.portablefreeware.com/forums/viewtopic.php?p=35220), [*paf*](http://portableapps.com/apps/graphics_pictures/xnview_portable)

### RAW
* [**Photivo**](http://photivo.org/start) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?p=81038), [*site*](http://photivo.org/download/windows)
* [**RawTherapee**](http://rawtherapee.com/) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?p=6669), [*paf*](http://portableapps.com/apps/graphics_pictures/rawtherapee-portable), [*rawpedia*](http://50.87.144.65/~rt/w/index.php?title=Making_a_Portable_Installation)

### Screen Capture
* [**Greenshot**](http://getgreenshot.org/) / [*tpfc*](https://www.portablefreeware.com/?id=2340), [*site*](http://getgreenshot.org/faq/will-there-ever-be-a-portable-apps-version-of-greenshot/), [*pen*](https://pendriveapps.com/free-screen-capture-tool-greenshot/) / dev distributes PAF version as well / not on PortableApps site due to .NET 2 requirement
* [**Lightscreen**](https://lightscreen.com.ar/) / [*tpfc*](https://www.portablefreeware.com/?id=1959), [*paf*](http://portableapps.com/apps/utilities/lightscreen_portable)
* [**PicPick**](http://ngwin.com/picpick) / [*tpfc*](https://www.portablefreeware.com/index.php?id=1496), [*paf*](http://portableapps.com/apps/graphics_pictures/picpick-portable) / pixel ruler, magnifier, whiteboard, etc
* [**Screenshot Captor**](https://www.donationcoder.com/Software/Mouser/screenshotcaptor/) / [*tpfc*](https://www.portablefreeware.com/?id=2412)
* [**ShareX**](https://getsharex.com/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=2409), [*steam*](http://store.steampowered.com/app/400040/) / multiple image capture and sharing methods
* [**Snipaste**](https://www.snipaste.com/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=2801)

### Vector Editors
* [**Inkscape**](https://inkscape.org/en/) / [*tpfc*](https://www.portablefreeware.com/?id=657), [*paf*](http://portableapps.com/apps/graphics_pictures/inkscape_portable), [*wpp*](http://www.winpenpack.com/en/download.php?view.39)

## Internet

[*contents*](#contents), [*top*](#awesome-portable-)

[![Smartphone](img/smartphone.jpg)](https://pixabay.com/en/google-on-your-smartphone-search-1796337/)

### Browsers
* [**Google Chrome**](https://www.google.com/chrome/browser/desktop/index.html) / [*tpfc*](https://www.portablefreeware.com/index.php?id=2074), [*paf*](http://portableapps.com/apps/internet/google_chrome_portable), [*thumb*](https://sourceforge.net/projects/thumbapps/files/Internet/Google%20Chrome/)
* [**K-Meleon**](http://kmeleonbrowser.org/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=520), [*paf*](http://portableapps.com/apps/internet/k-meleon-portable)
* [**Mozilla Firefox**](https://www.mozilla.org/en-US/firefox/new/) / [*tpfc*](https://www.portablefreeware.com/?id=132), [*paf*](http://portableapps.com/apps/internet/firefox_portable), [*thumb*](https://sourceforge.net/projects/thumbapps/files/Internet/Firefox/)
* [**Pale Moon**](http://www.palemoon.org/) | [**Portable**](http://www.palemoon.org/palemoon-portable.shtml) / [*tpfc*](https://www.portablefreeware.com/index.php?id=1978) / fork of Firefox focusing on efficiency and ease of use
* [**SeaMonkey**](http://www.seamonkey-project.org/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=2089), [*paf*](http://portableapps.com/apps/internet/seamonkey_portable) / all-in-one browser from Mozilla including email, RSS, newsgroups, IRC & HTML editing
* [**SlimJet**](http://www.slimjet.com/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=2633)
* [**Vivaldi**](https://vivaldi.com/) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?p=73125), [*thumb*](http://www.thumbapps.org/2015/02/vivaldi-108338-tech-preview-portable.html), [*sf*](https://sourceforge.net/projects/thumbapps/files/Internet/Vivaldi/)

### Download Managers
* [**Advanced Wget GUI**](https://github.com/Nenirey/AWGG) | [**Alt**](https://sites.google.com/site/awggproject/) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?p=77772), [*sp*](http://www.softpedia.com/get/PORTABLE-SOFTWARE/Internet/Others/Portable-AWGG.shtml), [*vh*](http://www.videohelp.com/software/AWGG)
* [**EagleGet**](http://www.eagleget.com/) / [*tpfc*](https://www.portablefreeware.com/?id=2597)
* [**WinWGet**](http://winwget.sourceforge.net/) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?t=20900), [*paf*](http://portableapps.com/apps/internet/winwget_portable), [*astatix*](http://www.astatix.com/tools/winwget.php), [*sf*](https://sourceforge.net/projects/winwget/) / see TPFC thread for Wget-related resources

### Email

[*seamonkey*](#browsers)

* [**Sylpheed**](http://sylpheed.sraoss.jp/en/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=1112), [*paf*](http://portableapps.com/apps/internet/sylpheed-portable), [*wpp*](http://www.winpenpack.com/en/download.php?view.1113)
* [**Mozilla Thunderbird**](https://www.mozilla.org/en-US/thunderbird/) | [**Lightning**](https://addons.mozilla.org/en-US/thunderbird/addon/lightning/) / [*tpfc*](https://www.portablefreeware.com/?id=133), [*paf*](http://portableapps.com/apps/internet/thunderbird_portable), [*wpp*](http://www.winpenpack.com/en/download.php?view.1277) / Lightning extension adds calendar and to-do list functionality
* [**Pegasus Mail**](http://www.pmail.com/index.htm) / [*tpfc*](https://www.portablefreeware.com/index.php?id=422)

### FTP
* [**Bitvise SSH Client**](https://www.bitvise.com/ssh-client) / [*tpfc*](https://www.portablefreeware.com/index.php?id=1982) / formerly *Tunnelier*
* [**FileZilla**](https://filezilla-project.org/) | [**Secure**](http://www.filezillasecure.com/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=9), [*paf*](http://portableapps.com/apps/internet/filezilla_portable), [*wpp*](http://www.winpenpack.com/main/download.php?view.717), [*secure*](https://www.portablefreeware.com/forums/viewtopic.php?p=83983#p83983) / test: can FileZilla Server can be used portably via [portable servers](#web-servers) like XAMPP or Neard? / FileZilla Secure is a fork of FileZilla with password encryption, however its portability status is murky
* [**WinSCP**](https://winscp.net/eng/index.php) / [*tpfc*](https://www.portablefreeware.com/index.php?id=214), [*paf*](http://portableapps.com/apps/internet/winscp_portable), [*wpp*](http://www.winpenpack.com/en/download.php?view.569) / PortableApps version integrates with PuTTY Portable

### Instant Messaging

[*teamviewer*](#remote-access)

* [**BeeBEEP**](http://beebeep.sourceforge.net/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=2783) / p2p, no server required / secure file sharing / includes tetris :)
* [**IsoToxin**](http://isotoxin.im/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=2774)
* [**Pidgin**](https://www.pidgin.im/) / [*tpfc*](https://www.portablefreeware.com/?id=1345), [*paf*](http://portableapps.com/apps/internet/pidgin_portable)
* [**qTox**](https://qtox.github.io/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=2755)
* [**RetroShare**](http://retroshare.net/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=2353) / includes secure p2p file sharing
* [**Ricochet**](https://ricochet.im/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=2851)
* [**Telegram**](https://telegram.org/) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?f=4&t=22115), [*paf*](http://portableapps.com/apps/internet/telegram-desktop-portable)

### Remote Access
* [**TeamViewer**](https://www.teamviewer.com/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=1703), [*paf*](http://portableapps.com/apps/utilities/teamviewer_portable) / file transfers, instant messaging and VoIP too

### RSS

[*thunderbird*](#email), [*seamonkey*](#browsers), [*ghacks*](http://www.ghacks.net/2013/07/31/quiterss-0-13-2-revisiting-the-windows-rss-reader-after-a-year/)

* [**QuiteRSS**](https://quiterss.org/) / [*tpfc*](https://www.portablefreeware.com/?id=2749), [*paf*](http://portableapps.com/apps/internet/quiterss-portable)
* [**RSSOwl**](http://www.rssowl.org/) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?f=4&t=975), [*purkdell*](http://purkdellapps.blogspot.co.za/2016/06/rssowl-portable.html), [*wpp*](http://www.winpenpack.com/en/download.php?view.973), [*paf*](http://portableapps.com/node/36808), [*discuss*](https://sourceforge.net/p/rssowl/discussion/296910/thread/a534d2e6/), [*git*](https://github.com/rssowl/rssowl-portable) / requires Java or JPortable

### Torrents
* [**Bit Che**](https://convivea.com/product.php?id=2) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?f=4&t=21658), [*yap*](http://rolandtoth.hu/yaP/#examples/Bit%20Che.ini)
* [**PicoTorrent**](http://www.picotorrent.org/) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?p=79128)
* [**qBittorrent**](http://qbittorrent.sourceforge.net/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=2406), [*paf*](http://portableapps.com/apps/internet/qbittorrent_portable), [*wpp*](http://www.winpenpack.com/en/download.php?view.1358)
* [**Tixati**](https://www.tixati.com/) / [*tpfc*](https://www.portablefreeware.com/?id=2571), [*site*](https://www.tixati.com/download/portable.html)
* [**Transmission-Qt**](https://sourceforge.net/projects/trqtw/) | [**Bt**](https://transmissionbt.com/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=2725), [*paf*](http://portableapps.com/apps/internet/transmission-portable), [*thumb*](https://sourceforge.net/projects/thumbapps/files/Internet/Transmission/)
* [**µTorrent**](http://www.utorrent.com/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=483), [*paf*](http://portableapps.com/apps/internet/utorrent_portable)

### VoIP

[*teamviewer*](#remote-access)

* [**Mumble**](http://wiki.mumble.info/wiki/Main_Page) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?p=9770), [*paf*](http://portableapps.com/apps/internet/mumble-portable)
* [**Skype**](https://www.skype.com/en/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=503), [*paf*](http://portableapps.com/apps/internet/skype_portable), [*yap*](http://rolandtoth.hu/yaP/#examples/Skype.ini) / video calling and conferencing as well

## Multimedia

[*contents*](#contents), [*top*](#awesome-portable-)

[![Microphone](img/microphone.jpg)](https://pixabay.com/en/microphone-mic-mike-voice-audio-1246057/)

### Audio Editors
* [**Audacity**](http://www.audacityteam.org/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=648), [*paf*](http://portableapps.com/apps/music_video/audacity_portable), [*wpp*](http://www.winpenpack.com/en/download.php?view.37)
* [**ocenaudio**](http://www.ocenaudio.com/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=2799), [*yap*](http://rolandtoth.hu/yaP/#examples/Ocenaudio.ini)
* [**Wavosaur**](http://www.wavosaur.com/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=1187)

### Disk Tools
* [**AnyBurn**](http://www.anyburn.com/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=2361), [*yap*](http://rolandtoth.hu/yaP/#examples/AnyBurn.ini)
* [**CDBurnerXP**](https://cdburnerxp.se/en/home) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?f=4&t=23161)
* [**cdrtfe**](http://cdrtfe.sourceforge.net/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=694), [*paf*](http://portableapps.com/apps/music_video/cdrtfe_portable), [*wpp*](http://www.winpenpack.com/en/download.php?view.179)
* [**ImgBurn**](http://www.imgburn.com/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=583), [*paf*](http://portableapps.com/node/21615), [*wpp*](http://www.winpenpack.com/en/download.php?view.1305)
* [**InfraRecorder**](http://infrarecorder.org/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=960), [*paf*](http://portableapps.com/apps/utilities/infrarecorder_portable)

### Media Conversion
* [**fre:ac**](http://www.freac.org/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=570), [*paf*](http://portableapps.com/apps/music_video/freac_portable)
* [**LameXP**](http://lamexp.sourceforge.net/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=2094)
* [**TAudioConverter**](http://taudioconverter.sourceforge.net/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=2556), [*paf*](http://portableapps.com/apps/music_video/taudioconverter-portable)

### Music Players
* [**1by1**](http://mpesch3.de1.cc/1by1.html) / [*tpfc*](https://www.portablefreeware.com/?id=90)
* [**AIMP**](http://www.aimp.ru/index.php) / [*tpfc*](https://www.portablefreeware.com/index.php?id=1444), [*paf*](http://portableapps.com/apps/music_video/aimp-portable)
* [**Audacious**](http://audacious-media-player.org/) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?p=81470), [*yap*](http://rolandtoth.hu/yaP/#examples/Audacious.ini)
* [**Foobar2000**](http://www.foobar2000.org/) / [*tpfc*](https://www.portablefreeware.com/?id=184)
* [**Nemp**](http://www.gausi.de/nemp-en.html) / [*tpfc*](https://www.portablefreeware.com/index.php?id=2170)
* [**Winyl**](http://vinylsoft.com/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=2110)
* [**Xion**](http://www.xionplayer.com/) / [*tpfc*](https://www.portablefreeware.com/?id=1290) / has cool PSD skinning feature
* [**XMPlay**](http://www.un4seen.com/xmplay.html) / [*tpfc*](https://www.portablefreeware.com/index.php?id=567), [*paf*](http://portableapps.com/apps/music_video/xmplay_portable), [*wiki*](https://en.wikipedia.org/wiki/XMPlay) / based on the [BASS](http://www.un4seen.com/bass.html) library by the same dev

### Podcasts
* [**gPodder**](http://gpodder.org/) / [*tpfc*](https://www.portablefreeware.com/?id=1673), [*paf*](http://portableapps.com/apps/internet/gpodder_portable)

### Scoring

[jedit syntax]

* [LilyPond]
* [MuseScore]

### Screen Recording
* [**OBS**](https://obsproject.com) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?p=80343), [*paf*](http://portableapps.com/node/53266), [*thumb*](http://www.thumbapps.org/2015/08/OBS-Open-Broadcaster-Software-32-64-bit-portable.html), [*obs*](https://obsproject.com/forum/resources/obs-and-obs-studio-portable-mode-on-windows.359/)
* [**oCam**](http://ohsoft.net/eng/ocam/download.php) / [*yap*](http://rolandtoth.hu/yaP/#examples/oCam.ini)

### Tagging
* [**Mp3tag**](http://www.mp3tag.de/en/index.html) / [*tpfc*](https://www.portablefreeware.com/index.php?id=1137)
* [**TagScanner**](http://www.xdlab.ru/en/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=1427)

### Video Editors
* [**Shotcut**](https://www.shotcut.org/) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?p=84320), [*site*](https://www.shotcut.org/blog/portable-app/)
* [**Vidiot**](https://sourceforge.net/projects/vidiot/) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?t=20911), [*vh*](http://www.videohelp.com/software/Vidiot)

### Video Players
* [**HamMultiPlayer**](http://hammultiplayer.org/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=2791) / view multiple media files at the same time
* [**Light Alloy**](http://www.light-alloy.ru/) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?p=46371)
* [**MPC-HC**](https://mpc-hc.org/) | [**BE**](https://sourceforge.net/projects/mpcbe/) / [*tpfc*](https://www.portablefreeware.com/?id=2054), [*be*](https://www.portablefreeware.com/forums/viewtopic.php?p=60655), [*paf*](http://portableapps.com/apps/music_video/mpc-hc-portable) / MPC-BE is a fork of MPC-HC with additional functionality and the obvious dark UI
* [**PotPlayer**](http://potplayer.daum.net/) / [*tpfc*](https://www.portablefreeware.com/?id=2483), [*paf*](http://portableapps.com/node/41287)
* [**SMPlayer**](http://smplayer.sourceforge.net/) | [**SMTube**](http://www.smtube.org/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=1358), [*paf*](http://portableapps.com/apps/music_video/smplayer_portable), [*wpp*](http://www.winpenpack.com/en/download.php?view.1245), [*7z*](http://smplayer.sourceforge.net/en/download-smplayer-portable) / use SMTube to browse and play YouTube videos
* [**VLC Media Player**](http://www.videolan.org/vlc/) / [*tpfc*](https://www.portablefreeware.com/?id=599), [*paf*](http://portableapps.com/apps/music_video/vlc_portable)

## Office

[*contents*](#contents), [*top*](#awesome-portable-)

[![Building](img/building.jpg)](https://pixabay.com/en/architecture-buildings-sky-1842614/)

### Calendar

[*pim*](#pims), [*thunderbird*](#email)

* [**Calendar**](http://www.horstmuc.de/wrem.htm#calendar) / submit to TPFC
* [**Date Reminder**](http://www.horstmuc.de/wrem.htm) / [*tpfc*](https://www.portablefreeware.com/?id=831), [*pen*](https://pendriveapps.com/date-reminder/)
* [**Rainlendar Lite**](http://www.rainlendar.net/cms/index.php) / [*tpfc*](https://www.portablefreeware.com/index.php?id=443) / Pro version available
* [**UK's Kalender**](http://www.ukrebs-software.de/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=647)

### Diary

[*mempad*](#outliners)

* [**Hazama**](https://krrr.github.io/hazama) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?p=79899)
* [**RedNotebook**](http://rednotebook.sourceforge.net/) / [*tpfc*](https://www.portablefreeware.com/?id=2086), [*paf*](http://portableapps.com/apps/office/rednotebook_portable)

### Desktop Publishing
* [**Scribus**](https://www.scribus.net/) / [*tpfc*](https://www.portablefreeware.com/?id=658), [*paf*](http://portableapps.com/apps/office/scribus_portable), [*wpp*](http://www.winpenpack.com/en/download.php?view.1325), [*sf*](https://sourceforge.net/projects/portablescribus/) / requires Ghostscript Portable for PDF functionality

### Document Scanning

[*viewers*](#image-viewers)

* [**NAPS2**](https://www.naps2.com/) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?f=4&t=22493), [*thumb*](http://www.thumbapps.org/2015/08/NAPS2-Not-Another-PDF-Scanner-2-portable.html), [*sf*](https://sourceforge.net/projects/naps2/) / includes OCR
* [**WinScan2PDF**](http://www.softwareok.com/?Microsoft/WinScan2PDF) / [*tpfc*](https://www.portablefreeware.com/?id=2051), [*paf*](http://portableapps.com/node/42115), [*pen*](https://pendriveapps.com/scan-files-to-pdf-winscan2pdf/)

### Document Viewers
* [**Evince**](https://wiki.gnome.org/Apps/Evince) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?p=84294), [*paf*](http://portableapps.com/apps/office/evince_portable)
* [**Foxit Reader**](https://www.foxitsoftware.com/products/pdf-reader/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=1041), [*paf*](http://portableapps.com/apps/office/foxit_reader_portable), [*yap*](http://rolandtoth.hu/yaP/#examples/Foxit%20Reader.ini)
* [**PDF-XChange Editor**](https://www.tracker-software.com/product/pdf-xchange-editor) / [*tpfc*](https://www.portablefreeware.com/index.php?id=2832) / Pro version available with more features
* [**PDF-XChange Viewer**](https://www.tracker-software.com/product/pdf-xchange-viewer) / [*tpfc*](https://www.portablefreeware.com/index.php?id=1436), [*paf*](http://portableapps.com/apps/office/pdf-xchange-portable) / superceded by Editor / last version was `v2.5.319.0` / OCR plugin & PDF help files available / Pro version available with more features
* [**STDU Viewer**](http://www.stdutility.com/stduviewer.html) / [*tpfc*](https://www.portablefreeware.com/index.php?id=2045)
* [**SumatraPDF**](http://www.sumatrapdfreader.org/free-pdf-reader.html) / [*tpfc*](https://www.portablefreeware.com/index.php?id=1193), [*paf*](http://portableapps.com/apps/office/sumatra_pdf_portable)
* [**WinDJView**](http://windjview.sourceforge.net/) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?p=10115), [*paf*](http://portableapps.com/apps/office/windjview_portable), [*yap*](http://rolandtoth.hu/yaP/#examples/WinDjView.ini)

### Finance
* [**GnuCash**](http://www.gnucash.org/) / [*tpfc*](https://www.portablefreeware.com/?id=1421), [*paf*](http://portableapps.com/apps/office/gnucash_portable) / personal and small-business accounting
* [**HomeBank**](http://homebank.free.fr/index.php) / [*site*](http://homebank.free.fr/downloads.php), [*thumb*](http://www.thumbapps.org/2015/10/Homebank-personal-finance-manager-portable.html), [*paf*](http://portableapps.com/node/19551), [*wpp*](http://www.winpenpack.com/en/download.php?view.1104) / installer includes portable option / submit to TPFC
* [**Money Manager Ex**](http://www.moneymanagerex.org/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=924), [*paf*](http://portableapps.com/apps/office/money_manager_ex_portable)

### Mindmapping
* [FreeMind]
* [Freeplane]

### Notetaking

[*tagspaces*](#file-tagging), [*outliners*](#outliners)

* [**CintaNotes**](http://cintanotes.com/) / [*tpfc*](https://www.portablefreeware.com/?id=1468), [*paf*](http://portableapps.com/apps/office/cintanotes-portable) / Pro version available
* [**Flashnote**](http://softvoile.com/flashnote/) / [*tpfc*](https://www.portablefreeware.com/?id=2775)
* [**Laverna**](https://laverna.cc/) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?p=82446)
* [**QOwnNotes**](http://www.qownnotes.org/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=2816)
* [**ResophNotes**](http://resoph.com/ResophNotes/Welcome.html) / [*tpfc*](https://www.portablefreeware.com/?id=1951) / includes [SimpleNote](https://simplenote.com/) syncing

### Office Suites
* [**LibreOffice**](https://www.libreoffice.org/) / [*tpfc*](https://www.portablefreeware.com/?id=2055), [*paf*](http://portableapps.com/apps/office/libreoffice_portable)
* [**OpenOffice**](https://www.openoffice.org/) / [*tpfc*](https://www.portablefreeware.com/?id=212), [*paf*](http://portableapps.com/apps/office/openoffice_portable), [*wpp*](http://www.winpenpack.com/en/download.php?view.1341)
* [**SoftMaker FreeOffice**](http://www.freeoffice.com/en/) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?t=20457), [*site*](http://www.freeoffice.com/en/tips-and-tricks-portable-installation)

### Outliners
* [**Cherrytree**](http://www.giuspen.com/cherrytree/) / [*tpfc*](https://www.portablefreeware.com/?id=2790), [*paf*](http://portableapps.com/apps/office/cherrytree-portable)
* [**KeyNote**](https://sourceforge.net/projects/keynote/) | [**NF**](https://github.com/dpradov/keynote-nf) / [*tpfc*](https://www.portablefreeware.com/?id=755), [*sf*](https://sourceforge.net/projects/keynote-newfeat/) / KeyNote NF is an active fork of the dead KeyNote with extended features
* [**MemPad**](http://www.horstmuc.de/wmem.htm) / [*tpfc*](https://www.portablefreeware.com/index.php?id=889) / can function as diary with auto-added dates
* [**The Guide**](http://theguide.sourceforge.net/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=1499), [*paf*](http://portableapps.com/apps/office/the_guide_portable), [*pen*](https://pendriveapps.com/the-guide/) / last updated 2008
* [**TreeLine**](http://treeline.bellz.org/) / [*tpfc*](https://www.portablefreeware.com/?id=971)
* [**TreePad**](http://www.treepad.com/treepadfreeware/) / [*tpfc*](https://www.portablefreeware.com/?id=1734), [*site*](http://www.treepad.com/docs/tpp/manual/documents/EF4D74B8A82E2967538FE68A60B39269B954DE12.html) / Pro version available 

### PIMs
* [**EssentialPIM**](http://www.essentialpim.com/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=98)
* [**Info-Base**](http://freeware.persoft.ch/program_en.htm) / [*tpfc*](https://www.portablefreeware.com/index.php?id=2521)

### Project Management
* [**DevProject Manager**](http://www.gaijin.at/en/dldevproject.php) / [*tpfc*](https://www.portablefreeware.com/index.php?id=1273)
* [**Task Coach**](http://www.taskcoach.org/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=2113), [*paf*](http://portableapps.com/apps/office/task_coach_portable)
* [**ToDoList**](http://abstractspoon.weebly.com/) | [**Alt**](https://www.codeproject.com/Articles/5371/ToDoList-An-effective-and-flexible-way-to-keep-on) / [*tpfc*](https://www.portablefreeware.com/index.php?id=816), [*paf*](http://portableapps.com/apps/office/todolist_portable) / was removed from PortableApps at the dev's request
* [**Todomoo**](http://todomoo.sourceforge.net/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=2486)

### TeX

[*biglist*](http://tex.stackexchange.com/questions/339/latex-editors-ides)

* [**MiKTeX**](https://miktex.org/) / [*site*](https://miktex.org/portable), [*paf*](http://portableapps.com/node/53801)
* [**TeX Live**](https://www.tug.org/texlive/) / [*site*](https://www.tug.org/texlive/doc/texlive-en/texlive-en.html#tlportable)
* [**TeXPortable**](https://symera.de/texportable/) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?p=81416#p81416)
* [**TeXstudio**](http://www.texstudio.org/) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?p=76798), [*paf*](http://portableapps.com/node/53350)

### Wiki

[*mediawiki*](https://www.mediawiki.org/wiki/Manual:Wiki_on_a_stick)

* [**DokuWiki**](https://www.dokuwiki.org/dokuwiki#) | [**On A Stick**](https://www.dokuwiki.org/install:dokuwiki_on_a_stick) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?p=83274) / self-hosted wiki software run on a portable [MicroApache](#web-servers) server
* [**OutWiker**](http://jenyay.net/Outwiker/English) / [*tpfc*](https://www.portablefreeware.com/index.php?id=2797)
* [**TiddlyWiki**](http://tiddlywiki.com/) | [**Classic**](http://classic.tiddlywiki.com/) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?t=2031), [*git*](https://github.com/Jermolene/TiddlyWiki5) / single HTML opened with a browser / not a program, per se, but certainly portable
* [**WikidPad**](http://wikidpad.sourceforge.net/) / [*tpfc*](https://www.portablefreeware.com/?id=1099), [*site*](http://wikidpad.sourceforge.net/help/ConfigurationFiles.html)
* [**Zim**](http://www.zim-wiki.org/) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?p=56775), [*paf*](http://portableapps.com/node/29350), [*site*](http://www.glump.net/software/zim-windows) / PAF available from dev

### Writing
* [**FocusWriter**](https://gottcode.org/focuswriter/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=2064), [*paf*](http://portableapps.com/apps/office/focuswriter_portable)
* [**Q10**](http://www.baara.com/q10/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=1381) / last updated 2011
* [**WriteMonkey**](http://writemonkey.com/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=1627), [*forum*](https://www.portablefreeware.com/forums/viewtopic.php?f=20&t=7231&hilit=writemonkey), [*thumb*](http://www.thumbapps.org/2016/08/WriteMonkey-portable-text-editor-writing-application.html)

## Security

[*contents*](#contents), [*top*](#awesome-portable-)

[![Rope](img/rope.jpg)](https://pixabay.com/en/rope-fasten-steadfast-fastening-1274372/)

### Antivirus
* [**ClamWin**](http://www.clamwin.com/) | [**Sentinel**](http://clamsentinel.sourceforge.net/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=601), [*paf*](http://portableapps.com/apps/security/clamwin_portable), [*wpp*](http://www.winpenpack.com/en/download.php?view.38), [*site*](http://www.clamwin.com/content/view/118/89/) / not as good as closed-source AV solutions / ClamSentinel adds real-time scanning capability

### Cleaners
* [**BleachBit**](http://www.bleachbit.org/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=1561), [*paf*](http://portableapps.com/apps/utilities/bleachbit_portable)
* [**CCleaner**](http://www.piriform.com/ccleaner) | [**CCEnhancer**](https://singularlabs.com/software/ccenhancer/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=885)
* [**PrivaZer**](http://privazer.com/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=2350)

### Deletion
* [**Blank And Secure**](http://www.softwareok.com/?seite=Microsoft/BlankAndSecure) / [*tpfc*](https://www.portablefreeware.com/index.php?id=1691)
* [**OW Shredder**](https://hendrik.tf/ow-shredder.html) / [*tpfc*](https://www.portablefreeware.com/index.php?id=2737)

### Malware Scanners
* [**Emsisoft Emergency Kit**](https://www.emsisoft.com/en/software/eek/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=2651)
* [**Spybot – Search & Destroy**](https://www.safer-networking.org/private/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=2047), [*paf*](http://portableapps.com/apps/security/spybot_portable)

### Passwords
* [**KeePass**](http://keepass.info/) | [**Edition Comparison**](http://keepass.info/compare.html) / [*tpfc*](https://www.portablefreeware.com/index.php?id=2829), [*classic*](https://www.portablefreeware.com/index.php?id=194), [*paf*](http://portableapps.com/apps/utilities/keepass_portable) / KeePass v.2 ("Professional") is a rewrite of v.1 ("Classic") with more features and a .NET 2 requirement / both versions are free, open source and **actively maintained**
* [**Password Gorilla**](https://github.com/zdia/gorilla/wiki) / [*tpfc*](https://www.portablefreeware.com/index.php?id=303), [*paf*](http://portableapps.com/apps/security/password-gorilla-portable)
* [**Password Safe**](https://pwsafe.org/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=1197), [*paf*](http://portableapps.com/apps/security/password-safe-portable)
* [**Sisma**](http://www.digitalconfidence.com/Sisma-Password-Manager.html) / [*tpfc*](https://www.portablefreeware.com/index.php?id=2848)

## Utilities

[*contents*](#contents), [*top*](#awesome-portable-)

[![Yamaha](img/yamaha.jpg)](https://pixabay.com/en/yamaha-motorcycle-details-1653663/)

### Archivers
* [**Bandizip**](http://www.bandisoft.com/bandizip/) / [*tpfc*](https://www.portablefreeware.com/?id=2397)
* [**Peazip**](http://www.peazip.org/) / [*tpfc*](https://www.portablefreeware.com/?id=1048), [*paf*](http://portableapps.com/apps/utilities/peazip_portable), [*thumb*](https://sourceforge.net/projects/thumbapps/files/Utilities/Bandizip/)

### Automation
* [**AutoHotkey**](https://www.autohotkey.com/) | [**SciTE4AutoHotkey**](http://fincs.ahk4.net/scite4ahk/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=217), [*awesome*](https://github.com/ahkscript/awesome-AutoHotkey)
* [**AutoIt**](https://www.autoitscript.com/site/autoit/) | [**SciTE4AutoIt**](https://www.autoitscript.com/site/autoit-script-editor/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=50), [*awesome*](https://github.com/J2TeaM/awesome-AutoIt)
* [**Pulover's Macro Creator**](http://www.macrocreator.com/) / [*tpfc*](https://www.portablefreeware.com/?id=2776), [*paf*](http://portableapps.com/node/41746)
* [**TinyTask**](http://www.vtaskstudio.com/support.php#tools) / [*tpfc*](https://www.portablefreeware.com/?id=1853), [*paf*](http://portableapps.com/apps/utilities/tinytask_portable)

### Backup
* [**Back4Sure**](http://www.ukrebs-software.de/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=1684)
* [**jaBuT Backup**](http://jabut.de/en) / [*tpfc*](https://www.portablefreeware.com/?id=2812)
* [**Personal Backup**](http://personal-backup.rathlev-home.de/index-e.html) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?p=28563), [*yap*](http://rolandtoth.hu/yaP/#examples/Personal%20Backup.ini)
* [**ZBack**](http://titan.fsb.hr/~dzorc/zback.html) / [*tpfc*](https://www.portablefreeware.com/index.php?id=1683)

### Calculators
* [**RedCrab**](http://www.redchillicrab.com/en/redcrab/index.html) / [*tpfc*](https://www.portablefreeware.com/index.php?id=2095) / shareware version available with extra functionality
* [**SpeedCrunch**](http://speedcrunch.org/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=1547), [*paf*](http://portableapps.com/apps/office/speedcrunch_portable)

### Cataloguing
* [**MiTeC DirList**](http://www.mitec.cz/dirlist.html) / [*tpfc*](https://www.portablefreeware.com/?id=2522), [*yap*](http://rolandtoth.hu/yaP/#examples/DirList.ini)

### Characters
* [**BabelMap**](http://www.babelstone.co.uk/Software/BabelMap.html) / [*tpfc*](https://www.portablefreeware.com/?id=2352), [*paf*](http://portableapps.com/apps/utilities/babelmap-portable), [*yap*](http://rolandtoth.hu/yaP/#examples/BabelMap.ini)
* [**BabelPad**](http://www.babelstone.co.uk/Software/BabelPad.html) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?p=57921), [*paf*](http://portableapps.com/apps/office/babelpad-portable)
* [**WinCompose**](https://github.com/SamHocevar/wincompose) / [*tpfc*](https://www.portablefreeware.com/index.php?id=2615)

### Clipboard
* [**ArsClip**](http://www.joejoesoft.com/vcms/97/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=734)
* [**Clipjump**](http://clipjump.sourceforge.net/) / [*tpfc*](https://www.portablefreeware.com/?id=2523), [*git*](https://github.com/aviaryan/Clipjump), [*ahk*](https://autohotkey.com/boards/viewtopic.php?f=6&t=401) / available as AHK script
* [**CopyQ**](http://hluk.github.io/CopyQ/) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?p=69636)
* [**Ditto**](http://ditto-cp.sourceforge.net/index.php) / [*tpfc*](https://www.portablefreeware.com/index.php?id=1361), [*paf*](http://portableapps.com/apps/utilities/ditto_portable)

### Control Panels

[*symenu*](#launchers)

* [**neuPanel**](http://nuetools.co.uk/) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?p=84209) / frontend for Control Panel and various Windows built-in utilities
* [**WSCC**](http://www.kls-soft.com/wscc/index.php) / [*tpfc*](https://www.portablefreeware.com/index.php?id=1666) / interface for Control Panel, NirSoft and SysInternals suites / PAF available from the developer

### Copiers
* [**FastCopy**](https://ipmsg.org/tools/fastcopy.html.en) / [*tpfc*](https://www.portablefreeware.com/index.php?id=1437), [*paf*](http://portableapps.com/apps/utilities/fastcopy-portable)

### Defragmentation
* [**Defraggler**](http://www.piriform.com/defraggler) / [*tpfc*](https://www.portablefreeware.com/?id=1418)
* [**IObit Smart Defrag**](http://www.iobit.com/en/iobitsmartdefrag.php) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?f=4&t=7922), [*paf*](http://portableapps.com/apps/utilities/smart_defrag_portable)
* [**UltraDefrag**](http://ultradefrag.sourceforge.net/en/index.html) / [*tpfc*](https://www.portablefreeware.com/index.php?id=2228), [*paf*](http://portableapps.com/apps/utilities/ultradefrag-portable)
* [**WinContig**](http://wincontig.mdtzone.it/en/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=1215) / *file* defrag

### Duplicates
* [**AllDup**](http://www.alldup.de/en_index.php) / [*tpfc*](https://www.portablefreeware.com/index.php?id=1791)

### File Managers
* [**Double Commander**](http://doublecmd.sourceforge.net/) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?t=4648)
* [**FileVoyager**](http://www.filevoyager.com/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=2826)
* [**Free Commander XE**](http://freecommander.com/en/summary/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=291), [*paf*](http://portableapps.com/apps/utilities/freecommander_portable) / 64-bit version is donationware
* [**MultiCommander**](http://multicommander.com/) / [*tpfc*](https://www.portablefreeware.com/?id=2304)
* [**NexusFile**](http://www.xiles.net/) / [*tpfc*](https://www.portablefreeware.com/?id=1419)
* [**Q-Dir**](http://www.softwareok.com/?seite=Freeware/Q-Dir) / [*tpfc*](https://www.portablefreeware.com/?id=1431), [*paf*](http://portableapps.com/apps/utilities/q-dir-portable/)
* [**Tablacus Explorer**](http://www.eonet.ne.jp/~gakana/tablacus/explorer_en.html) / [*tpfc*](https://www.portablefreeware.com/index.php?id=2781), [*thumb*](http://www.thumbapps.org/2016/09/Tablacus-Explorer-portable-multi-tab-Windows-file-explorer.html) / addon support via built-in addon manager
* [**Total Commander**](https://www.ghisler.com) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?p=527), [*paf*](http://portableapps.com/node/14220), [*totalcmd*](https://www.ghisler.com/usbinst.htm) / not free, but certainly very good

### File Tagging
* [**TagSpaces**](https://www.tagspaces.org/) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?f=4&t=21728), [*site*](https://www.tagspaces.org/documentation/installation/#portableMode) / notetaking ability as well

### Fonts
* [**NexusFont**](http://www.xiles.net/) / [*tpfc*](https://www.portablefreeware.com/?id=731)

### Launchers

[*sites*](#important-sites), [*automation*](#automation)

* [**ASuite**](http://www.salvadorsoftware.com/asuite) / [*tpfc*](https://www.portablefreeware.com/?id=692)
* [**Clavier+**](http://utilfr42.free.fr/util/Clavier.php) / [*tpfc*](https://www.portablefreeware.com/index.php?id=983) / hotkeys
* [**FARR**](https://www.donationcoder.com/Software/Mouser/findrun/) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?p=6848)
* [**Executor**](http://www.1space.dk/executor/) | [**Alt**](http://executor.dk/) / [*tpfc*](https://www.portablefreeware.com/?id=1308)
* [**KeyPirinha**](http://keypirinha.com/) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?p=81346), [*docs*](http://keypirinha.com/install.html)
* [**PopSel**](http://www.horstmuc.de/wpop.htm) / [*tpfc*](https://www.portablefreeware.com/?id=2679)
* [**Portable Start Menu**](http://www.aignes.com/psmenu.htm)/ [*tpfc*](https://www.portablefreeware.com/?id=1365)
* [**PowerPro**](http://powerpro.cresadu.com/) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?f=4&t=209)
* [**PStart**](http://www.pegtop.net/start/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=374) / last updated 2007 / check out ASuite for a more up-to-date alternative
* [**Qsel**](http://www.horstmuc.de/wqsel.htm) / [*tpfc*](https://www.portablefreeware.com/?id=1133)
* [**Quick Access Popup**](http://www.quickaccesspopup.com/) | [**Folders Popup**](http://code.jeanlalonde.ca/folderspopup/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=2765), [*fp*](https://www.portablefreeware.com/?id=2557) / QAP supercedes Folders Popup / created with AHK
* [**Run-Command**](http://www.softwareok.com/?seite=Microsoft/Run-Command) / [*tpfc*](https://www.portablefreeware.com/?id=2402)
* [**SideSlide**](http://www.northglide.com/sideslide.html) / [*tpfc*](https://www.portablefreeware.com/index.php?id=1409)
* [**Splat**](http://skwire.dcmembers.com/fp/?page=splat) / [*tpfc*](https://www.portablefreeware.com/index.php?id=2667) / includes sequencing and grouping capabilities
* [**SyMenu**](http://www.ugmfree.it/) / [*tpfc*](https://www.portablefreeware.com/?id=2394) / NirSoft and SysInternals utilities available to download & update within suite 
* [**XVA Assistant**](http://www.idesktop.me/) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?p=83028)

### Processes
* [**DTaskManager**](http://dimio.altervista.org/eng/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=944), [*paf*](http://portableapps.com/apps/utilities/dtaskmanager_portable)
* [**MiTeC Task Manager DeLuxe**](http://www.mitec.cz/tmx.html) / [*tpfc*](https://www.portablefreeware.com/index.php?id=2345)
* [**Process Explorer**](https://technet.microsoft.com/en-us/sysinternals/bb896653) / [*tpfc*](https://www.portablefreeware.com/index.php?id=32), [*paf*](http://portableapps.com/apps/utilities/process-explorer-portable)
* [**Process Hacker**](https://wj32.org/processhacker/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=1934), [*paf*](http://portableapps.com/apps/utilities/process-hacker-portable)
* [**System Explorer**](http://systemexplorer.net/) / [*tpfc*](https://www.portablefreeware.com/?id=1491), [*paf*](http://portableapps.com/apps/utilities/system_explorer_portable) / many advanced features

### Registry
* [**RegAlyzer**](https://www.safer-networking.org/products/regalyzer/) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?t=1174), [*paf*](http://portableapps.com/apps/utilities/regalyzer-portable), [*thumb*](http://www.thumbapps.org/2015/07/RegAlyzer-registry-file-editor-portable.html)

### Renamers
* [**Advanced Renamer**](https://www.advancedrenamer.com/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=1848)
* [**Ant Renamer**](http://www.antp.be/software/renamer) / [*tpfc*](https://www.portablefreeware.com/index.php?id=66), [*paf*](http://portableapps.com/apps/utilities/ant_renamer_portable)
* [**Bulk Rename Utility**](http://www.bulkrenameutility.co.uk/) | [**Command**](http://www.bulkrenameutility.co.uk/Command.php) / [*tpfc*](https://www.portablefreeware.com/?id=1008)
* [**Lupas Rename**](http://rename.lupasfreeware.org/lupasrename.php) / [*tpfc*](https://www.portablefreeware.com/?id=47) / last updated 2005
* [**Rename Master**](http://www.joejoesoft.com/vcms/108/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=269)
* [**ReNamer**](http://www.den4b.com/products/renamer) / [*tpfc*](https://www.portablefreeware.com/index.php?id=562), [*5.71*](http://download.cnet.com/ReNamer-Portable/3000-2248_4-75894242.html) / versions after `5.71` are crippleware, with a max of 5 presets and 5 rules

### Search
* [**Everything**](http://www.voidtools.com/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=1479)
* [**Listary**](http://www.listary.com/) / [*tpfc*](https://www.portablefreeware.com/?id=1680), [*paf*](http://portableapps.com/apps/utilities/listary_portable) / Pro version available with more features

### Time
* [**TheAeroClock**](http://www.softwareok.com/?seite=Freeware/TheAeroClock) / [*tpfc*](https://www.portablefreeware.com/?id=2209)
* [**TimeSync**](http://www.horstmuc.de/wrem.htm#timesync) / [*tpfc*](https://www.portablefreeware.com/?id=836) / sync with NIST server
* [**Titlebar Date-Time**](http://www.whisperingpinessoftware.com/tbdt.html) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?p=84159)
* [**TTclock**](http://www.horstmuc.de/wrem.htm#ttclock) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?f=4&t=17670) / desktop clock, timer, stopwatch, alarm

### Uninstallers
* [**Bulk Crap Uninstaller**](http://klocmansoftware.weebly.com/) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?p=77953)
* [**IObit Uninstaller**](http://www.iobit.com/en/advanceduninstaller.php) / [*tpfc*](https://www.portablefreeware.com/forums/viewtopic.php?p=30919), [*paf*](http://portableapps.com/apps/utilities/iobit_uninstaller_portable) / requires admin rights
* [**Revo Uninstaller**](http://www.revouninstaller.com/) / [*tpfc*](https://www.portablefreeware.com/index.php?id=1398), [*paf*](http://portableapps.com/apps/utilities/revo_uninstaller_portable) / Pro version available
* [**ZSoft Uninstaller**](https://www.zsoft.dk/index/software_details/4) | [**Portable**](https://www.zsoft.dk/index/software_details/6) / [*tpfc*](https://www.portablefreeware.com/index.php?id=2299), [*paf*](http://portableapps.com/apps/utilities/zsoft_uninstaller_portable)

### Window Managers
* [**TidyTabs**](http://www.nurgo-software.com/products/tidytabs) / [*tpfc*](https://www.portablefreeware.com/index.php?id=2850) / Free version limited to 3 tabs

## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, Shane Bowman has waived all copyright and related or neighbouring rights to this work.

*Images courtesy [Pixabay](https://pixabay.com/), `CC0`*.


