# Browsers

## What is a browser?

A browser is a program that allows you to access and view websites on the internet. It acts as your gateway to the online world, enabling you to browse websites, search for information, watch videos, and interact with various online services. Think of a browser as a window into the internet. When you open a browser, you can type a website address or search keywords in a search bar. The browser then retrieves the requested information and displays it on your screen.

Browsers provide a user-friendly interface that allows you to navigate websites using menus, buttons, and clickable links. They interpret the underlying code of a webpage (Essentially a text file written in the HTML, CSS, and JavaScript languages) and then present it to you in a visually appealing format.

## What is a Search Engine?

A search engine is like a gigantic library that takes your search query and gives you a list of websites it thinks fits that query the best. When you use a search engine, you type in words or phrases that describe what you want to find. It could be anything from a recipe for chocolate chip cookies to information about your favorite movie. The search engine then looks through its huge collection of websites to find the best results for your search query.

## What Browsers are out there?

When choosing a browser, there are many possible choices that fit different use-cases, but you can essentially boil them down to two different browser engines:

- Chromium (Developed by Google) 
  * Google Chrome
  * Google Chromium (Chrome, but only the Open-Source part)
  * Microsoft Edge
  * Brave
  * Vivaldi
- Gecko (Developed by Mozilla) 
  * Firefox
  * Librewolf
  * Tor Browser
  * Mullvad Browser

## Can't I just use Incognito Mode?

Contrary to popular belief, Incognito Mode does not actually anonymize you. The only difference to regular browsing, is that incognito mode doesn't save your browser history, cookies and site data locally.

## Which Browser should I use?

This highly depends on your usage case. Do mind that you aren't limited to using only one browser, as it is actually advised to 'compartmentalize', aka. seperate personal searches (shopping, banking, etc.) with work or school for extra productivity, security and privacy. You just have to figure out a workflow that works best for you based on your own needs! You can use different browsers for different use cases, it's all up to you.

- For most people, I would suggest using Firefox and; disable Mozilla Telemetry, set 'Enhanced Tracking Protection' to 'Strict', use a privacy-friendly \[Search Engine\](# Which Search Engine should I use?) and install essential \[Browser Extensions\](## What Browser Extensions should I install?). For more privacy you could use a VPN, use a ad/tracker-blocking DNS-Server such as a selfhosted pihole instance or NextDNS or if you're technically versed even harden your firefox installation, although with the previously mentioned steps you'd already be a lot better off than most people. Additionally, people coming from Chrome will also be delighted to hear that their Logins and Bookmarks can be imported with a single click during the Firefox install.
- As a start, I would heavily advise against using Opera, Opera GX, Google Chrome and Microsoft Edge due to the huge amounts of data collection happening in the background, even when you turn all of the supposed telemetry off. You do EVERYTHING on your browser nowadays, you do not want these companies to be able to access highly private information including financial information and all of your browsing history, that's absolutely none of their business.
  - If you're currently using Chrome and do not want to switch your browser at all I would at least switch to Chromium as it doesn't phone home to google, otherwise you can also just stay with chrome, ultimately it's your choice. I just think that it doesn't hurt to try new things every once in a while, yknow? Just try something new for a week, come back to chrome, and see what you prefer in the end.
    - If you're open to a replacement to Google Chrome but under any circumstance do not want to / cannot switch to a Firefox-based Browser, Brave is the next best alternative out there. It blocks ads and trackers out of the box, is open-source and doesn't rely on google search. It's sadly not as customizable as Firefox and is quite bloated out of the box (Brave BAT, Brave News, Brave Talk, Brave Rewards, some telemetry which you should turn off during first install), this bloat can however be disabled, so it's not too big of a problem. The only other nitpick I have about brave is their deep involvement/integration with crypto, but other than that it's a great Browser and I hope that the devs do not stray away from their goals.
  - If you're using Opera, I would uninstall it immediately. No questions asked. As the original developers of Opera left the project after the company has been sold to china, where the chinese government has the authority to ask for all data that companies collect. And data they do collect... the Opera built-in 'VPN' so many people installed the browser for is not *actually* a VPN, but rather an opera-controlled proxy server, which is not encrypted, meaning that Opera gets to see ALL of your web traffic as is, down to every single packet that is being sent and received. Technically it bypasses geoblocking as you're connected to a proxy in a different country, but consider all of your internet traffic through the Opera 'VPN' as private and secure as giving a stranger your only house key and address. Especially so if you save your information in the browser or access other highly private information on it, may it be financial, medical or institutional.
- If you need to browse the internet anonymously, you should use the <a href="https://www.torproject.org/" target="\_blank">Tor Browser</a> and make sure you're using the "Safer" or "Safest" Security Level to protect your anonymity. Using Tor properly anonymizes you and also allows you to browse the dark web through .onion links.
- If you need to protect yourself from fingerprinting, or just want to have a throwaway browser that leaves no traces on your local machine then the <a href="https://mullvad.net/en/browser" target="\_blank">Mullvad Browser</a> is a fantastic choice. It's essentially the Tor Browser without actually connecting to the Tor Network. The point of the browser is to leave the settings as is so every installation is the exact same, making it impossible to fingerprint individuals through their browser configuration even behind Mullvad's VPN service. You don't need to have a Mullvad VPN Subscription to use it, though. You can however use it in tandem with the browser and the preinstalled extension for better privacy by hiding your real IP address.

Do note that even if you have taken all the required steps to anonymize and hide yourself from the internet via Tor, Proxies and VPNs, Websites will still know who you are if you log in to your personal accounts. In this case, either create an account with absolutely no personal ties to you (Including Email), create a throwaway account or just do not log in at all.

## The Browser I use

As someone who values privacy and security, I have chosen Librewolf as my primary browser. Librewolf is a modified version of Firefox that focuses on enhancing protection against tracking and fingerprinting techniques, as well as providing built-in security improvements, removal of telemetry and an ad-blocker out of the box similar to Brave, however Firefox-based.

One of the standout features of Librewolf are Container Tabs and its automatic deletion of browser cookies when you close the browser. This means that once you reopen Librewolf, you will be logged out of all websites you previously visited and all local data of them will be deleted. While this may seem inconvenient at first, it ensures that no tracking cookies are lingering to monitor your web activity, offering an additional layer of privacy.

- If you hold down the '+' button to create a new Tab, you can select to create what is called a 'Container Tab', Container Tabs let you seperate your browsing activities through different color-coded Containers. These Containers are completely isolated from each other, meaning that the logins from your "Work" container are completely seperated from your "Personal" container. Container Tabs are very beneficial for compartmentalization, as in this manner, you can manage different online identities or access multiple accounts on the same website simultaneously in different tabs.

For a more usable and convenient browsing experience, there are two ways you can go about the auto-deletion of cookies. You can either completely disable this functionality under `Settings -> Privacy & Security -> disable 'Delete cookies and site data when LibreWolf is closed'` or for more privacy you can manually add exceptions to the sites where you want/need your site data and logins to remain.

To strike a balance between convenience and privacy, I have taken advantage of the browser's functionality to add exceptions for websites I regularly use. By navigating to `Settings -> Privacy & Security -> Cookies and Site Data -> Manage Exceptions -> (Insert Web Address) -> Save`, I have specified the websites where I want to maintain my login status and site data. This way, I can enjoy the convenience of staying logged in to those essential websites while still safeguarding my privacy from other tracking cookies that come from everyday-browsing.

## Which Search Engine should I use?

If you want to protect your privacy, you should stay away from Google, Bing and Yahoo as they collect personal data from all of your search queries. Instead, you can look for more privacy-friendly alternatives such as <a href="https://www.startpage.com" target="\_blank">Startpage</a> or <a href="https://www.duckduckgo.com" target="\_blank">DuckDuckGo</a>.

As to which one to use, there's no real "true" answer here as I always find myself switching between the two depending on what I need. In my experience, Startpage is identical to Google's Search results, has an "Anonymous View" which enables you to view websites anonymously (Acts like a site preview through a proxy) and has better Image Search than DuckDuckGo, while DuckDuckGo has better results for tech troubleshooting and has Bangs!, which are essentially quick shortcuts to other search engines and websites right on the search bar. Using either Startpage or DuckDuckGo is a huge improvement to your privacy, although I believe most people will feel more at home using Startpage coming from Google.

### Change your default Search Engine

- Chrome/Chromium:   `Settings -> Search Engine -> Manage search engines -> Add -> Insert URL of (Search Engine of choice) under 'Search engine' -> Add -> Click the 3-dot icon next to (Search Engine of choice) -> Make Default`
- Firefox/FF derivative:    `Open (Search Engine of choice) in a New Tab -> Right-Click the Address Bar -> 'Add (Search Engine of choice)' -> Settings -> Search -> Default Search Engine -> (Search Engine of choice)`

## What Browser Extensions should I install?

When it comes to Browser Extensions, you will want to be careful with what you install, as they may compromise your privacy and most importantly your browser's security. Do not install too many Extensions, as a very unique configuration can be used to fingerprint your browser with your identity (even through a VPN) and do not install random Extensions willy-nilly, as they could harm your privacy and may even be malicious in nature, less is more in this case. Here's a couple of Browser Extensions I use and can recommend:

- uBlock Origin  
  Efficient, Lightweight and Open-Source Content Blocker (Much more powerful than an Ad-Blocker!). Easily the best and most trusted choice to blocking ads and trackers on the internet. I strongly believe every single person on the internet should have this extension installed in all of their browsers, in my opinion the internet is unusable without it.
- Bitwarden  
  Encrypted Cloud-Based Password Manager extension with Auto-Fill functionality on nearly all Sites. More on this can be found in my Article about [Password Managers](/tools/password-managers.md).
- SponsorBlock  
  Skips sponsor segments, promotions and adds video highlights to youtube videos. Very useful if you only want to watch the content that is relevant and save time.
- Return Youtube Dislike  
  As the name implies, this Extensions returns the dislike view of Youtube videos. Due to technical reasons it's not 100% accurate, but serves as a good guess to stay away from sketchy/malicious youtube content and bad tutorials.
