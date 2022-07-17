# **Stop using Discord and Windows.**  

(**Discord** to fight for your privacy, **Windows** to fight the monopoly)

Discord is one of the most popular instant messaging platforms and Windows is the monopoly of desktop computing. _This is a very bad thing_, even if you can't see it at first glance.  

In this article we will explain the things that Discord and Microsoft do to you, the user(s) and how it actually _does_ affects you (even if you don't think so at the moment). There will also be alternatives for you to use instead.

Of course there are more evil companies and malware-like products out there which we may write about, but Discord and Windows are the most taunting ones as of now.

  

## **Discord**

Discord is a company that doesn't care about its users, this is a fact as the services that they offer like Nitro aren't profitable as most of these services' features aren't even more expensive to run for free, **Discord is not profitable, they make money through other means other than Nitro**. And these means are perfectly expressed in their _clearly cryptic_ Terms of Service.

But before we get into how they make money, let's analyze how the service works as a whole:  

*   Messages are stored unencrypted in their **centralized** servers, meaning that Discord's (possibly) underpaid employeers and hackers can access them almost like **normal plain text files** and do whatever they want with them, even publishing it on the internet, _this has happened before and will keep happening_.
*   User security is mediocre by default, even with measures, your Discord account is **not secure**. Discord's User Authentication model is badly designed and incredibly insecure, [allowing unprivileged programs to gain total control over your account](https://blog.cyble.com/2022/06/01/hazard-token-grabber/) in some cases
*   Deleted messages aren't actually deleted as they stay, even deleting an account just removes its profile picture and changes the username, messages stay, and are even still publicly visible.
*   Calls are not End to End Encrypted, all voice data passes through their servers unencrypted, _allowing them to record and store them for analytics purposes_, also unencrypted.

  

After reading that it should be enough for you to move away instantly, but in the rare case that you trust Discord and its employees as if they were your parents, we still haven't even got started on their ToS.

According to Discord's Terms of Service (and common sense), they make profit off of data processing and selling. As Discord states (cryptically), they have full access and rights to read and process any thing that goes into it (server info, profile info, interests, **even private messages!**)

> The Service provides communication channels such as forums, communities, or chat areas ("Communication Channels") designed to enable you to communicate with other Service users. The Company has no obligation to monitor these communication channels but it may do so in connection with providing the Service.  

  

Discord can and will keep any information that comes into it, including _deleted messages, programs you've opened in your computer while having the Discord desktop app, people you've taked to and more_.

> We generally retain personal data for so long as it may be relevant to the purposes identified herein.  

  

Anything that goes through Discord is legally owned by Discord, if you just made a drawing and want to show it to your friends _Discord will own it and will have the rights to do anything it wishes with it, **even selling it**_.  

> By uploading, distributing, transmitting or otherwise using Your Content with the Service, you grant to us a perpetual, nonexclusive, transferable, royalty-free, sublicensable, and worldwide license to use, host, reproduce, modify, adapt, publish, translate, create derivative works from, distribute, perform, and display Your Content in connection with operating and providing the Service.  

  

In case of Discord being sold or going bankrupt, it can and will sell user data to third parties, **including messages**.

> In the event of a corporate sale, merger, reorganization, bankruptcy, dissolution or similar event, your information may be part of the transferred assets.  

  

Last but not least, _Discord is considered to be spyware as a whole_, not only the service, but also the apps. [Feel free to check out this article on it!](https://spyware.neocities.org/articles/discord.html)

And you might be wondering, why should you care? Even if by some type of miracle your chats don't go out in the wild and stay on Discord's floppy hands there is still the great risk of a governamental entity getting in the way. Let's say you get falsely reported by someone, it's very likely that Discord will hand out all of your data and if that happens, you are fucked. Things can be taken out of context very easily, especially if you like things like dark humor, and considering Discord's bad security someone may even impersonate you. All of this could just be avoided by using e2ee chat platforms like Matrix.

**TL;DR**: Discord is insecure, sells your data, stores all sorts of information, does not delete user information, doesn't use any sort of e2ee, has trackers, owns anything that you send to it and does not support free speech among other things.  

  

## **Windows**  

Windows (also known as MonopolyOS to many) is one of the most evil producs ever created. When you install Windows 7 or newer on your computer and agree to the license agreement, Microsoft legally owns your computer, not you. (You don't even own the hardware)  

These are _some things_ that Microsoft can do to your computer (many were stolen from [the FSF](https://www.fsf.org/windows)):  

*   Microsoft has full access to your hardware, even the essential components.  
    
*   Microsoft can install and uninstall programs without your permission nor knowledge.  
    
*   Microsoft has complete remote access to your computer.  
    
*   Windows 11 has a TPM requirement: By requiring a TPM, Microsoft can impose more severe DRM on media, and refuse to install programs that Microsoft doesn't approve.  
    
*   Windows 11 requires a Microsoft account to be connected to every local user account, giving Microsoft more ability to spy on their users and correlate what they do on the machine with their personal identity.
*   Microsoft Windows sends the encryption keys to Microsoft's servers in case of you encrypting your Windows install with BitLocker (possibly even as raw text)  
    
*   Windows' 10's privacy policy [asserts the privilege to sell almost any information it wants about users](https://edri.org/microsofts-new-small-print-how-your-personal-data-abused/), even creating a unique advertising ID for each user to sweeten the deal.  
    
*   Microsoft supports and enforces DRM in every single way possible, limiting the freedom of the user and making them more dependant on the company, for example ebooks “bought” from Microsoft's store check that their DRM is valid by connecting to the store every time their “owner” wants to read them. Microsoft is going to close this store, [bricking all DRM'ed ebooks it has ever “sold”](https://www.bbc.com/news/technology-47810367).  
    
*   Microsoft can sue you when they notice that you made any modification to the Microsoft Windows operating system, or customised the OS the way it isn't intended to be, since they own your PC. And it's completely legal.  
    
*   Microsoft is now pushing out a requirement for PCs to prevent from booting any other OS than Windows.  
    

  

If you don't care, your ideals are questionable, but it's still really bad. Bad in the sense that a single company, Microsoft, would have remote control over every existing computer making us believe they are the good guys. Credit card information, online accounts... All at the mercy of Microsoft and its employees.

  


# **How to get out**    

## **Discord**  

The most viable privacy-respectng alternative to Discord as of now is Matrix. It's still somewhat new and some things aren't too polished, but I can safely say it's the future. Here are its features compared to Discord's

*   Messages are stored ~~unencrypted~~ **End To End Encrypted with a quantum-resistant encryption method** in their ~~centralized~~ decentralized servers (similar to what email does!), meaning that not even Matrix's employees and contributors can't view or modify them.
*   User security is ~~mediocre~~ almost unbeatable by default, your Matrix account is **secured with 2fa and will let your friends know when a hacker could have entered your account with its advanced verification system**. Matrix's User Authentication model is ~~badly~~ wonderfully designed and incredibly ~~in~~**secure**, not allowing 3rd parties (even with your password) to access any messages.
*   Deleted messages ~~aren't actually deleted as they stay~~ will always be fully deleted on most homeservers, ~~even deleting an account just removes its profile picture and changes the username, messages stay, and are even still publicly visible.~~
*   Calls **are** ~~not~~ End to End Encrypted by default, all voice data passes through ~~their servers unencrypted~~ a secure peer to peer network **fully encrypted**, **not** _allowing them to record or store them for any purpose._

Privacy is not even the main plate! Matrix, as a **user-centric** chat platform offers more useful features like _bridges, chat widgets, (soon to come) Discord-like voice and video channels, peer audited and open source software, total control over your data and more!_ You can learn more and join at [joinmatrix.org](https://joinmatrix.org/)  

  

## **Windows**  

The best alternative to Windows is probably Linux. Linux is rather a kernel than an OS, and has multiple distros and package managers you can try out. Here are the features:  

*   Linux is ~~prop​​​​​​​rietary and has access to your personal data~~ open source, private and secure.  
    
*   Linux doesn't legally own your computer, nor is Linux owned by any company. Your computer and system is completely **yours**, ethically, legally and hipotheticaly.  
    
*   Linux is modular, lets you customize and fine-tune your computer in unimaginable ways in comparison to Windows.  
    
*   Linux has a better program managment, you can install programs from an app store in most distributions, all of them will automatically be updated by the package manager  
    

If you want to use Linux you need to choose a distribution, [distrochooser](https://distrochooser.de/) is a good way to find the best fit for you.  

Are you gonna stay on these platforms and boost insecure messaging and monopoly? Or are you gonna try to contribute into saving the future of computing? It's on your hands.
