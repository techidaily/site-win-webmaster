---
title: "Karaoke Software Update Released: New Features and Seamless SongBookDB Syncing"
date: 2024-12-23T17:50:52.557Z
updated: 2024-12-30T02:57:40.643Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/wNhKhWc0wLc?si=1XLYV0sXV52Xc0lu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-blue.techidaily.com/new-in-2024-premier-auditory-solutions-iphone-tunes-makers/"><u>[New] In 2024, Premier Auditory Solutions IPhone Tunes Makers</u></a></li>
<li><a href="https://location-fake.techidaily.com/5-easy-ways-to-change-location-on-youtube-tv-on-vivo-v30-drfone-by-drfone-virtual-android/"><u>5 Easy Ways to Change Location on YouTube TV On Vivo V30 | Dr.fone</u></a></li>
<li><a href="https://win-webmaster.techidaily.com/experiencing-sluggish-gameplay-on-powerful-gpus-unraveling-the-mystery-with-yl-software-solutions/"><u>Experiencing Sluggish Gameplay on Powerful GPUs? Unraveling the Mystery with YL Software Solutions</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/full-guide-to-catch-100-iv-pokemon-using-a-map-on-nokia-g42-5g-drfone-by-drfone-virtual-android/"><u>Full Guide to Catch 100 IV Pokémon Using a Map On Nokia G42 5G | Dr.fone</u></a></li>
<li><a href="https://win-webmaster.techidaily.com/high-resolution-audi-a7-desktop-wallpapers-and-screen-savers-innovative-wallpaper-collections-by-yl-computing/"><u>High-Resolution Audi A7 Desktop Wallpapers and Screen Savers - Innovative Wallpaper Collections by YL Computing</u></a></li>
<li><a href="https://win-able.techidaily.com/how-to-fix-microsoft-flight-simulator-2020-when-its-frozen-at-update-prompt/"><u>How to Fix Microsoft Flight Simulator 2020 When It's Frozen at Update Prompt</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/in-2024-mastering-facebook-video-auto-play/"><u>In 2024, Mastering Facebook Video Auto-Play</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-why-does-the-pokemon-go-battle-league-not-available-on-realme-c67-4g-drfone-by-drfone-virtual-android/"><u>In 2024, Why does the pokemon go battle league not available On Realme C67 4G | Dr.fone</u></a></li>
<li><a href="https://win-webmaster.techidaily.com/is-your-printer-and-os-matched-right-discover-here-at-yl-computing/"><u>Is Your Printer and OS Matched Right? Discover Here at YL Computing</u></a></li>
<li><a href="https://win-webmaster.techidaily.com/marvels-iron-man-featured-desktop-wallpapers-and-imagery-downloadable-hd-collection-by-yl-computing/"><u>Marvel's Iron Man Featured Desktop Wallpapers & Imagery - Downloadable HD Collection by YL Computing</u></a></li>
<li><a href="https://win-webmaster.techidaily.com/setting-up-your-own-crypto-miner-a-step-by-step-guide-with-yl-computings-expertise/"><u>Setting Up Your Own Crypto-Miner: A Step-by-Step Guide with YL Computing's Expertise</u></a></li>
<li><a href="https://win-webmaster.techidaily.com/stunning-natural-landscapes-premium-wallpapers-backdrops-and-photographs-by-yl-computing/"><u>Stunning Natural Landscapes: Premium Wallpapers, Backdrops & Photographs by YL Computing</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/0-hashtags-propel-video-views-in-gameplay/"><u>Top 30 Hashtags Propel Video Views in Gameplay</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/transformative-grading-3-simplified-photoshop-routines/"><u>Transformative Grading 3 Simplified Photoshop Routines</u></a></li>
<li><a href="https://win-webmaster.techidaily.com/understanding-potential-pitfalls-a-deep-dive-into-cryptocurrency-safety-concerns-insights-from-yl-computing-and-yl-software/"><u>Understanding Potential Pitfalls: A Deep Dive Into Cryptocurrency Safety Concerns - Insights From YL Computing and YL Software</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/unveiling-the-superiority-of-ring-video-doorbell-2-in-our-expert-review/"><u>Unveiling the Superiority of Ring Video Doorbell 2 in Our Expert Review</u></a></li>
<li><a href="https://win-webmaster.techidaily.com/unveiling-the-true-expenses-the-complete-breakdown-of-hosting-karaoke-at-your-local-bar-or-eatery/"><u>Unveiling the True Expenses: The Complete Breakdown of Hosting Karaoke at Your Local Bar or Eatery</u></a></li>
</ul></div>

