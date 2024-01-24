# Browsers

## What is a browser?

A web browser is software that allows you to access and view websites on the internet. It acts as your gateway to the online world, enabling you to browse through websites, search for information, watch videos and interact with various online services. Think of a browser as a window into the internet. When you open a browser, you can type a website's address or search keywords in a search bar. The browser then retrieves the requested information and displays it on your screen.

Browsers provide a user-friendly interface that allows you to navigate websites using menus, buttons, and clickable links. They interpret the underlying code of a webpage (Often a text file written in HTML, CSS and JavaScript) and present it to you in a visually appealing format.

## What is a Search Engine?

A search engine is essentially a library for the internet, a place to find the books (web pages) you want to see. When you use a search engine, you type in words or phrases to describe what you want to find, may it be a recipe for chocolate chip cookies or information about your favorite movies. It does this by taking your search query, comparing it with a huge collection of websites and then showing the most relevant sites based on that query.

For a Search Engine to gather its library of websites, it uses a 'web crawler'. These web crawlers explore the internet, visit websites and map their content. The websites in question are then indexed for the Search Engine to compare search queries against.

## What Browsers are out there?

When choosing a web browser, there are many possible choices that fit different use-cases, but you can essentially boil them down to three different browser engines:

- Chromium/Blink (Developed by Google) 
  * Google Chrome
  * Google Chromium (Chrome, but only the Open-Source part)
  * Microsoft Edge
  * Ungoogled Chromium
  * Brave
  * Vivaldi
  * Opera
  * Bromite (Mobile)
- Gecko (Developed by Mozilla)
  * Firefox
  * Librewolf
  * Tor Browser
  * Mullvad Browser
  * Floorp
  * Fennec (Mobile)
  * Mull (Mobile)

- Webkit
 * Safari
 * iOS Browsers (Apple enforces Browsers to use the WebKit Engine on iOS)
 * Gnome Web

## Can't I just use Incognito Mode to stay anonymous?

Contrary to popular belief, Incognito Mode doesn't anonymize you or protect your online privacy as much as it sounds like it does. Using incognito mode helps to keep your _local_ browsing history and cookies from being permanently stored on your device. However, your Internet Service Provider (ISP) and websites can still absolutely track your online activity using your IP Address and various fingerprinting metrics.

## Which Browser should I use?

Choosing a Browser highly depends on what you want to use it for. Do not forget that it's absolutely possible to install multiple Browsers, which I would heavily recommend to seperate your searches and the various parts of your online life. (E.g. seperate your banking and shopping from work and school etc.)

In the end, try out as many options as you can and stick with the thing that works best for you.

- For most people, I'd suggest installing ﻿﻿﻿<a href="https://www.mozilla.org/en-US/firefox/new/" target="\_blank">Firefox</a>. For a better and more private browsing experience, I've even written a [firefox setup guide](/content/guides/firefoxsetup.md). If you're forced to use a Chromium-based Browser or don't want to bother with a lot of setup, I'd say that Brave is a good option as well. Although it's pretty bloated out of the box (Brave BAT, Brave News, Brave Talk, Brave Rewards, Brave Leo, etc.), this bloat can be disabled, so it's not too big of an issue in the long run.

- I advise against using Opera, Opera GX, Google Chrome and Microsoft Edge because of the following:
  - Personally, I choose to avoid using a Chromium-based browser as much as possible and only use **Ungoogled Chromium** as a backup, in case a site doesn't work on my main browser.
  - All of these mentioned browsers are not only completely proprietary, but also based on Chromium, which is developed by Google. Google has shown time and time again that they'll do anything to abuse their chromium browser monopoly, worsening the internet for **everybody**. From <a href="https://youtu.be/18VM1xZQdXc?si=EMr2bCrFeC2ttjTP" target="\_blank">crippling Ad and Tracker Blockers</a> , <a href="https://youtu.be/Jyk87VVfh9s?si=nkzjgPDybc2j1tOE" target="\_blank">removing support for competing standards</a> or hell, <a href="https://youtu.be/0i0Ho-x7s_U?si=bph6GX0aqvMPJaYL" target="\_blank">trying to **DRM the entire fucking internet**</a>.

- If you need to protect yourself from fingerprinting or just want to have a throwaway browser that leaves no traces on your local machine, then the <a href="https://mullvad.net/en/browser" target="\_blank">Mullvad Browser</a> is a fantastic choice. It's essentially a version of the Tor Browser, without actually connecting to the Tor Network. The point of the browser is to leave the settings as is so every installation is the exact same, making it impossible to fingerprint individuals through their browser configuration behind Mullvad's VPN service. You don't need to have a Mullvad VPN Subscription to use it, you can however use it in tandem with the Mullvad browser by also hiding your IP Address; making you essentially indistinguishable from other Mullvad Browser + VPN users.

- If you want to browse the internet somewhat anonymously, you should definitely use the <a href="https://www.torproject.org/" target="\_blank">Tor Browser</a>. Using Tor has the power to anonymize you and also allows you to browse the dark web through .onion links. If your threat model requires you to fully anonymize yourself, you have to make sure that your Operating System doesn't expose your activities and is secure to attacks. In this case you can either use <a href="https://www.qubes-os.org/" target="\_blank">QubesOS</a> for maximum security in conjunction with the Whonix integration or, if you need a more portable solution, flash a USB-Stick with <a href="https://tails.net/" target="\_blank">TailsOS</a>. It creates a Live Session that routes all of its traffic through tor and works on RAM only, meaning that the session is fully erased when you shutdown the computer or unplug the USB-Stick.

Do note that even if you have taken all the required steps to anonymize and hide yourself from the internet via Tor, Proxies and VPNs, Websites will still know who you are if you log in to your personal accounts. In this case, either create an account with absolutely no personal ties to you (Including Email), create a temporary throwaway account or just don't log in at all.

## My current browser setup

Desktop
Librewolf
- My main browser. Firefox with hardened settings and uBlock Origin out of the box, set up to delete all cookies except for the ones I want to stay logged in to
Ungoogled Chromium
- Chromium backup, in case a site doesn't work on the other two
Mullvad Browser
- For browsing the web privately behind Mullvad VPN, deletes all local data after closing

Mobile
Fennec
- Only for sites I want to stay logged in to
Mull
- General surfing, deletes all local data after closing
Bromite
- Chromium backup, in case a site doesn't work on the other two

## Which Search Engine should I use?

If you want to protect your online privacy, you should stay away from Google, Bing, Yahoo and Yandex. Instead, you can look for more privacy-friendly alternatives such as <a href="https://www.startpage.com" target="\_blank">Startpage</a> or <a href="https://www.duckduckgo.com" target="\_blank">DuckDuckGo</a>. 
- If you're more technical or wish to have more control over your searches, you should check out a Meta search engine that aggregates the results of other search engines into one, akin to <a href="https://docs.searxng.org" target="\_blank">SearXNG</a> or <a href="https://metager.org/" target="\_blank">MetaGer</a>.

As to which one you should use? There's no definitive answer here, I always find myself switching between DuckDuckGo and Startpage depending on what I need. Startpage is identical to Google's Search results, has an "Anonymous View" which enables you to view websites anonymously (Acts like a site preview through startpage as a proxy) and has better Image Search than DuckDuckGo, while DuckDuckGo has (in my experience) better results for tech troubleshooting and has Bangs!, which are essentially quick shortcuts to other search engines and websites. Using one of these search engines is a huge improvement to your privacy, although I believe most people coming from Google will feel more at home using Startpage.

### How to change your default Search Engine

- Chrome/Chromium:   `Settings -> Search Engine -> Manage search engines -> Add -> Insert URL of (Search Engine of choice) under 'Search engine' -> Add -> Click the 3-dot icon next to (Search Engine of choice) -> Make Default`
- Firefox/FF derivative:    `Open (Search Engine of choice) in a New Tab -> Right-Click the Address Bar -> 'Add (Search Engine of choice)' -> Settings -> Search -> Default Search Engine -> (Search Engine of choice)`

## What Browser Extensions should I install?

When it comes to Browser Extensions, you will want to be careful with *what* and *how many* you install, as they may not only compromise your privacy, but also hamper with your online security. Do not install too many Extensions, as a very unique configuration can be used to fingerprint your browser with your identity (even through a VPN) and do not install random Extensions willy-nilly, as they could be malicious. Less is more in this case. Here's a couple of Browser Extensions I can recommend:

<a href="https://ublockorigin.com/" target="\_blank">uBlock Origin</a>
- Efficient, Lightweight and Open-Source Content Blocker (Much more powerful than just an Ad-Blocker!). Easily the best and most trusted choice to blocking ads and trackers on the internet. I strongly believe every single person on the internet should have this extension installed in all of their browsers. In my opinion, the internet is unusable without it.

<a href="https://bitwarden.com/" target="\_blank">Bitwarden</a>
- Encrypted, Cloud-Based Password Manager extension with Auto-Fill functionality on nearly all Sites. More on this can be found in my Article about [Password Managers](/content/tools/password-managers.md).

<a href="https://sponsor.ajay.app/" target="\_blank">SponsorBlock</a>
- Skips sponsor segments, promotions, self-advertising and adds video highlights to youtube videos. Very useful if you only want to watch content that is actually relevant and save your time.
