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

This highly depends on your usage case. Do mind that you aren't limited to using only one browser, as it is actually advised to 'compartmentalize', aka. seperate personal searches (shopping, banking, etc.) with work or school for extra productivity, security and privacy. You just have to figure out a workflow that works best for you based on your own needs.

- For most people, I would suggest using Firefox and; disable Mozilla Telemetry, set 'Enhanced Tracking Protection' to 'Strict', use a privacy-friendly \[Search Engine\](# Which Search Engine should I use?) and install essential Browser Extensions. For more privacy you could even harden your Firefox installation with a custom user profile, however this setup alone makes you much better off than most people with minimal effort. Additionally, people coming from Chrome will also be delighted to hear that their Logins and Bookmarks can be imported with a single click upon installation of Firefox.
- As a start, I would heavily advise against using Google Chrome, Opera and Microsoft Edge due to the huge amounts of data collection compromising your privacy. Having control of your privacy is especially important for your browser, as you do EVERYTHING on it through the internet. 
  - If you're currently using Chrome and do not want to switch your browser at all, I would at the very least recommend using bare Chromium or ungoogled Chrome as a compromise to preserve some of your privacy, although it still promotes the Chromium monopoly.
    - If you're open to a replacement to Google Chrome but under any circumstance do not want to switch to a Firefox-Based browser, I would give Brave or Vivaldi a try. Compared to chrome, they do a lot more to protect fingerprinting and tracking out of the box.
  - If you're using Opera, I would uninstall it immediately. No questions asked. As the original developers of Opera left the project after the company has been sold to china, where the chinese government has the authority to ask for any data that companies colelct. And data they do collect... did you know that the Opera built-in 'VPN' is not *actually* a VPN, but a proxy where all of your internet traffic is passed through. Technically it bypasses geoblocking as you're connected to a chinese proxy, but consider all of your internet traffic through the Opera 'VPN' as private and secure as giving a stranger your house key and address. Especially so if you save your financial information in the browser or do other highly personal activities on it.
- If you need to browse the internet anonymously, you should use the <a href="https://www.torproject.org/" target="\_blank">Tor Browser</a> and make sure you're using the "Safer" or "Safest" Security Level to protect your anonymity. Using Tor properly anonymizes you and also allows you to browse the dark web through Onion links.
- If you need to protect yourself from fingerprinting, or just have a throwaway browser that leaves no traces on your local machine then the <a href="https://mullvad.net/en/browser" target="\_blank">Mullvad Browser</a> is the choice for you. It's essentially the Tor Browser without actually connecting to the Tor Network. The point of the browser is to leave the settings as is so every installation is the same, making it impossible to fingerprint individuals through their browser configuration. You don't need to have a Mullvad VPN Subscription to use it, you can however use it in tandem with it for better privacy by hiding your real IP address.

Do note that even if you have taken all the steps to anonymize and hide yourself from the internet via Tor and VPNs, Websites will still know who you are if you log in to your personal accounts. In this case either create an account with no personal ties to you (Including Email), create a throwaway account or just don't log in at all.

## The Browser I use

As someone who values privacy and security, I have chosen Librewolf as my primary browser. Librewolf is a modified version of Firefox that focuses on enhancing protection against tracking and fingerprinting techniques, as well as providing built-in security improvements, removal of telemetry and an ad-blocker out of the box.

One of the standout features of Librewolf are Container Tabs and its automatic deletion of browser cookies when you close the browser. This means that once you reopen Librewolf, you will be logged out of all websites you previously visited and all local data of them will be deleted. While this may seem inconvenient at first, it ensures that no tracking cookies are lingering to monitor your web activity, offering an additional layer of privacy.

- If you hold down the '+' button to create a new Tab, you can select to create what is called a 'Container Tab', Container Tabs let you seperate your browsing activities through different color-coded Containers. These Containers are completely isolated from each other, meaning that the logins and cookies from your "Work" container are completely seperated from your "Personal" container. Container Tabs are very beneficial for your privacy and compartmentalization, as websites for your work cannot access the cookies from other websites. In this manner, you can also manage different online identities or access multiple accounts on the same website simultaneously. I LOVE THESE

For a more usable and convenient browsing experience, there are two ways you can go about the auto-deletion of cookies. You can either completely disable this functionality under `Settings -> Privacy & Security -> disable 'Delete cookies and site data when LibreWolf is closed'` or for more privacy you can manually add exceptions to the sites where you want/need your site data and logins to remain.

To strike a balance between convenience and privacy, I have taken advantage of the browser's functionality to add exceptions for websites I regularly use. By navigating to `Settings -> Privacy & Security -> Cookies and Site Data -> Manage Exceptions -> (Insert Web Address) -> Save`, I have specified the websites where I want to maintain my login status and site data. This way, I can enjoy the convenience of staying logged in to those essential websites while still safeguarding my privacy from other tracking cookies that come from everyday-browsing.

## Which Search Engine should I use?

If you want to protect your privacy, you should stay away from Google, Bing and Yahoo as they collect personal data from all of your search queries. Instead, you can look for privacy-friendly alternatives such as <a href="https://www.startpage.com" target="\_blank">Startpage</a> or <a href="https://www.duckduckgo.com" target="\_blank">DuckDuckGo</a>.

As to which one to use, there's no real "true" answer here as I always find myself switching between the two depending on what I need. In my experience, Startpage is identical to Google's Search results, has an "Anonymous View" which enables you to view websites anonymously (Acts like a site preview through a VPN) and has better Image Search than DuckDuckGo, while DuckDuckGo has better results for tech troubleshooting and has Bangs!, which are essentially quick shortcuts to other search engines and websites right on the search bar. Using either Startpage or DuckDuckGo is a huge improvement to your privacy, although I believe most people will feel more at home using Startpage coming from Google.

### Change your default Search Engine

- Chrome/Chromium:   `Settings -> Search Engine -> Manage search engines -> Add -> Insert URL of (Search Engine of choice) under 'Search engine' -> Add -> Click the 3-dot icon next to (Search Engine of choice) -> Make Default`
- Firefox/FF derivative:    `Open (Search Engine of choice) in a New Tab -> Right-Click the Address Bar -> 'Add (Search Engine of choice)' -> Settings -> Search -> Default Search Engine -> (Search Engine of choice)`

## What Browser Extensions should I install?

When it comes to Browser Extensions, you will want to be careful with what you install, as they may compromise your privacy and most importantly your security. Do not install too many Extensions, as a unique configuration can be used to fingerprint your browser with your identity or install random Extensions willy-nilly, as they could harm your privacy and may even be malicious. Here's a couple of Browser Extensions I use and can recommend:

- uBlock Origin  
  Open-Source Content Blocker (Much more powerful than just an Ad-Blocker!). Easily the best and most trusted choice to blocking trackers and ads on websites. I strongly believe everyone should have this extension installed in all of their browsers, in my opinion the internet is nearly unusable without it.
- Bitwarden  
  Encrypted Cloud-Based Password Manager extension with Auto-Fill functionality on nearly all Sites. More on this can be found in my Article about [Password Managers](/tools/password-managers.md).
- SponsorBlock  
  Skips sponsor segments, promotions and adds video highlights to youtube videos. Very useful if you only want to watch the content that is relevant and save time.
- Return Youtube Dislike  
  As the name implies, this Extensions returns the dislike view of Youtube videos. Due to technical reasons it's not 100% accurate, but serves as a good guess to stay away from sketchy/malicious content and bad tutorials.
