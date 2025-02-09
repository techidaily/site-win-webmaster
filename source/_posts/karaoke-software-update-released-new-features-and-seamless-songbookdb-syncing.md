---
title: "Karaoke Software Update Released: New Features and Seamless SongBookDB Syncing"
date: 2025-02-05T01:45:28.249Z
updated: 2025-02-09T00:09:07.808Z
tags:
  - product
categories:
  - pcdj
thumbnail: https://thmb.techidaily.com/25814137ff2b0c0573cec745d5d0a7576d58b816448c60f70b991c5a0f3d865d.jpeg
---

## Karaoke Software Update Released: New Features and Seamless SongBookDB Syncing

[![](https://i0.wp.com/pcdj.com/wp-content/uploads/2014/11/karaokibeta-songbookdbcover.jpg?resize=530%2C298&ssl=1)](https://i0.wp.com/pcdj.com/wp-content/uploads/2014/11/karaokibeta-songbookdbcover.jpg?fit=530%2C298&ssl=1 "karaokibeta-songbookdbcover")

It’s [karaoke software](https://tools.techidaily.com/pcdj/products/) beta test time, now with direct in-application integration of SongbookDB’s internet based remote request plugin.

Last week we posted about [how the SongbookDB integration in Karaoki will work](https://tools.techidaily.com/pcdj/products/), now we call on KJs to download and try the new beta now. Included in this beta are multiple performance upgrades and other new features to try.

#### Here are all the details and info below on how you can download and test the latest beta today:

**Karaoki Beta 0.8.5419** Notes:

_You will notice that there is a new item on the ‘Options’ button menu ‘Remote Connections’ and when clicked you will see a new screen. This screen is similar to the old ‘Remote Request Station’ area that was on the config screen and if you have used the old interface shouldn’t have any issues using the new screen._

[![](https://i1.wp.com/pcdj.com/wp-content/uploads/2014/10/Songbook-Plugin.png?fit=300%2C183&ssl=1 "Songbook Plugin")](https://i1.wp.com/pcdj.com/wp-content/uploads/2014/10/Songbook-Plugin.png?fit=981%2C601&ssl=1)

The majority of the new screen (the entire lower half and the ‘Cases’ drop down list) is for the existing ‘Remote Terminal’ application and for similar future plugins, this lower section is not used for the SongbookDB plugin as it manages its own incoming requests itself.

**Here are a few pointers.**  
Most of the items on the upper section of the screen should already be familiar to you and so I’ll only go over any changes…

**Changing the port:**  
Karaoki will probably have the port set to 6000 as this is the old default, however, the new plugin will have its port set to 81 by default so it will have to be changed either in Karaoki or on the plugin.. In Karaoki the port can only be changed when the ‘Remote’ is disabled using the ‘Enable/Disable’ button (the large top left button on the new screen). So to change the port, If enabled, disable the remote connections using the ‘Enable/Disable’ button, Change the port number in the port box, then re-enable the remote connections using the Enable button.

**Remote Options:**  
1.) ‘Shutdown Client Applications/Plugins on Exit’: when checked Karaoki will send the ‘shutdown’ command to any connected plugin before it closes, If the plugin supports this command the plugin should then close.  
2.) ‘Disable Request Alerts’: when Karaoki receives a singers request it will notify you by flashing a message on the main screen and on the ‘Remote Connections’ screen, Checking the option disables the flashing massages as they could be annoying to some users.

_**The lower half of the screen… ‘Remote Request Station’ (and any future equivalents) only:**_

Requested Tracks list: when Karaoki receives a track form ‘Remote Request station’ the request is now placed in this list where it will remain until it is ‘Accepted’ or Declined’, Accepting the request will transfer the request to Karaoki’s rotation, ‘Declining’ the request will remove the request from the list.

**Ban:** If you have a singer that’s being a PITA you now have the option to ‘Ban’ Him/Her, when banned any requests from the banned individual are ignored and will not be added to the ‘Requested Tracks’ list.

**‘Auto Accept’ option:** when checked all incoming requests are automatically accepted, so when receiving incoming requests from a ‘Remote Request Station’ Karaoki will behave as it did in previous builds and place the requested tracks directly into rotation.

[![](https://i2.wp.com/pcdj.com/wp-content/uploads/2014/10/Karaoki-Remote-Users..png?fit=300%2C188&ssl=1 "Karaoki Remote Users.")](https://i2.wp.com/pcdj.com/wp-content/uploads/2014/10/Karaoki-Remote-Users..png?fit=594%2C374&ssl=1)

**General use:**  
When a request is sent from a terminal or via SongbookDB an alert message will flash on Karaoki’s main screen and also in the ‘Remote Connections’ screen, clicking on the message on the main screen will cancel the message and display either the SongbookDB plugin (for requests from SongbookDB users) or the ‘Remote Connections’ screen (for all other requests), the request will then need to be ‘Accepted’ (‘add +’ on the SongbookDB plugin) for it to be added to the rotation.

**_That’s it!!_**

**Here’s a list of all Fixes, Additions and Changes since the last beta.**

_**Build #0.8.5419.37065 Nov 2nd 2014**_  
Added: SongbookDB plugin integration and ‘Remote Connections’ screen added.  
Added: ‘/lockcases’ command line switch and ‘Ctrl+Shift+W’ Key Combo that hides the ‘Min’, ‘Max’, ‘Exit’, ‘Options’, ‘Add Case’ and ‘Add Songs’ buttons.  
Change: Remote Terminal interface enhanced and moved to ‘Remote Connections’ screen.  
Change: New Licencing System.  
Change: A Few skin changes.  
Fixed: Karaoki not reading some ID3 tags correctly.  
Fixed: Karaoki not displaying ‘&’ on singer screen and preview display and ticker.  
Fixed: Karaoki cutting ticker message short if it contains a carriage return, the Ticker is now limited to 250 characters.  
Fixed: Preview player not working on Win 8 onwards.

[Download Karaoki Beta With SongbookDB Integration](https://tools.techidaily.com/pcdj/products/)

[SongBookDB Video Tutorials - See How It Works!](https://www.songbookdb.com/docs/djs/tutorialVideos/)

ALL BETA REPORTS FOR KARAOKI CAN BE POSTED [HERE ON THE PCDJ FORUM](https://tools.techidaily.com/pcdj/products/)

#### To Gain Access To The SongbookDB Custom PCDJ Plug-In, Fill Out The Form Below. We Will Get Back To You Shortly With Testing Details

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LW6wNx3XAj8?si=VaIuFIIx8MM_RhUR" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### _Related_

https://i0.wp.com/pcdj.com/wp-content/uploads/2014/11/karaokibeta-songbookdbcover.jpg?fit=530%2C298&ssl=1 298 530 Ryan Sherr https://www.pcdj.com/wp-content/uploads/2021/07/pcdj-main-logo-2.png Ryan Sherr2014-11-04 09:59:272023-04-10 17:04:33Karaoki Beta Test Launched with SongBookDB Integration}

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>

<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://article-helps.techidaily.com/updated-mastering-video-production-a-compreey-guide-to-powerdirector-for-2024/"><u>[Updated] Mastering Video Production A Compreey Guide to PowerDirector for 2024</u></a></li>
<li><a href="https://win-webmaster.techidaily.com/1-free-online-conversion-transform-mp3-to-high-quality-flac-files-with-movavi/"><u>1. Free Online Conversion: Transform MP3 to High-Quality FLAC Files with Movavi</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-ideal-14-visual-effects-with-text-animations/"><u>2024 Approved Ideal 14 Visual Effects with Text Animations</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/approved-nixing-the-green-glow-youtubes-mac-solution-manual/"><u>2024 Approved Nixing the Green Glow YouTube's Mac Solution Manual</u></a></li>
<li><a href="https://win-webmaster.techidaily.com/swfmp3-movavi/"><u>在线无成本将SWF文件转换为MP3音频 - 以Movavi为解决方案</u></a></li>
<li><a href="https://win-webmaster.techidaily.com/como-convertir-archivo-rampeam-para-reproducirlos-en-cualquier-dispositivo-gratis-online-soluciones-faciles-de-uso-movavi/"><u>Cómo Convertir Archivo RAMPEAM Para Reproducirlos en Cualquier Dispositivo Gratis Online: Soluciones Fáciles De Uso - Movavi</u></a></li>
<li><a href="https://android-location.techidaily.com/for-people-wanting-to-mock-gps-on-honor-80-pro-straight-screen-edition-devices-drfone-by-drfone-virtual/"><u>For People Wanting to Mock GPS on Honor 80 Pro Straight Screen Edition Devices | Dr.fone</u></a></li>
<li><a href="https://win-webmaster.techidaily.com/free-online-avi-to-mp4-converter-by-movavi/"><u>Free Online AVI to MP4 Converter by Movavi</u></a></li>
<li><a href="https://win-webmaster.techidaily.com/gratuit-online-omzetten-van-ogv-naar-mp4-movavi/"><u>Gratuit Online Omzetten Van OGV Naar MP4 - Movavi</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-open-your-iphone-xr-without-a-home-button-by-drfone-ios/"><u>How To Open Your iPhone XR Without a Home Button</u></a></li>
<li><a href="https://iphone-location.techidaily.com/in-2024-does-pokegoplusplus-still-work-on-apple-iphone-11ipad-drfone-by-drfone-virtual-ios/"><u>In 2024, Does PokeGo++ still work on Apple iPhone 11/iPad? | Dr.fone</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/in-2024-the-ultimate-guide-to-iphone-landscape-photography-excellence/"><u>In 2024, The Ultimate Guide to iPhone Landscape Photography Excellence</u></a></li>
<li><a href="https://buynow-help.techidaily.com/inside-look-at-the-mohu-blade-tv-antenna-remarkable-performance-and-cutting-edge-aesthet-culet/"><u>Inside Look at the Mohu Blade TV Antenna - Remarkable Performance & Cutting-Edge Aesthet Culet</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/quick-tips-for-easy-snapchat-screen-captures-on-phones-for-2024/"><u>Quick Tips for Easy Snapchat Screen Captures on Phones for 2024</u></a></li>
<li><a href="https://win-webmaster.techidaily.com/top-6-finns-gratuiti-brannprogram-for-windows-11-8-och-7-fullstandiga-guide/"><u>Top 6 Finns Gratuiti Brännprogram För Windows 11, 8 Och 7 – Fullständiga Guide</u></a></li>
<li><a href="https://win-webmaster.techidaily.com/ultimate-guide-editing-and-trimming-footage-on-a-mac-with-movavi-video-editor/"><u>Ultimate Guide: Editing & Trimming Footage on a Mac with Movavi Video Editor</u></a></li>
<li><a href="https://win-webmaster.techidaily.com/m1vmpg-movavi/"><u>オンラインでM1VからMPGへの変換: Movaviが無料提供！</u></a></li>
</ul></div>

