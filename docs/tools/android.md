# Android

> Thank you, Bee for writing the basis of this article!


## What is Android?

The AOSP (Android Open-Source Project), also known as Android is an Open-Source Kernel based on Linux, primarily used for mobile devices such as the smartphones and tablets that we use on a daily basis. While a significant portion of the code involves proprietary software designed for closed ecosystems by Google and device manufacturers, the project's openness and accessibility to the public have given rise to a diverse array of custom ecosystem versions, commonly referred to as ROMs.

## General Advice

For the people that prefer a concise overview over delving into the detailed content of this article, here are some general tips to make your Android devices safer:

 * Use a safe password for your device lock. Remember to make it as unique as you can.
 * Avoid the default proprietary apps as much as you can. Not only do they often lack open functionality, but are a serious hazard to your privacy. That includes default browsers, sms/contacts/mail clients and app stores.
 * Do not download strange files or install shady APKs from untrustworthy sources.
 * With some exceptions, most of the time Privacy-wise: FOSS > Proprietary Apps
 * Be cautious of the apps you install, may it come from the Google Play Store or from FOSS Repositories. Either source can be prone to malicious software.
 * Make sure to check your apps' permissions. Camera, Location, SMS, Storage, Contacts, etc. Don't give apps permissions that they do not need for their base functions.
 * Don't hand over your phone number to sites, services or people that you don't trust, your phone number is one of the points of information least likely to change about you. Some phones have Dual-SIM support, which can be useful if you have/plan to get a disposable prepaid number.
 * If you don't need or use an app anymore, just uninstall it.

## What are FOSS Apps?

In today's technological landscape, it's easy to forget the beginning of home-made apps (homebrew, as some people put it) that used to be all around the start of personal computers. Nowadays, apps tend to be centralized and created by the big tech companies such as Google, Microsoft, Samsung, you get the picture.

While this has given better accessibility and some convenience to consumers in some regard, this also has made a majority of apps not only abuse their pricing or slash their functionality, but are sometimes straight up dangerous for your security and privacy.
From the best effort of collaborators and users such as yourself, FOSS Apps (as in Free Open Source Software) apps can become a superior alternative to some of the popular proprietary apps that are out there on the market and may even allow the modification of certain apps from contributors to improve on their featureset.

Here are a couple of FOSS apps I can generally recommend:

  * F-Droid - The Biggest Repo market for FOSS Apps. Comes in a lot of flavours too, my favorite is Droid-ify.
  * Aurora Store - An alternative for the Google Play Store for those who don't want to rely on Google.
  * Micro G Project - A Open Source and more privacy-friendly implementation of Google's Play Services (Play Store, Youtube, etc)
  * ReVanced - A general modificaton project to patch proprietary apps. These modifications can range from custom themes to blocking ads.
  * Aegis Authenticator - FOSS 2FA Authenticator, encrypted behind a password/biometrics with automatic backup functionality.
  * FairEmail / K-9 Mail - An alternative client for email services that support external IMAP (Not to confuse with the Email service itself!)
  * Signal - Encrypted and actually secure and private messaging, get WhatsApp outta here!
  * QKSMS - Privacy-respecting SMS Client

  * DAVx5 - Calender/Contacts/Notes/Tasks synchronization
  * QuillPad - Privacy-friendly notetaking, supports Nextcloud Syncing
  * Tasks.org - Privacy-friendly Task & To-Do list, supports DAVx5

For social media, there are custom clients created by the community that may offer additional features and better privacy
 * Youtube - Newpipe
 * Reddit - Infinity / Boost / Relay / Stealth
 * Twitter - Nitter
 * Mastodon - Tusky / Subway Tooter / Shitter

Keep in mind, that some apps (may it be Proprietary or FOSS) may require rooting your device for better functionality.

## What are ROMS?

Have you ever noticed that your smartphone's interface looks different from a family member's? Despite them also having an android device? This is because each vendor that uses Android as their main OS modifies it to create their own ROM to fit their needs and promote their own ecosystem of apps.

While their functionality can vary, it's obvious that the proprietary nature of these custom vendor roms put anyone that actually cares about keeping their data secure in a bad position and are known to heavily restrict the freedom of the end user for the sake of control.

Because of this lack of freedom, many talented minds have taken a poke at the Open-Source nature of Android and have created their own set of custom ROMs and FOSS apps to strengthen the amount of control that the user has over their own devices.

Depending on your objectives and mobile device specifications, you may need to do your own research past what this article can tell you. However, there are some general pieces of information that you may want to know first.

## What are Custom ROMS? 
Because of the nature of these projects, a variety of communities have created new versions of the android operating system to fulfill their usage and privacy needs. This can range from the removal of all telemetry to the development of new features or even the expansion of ecosystems to be used on devices that normally would have no support whatsoever.

## What Custom ROMS are out there?

While there are a large amount of them, here's a list of the most supported ones nowadays.

WARNING: Using a Custom ROM will void your warranty. While the process of installation can be simple due to the clear instructions (especially on Lineage OS), there is still a slight possibility for issues and in the worst case scenario, a chance of bricking the device. Remember to do your own research for your device first.

WE AREN'T RESPONSIBLE FOR ANYTHING YOU DO, AND REMEMBER TO READ THE DEVELOPER'S INSTRUCTIONS THOROUGHLY, MAKE SURE IT IS SUPPORTED ON YOUR DEVICE.

  * LineageOS - As Vanilla as Android gets. No telemetry, no Google.
  * Pixel Experience - Simulating Google's Pixel OS features on unsupported devices
  * Paranoid Android - Vanilla Android, but with an aesthetically pleasant UI twist

Out of all of them, LineageOS tends to be the one to go for for most people starting out, as it has compatibility with tons of devices, good stability and is generally supported for a long  time across multiple Android Versions.

## Ok.. but what is ROOTING?

Rooting, as in getting to the "root" of the device, allows users to access and control every aspect of the device without any interference from safety nets made for the common user, essentially making you the administrator of the device. 

Being a common practice since the beginning of the smartphone uprising, rooting lets more experienced users have total control of their device and modify/patch as they see fit. Modifying the underlying system, removing forced upon bloatware or forcefully replacing system apps with custom ones.

## Should I root my device?

WARNING: ROOTING CAN BE A DANGEROUS PROCEDURE IF NOT DONE CORRECTLY AND MESS UP YOUR OPERATING SYSTEM OR COMPROMISE THE SECURITY OF YOUR DEVICE.

That's a pretty hard question. As companies stop putting walls against user needs, and start fighting more and more against rooting (looking at you, Google, Samsung), the question of *if* rooting is becoming a thing of the past plagues the scene constantly. While a rooted device allows those who care about their data and customizing their devices for more freedom, efforts against this (hardware-wise or software-wise) are making more people turn their backs on rooting, as it may also compromise the android security model.

An example of this is Google's Play Integrity API, the result of their constant efforts to go against rooting. Allowing app developers to block users from using apps if they detect any system modifications as a "safety" measure. While the community is constantly fighting back against such solutions, these companies are making stronger and stronger walls for the scene to go against, which could put rooting obsolete in a few years or decades.

That being said, this is just speculation from our part, there is actually no way to know the true prevalance of rooting, but it is true that it's a decision that the user has to do, and have enough preparation and understanding of the consequences and measures before doubling down on it.

TL:DR: Do your own research and decide if it's worth it to you.
