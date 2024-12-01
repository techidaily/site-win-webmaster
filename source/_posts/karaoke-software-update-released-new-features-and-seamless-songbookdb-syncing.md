---
title: "Karaoke Software Update Released: New Features and Seamless SongBookDB Syncing"
date: 2024-11-29T16:56:43.636Z
updated: 2024-11-30T16:14:14.510Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/XIUatTFH0Zw?si=ZCtoBtIy18y2F5Vc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-leveraging-teamsnap-for-dynamic-virtual-presentations/"><u>[New] In 2024, Leveraging TeamSnap for Dynamic Virtual Presentations</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-the-sound-savants-playbook-for-efficient-audible-records/"><u>[New] The Sound Savant's Playbook for Efficient Audible Records</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-in-2024-exploring-shades-insights-from-the-best-11-color-guides/"><u>[Updated] In 2024, Exploring Shades Insights From the Best 11 Color Guides</u></a></li>
<li><a href="https://win-webmaster.techidaily.com/1-resolving-continuous-beeps-a-guide-to-troubleshooting-your-external-hdd/"><u>1. Resolving Continuous Beeps: A Guide to Troubleshooting Your External HDD</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-market-precision-strategic-package-interpretations/"><u>2024 Approved Market Precision Strategic Package Interpretations</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-premier-church-live-streaming-services-revealed/"><u>2024 Approved Premier Church Live Streaming Services Revealed</u></a></li>
<li><a href="https://tech-revival.techidaily.com/first-glimpses-uncovering-the-history-of-ai/"><u>First Glimpses: Uncovering the History of AI</u></a></li>
<li><a href="https://win-webmaster.techidaily.com/guide-pour-lactivation-de-la-fonction-offline-et-la-synchronisation-des-fichiers-dans-windows-nouvelle-generation/"><u>Guide Pour L'Activation De La Fonction Offline Et La Synchronisation Des Fichiers Dans Windows Nouvelle Génération</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/how-to-transition-your-facebook-vids-into-stellar-hd-for-2024/"><u>How to Transition Your Facebook Vids Into Stellar HD for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/interactive-illusions-vr-storytelling-for-2024/"><u>Interactive Illusions VR Storytelling for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/key-digital-platforms-enhance-your-youtube-traffic/"><u>Key Digital Platforms Enhance Your YouTube Traffic</u></a></li>
<li><a href="https://win-webmaster.techidaily.com/secure-techniques-for-combining-several-vmdk-disks-into-a-single-file/"><u>Secure Techniques for Combining Several VMDK Disks Into a Single File</u></a></li>
<li><a href="https://win-webmaster.techidaily.com/step-by-step-tutorial-for-easily-and-safely-duplicating-your-windows-10-x64x32-system-drive/"><u>Step-by-Step Tutorial for Easily and Safely Duplicating Your Windows 10 (X64/X32) System Drive</u></a></li>
<li><a href="https://win-webmaster.techidaily.com/transfer-videocontent-na-ipad-pro-air-and-mini-schnelle-und-einfache-anleitung/"><u>Transfer Videocontent Na Ipad Pro, Air & Mini - Schnelle Und Einfache Anleitung</u></a></li>
<li><a href="https://win-webmaster.techidaily.com/understanding-vmware-vsphere-features-licensing-and-editions/"><u>Understanding VMware vSphere: Features, Licensing & Editions</u></a></li>
<li><a href="https://win-webmaster.techidaily.com/une-guide-pratique-repasser-votre-disque-dur-vers-un-nouveau-avec-cloner-le-disque-dur-using-clonezilla-sur-les-systemes-dexploitation-windows/"><u>Une Guide Pratique : Repasser Votre Disque Dur Vers Un Nouveau Avec Cloner Le Disque Dur Using Clonezilla Sur Les Systèmes D'Exploitation Windows</u></a></li>
<li><a href="https://win-webmaster.techidaily.com/windows-server-2019c/"><u>Windows Server 2019でシームレスなCドライブのクローニング手順</u></a></li>
</ul></div>

