# Browsers

## What is a browser?

A web browser is software that allows you to access and view websites on the internet. It acts as your gateway to the online world, enabling you to browse through websites, search for information, watch videos and interact with various online services. Think of a browser as a window into the internet. When you open a browser, you can type a website's address or search keywords in a search bar. The browser then retrieves the requested information and displays it on your screen.

Browsers provide a user-friendly interface that allows you to navigate websites using menus, buttons, and clickable links. They interpret the underlying code of a webpage (Often a text file written in HTML, CSS and JavaScript) and present it to you in a visually appealing format.

## What is a Search Engine?

A search engine is essentially a library for the internet, a place to find the books (web pages) you want to read. When you use a search engine, you type in words or phrases to describe what you want to find, may it be a recipe for chocolate chip cookies or information about your favorite movies. It does this by taking your search query, comparing it with a huge collection of websites and then showing the most relevant sites based on that query.

For a Search Engine to gather its library of websites, it uses a 'web crawler'. These web crawlers essentially explore the internet, visit websites and map their content. The websites in question are then indexed for the Search Engine to compare search queries against.

## What Browsers are out there?

When choosing a web browser, there are many possible choices that fit different use-cases, but you can essentially boil them down to two different browser engines:

- Chromium (Developed by Google) 
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
  * Mull (Mobile)
  * Fennec (Mobile)

## Can't I just use Incognito Mode to stay anonymous?

Contrary to popular belief, Incognito Mode doesn't anonymize you or protect your online privacy as much as it sounds like it does. Using incognito mode helps to keep your local browsing history and cookies from being stored on your device. However, your Internet Service Provider (ISP) and websites can still track your online activity.

## Which Browser should I use?

Choosing a Browser highly depends on your use-case. Do not forget that it's possible to install multiple Browsers, which I would actually recommend to seperate your searches and the various parts of your online life. (E.g. seperate your banking, shopping, work, 'private' searches, etc.)

In the end, try out as much as you can and stick with the thing that works best for you.

- For most people, I suggest using <a href="https://www.mozilla.org/en-US/firefox/new/" target="\_blank">Firefox</a> and taking 5 minutes to tweak a couple of settings; disable Mozilla Telemetry, disable Pocket, set 'Enhanced Tracking Protection' to 'Strict', switch to a privacy-friendly Search Engine and install essential Browser Extensions. (details to that further down the page)
  - With the setup above you're already way better off than a lot of people, but if you take your privacy very seriously you can also:
    - hide your IP behind a VPN connection.
    - use an Ad/Tracker-blocking DNS Server such as NextDNS or selfhost your own pihole.
    - harden your Firefox Installation.
  - If you're coming from another browser and think it's too much effort to try it out, don't be scared! <a href="https://support.mozilla.org/en-US/kb/import-data-another-browser?redirectslug=import-bookmarks-data-another-browser&redirectlocale=en-US#w_how-to-import-your-data-from-another-browser" target="\_blank">It's super easy to import your browsing history, passwords and bookmarks.</a>


- I advise against using Opera, Opera GX, Google Chrome and Microsoft Edge because of the following:
  - Personally, I choose to avoid using a Chromium-based browser as much as possible and only use **Ungoogled Chromium** as a backup, in case a site doesn't work on my main browser.
  - All of the above mentioned browsers are not only completely proprietary, but also based on Chromium, which is developed by Google. Google has shown time and time again that they'll do anything to abuse their browser monopoly, worsening the internet for **EVERYBODY**. From <a href="https://youtu.be/18VM1xZQdXc?si=EMr2bCrFeC2ttjTP" target="\_blank">crippling Ad and Tracker Blockers</a> , <a href="https://youtu.be/Jyk87VVfh9s?si=nkzjgPDybc2j1tOE" target="\_blank">removing support for competing standards</a> or hell, <a href="https://youtu.be/0i0Ho-x7s_U?si=bph6GX0aqvMPJaYL" target="\_blank">trying to **DRM the entire fucking internet**</a>.

- If you're open to a replacement to Google Chrome but cannot or prefer not to switch to a Firefox-based Browser, then <a href="https://brave.com/" target="\_blank">Brave</a> is a straightforward alternative. It blocks ads and trackers out of the box, is open-source, and doesn't rely on Google for search. Sadly, it's pretty bloated out of the box (Brave BAT, Brave News, Brave Talk, Brave Rewards, Brave Leo), this bloat can however be disabled, so it's not too big of an issue.

- If you need to protect yourself from fingerprinting vectors or just want to have a throwaway browser that leaves no traces on your local machine, then the <a href="https://mullvad.net/en/browser" target="\_blank">Mullvad Browser</a> is a fantastic choice. It's essentially a fork of the Tor Browser, without actually connecting to the Tor Network. The point of the browser is to leave the settings as is so every installation is the exact same, making it impossible to fingerprint individuals through their browser configuration behind Mullvad's VPN service. You don't need to have a Mullvad VPN Subscription to use it, you can however use it in tandem with the Mullvad browser by also hiding your IP Address; making you essentially indistinguishable from other Mullvad Browser + VPN users.

- If you want to browse the internet somewhat anonymously, you should use the <a href="https://www.torproject.org/" target="\_blank">Tor Browser</a>. Using Tor has the power to anonymize you and also allows you to browse the dark web through .onion links. If your threat model requires you to fully anonymize yourself, you have to make sure that your Operating System doesn't expose your activities and is secure to attacks. In this case you can either use <a href="https://www.qubes-os.org/" target="\_blank">QubesOS</a> for maximum security in conjunction with the integrated Whonix VMs or, if you need a more portable solution, flash a USB-Stick with <a href="https://tails.net/" target="\_blank">TailsOS</a>. It creates a Live Session that routes all of its traffic through tor and works on RAM only, meaning that the session is fully erased when you shutdown the computer or unplug the USB-Stick.

Do note that even if you have taken all the required steps to anonymize and hide yourself from the internet via Tor, Proxies and VPNs, Websites will still know who you are if you log in to your personal accounts. In this case, either create an account with absolutely no personal ties to you (Including Email), create a temporary throwaway account or just don't log in at all.

## My main Browser

As someone who values my online privacy against all of these tech giants, I have chosen Librewolf as my main browser. Librewolf is a modified version of Firefox that focuses on enhancing protection against tracking and fingerprinting techniques, removes all forms of bloat and telemetry from Firefox and comes with UBlock Origin out of the box.

One of the standout features of Librewolf are Container Tabs and its automatic deletion of browser cookies when you close the browser. This means that once I reopen Librewolf, I will be logged out of all websites I previously visited and all local data of them will be deleted. While this may seem inconvenient at first, it ensures that no tracking cookies are lingering to monitor my web activity, offering an additional layer of privacy.

For a more usable and convenient browsing experience, there are two ways you can go about the auto-deletion of cookies. You can either completely disable this functionality under `Settings -> Privacy & Security -> disable 'Delete cookies and site data when LibreWolf is closed'`, or like me, you can manually add exceptions to the sites where you want/need your site data and logins to remain. This leaves me logged in to the sites I visit frequently, while automatically deleting any cookies that I don't need to have.

- If you hold down the '+' button to create a new Tab, you can select to create what is called a 'Container Tab', Container Tabs let you seperate your browsing activities through different color-coded Containers. These Containers are completely isolated from each other, meaning that the logins from your "Work" container are completely seperated from your "Personal" container. Container Tabs are very useful for compartmentalization, as in this manner, you can manage different online identities or access multiple accounts on the same website simultaneously in different tabs, this is especially handy for school accounts that use gmail or outlook.

## Which Search Engine should I use?

If you want to protect your online privacy, you should stay away from Google, Bing and Yahoo. Instead, you can look for more privacy-friendly alternatives such as <a href="https://www.startpage.com" target="\_blank">Startpage</a> or <a href="https://www.duckduckgo.com" target="\_blank">DuckDuckGo</a>.

As to which one you should use? There's no definitive answer here, I always find myself switching between the two depending on what I need. Startpage is identical to Google's Search results, has an "Anonymous View" which enables you to view websites anonymously (Acts like a site preview through a proxy) and has better Image Search than DuckDuckGo, while DuckDuckGo has (in my experience) better results for tech troubleshooting and has Bangs!, which are essentially quick shortcuts to other search engines and websites right on the search bar. Using either Startpage or DuckDuckGo is a huge improvement to your privacy, although I believe most people coming from Googlewill feel more at home using Startpage.

### Howto change your default Search Engine

- Chrome/Chromium:   `Settings -> Search Engine -> Manage search engines -> Add -> Insert URL of (Search Engine of choice) under 'Search engine' -> Add -> Click the 3-dot icon next to (Search Engine of choice) -> Make Default`
- Firefox/FF derivative:    `Open (Search Engine of choice) in a New Tab -> Right-Click the Address Bar -> 'Add (Search Engine of choice)' -> Settings -> Search -> Default Search Engine -> (Search Engine of choice)`

## What Browser Extensions should I install?

When it comes to Browser Extensions, you will want to be careful with *what* and *how many* you install, as they may not only compromise your privacy, but most importantly your browser's security. Do not install too many Extensions, as a very unique configuration can be used to fingerprint your browser with your identity (even through a VPN) and do not install random Extensions willy-nilly as they could be malicious in nature, less is more in this case. Here's a couple of Browser Extensions I use and can recommend:

<a href="https://ublockorigin.com/" target="\_blank">uBlock Origin</a>
- Efficient, Lightweight and Open-Source Content Blocker (Much more powerful than just an Ad-Blocker!). Easily the best and most trusted choice to blocking ads and trackers on the internet. I strongly believe every single person on the internet should have this extension installed in all of their browsers. In my opinion, the internet is unusable without it.

<a href="https://bitwarden.com/" target="\_blank">Bitwarden</a>
- Encrypted, Cloud-Based Password Manager extension with Auto-Fill functionality on nearly all Sites. More on this can be found in my Article about [Password Managers](/tools/password-managers.md).

<a href="https://sponsor.ajay.app/" target="\_blank">SponsorBlock</a>
- Skips sponsor segments, promotions, self-advertising and adds video highlights to youtube videos. Very useful if you only want to watch content that is actually relevant and save time.
