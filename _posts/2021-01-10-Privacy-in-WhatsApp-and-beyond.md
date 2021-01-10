---
layout: post
title: Privacy In WhatsApp And Beyond...
permalink: /Privacy-in-WhatsApp-and-beyond/
description: Switching to signal is best, staying with Whatsapp is okay, switching to telegram blindly maynote be wise. But wait, there are more variables involved. Here's a quick read how to really take back your privacy
comments: true
image: images/privacywhatsapp.jpg
---
![privacy please]({{site.url}}/images/privacywhatsapp.jpg)

CONTENT:
* 
{:toc}

  
### Intro

WhatsApp was founded in 2009 by Brian Acton and Jan Koum. In 2014, Facebook had acquired WhatsApp for 19 Billion USD. After shelling out billions for WhatsApp, Zuckerberg would obviously be trying to convert WhatsApp into his surveillance fortress, to create a better profile on you. And there have been baby steps taken towards this. But now he has taken a big step of publicly disclosing Whatsapp will share data with Facebook. But I suspect the sharing has been going on for a while, but now Zuckerberg is being forced to disclose it after Apple started forcing iOS app makers to disclose any data collection.

### Privacy Policy update

- Some of the metadata (means - data that provides information about other data) which is going to be shared with Facebook are battery level, signal strength, app version, browser information, mobile network, connection information (including phone number, mobile operator or ISP), language and time zone, IP address, device operations information, and identifiers (including identifiers unique to Facebook Company Products associated with the same device or account). In short, the update tells that WhatsApp will share almost all possible metadata with Facebook which will use to create a profile on you and show ad.
- I am seeing many local YouTubers mindlessly claiming, your messages are going to be read by Facebook to show you ads. Don't worry your message content won't be exploited here, because your messages are end to end encrypted (which means only you and the recipient, not even WhatsApp, has the password to decrypt the message you send), so Facebook or Whatsapp, at least for now, can't read your messages.
- This latest change to the WhatsApp privacy policy has stirred up the whole world. Many thinking of switching to other alternatives. With Musk tweeting on the support of signal, the app is seeing a surge in installation count. Along with signal, Telegram is also being suggested as an alternative. Let's look at both of them

### Alternatives Being Suggested

#### Signal

- [The signal](https://signal.org/en/) app, an open-source nonprofit messaging app, is the best option for privacy among messaging app. There is no better alternative for messaging in terms of privacy and security.
- Fun fact - End to end encryption implemented in WhatsApp is the signal's encryption protocol.
- Only practical hindrance with the signal app is there is no cloud-based backing up of your messages, so when you get a new device, you have to back up your message manually and move.
- There is no status feature in the signal, this may put off some people, but I personally hate status feature in any app, especially in a chatting app🤷🏻‍♂️, such a distracting thing. So I find the absence of status to be positive, but I am sure this is a negative for most of the others.

#### Telegram

- Telegram is another alternative put forward by media and YouTubers as a privacy-oriented alternative.
- By default, Telegram chats are not end to end(e2e) encrypted. Only the secret chat feature present in telegram gets e2e encryption
- If signal can be considered following a minimalist approach, telegram is the straight opposite, packed with tons of features.

### My Opinion

My opinion, based only on security and privacy features, will be

#### Switch to Signal - Best Decision

- The best decision you can take in terms of security and privacy. With Facebook owning WhatsApp, it's only a matter of time before WhatsApp becomes the data mine of Facebook. If you have decided to switch I am happy and do support your decision.

#### Staying in WhatsApp - It's Kind of OK

- Security remains good because of e2e, but your privacy takes a hit.
- As long as e2e is present, I am personally ok as my message content is safe and cannot be read by others ( this is just my opinion, you can take your decision based on how much you value security than privacy)
- So I will stay as long as e2e stays and my contacts stay, if either one goes away, then bye-bye WhatsApp👋🏻

#### Switching to Telegram - Not Recommended.

- Do only if you are only going to use secret chat, which many are not going to do. Because only this type of chat is supported with e2e encryption
- Do note that this doesn't mean telegram has a security flaw or if you use telegram, 3rd party is going to read your message, it's just in comparison for WhatsApp's default e2e encryption, telegrams regular chat's security is a tad bit less.
- But the amount of data collected by telegram seems to be less than WhatsApp (this is based on "App Privacy" details listed on Apple's app store)
- So it comes down to your priority over security vs privacy. The choice is yours.

### Let Me Introduce You To The Actual Problem

- The impact of the data being taken from you because of this WhatsApp update is very small when you compare how much data obtained from you when using Google search or when browsing the internet (see what every browser can know about you - [link](https://webkay.robinlinus.com/))
- Apple store recently started to educate its user with how much an app mines data on you, just see the pic below, even though WhatsApp has highest data collection among the three apps we were seeing, see how it pales away in comparison with Facebook messenger app.

![apple_labels.png]({{site.url}}/images/apple_labels.png)

Let's see how much data Google has collected on you. Google knows:
- Where you have been: click [here](https://www.google.com/maps/timeline?pb) to see your timeline
- Everything you have searched (and deleted): click [here](https://myactivity.google.com/myactivity) to know how much of your web activities have been tracked by Google.
- All the apps you use: click [here](https://security.google.com/settings/security/permissions)
- All of your YouTube history: click [here](https://www.youtube.com/feed/history/search_history)
- Google has created an advertisement profile for you based on the information it has collected, click [here](https://www.google.com/settings/ads/) to see your ad profile.
- If you are getting to know about these google links for the first time, then please stop, nothing else matters in the world, open these links and get awestruck on how much data Google has on you. Want to know more about the tracking by Google, you can read further in my article [How to See Exactly Who Google Thinks You Are — And Then Turn off Their Tracking](https://medium.com/hackernoon/how-to-see-exactly-who-google-thinks-you-are-and-then-turn-off-their-tracking-94e83183fe36)
- The websites you browse also have trackers. You are so special to the big tech companies that they want to get to know you better, even when you don't directly use their product. So they track you throughout the net. For eg, Facebook tracks you throughout the internet building a profile for you, even though you don't have a Facebook account.

![verge_trackers.png]({{site.url}}/images/verge_trackers.png)

- Nope, these are not the amount of trackers you get after browsing for one day, these trackers are from a single website, [The Verge](https://www.theverge.com/) - a fairly popular tech website. Disturbing and shocking isn't it.
- It's not just this website, there is a high chance that almost all websites you use include at least one tracker.

### Solution

Now that you have seen about tracking throughout the web, Lets first try to

#### Block trackers throughout the web

- Install block origin which blocks ads, tracking scripts. It also comes with the added benefit of blocking ads on YouTube!!! (but this may reduce your favourite YouTuber's income)
- It is available for [Chrome](https://chrome.google.com/webstore/detail/ublock-origin/cjpalhdlnbpafiamejdnhcphjbkeiagm?hl=en) (thereby Edge, Brave, other chromium-based browsers can use the same extension)and [Firefox](https://addons.mozilla.org/en-US/firefox/addon/ublock-origin/). In the case of Firefox, you can install the extension in your android phone also. To know how to use the extension, see this amazing [explanation in YouTube](https://youtu.be/2lisQQmWQkY) (note: the video may be overwhelming with tons of information - start by just installing the extension, gradually you can learn about advanced features)

#### Reduce trackings by Google.

- [Startpage](https://www.startpage.com/), [Duckduckgo](https://duckduckgo.com/) are two good privacy alternatives for Google. For the last 2 years, I search only using either one of them. Yes, you read it right, I don't use Google search. Although DuckDuckGo is most popular, I would suggest you try Startpage because the search results almost resemble Google results, its because start page takes your search query, ask the same to Google, like it's their own query and give the result to you. Startpage is like a middleman between you and Google. Why would Google accept for such a bad deal? Because Google needs to prove competitors exist, so they charge Startpage some fee and give the results to Startpage
- You can check the resemblance in result yourself, I have given the same query to google (search [link](https://www.google.com/search?client=firefox-b-d&q=Whatsapp%20privacy%20update,%20should%20i%20switch%20to%20signal)) and Startpage (search [link](https://www.startpage.com/do/dsearch?query=Whatsapp%20privacy%20update,%20should%20i%20switch%20to%20signal&cat=web&pl=opensearch&language=english)), open these links in side by side tabs and compare the results. They will look almost the same. So if you really value your privacy, you can switch to start page or Duckduckgo.
- To stop every optional tracking done when using google products, Go to this [link](https://myaccount.google.com/activitycontrols?utm_source=my-activity&utm_medium=home&utm_campaign&continue=https%3A%2F%2Fmyactivity.google.com%2Fmyactivity%3Futm_campaign%3Dcontinue) and pause everything (but if you pause web and voice tracking then you can’t use google assistant).
##### Privacy Oriented Alternatives to Google Services
- Gmail - [Proton Mail](https://protonmail.com/)
- Youtube - [NewPipe](https://newpipe.net/), it's android youtube client app, so this is not an alternative but a good incognito mode app for youtube, it blocks youtube ads too. (won't be available in Google playstore, only in the link given)
- Chrome (Browser) - Best privacy alternative is [Tor browser](https://www.torproject.org/), it gives complete anonymity and easy to start using, give it a go. [Mozilla Firefox](https://www.mozilla.org/en-US/firefox/new/) and [Brave](https://brave.com/) are also good alternatives compared to Google Chrome or Edge. (i have no idea regarding Samsung's browser, so not mentioning about it here)
- Google Drive (Cloud) - [Mega](https://mega.nz/) - An e2e encrypted cloud service which provides 50GB free space (note: I have not read in-depth about this service, so do research before using this service)
- Google keep (Notes) - [Standard notes](https://standardnotes.org/) (google keep alternative), [Joplin](https://joplin.cozic.net/) (Evernote) alternative<br>
<br>Even though Google doesn't provide, I am mentioning a good VPN, just in case you have to use a good VPN
- VPN - [Proton VPN](https://protonvpn.com/). Be careful with any other VPN service, try to use a VPN which maintains no log. Even if they claim no log, better to be cautious. Proton is an upcoming privacy-oriented company with a good reputation. I have been using its free tier service for some time now.

[Privacytools.io](http://privacytools.io/) is a quality guide website which I have found useful in my never-ending quest of online private life. It may help you too.

We are living in a wonderful time where everything is within our reach thanks to the internet. But sadly it comes with the cost of Big Brother watching you, sometimes even without your knowledge. It's safe to assume anything you do on internet is not 100% secure or private

<br> Learnt Something new? <br>Show some ❤ by sharing this article to your friends. Help them safeguard their privacy <br> 
