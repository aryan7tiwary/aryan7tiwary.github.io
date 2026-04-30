---
author: Kevin D. Mitnick
cover: "/assets/images/books/Pasted image 20260303000023.png"
---
Kevin Mitnick

**About book:** Kevin talks about how privacy matters. Techniques to stay invisible online.

**Status:** Read

**Date Completed:** 13th-Oct-2024

* * *

- A program created at MIT called Immersion will visually map the relationships between the senders and receivers of all the email you have stored in your email account just by using the metadata.

- Instead of hosting your own proxy, you can use a service known as an anonymous remailer, which will mask your email’s IP address for you. An anonymous remailer simply changes the email address of the sender before sending the message to its intended recipient.

- When you use Tor, the direct line between you and your target website is obscured by additional nodes, and every ten seconds the chain of nodes connecting you to whatever site you are looking at changes without disruption to you.

- Unless your entry point and your exit point become associated somehow, your connection is considered anonymous.

- Skype numbers work well for Google account registration

- To protect the identity of the user somewhat, these beacons from your cell phone use what is known as international mobile subscriber identity, or IMSI, a unique number assigned to your SIM card.

- Law enforcement has created devices that pretend to be cellular base stations. These are designed to intercept voice and text messages.

- Most mobile devices ping three or more towers at a time. Using logs from those cell towers, someone can triangulate, based on the relative strength of each ping, a fairly exact location of the phone’s user. So the phone you carry around every day is essentially a tracking device.

- Signaling system 7 (SS7) does basically everything necessary to route a call, such as:

- SS7 handles the process for callestablishment, billing, routing, and informationexchange functions.

- SSL7 is a protocol

- VoIP phone systems do use encryption; specifically, something called session description protocol security descriptions, or SDES. The bad news is that on its own, SDES is not very secure.

- Signal, an application from Open Whisper Systems, is a free, opensource VoIP system for mobile phones that provides true endtoend encryption for both iPhone and Android.

- The keys exist only on the devices at either end of the call. And once the call ends, those session keys are destroyed.

- encryption, Signal also uses perfect forward secrecy (PFS).

- The purpose of these secret rooms was to channel all the Internet, email, and phone traffic through a special filter that would look for keywords.

- opensource and nonprofit organizations provide perhaps the most secure software and services because there are literally thousands of eyes poring over the code and flagging anything that looks suspicious or vulnerable.

- When you’re on the app store or Google Play, look for apps that use something called offtherecord messaging, or OTR.

- ChatSecure is a secure textmessaging app that works on both Android and iPhones. 21

- The message here is that in the United States you are not allowed to erase anything you do on your computer. Prosecutors want to see your entire browser history.

- encrypted. If you access a website that uses encryption, then the ISP can obtain the metadata— that you visited such and such site at such and such date and time.

- There are also a lot of Content Delivery Networks (CDNs) that cache pages for their clients to deliver them faster, no matter where you are in the world, and therefore come between you and the desired website.

- Keep in mind, too, that if you are logged in to your Google, Yahoo, or Microsoft accounts, these accounts may record the Web traffic on your PC or mobile device— perhaps building your online behavioral profile so the companies can better target the ads you see.

- If it is and you want to be invisible, then disable the feature. Fortunately, you can turn off browser location tracking. In Firefox, type “about: config” in the URL address bar. Scroll down to “geo” and change the setting to “disable.” Save your changes. In Chrome, go to Options > Under the Hood > Content Settings > Location. There’s a “Do not allow any site to track my physical location” option that will disable geolocation in Chrome.

- You might also want to fake your location— if only just for fun. If you want to send out false coordinates— say, the White House— in Firefox, you can install a browser plugin called Geolocator. In Google Chrome, check the plugin’s builtin setting called “emulate geolocation coordinates.” While in Chrome, press Ctrl + Shift + I on Windows or Cmd + Option + I on Mac to open the Chrome Developer Tools. The Console window will open, and you can click the three vertical dots at the top right of the Console, then select more tools > sensors. A sensor tab will open. This allows you to define the exact latitude and longitude you want to share.

- And even the best proxy sites admit that clever Flash or JavaScript tricks can still detect your underlying IP address— the IP address you use to connect to the proxy in the first place.

- But the best way to prevent JavaScript injection from monitoring you via your browser is to use the HTTPS Everywhere plugin

- But there’s more work to be done. Take a moment and surf over to Panopticlick.com. This is a site built by the Electronic Frontier Foundation that will determine just how common or unique your browser configuration is compared to others, based on what’s running on your PC or mobile device’s operating system and the plugins you may have installed.

- Something else to watch out for is that marketers and criminal hackers alike learn something about visitors to a website through what’s known as a onepixel image file or web bug. Like a blank browser popup window, this is a 1 × 1pixel image placed somewhere on a Web

- page that, although invisible, nonetheless calls back to the thirdparty site that placed it there. The backend server records the IP address that tried to render that image. A onepixel image placed on a healthcare site could tell a pharmaceuticals company that I was interested in athlete’s foot remedies.

- researcher caught AT& T and Verizon appending additional code to every Web page request made through

- a mobile browser. This is not the IMSI— international mobile subscriber identity— I

- Even if you turn off JavaScript, a website may still pass a text file with data called an http cookie back to your browser. This cookie could be stored for a long time.

- You may also want to consider using a cookie cleaner software tool, such as the one at piriform.com/ ccleaner, to help manage your cookies easily.

- Websites are coded using something called Hypertext Markup Language, or HTML. There are many new features available in the current version, HTML5. Some of the features have hastened the demise of the super cookies Silverlight and Flash— which is a good thing. HTML5 has, however, enabled new tracking technologies, perhaps by accident.

- The idea is that your hardware and software, when combined as resources for the browser, will render the image uniquely. The image— it could be a series of variously colored shapes— is then converted into a unique number, roughly the way passwords are. This number is then matched to previous instances of that number seen on other websites around the Internet. And from that— the number of places where that unique number is seen— a profile of websites you visit can be built up. This number, or canvas fingerprint, can be used to identify your browser whenever it returns to any particular website that requested it, even if you have removed all cookies or blocked future cookies from installing, because it uses an element built into HTML5 itself. 20

- CanvasBlocker.

- If, say, your credit card account says you live in New York, why does your

- Tor exit node say you are in Germany? A geolocation discrepancy like this often flags an attempt to purchase as possible abuse and invites additional scrutiny.

- One way to avoid this hassle with Tor is to configure the torrec config file to use exit nodes located in your home country. That should keep the credit card companies happy.

- A tumbler takes some Bitcoins from me, some from you, and some from other people chosen at random and mixes them together. You keep the value of the coins minus the tumbling fee— it’s just that the cryptographic signature of each coin may be different after it’s mixed with others. That anonymizes the system somewhat.

- Another WPS attack method is known as Pixie Dust. This is an offline attack and affects only a few chip makers, including Ralink, Realtek, and Broadcom. Pixie Dust works by helping hackers gain access to the passwords on wireless routers. Basically the tool is very straightforward and can gain access to a device in seconds or hours depending on the complexity of the chosen or generated WPS PIN.

- Reaver, can crack a WPSenabled router within several hours.

- There’s also a new Artificial Intelligence– based tool announced at the DEF CON 2016 conference that will analyze a target’s tweets. It will then construct a spearphishing email based on their personal interests. 13 So be careful when clicking links within a tweet.

- One of the most famous phishing schemes was Operation Aurora, in which a phishing email was sent to Chinese employees of Google. The idea was to infect their machines in China in order to gain access to the internal network at Google’s world headquarters, in Mountain View, California. This the attackers did, getting dangerously close to the source code for Google’s search engine. Google wasn’t alone. Companies such as Adobe reported similar intrusions. As a result Google briefly pulled its operations from China. 14

- Cryptowall is one example: it encrypts your entire hard drive, locking you out of every file until

- you pay the attacker to give you the key to unlock your files. Unless you have a full backup, the contents of your traditional PC or Android device will be inaccessible until you pay the ransom.

- Just viewing a page with an infected banner ad can infect your traditional PC— this is called a driveby because you didn’t actively click on the ad. Here’s where having adremoval plugins such as Adblock Plus in your browser is really effective.

- In fact the FBI now advises people whose computers are infected with ransomware to simply pay up.

- Maybe he’s redirecting your connection to a proxy that implants a javascript keylogger in your browser so when you visit Amazon your keystrokes will be captured as you interact with the site. Maybe he gets paid to harvest your credentials— your username and password. Remember that your credit card may be associated with Amazon and other retailers.

- But by using a VPN you can tunnel through the public network back to a private and secure network. Everything you do within the VPN is protected by encryption, as all your Internet traffic is now secured over the public network.

- choosing a VPN service that uses the TCP protocol instead of UDP, such as TorGuard

- or ExpressVPN, can greatly improve performance. Both of these VPN services allow the user to set either TCP or UDP as their preferred protocol.

- To be invisible, it’s always best to layer your privacy. Your risk of having your traffic viewed by others in a public network declines with each additional layer of security you employ. For example, from a public WiFi network, access your paid VPN service, then access Tor with the HTTPS Everywhere extension installed by default in the Firefox browser.

- According to documents released by Edward Snowden, the Communications Security Establishment Canada (CSEC) can identify travelers passing through Canadian airports just by capturing their MAC addresses. These are readable by any computer that is searching for any probe request sent from wireless devices. Even if you don’t connect, the MAC address can be captured. So if you don’t need it, turn off your WiFi.

- There is another clandestine way to exchange messages via email: use the drafts folder on a shared email account.

- I grabbed my cell phone, called the DMV, and impersonated law enforcement. I got the DMV to run his plate,

- then they gave me his name, address, and Social Security number. Then I called AirTouch Cellular, impersonating an AirTouch employee, and had them do a search on his Social Security number for any cellular accounts. That’s how I was able to get his cell number.

- On the flip side of that, Fitbit data has been successfully used in court cases to prove or disprove previously unverifiable claims. In one extreme case, Fitbit data was used to show that a woman had lied about a rape. 10

- What if the third party was your bank? If it had an agreement with your car’s manufacturer, it could track your driving ability and judge your eligibility for future auto loans accordingly. Or your health insurer could do the same. Or even your car insurer. It might be necessary for the federal government to weigh in on who owns data from your car and what rights you have to keep such data private.

- In one vengeful product review of the Honeywell WiFi Smart Touchscreen Thermostat, someone who calls himself the General wrote on Amazon that his exwife took the house, the dog, and the 401( k), but he retained the password to the Honeywell thermostat. When the exwife and her boyfriend were out of town, the General claimed he would jack up the temperature in the house and then lower it back down before they returned: “I can only imagine what their electricity bills might be. It makes me smile.” 1

- There have been numerous legal cases in which neighbors using the same brand of baby monitor set to the same channel eavesdropped on one other. In 2009 Wes Denkov of Chicago sued the manufacturers of the Summer Infant Day & Night baby video monitor, claiming that his neighbor could hear private conversations held in his home. 9

- Unencrypted data streams are not unique to Samsung. While testing LG smart TVs, a researcher found that data is being sent back to LG over the Internet every time the viewer changes the channel. The TV also has a settings option called “Collection of watching info,” enabled by default. Your “watching info” includes the names of files stored on any USB drive you connect to your LG television— say, one that contains photos from your family vacation. Researchers carried out another experiment in which they created a mock video file and loaded it to a USB drive, then plugged it into their TV. When they analyzed network traffic, they found that the video file name was transmitted unencrypted within http traffic and sent to the address GB.smartshare.lgtvsdp.com.

- Some still argue that the NSA has put chips in our phones that provide power and allow tracking even when the phone is physically powered off (even if the physical battery is pulled).

- For example, using the traditional PC version of the Chrome browser, researchers found that someone— Google?— appeared to be listening all the time by enabling the microphone. This feature came to Chrome from its opensource equivalent, a browser known as Chromium. In 2015, researchers discovered that someone— Google?— appeared to be listening all the time. Upon further investigation, they discovered that this is because the browser turns the microphone on by default. Despite being included in opensource software, this code was not available for inspection.

- They did offer a means for people to opt out, but that optout requires coding skills so complicated that average users can’t do it on their own. 13

- To do this, get an old, broken set of headphones or earbuds and simply cut the wire near the microphone jack. Now plug that stub of a mic jack into the socket. Your computer will think there’s a microphone there when there isn’t. Of course if you want to make a call using Skype or some other online service, then you will need to remove the plug first. Also— and this is very important— make sure the two wires on the mic stub do not touch so that you don’t fry your microphone port.

- Fortunately, Amazon provides ways to remove your voice data from Echo. 14 If you want to delete everything (for example, if you plan to sell your Echo to another party), then you need to go online to do that. 15

- Preventing someone from grabbing your documents off the printer, secure printing, also known as pull printing, ensures that documents are only released upon a user’s authentication at the printer (usually a passcode must be entered before the document will print). This can be done by using a PIN, smart card, or biometric fingerprint.

- With the malware installed on your mobile phone, the gyroscope within the phone is now sensitive enough to pick up slight vibrations. The malware in this case, researchers say, can also pick up minute air vibrations, including those produced by human speech.

- Security researcher Samy Kamkar developed something called KeySweeper that’s designed to do just that: a disguised USB charger that wirelessly and passively looks for, decrypts, logs, and reports back (over GSM) all keystrokes from any Microsoft wireless keyboard in the vicinity. 13

- Femtocells are small devices available from your mobile carrier. They’re designed to boost cellular connections within a home or office where the signal might be weak.

- In the United States, law enforcement uses something called a StingRay, also known as an IMSI catcher, a cellsite simulator. Additionally there are TriggerFish, Wolfpack, Gossamer, and swamp box. Though the technologies vary, these devices basically all act like a femtocell without the cellular connection. They’re designed to collect the international mobile subscriber identity, or IMSI, from your cellular phone.

- Some versions of Android will inform you when you switch cellular networks; iPhones will not. “Your phone will associate to a femtocell without your knowledge,” explained researcher Doug DePerry. “This is not like WiFi; you do not have a choice.” 15

- I recently did a pen test where the client added Google’s 2FA to their VPN website using publicly available tools. The way I was able to get in was by obtaining the active directory login credentials for a user who didn’t sign up to use the VPN portal. Since I was the first to log in to the VPN service, I was prompted to set up 2FA using Google Authenticator. If the employee never accesses the service himself, then the attacker will have continued access.

- For data at rest, Dropbox uses 256bit AES encryption (which is pretty strong). However, it retains the keys, which could lead to unauthorized access by Dropbox or law enforcement. Google Drive and iCloud use a considerably weaker 128bit encryption for data at rest. The concern here is that the data could potentially be decrypted by strong computational force. Microsoft OneDrive doesn’t bother with encryption, which leads one to suspect that this was by design, perhaps at the urging of some governments.

- Microsoft has also introduced a unique perfile encryption feature, which is what it sounds like: a feature that encrypts each individual file with its own key. If one key is compromised, only that individual file will be affected rather than the whole archive. But this is not the default, so users will have to get in the habit of encrypting each file themselves.

- You could also choose to use the one cloud service provider that sets itself apart from the rest— SpiderOak, which offers the full benefits of cloud storage and sync capability along with 100 percent data privacy. SpiderOak protects sensitive user data through twofactor password authentication and 256bit AES encryption so that files and passwords stay private. Users can store and sync sensitive information with complete privacy, because this cloud service has absolutely zero knowledge of passwords and data.

- In Canada, however, it’s the law; you must, if you are a Canadian citizen, provide your passcode when it’s requested. This happened to Alain Philippon, from SainteAnnedesPlaines, Quebec. He was on his way home from Puerto Plata, in the Dominican Republic, when he refused to provide the border agents in Nova Scotia with his mobile phone’s passcode. He was charged under section 153.1( b) of the Canadian Customs Act for hindering or preventing border officers from performing their role. The penalty if you’re found guilty is $ 1,000, with a maximum fine of $ 25,000 and the possibility of one year in jail. 5

- Learn the mechanism of hard disk encryption. How Tails OS has better encryption?

- BitLocker takes advantage of a special chip on your motherboard known as a trusted platform module, or TPM. It’s designed to unlock your encryption key only after confirming that your bootloader program hasn’t been modified. This is a perfect defense against evil maid attacks,

- There is also WinMagic, one of the few options that requires twofactor authentication instead of just a password. WinMagic also doesn’t rely on a master password. Rather, encrypted files are grouped, and each group has a password. This can make password recovery harder, so it may not be suitable for everyone.

- And for Apple there’s FileVault 2. After installation, you can enable FileVault 2 by opening System Preferences, clicking on the “Security & Privacy” icon, and switching to the FileVault tab. Again, do not save your encryption key to your Apple account. This may give Apple access to it, which they in turn could give to law enforcement. Instead choose “Create a recovery key and do not use my iCloud account,” then print out or write down the twentyfourcharacter key. Protect this key, as anyone who finds it could unlock your hard drive.

- Going a step further, Apple has said that the key remains on the device, with the user. That means that the US government cannot ask Apple for the key: it’s unique to each and every device.

- A German antivirus company, G DATA, found that in hotel rooms where their research staff stayed, “more often than not” the safe had the default password (0000) in place. In cases like that, no matter what private password you select, anyone knowing the default password could also gain access to your valuables inside.

- One trick for getting free Internet at any hotel is to call any other room— perhaps the one across the hall— posing as room service. If the hotel uses caller ID, just use the house phone in the lobby. Tell the party answering the phone that her two burgers are on the way. When the guest says she didn’t place an order, you politely ask for her surname to fix the error. Now you have both the room number (you called it) and the surname, which is all that’s needed to authenticate you (a nonpaying guest) as a legitimate guest at that hotel.

- Researchers at Kaspersky Lab, a software security company, discovered a group of criminal hackers they call DarkHotel (also known as Tapaoux) who use this technique. They operate by identifying business executives who might be staying at a particular luxury hotel, then anticipate their arrival by placing malware on the hotel server. When the executives check in and connect to the hotel WiFi, the malware is downloaded and executed on their devices. After the infection is complete, the malware is removed from the hotel server. Apparently this has been going on for almost a decade, the researchers noted.

- One early analysis suggested that DarkHotel was South Korea– based. A keylogger— malware used to record the keystrokes of compromised systems— used in the attacks contains Korean characters within the code. And the zerodays— vulnerabilities in software that are unknown to the vendor— were very advanced flaws that were previously unknown. Moreover, a South Korean name identified within the keylogger has been traced to other sophisticated keyloggers used by Koreans in the past.

- Also, software can be made to look as though it is created in one country when it is actually created in another.

- Rule number 1 about being invisible: you can’t ever link your anonymous online persona with your realworld persona. You just can’t.

- ProxyHam is a very remote access point. Using it is much like putting a WiFi transmitter in your home or office. Except that the person using and controlling ProxyHam could be up to a mile away. The WiFi transmitter uses a 900 MHz radio to connect to an antenna dongle on a computer as far as 2.5 miles away.

- the onion router was created by the US Naval Research Laboratory to give oppressed people a way to contact each other as well as the outside world.

- And never turn on your personal phone or personal laptop in the same location where you turn on your anonymous laptop or burner phone or anonymous hotspot. The separation is really important. Any record that links you to your anonymous self at a later date and time negates the whole operation.

- Because keystroke analysis is so disturbingly easy to deploy, researchers Per Thorsheim and Paul Moore created a Chrome browser plugin called Keyboard Privacy. The plugin caches your individual keystrokes and then plays them out at different intervals. The idea is to introduce randomness in your normal keystroke cadence as a means of achieving anonymity online. The plugin might further mask your anonymous Internet activities.

