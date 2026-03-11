# Projects
## Mario Party Like Game
Pull inspiration from things like Dokapon Kingdom, Sonic Shuffle, Mario Party, Wii Party (U), Fortune Street, Go Go Princess, other video board games, https://boardgamegeek.com/geeklist/147902/video-games-that-feel-like-board-games?page=2 and etc. Be ready to play alot of party games in single player from SNES To today.


## Port Nones (NES Emulator)
### Learn WUT
- https://wiiubrew.org/wiki/Homebrew_development_guide
- https://gamefaqs.gamespot.com/boards/631516-wii-u/69428807
- https://github.com/devkitPro/wut
- https://github.com/devkitPro/wut-packages
- https://gbatemp.net/threads/retroarch-wii-u-devkitpro-r38-and-wut.581160/
- https://wii-u-homebrew-docs.readthedocs.io/en/latest/quickstart.html
- https://github.com/yawut/ProgrammingOnTheU/blob/master/tutorial/Chapter%201.md
- https://wut.devkitpro.org/topics.html
### Learn SDL3
### Set Up default SDL3
Create a menu to test each of SDL3 menus by porting and creating a menu


https://wiki.libsdl.org/SDL3/FrontPage

https://examples.libsdl.org/SDL3/

https://github.com/libsdl-org/SDL/tree/main/test

https://packages.fedoraproject.org/pkgs/SDL3/SDL3-test/index.html

### Port SDL3 to Wii U

Use SDL3 to build ontop of WUT like how sdl2-wut works

https://wiiubrew.org/wiki/Homebrew_development_guide

https://github.com/yawut/sdl2-wiiu

Handle gamepad stuff

### Port NONES to Wii U

Take the SDL3 code and port to wii u

https://github.com/purpasmart96/nones

## Unified Body Tracking app using Kotlin Multiplatform
https://f-droid.org/packages/com.waist.line/
https://medevel.com/openscale/
https://www.androidpolice.com/best-open-source-fitness-apps-android/
https://github.com/simonoppowa/OpenNutriTracker/wiki
https://kotlinlang.org/docs/multiplatform.html
Try to store open nutritional facts and push back new information and filter.


## Build a Better Quickbooks Sharp API V2 since the one that exist on nuget is weak. Try to make it multi API so it for all the business languages like Java, C#, Python,  C++, C, maybe Rust and Go.
- [QuickBooksSharp](https://www.nuget.org/packages/QuickBooksSharp)
- [Java and C# get first class support since they are supported natively. ](https://developer.intuit.com/app/developer/qbo/docs/get-started/build-your-first-app#:~:text=build%20a%20%E2%80%9CDemo-,app,-%E2%80%9D%20in%20.NET%2C%20Java)
- Just create a memory safe C versions for other to build ontop of or make API calls to support Python, C++ and C in a memory safe way.

## A Meta Job Engine which handles the effort of syncing all Job boards
information together like resumes, projects, messages and etc.
Similiar to video sharing site, an applicaiton that syncs all Job Boards websites information like description and projects job status so it doesn't need to be done manually.
A unified Job search application that use AI to automatically search companies for Jobs and determine which skills they require and years of expierince and combine with user information automatically fills out application

- Any changes to the metasite affects all sites
	- Updating resume should update default resume for all websites
- Uses AI to extract required skills and requested years of experience to improve job search
- Should support company websites to allow more direct
- Do NOT handle creating accounts rather the user should handle getting the account. Only use login
- Site must be secure completely.
- It should show jobs on a page and remove them once they've gone missing.
- Should keep track of any duplicates and repostings ideally.





## Tagged File System

A tool that allows files to be tagged with metadata in a centralized database. It should also add data where applicable to the file if possible.

- Should be written in C for max compatiblity with tools.
- Should work similiar to anime sites tagging system
	- https://www.pixiv.net/en/artworks/130315454
	- https://www.artstation.com/artwork/x3xdnX
	- https://www.artstation.com/artwork/b386E
	- http://www.minitokyo.net/
	- https://www.zerochan.net/3351462
	- https://www.zerochan.net/Fanart
	- https://www.deviantart.com/lost-lily88/art/Usagi-Rain-1046757404
	- https://www.deviantart.com/forum/art/general/2029544
	- https://pixai.art/artwork/1853216311935180825-Kafuka-4
	- https://www.quora.com/Are-there-any-good-art-sites-for-anime-manga-style-artists ("Assistant" bot comment)
- Allow tags to have descriptions
- Should pull inspiration from these two videos for features and code base. Read the comments for the first video as they are very helpful
	- https://www.youtube.com/watch?v=wTQeMkYRMcw
	- https://www.youtube.com/watch?v=x_x3FYfykgc&t=607s
- Maybe helpful: https://www.youtube.com/watch?v=MM-MPS57qKA


## Help fix bugs and improve code decoupling from UI in Libreoffice
Reasons why provided

- Read comments
- https://news.ycombinator.com/item?id=16180936
- https://meeksfamily.uk/~michael/data/2016-04-29-solving-problems.pdf
- Maybe add the ability to use sftp to perform live data alteration like with online google Doc or Microsoft office suite

## Unified Record Tracking for Ketro Care Inc
- Call it "Medical Software Provider"
- As of 2025, the healthcare software development market is highly competitive, with several prominent companies leading the way. Here are some of the top medical software providers:
- Research Topics
  
	Epic: Known for its comprehensive EHR software, "Epic EHR," which is widely used by top-ranked US hospitals and medical schools. Epic offers integrated healthcare information systems, including patient records, billing, scheduling, and clinical decision support. The company has been recognized as the Best in KLAS for overall software suite for 13 consecutive years.

	Cerner: A leading provider of healthcare information technology solutions, including EHR systems, revenue cycle management, and clinical decision support tools. Cerner was acquired by Oracle in 2021 for $28.3 billion, further solidifying its position in the market.
	athenahealth: Specializes in cloud-based EHR systems, practice management, revenue cycle management, and patient engagement tools. The company has won numerous awards for its culture, solutions, customer service, and commitment to diversity.

	Siemens Healthineers: A major player in medical technology, offering EHR systems, laboratory information systems, and healthcare analytics tools. Their solutions aim to improve patient outcomes and operational efficiency.

	eClinicalWorks: Provides EHR systems and practice management solutions for ambulatory care settings. Their software includes patient engagement tools, telehealth solutions, and population health management capabilities.

	Veradigm: Offers a wide range of healthcare technology solutions, including EHR systems, practice management systems, and patient engagement platforms. Veradigm is committed to supporting healthcare providers in delivering their best clinical and financial performance.

	McKesson: A diversified healthcare company that provides pharmaceutical distribution, medical supplies, and healthcare software development. Their solutions include EHR systems, revenue cycle management software, and clinical decision support tools.

	KMS Healthcare: A renowned company that provides innovative tools and expertise for creating industry-leading health solutions. They offer a comprehensive range of services, including management, care delivery, data analytics, and patient experience.

	Wipro: A multinational corporation that develops software for various industries, including healthcare. Wipro offers revenue cycle management systems, interoperability solutions, Medicaid platform, enrollment and billing, and healthcare insurance exchanges.

	GE Healthcare: A subsidiary of General Electric, GE Healthcare provides medical equipment and healthcare information technology solutions. They have been developing AI-based software in collaboration with Spectronic Medical.




## Create Comprehensive Online Content Tracking and interactions web application
This is a website the rolls forums/discussions (reddit), wikis (guidance), rating( metacritic and opencritic) and tracking (myanimelist, anilist, goodread, etc) into one.

## Games
https://boardgamegeek.com/geeklist/359738/board-game-covers-recreated-with-lego
### Manuals / Covers
- https://www.digitpress.com/library/manuals/nes/index.html
- http://pdf.textfiles.com/manuals/ARCADE/
- https://www.digitpress.com/library/manuals/snes/index.html
- https://vimm.net/manual
- https://archive.org/details/consolemanuals
- https://www.videogamemanual.com/
- https://www.thecoverproject.net/view.php?game_id=12474
### Game List
- https://www.gamesdatabase.org/list.aspx?publisher=sega
- https://www.mobygames.com/
- https://www.myabandonware.com/browse/genre/
- https://abandonwaregames.net/
- https://www.abandonwaredos.com/abandonware-linux.php?pag=630&l=Abandoned+Linux+classic+games
- https://www.abandonwaredos.com/charts-top-10.php?pag=578&l=The+best+abandonware+PC+games+of+all+time
- https://gamefaqs.gamespot.com/
- 

## Supports
- It should support all media types
	- Visual Novels
	- Books
	- Games
	- Movies
	- TV Series
	- Franchises
	- User Generate Content liek Fanfiction to create an english version to japanese web novel site
		- Allow users to generate and sell merchandise easily on site through partners.
- Built in Wikia (Improvement over lack luster character info from Myanimelist)
- Store to cell products through affiliate links for profit potentially
- Should be able to support reddit like discussions
- Potentially allow user generated content for things like guides so user can know about the order of using content. (Limited to franchises or multi-media entitites)
- Replace fanfiction and the like with better filtering.
- Should most likely use spring, sqlite and thymeleaf
- Make sure to handle AI webscrapping by rate limiting somehow. Maybe Use IP, or some other metric.

## Create libOfficeSuite
A comprehensive library the allows a user to just create a UI for an office sutie.

- Should pull inspiration from all Office suites
	- Libreoffice
	- Caligra's entire office suite
		- Caligra's feature section : https://www.wps.com/blog/calligra-vs-libreoffice-which-is-better-for-you/#post-content-headline-2
	- WPS
	- Microsoft office
	- https://www.freeoffice.com/en/
- Finally kill off openOffice
- Partial Inspirations: https://news.ycombinator.com/item?id=26133614

## Create a Discord Replacement
https://opensourcealternative.to/alternativesto/discord
https://itsfoss.com/revolt/
https://github.com/spacebarchat/spacebarchat?tab=AGPL-3.0-1-ov-file - will not COC
https://news.ycombinator.com/item?id=43277918
https://news.ycombinator.com/item?id=43784056
https://news.ycombinator.com/item?id=43795300 (search for "trust")
https://rauno.me/craft/interaction-design
Use fediverse or make fediverse compatible?
https://fediverse.info/explore/projects
https://en.wikipedia.org/wiki/Ventrilo - find libraries


## Calibre library to decouple code from UI

## New CalibreUI to be cross platform and run on more targets
 - If using Java (Swing, etc), called Cava
 - If C# (Avalonia), Calibre#
 - If C++(Qt), Calibre++

## GPL 3 Open Techinical Writer Application
 - https://news.ycombinator.com/item?id=37994725

## Email based secured chat app
 - https://news.ycombinator.com/item?id=44335065
 

## Learn other game engines and implement features into Redot
- Prereq is C++

## Assist with developing Emulators for Wii U and 3ds
- [Link](https://gbatemp.net/threads/seta-gx-sega-saturn-emulator.668776/)
- [Link2](https://gbatemp.net/threads/most-powerful-console-to-be-emulated-by-a-wii-u.671609/)

## [Improve WUPClient](https://gbatemp.net/threads/wupclient-and-gui-updates.672551/)
## [Port Ladybird to Wii U](https://gbatemp.net/threads/wii-u-browser-upgrade.524823/)
## Fix and Improve
- https://gbatemp.net/threads/release-uwuvci-injectiine.486781/page-53
- https://gbatemp.net/threads/modmii-is-now-supporting-the-wii-u.668223/
## Port Recomps to Wii U
- https://gbatemp.net/threads/new-static-recompiler-tool-n64recomp-aims-to-seamlessly-modernize-n64-games.655670/page-4#post-10419554
- https://gbatemp.net/threads/mario-kart-64-decomp-gets-ported-to-pc.672569/
- https://gbatemp.net/threads/star-fox-64-is-getting-a-native-pc-port.663682/
- https://gbatemp.net/threads/mario-party-4-decompilation-project-reaches-completion.671028/
- https://gbatemp.net/threads/animal-crossing-for-the-gamecube-has-been-decompiled.672373/page-4#post-10675359
- https://gbatemp.net/threads/pc-port-of-sonic-unleashed-created-by-fans-through-recompilation-project.667773/page-2#post-10601177
- https://gbatemp.net/threads/diddy-kong-racing-decompilation-is-nearing-completion.670454/page-2#post-10643732
- https://gbatemp.net/threads/banjo-kazooie-fully-decomped.660210/#post-10485423
- https://gbatemp.net/threads/retroarch-wiiu-wip.447670/page-743
- https://gbatemp.net/threads/unreleased-dinosaur-planet-n64-game-by-rare-gets-an-initial-recompilation-port-using-n64-recompiled.670742/page-2#post-10648513
- https://gbatemp.net/threads/majoras-mask-pc-port-2ship2harkinian-gets-its-first-release.656419/page-3#post-10429110
- https://gbatemp.net/threads/animal-crossing-for-the-gamecube-has-been-decompiled.672373/
- https://github.com/HarbourMasters/SpaghettiKart
	- https://search.brave.com/search?q=common+ui+elements&summary=1&conversation=75781b32c6bb06121e6b01

## Fix Wii U
 - https://gbatemp.net/threads/ultimate-wii-u-troubleshooting-guide-system-memory-error-160-0103-stuck-wii-u-screen-stuck-factory-reset-black-screen-after-stuck-update.642339/#post-10308257
 - https://gbatemp.net/threads/how-to-setup-rednand-to-fix-system-memory-error-160-0103-failing-emmc-without-soldering.642268/
 - https://gbatemp.net/threads/ultimate-wii-u-troubleshooting-guide-system-memory-error-160-0103-stuck-wii-u-screen-stuck-factory-reset-black-screen-after-stuck-update.642339/
 - https://gbatemp.net/threads/wii-u-bricked-black-screen-of-death.672402/

## Write a program to replace Artist and Album Sort
1. If split by ;, split into character seperated list using ';' and run the ',' reverser. 'Doe, John;Bill' => 'John Doe;Bill'
2. Just run ',' reverse. So, Doe, John => John Dow
## Learn basic of Ide, base languages and their frameworks.


## Libreoffice
Add ability to update the properties of multiple selected slides and have the context menu display it.
- For example, if I select one slide, I can change the background but if I select two then it won't show it because its confusing when it only affect one slide. Either make it affect all or make it not show up at all.

## Make better Linux Music Player (https://andreyor.st/posts/2023-11-19-linux-music-players/)
- Should allow proper shuffle rather than just albums

## Build my own UI Library
### Apple
	https://andymatuschak.org/files/papers/Apple%20Human%20Interface%20Guidelines%201987.pdf
	https://blog-geofcrowl-static-images.s3.us-east-1.amazonaws.com/2020-02-17-collection-higs/APPLE-Guidelines-2005.pdf
	https://vintageapple.org/inside_r/pdf/Human_Interface_Guidelines_1992.pdf
	https://developer.apple.com/design/human-interface-guidelines
	https://codershigh.github.io/guidelines/ios/human-interface-guidelines/resources/index.html
	https://vintageapple.org/inside_r/pdf/Human_Interface_Guidelines_1992.pdf
	https://dev.os9.ca/
	https://dev.os9.ca/techpubs/mac/HIGuidelines/HIGuidelines-2.html
	https://www.macintoshrepository.org/32856-apple-human-interface-guidelines
	https://github.com/sindresorhus/human-interface-guidelines-extras?tab=readme-ov-file
	https://gist.github.com/eonist/f4ba31012815731284d867232f6c70e4

### Palm OS
	https://palm.wiki/development/docs/601/PalmOSCompanion/Nutshell.html
	https://cs.uml.edu/~fredm/courses/91.308-spr05/files/palmdocs/uiguidelines.pdf
	https://palm.wiki/development/docs/601/PalmOSCompanion/UserInterface.html
	https://palm.wiki/development/docs/601/PalmOSCompanion/UserInterface.html
	https://github.com/discatte/palm-development-docs
### Windows
	http://bitsavers.informatik.uni-stuttgart.de/pdf/microsoft/windows_95/Programming_the_Windows_95_User_Interface_1995.pdf
	https://blog.prototypr.io/why-windows-98s-user-onboarding-is-better-than-yours-f93a2d431472
	https://ics.uci.edu/~kobsa/courses/ICS104/course-notes/Microsoft_WindowsGuidelines.pdf
	https://blog-geofcrowl-static-images.s3.us-east-1.amazonaws.com/2020-02-17-collection-higs/MS-Windows-User-Experience-2001.pdf
	https://ics.uci.edu/~kobsa/courses/ICS104/course-notes/Microsoft_WindowsGuidelines.pdf
	https://archive.org/details/windowsinterface00micr
	https://www.bitsavers.org/pdf/microsoft/windows_95/Introducing_Microsoft_Windows_95_1995.pdf
### Gnome / KDE / Third-Party
	https://developer.blender.org/docs/features/interface/human_interface_guidelines/
	https://developer.gnome.org/hig/
	https://develop.kde.org/hig/
	https://docs.qgis.org/3.40/en/docs/developers_guide/hig.html
	https://wiki.documentfoundation.org/Category:HIG
	https://develop.kde.org/hig/
	https://docs.ubports.com/no/latest/humanguide/index.html
	https://www.interaction-design.org/literature/article/user-interface-design-guidelines-10-rules-of-thumb
	https://app.uxcel.com/glossary/human-interface-guidelines
	https://docs.elementary.io/hig
	https://www.geofcrowl.com/blog/articles/2020/2/17/collection-higs/
	https://blog.logrocket.com/ux-design/human-interface-guidelines/
	https://en.wikipedia.org/wiki/Human_interface_guidelines
	https://pdfcoffee.com/designing-interactions-bill-moggridge-pdf-free.html
	- Should be able to sync music between devices
	- Should be able to convert music to another format for other device
	- Should automatically pull useful information from music brainz and what not to get proper organizations
	- Should be able to update tags
	- Should be a type of x app or just a library that allows someone to simply build a UI that calls it so everyone can have their own app
