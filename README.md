# bash.conf
ok I've been a linux user for almost 10 years. All of that time I said that mac just sucks w/o being reasonable about. I've never had a chance to use a macbook as my main machine and develop on it. And all the friends kept telling me " if you try to use mac you won't get back to your linux machine, never agina": Here're my thought
 
 ### 2 Month before:
  Year 2019 , mac 16" came out, seems to be a good model comparing to what we had: 64gb ram, 8tb storage, bazzles got thiner, keyboard became better, price for specs seem to be not as crazy as b4, lets check it.
   - taxes in Ukraine are high, I overpaid 1000$ compared to price on apple.com and got my mac from didi.com, (don't use that site please) 
   - day 1, unboxing. THe laptop is really cool, solid chassis. Speakers, omg - yeah probably was worth it.
  
  - Got my azdome adapter from ebay, the ethernet doesn't work on linux msi laptop, usb-ethernet driver just crashes, nevertheless display ports work, but kernel freezes sometime brah
  Plugged that exact seem into mac, - everything works. It works every 2nd time I plug the docker station into mac. Macbook detects external displays as a single one, outputting mirrored image to both of them. Apple support is so polite but so retarded. I was trying to explain for 10 messages what thing doesn't work and the conversation always come to to a way when people just being retarded. e.g.
  
  ##### Apple software help:
  
   Help: please press Command F1
   Me: I don't have f1 on my keyboard , should I press fn + command + f1
   Help: No, only f1
   Me: I have a touchbar, my keyboard doesn't have f1
   Help: wait a second
   Help: TO press f1 hold on a function key and then press f1
   Me: facepalm (The interesting fact I told the model of my macbook b4 the converstation)
  
  
  ##### Apple hardware help
  The guy seems to understand some basic of hardware just told me that apple only supports thing that are being sold only on apple site. For everything else - go fuck yourself. So if I buy a USB mouse and mac support usb, it doesn't guarantee that it would work. Ok w/e sounds reasanoble. Hail apple. FOr those people who says everything works on mac. Come on mac has very limited number of things, it will never deliver support for those. Kernel modules should be singed in order to load them. THings like thunderbolt adapters will never come with drivers, since they don't have permissions to load them into the kernel. And you know what apple says: we don't support that. That's the fact for all of the thing you can buy from non apple site that stays that "It supports macbook" https://www.azdomes.com/product/usb-c-docking-station/
  
  ##### Day 2: 
 - huge touchpad is a good thing right? I wonder how people use apple watch together with that macbook thing. My miband just scratches the chassis all the time, on my msi touchpad was smaller so my wrist always was right near the chassis
 - Ok, I installed google chrome, I have core i9, 2tb ssd, 64RAM. Guess what happens when I try to maximize chrome window? Animation is freaking lagging. I have cpu at iddle, no other apps open and animation happens like 2-3 FPS. Freaking embarassing, 2 top 10 companies can make a soft that works together - facepalm
 - ok I downloaded slack, and it turns out that it doesn't have an icon tray, so now I have no way to inspect my slack notifictations. I've hidden the "dock" panel ( and if I didn't slack displays a red circle even if a notification was made from muted channel) . I've tried to install the https://getbitbar.com/ took me 20-30 mins to understand how to switch to python3 by default, install a package to python2 since macos permission system denies you access to system lib even if you're root. So you can't just do `ln -sf $(which python3) $(which pyhon)`. Oh you knw why everything doesn't crash? They just don't bump libs, new macos uses python2.7 which is no longer supported.
 - oh yeah if you hold your macbook on your belly sharp edges just scratch your body
 - I have a 5k $ machine and it has like 480x640 camera, what the hell? Well at least speakers and micrphone are good (there're laptops with the same quality)
 - usb flash feature from macbook (when you restart your mac in a disk mode) just doesn't work with my other laptop. I can't mount freaking apple device, how the fuck can you screw a mount storage (I mean if a 1$ usb flash drive can be mounted by every machine, why 5'000$ laptop can't)
 - I install iterm2, seems to be better than yakuake, can't find a featuer to open in at the same screen when it was opened b4, but I like the fact that it doesn't crash
 - ok, apple wifi hospot SUCKS. I created one and wasn't able to connect to it, neither from my Xiami mi9 niether from my another laptop. Both device can see it and both are unable to connect. 
 - when I connect to peer too peer patchcord DNS stops working on mac. So i can't google anymore (at least google.com is cached)
 -keyboard shortcut sucks, I wanted to run an app by a shorcut, intutial thing is to visit system preference and search for shortcuts, no apple allow to add a laucnh app from there, but it doesn't work. It turns out it's another feature. You need to know that there's an app call automator, in this thing you need to create a service and give it a unique name, then just match that name in keyboard shortcust (who there said that apple is so fucking userfriendly)
 - I still think mac is better than linux, at least everything works out of the box. I love that bluetooth earphones work along with integrated microphone, linux just don't support input from aptx via bluetooth.
 - touchbar is really an awesome thing, I'm not sure why people keep coplaining about it,the surface feels really great, despite it's not a physical button, for those who need f1-f12 all the time, it can be done via settings, I'm ok with the things it shows above the keyboard, If i had to chose between touchbard mac and non-touchbar I would definitely stick to touchbar model
 - dark theme integration is better than any DE (kde|gnome|Lxde|mate)
 -wow scheduled boot is a really cool thing (it probably exists on linux too, but I doubt has a program can schedule a boot, should be some kind of bios alarm) but even that way i won't spend time on that on Linux, have other things to do.
  - ok I trying to copy all my files from msi to mac, took me 2 hour to setup vsftpd\pure-ftpd and I failed, all ftp on appstore cost money (really, this is ftp, not a gold formula). Who said that apple is so easy to use?
 - ok t2 chip seems to be shit, COpying files with 1Gbit lan started with 120MB|s, and when the memory just fill up, it dropped down to 20MB\s. Who said that write speed on t2 is amazing? Probably gonna remove encryption on my laptop.
 - scp on mac had a bug, I tried to copy my laptop reqursivly and end up that 200gb directory become 1.2TB and copying never ended. I checked the disk usage, the issue was with wine folder, it had link to home folder which had this wine folder. SO it would ate up all my space.
 - brew sucks comparing to pacman/apt-get (no pkgfile or apt-file).
 
