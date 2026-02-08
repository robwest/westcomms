# Family Comms Planning
Author: Rob West
[Github Repo](https://github.com/robwest/westcomms/tree/main)

**These documents are a work in progress and will be updated over time**
Last update: 2/6/2026 (v0.2)
- 2/8/2026 - Version 0.2 - corrected some typos, updated GMRS, Antenna and Mesh sections. Added Power options.
- 2/5/2026 - Version 0.1 - initial release, updated to remove family-specific information

## Table of Contents
[[/What is this document? Who is it for?]]
[[/I don’t want to read - just tell me what to get]]
[[/How far can I communicate?]]
[[/Voice Communication - Two-way Radio]]
[[/Text Messaging - Mesh Networks]]
[[/Internet - Satellite and Others]]
[[/Gear Recommendations]]

## What is this document? Who is it for?
A document about learning about and communicating with technology as a hobby and for times when normal communications methods are not available.  The intended audience is my direct and chosen family in the Pacific Northwest, but much of this applies to any region.

> [!NOTE] **General Caveat and Approach**: Not all communications methods are always reliable, nor are they guaranteed for a particular distance or purpose. Most communications methods depend on a number of environmental factors. This is why a “multi-valent” strategy is proposed. In other words, don’t put all your eggs in one basket.

> [!WARNING] Second Caveat: I am no where near an expert on this stuff. I am still learning and experimenting. I’m sharing what I’ve learned so far, but I may get stuff wrong. Please do your own homework. There are a ton of great and knowledgeable people on YouTube and consider joining a local Amateur Radio club. Any mistakes in this document are my own.

### What does this plan cover?
There may be occasion when you are experiencing a power outage, or a loss of regular communications methods. This document is an attempt to provide you additional options for staying in touch *locally*, *regionally*, and *globally*. 

**NOTE: **As you move from local to regional to global, reliability is less certain and generally more experimental.

### A Note on Privacy and Secrecy

**Secrecy.** Most radio communications available to the general public should always be considered open and non-secure. This guide is **not** a guide to secret or encrypted communications. There are other guides for this, but know that encrypted communication rules vary depending on what you are trying to do and in some cases it is illegal to obfuscate your communications. Do the homework if this is your goal. 

**For this guide, consider that you have a need to communicate outside of normal means, and that secrecy is less important than the communication itself.**

**Privacy.** Some methods of alternative comms can be *more* private, but none are 100% private. Private in this document means others cannot easily hear or see your messages without an invitation to join a pre-defined group.

Whenever using alternative comms, assume that someone else can:
- Hear/read your conversation
- Know your location

> [!CAUTION] In practice, most comms methods should not be considered 100% private or secure. Where a degree of privacy is possible with a method below, I will indicate that. But if it isn’t mentioned, **you should consider communicating in this way as if you were standing on either side of a crowded room and shouting to each other**.

Another note: any system that is centralized, where messsages pass through a company’s servers, even if they advertise privacy/secrecy should be treated as only a temporary situation. At any time, whomever controls the comms infrastructure could turn over the keys to un-hiding your comms. This includes things like Signal. 
## I don’t want to read - just tell me what to get
This is a tough question. I have provided listings of the equipment I have purchased, but your application may be different. In this section, I’ll recommend some broad categories of comms methods and what I consider a good place to start, plus some add-ons if your curiousity takes over. You don’t need to get this all at once, either. Get one thing, learn about it, then add the next, etc.

This list is based on a PACE approach: Primary, Alternate, Contingency, Emergency. The idea behind this concept is redundancy. If a primary method isn’t working, move to the next and so on.

After all my reading, and to cover multiple scenarios of communication with loved ones and your community you should have access to:
1. A cell phone
2. A home internet connection
3. A GMRS handheld radio that lets you upgrade the antenna
4. A way to charge batteries if the power goes down (generator or big-ol’ battery + solar)

I am choosing these based on my interests but these should be considered optional. I recommend them though for additional coverage options.

1. Satellite Internet (StarLink - but see caveats)
2. Meshtastaic and Meshcore LoRa nodes

Each of these is explained in more detail below and my evolving recommendations on what to buy can be found in the [[/Gear Recommendations]] section below.

## How far can I communicate?
Most alternative communications systems work with radio waves, which are - and this is oversimplified - dependent on line-of-sight. Said another way, radios work best when they can see each other. Radio waves eventually get absorbed by environmental objects, including the curvature of the earth. There are strategies to extending the range of radio-based communications including repeaters, mesh networks and others.

Generally, you should not expect all of your communications methods to be reliable all of the time. There are just a lot of factors to consider. However, with some basic investments, you can increase your chances of making communications possible.

This document will use the following words to denote the scale of communications range:
- Local - meaning between 1 and 5 miles - your neighborhood or current location
- Regional - meaning 5-30 miles from your current location
- National - meaning within the country you live in
- Global - meaning anywhere in the world

Communications alternatives decrease in reliability and increase in cost as you want to reach farther. In other words, these mthods are:
* GOOD and CHEAP for local 
* PLAUSIBLE and REASONABLE COST for regional
* EXPERIMENTAL and EXPENSIVE for National or Global

> [!NOTE] The farther you get from line-of-sight communications, the more that needs to go right for your comms to be successful. This is not said to discourage you from learning and using these methods but set your expectations appropriately. Comms is about patience and persistence.

Some additional considerations:
- More radio power does not necessarily mean farther reach. It is a factor, but line of sight is often more influential to reach. You will more reliable have more reach the higher you go in elevation, and the fewer objects there are around to absorb your signals.
- The quality and tuning of your antenna is a big factor as well. It is likely that you will want to upgrade any antennas that come with any item you buy pretty soon after you buy it because they are often cheap and less effective. Be sure to buy one made for the frequency band (GMRS, LoRA, etc.) you need. 
  - Antenna science is out-of-scope for this document. The short answer is the right tuned antenna placed as high as you can put it has a chance of better line-of-sight and is will be more effective.

OK - with all of the caveats out of the way, let’s talk about modes of communication. There are three that become important in the case of a grid or internet outage.

---
## Voice Communication - Two-way Radio
The best communications tool is always the one you have on you, first of all. After that, the one that is working is second best. This sounds obvious, but underlines the need for a layered approach to comms.

Practially, the best voice communication tool is a cell phone or home phone if the grid is up. The next best is a handheld or mobile radio. I recommend GMRS radios because they work on the same channels as regular walkie-talkies (AKA “FRS” Radios) but open options for larger antennas and the use of repeaters. 

**Use cases**
- Local comms in your neighborhood or when hiking, camping, climbing etc.
- Regional comms when used with a repeater channel

**What you need**:

* a GMRS radio (see [[/Gear Recommendations]] section). You’ll want a handheld for sure, and consider a mobile radio for your car/home.
* A proper antenna tuned for GMRS frequencies and appropriate for your application
* a GMRS license for your family ($35)

### Radio Categories available to the public

| Type                                                         | Usage                    | Range                                                  | License need                            | Private |
|:------------------------------------------------------------:|:------------------------:|:------------------------------------------------------:|:---------------------------------------:|:-------:|
| Family Radio Service (FRS - walkie talkies you probably already have) | Family short range comms | Line of Sight 1-2 miles                                | No                                      | No      |
| GMRS - General Mobile Radio Service                          | Local comms              | Line of Sight 1-2 miles. Farther if you use a repeater | Yes, $35 covers entire family, 10 years | No      |
| Ham (Amateur) Radio                                          | Local, regional, global  | Varies, depending on your license and what you spend   | Yes, $35 for an individual, 10 years    | No*     |

Again, all range estimates depend on all the factors above. You might get farther, you might not! If you are standing at the top of a mountain and looking at a friend below, range can surprise you. But, expect less and be happy when you get more.

My reasoning for selecting GMRS for this mode of voice communication is this:
- Low cost of entry
- Interoperability with consumer FRS radios (walkies you or friends may already have)
- Ability to upgrade antenna and transmit with higher power and use repeaters (this is the main difference with FRS radios)

Start your GMRS learning and read about regional GMRS here: 
- [GMRS Repeater Directory and Community](https://mygmrs.com/)
- [GMRS and FRS Radio in Western Washington - PSRG Wiki](https://wiki.psrg.org/wiki/GMRS_and_FRS_Radio_in_Western_Washington)
- https://www.oregongmrs.org/

Generally here’s the decision tree for voice communications:
- If cell phones are working, use them
- If internet is working, use something like Zoom, Discord, Teams, etc.
- Failing that, communicate locally or regionally with GMRS
- For longer-range connections to a wider community, use Ham

#### Channel Selection
- For local comms, coordinate with others in your group to choose a preferred channel, and always have an alternate channel in mind in case there is lots of talk on your first choice.
- For regional comms, look into your local region’s preferred channels. Pre-coordinate with family/friends on channels otherwise. Repeater channels can be transmitted to with more power (you’ll need a mobile or base station radio for this).
- GMRS radios use 22 channels, with channels 1-7 shared with FRS but at higher power levels, and channels 15-22 exclusively for GMRS. Channels 8-14 are limited to FRS power levels and are not recommended for GMRS use.

| Channel Number | Frequency (MHz) | Power Level | Usage |
|:-:|:-:|:-:|:-:|
| 1 | 462.5625 | Up to 50 W | General Use |
| 2 | 462.5875 | Up to 50 W | General Use |
| 3 | 462.6125 | Up to 50 W | General Use |
| 4 | 462.6375 | Up to 50 W | General Use |
| 5 | 462.6625 | Up to 50 W | General Use |
| 6 | 462.6875 | Up to 50 W | General Use |
| 7 | 462.7125 | Up to 50 W | General Use |
| 8-14 | 467.5625 to 467.7125 | 0.5 W | Low-power channels shared with FRS |
| 15 | 462.5500 | Up to 50 W | Repeater Outputs |
| 16 | 462.5750 | Up to 50 W | Repeater Outputs |
| 17 | 462.6000 | Up to 50 W | Repeater Outputs |
| 18 | 462.6250 | Up to 50 W | Repeater Outputs |
| 19 | 462.6500 | Up to 50 W | Repeater Outputs |
| 20 | 462.6750 | Up to 50 W | Repeater Outputs |
| 21 | 462.7000 | Up to 50 W | Repeater Outputs |
| 22 | 462.7250 | Up to 50 W | Repeater Outputs |
| Repeater Inputs (15-22) | 467.5500 to 467.7250 | Up to 50 W | Repeater Inputs |
TL;DR - for most small group comms in a local area, use Channels 1-8, for repeater use 15-22. You can work on channels 8-14, but you will likely be violating the rules.

> [!CAUTION] GMRS Privacy Channels. A note on radio marketing nonsense. If a GMRS radio advertises more than 22 channels, it is likely they are talking about [“privacy” codes](https://www.k0tfu.org/deep-dives/frs-gmrs-privacy-codes-demystified). These are just the standard channesl with special “chirp” tones that tell the radio - only play back the audio when you hear these prefix tones. Everyone else can hear you on these channels. For real. It’s just a convenience feature to “squelch” (silence) other people talking. It does not encrypt or make truly private your messages.

#### A note on licensing, the rules and the FCC
You can listen to any frequency on any radio you like. Transmit privileges, however, vary.

**GMRS**. Legally, you should own a GMRS license (takes about 24 hours and $35 on the FCC website) to transmit on GMRS frequencies, use repeaters and use higher-power radios. Get one. It’s easy. One price, covers your entire family (except for cousins, strangely) for 10 years. You will get a callsign that everyone can use. Note that it is standard to use your callsign frequently when transmitting on GMRS. Read the rules. Also note you are submitting your info to the FCC.

From an equipment perspective, GMRS radios are only legal when they are Part 95 certified by the FCC. It is against the rules to transmit on GMRS channels with radios that have not been certified. Shop aware.

**Amateur (Ham) Radio.** To transmit on ham frequencies you need one or more levels of certification from the FCC: Technician, General and Extra are the three levels that open up ever larger frequencies you are authorized to use. You need to study for and take a test to get your license. Again, $35 covers you (and only you) for 10 years. Ham radio study and licensing is out of scope for this document.

Now, those are the rules. You should be aware that the FCC has almost never tracked anyone down for violating these rules. People buy and use GMRS radios all the time without a license. They sometimes use a Ham radio to talk on GMRS, etc. 

So who cares about the rules? I do - to a degree. In an emergency, I’m going to use whatever I can to make contact. But outside of that, the rules exist to make these radio frequencies available for everyone and to provide a framework for common courtesy in radio use and experimentation. Some governance is good and promotes fairness.

**Bottom line**:  [Getting a GMRS license is fast, simple and cheap](https://mygmrs.com/help/get-gmrs-license).  Well, the website does take some getting used to, but you can do it. I recommend it. Getting a ham license is harder, but still doable if your curiousity matches your free time. Get your Technician license first it if you have interest. Note that Amateur Radio licenses do not cover you for GMRS and *vice versa*. You need both to transmit on both. 

Now, if you do flaunt the Ham Radio rules, the government may not come for you, the very active volunteer-led ham commnuity might. This is a community that lives and dies by its rules. So if you want to transmit on ham, go study up, take your test and get your license.

Also be aware that finding the source of a radio transmission is pretty easy these days, so consider that when you are transmitting. Search for “[fox hunt radio](https://en.wikipedia.org/wiki/Transmitter_hunting)” if you want to [learn more](https://www.krakenrf.com).

### More resources
- [myGMRS.com Store](https://shop.mygmrs.com/)
- [Beginner's Guide to GMRS Radios](https://tidradio.com/blogs/news/beginners-guide-to-gmrs-radios)

#### What about CB Radios?
If you have one, great. And if it is all that is working, also great. I don’t enjoy the community that uses CB primarily, so I am avoiding it for now. Again - any radio that puts you in touch with the people you need to talk to is the right one, so don’t let my bias impact you.

--- 
## Text Messaging - Mesh Networks
When the cellular network and internet are down, or if you are in a remote area, text messaging can sometimes still be available if you take advantage of a newer technology called LoRa (Long Range) radio. The term itself is a bit deceptive. The radios themselves operate at a lower frequency and therefore travel farther than other radios, but they are low power. The real power of mesh networks is that generally, every radio transmits signals it can hear to all other radios within range meaning that you depend less on centralized towers for connection and more on the “mesh” of other users.

LoRa devices are cheap and enjoy low battery consumption. In most cases, you buy a LoRa (or “mesh”) device (it’s a specialized radio), connect it to your phone, and then (if conditions are right) you can text with other people on this network. 

> [!IMPORTANT] This is not the text messaging you have on your cell phone. You can only text with others who also have these devices and are using the same app as you. The advantage with these methods is they do not require cell service or internet.

### Warning - Nerdery Ahead
LoRa is not too hard to learn, but it does require some work. It is an open-source, community driven project and as a result, things are always changing. It is possible to buy “turnkey” devices, but in many cases, you will want to learn how to update and maintain the firmware (software) on the devices you own. 

### How does it work?
LoRa devices are “mesh” devices, meaning that LoRa devices that can hear each other can transmit and re-transmit messages sent to the network. All devices talk to each other and serve to pass along messages to improve the chances that messages can be delivered and to extend the range beyond local communications. 

There are two popular apps that work with LoRa radios - **Meshtastic** and **Meshcore**. Meshtastic is definitely the more popular right now, but Meshcore is growing fast. To use either, you download the appropriate app to your phone and then connect via Bluetooth to the LoRa device. No internet or cell service is needed to use the messaging system. Learn more about each protocol here:

- [Meshtastic](https://meshtastic.org/)
- [Meshcore](https://meshcore.co.uk/)

> Think of sending a whisper across a playground. With Meshtastic, everyone passes your whisper along, so the "chain" can move and grow as people move around, but they stop sharing your message after it's passed through 7 people. With MeshCore, only special helpers ([repeaters](https://www.austinmesh.org/devices/#parts-list)) pass the whisper, but they can pass it to up to 64 more helpers.
> 
> By default, with MeshCore those helpers also talk faster and there are fewer side conversations that might delay your whisper. On Meshtastic, the other people talk slower and are having side conversations that have to finish before your whisper can be shared, slowing down the rate at which your whisper makes its way through the crowd.
> 
> Meshtastic works well when people and links are moving (friends at an event, a hike, a bike ride). Regular nodes help by rebroadcasting, so coverage can shift and grow as people move. MeshCore works well when you can place fixed repeaters on rooftops or hills. Phones connect through companion radios; companions do not rebroadcast, so repeaters are what grow the mesh. [Source: AustinMesh](https://www.austinmesh.org/learn/meshcore-vs-meshtastic/)


### Working with Mesh Radio
You will need to get comfortable installing either Meshtastic or Meshcore on your LoRa device. I recommend getting enough radios to support both protocols. Meshtastic is the “first mover” and has brand recognition. Meshcore may have fewer people on it (depending on your location) but message delivery is more reliable. In the Seattle area, Meshcore is more popular and is growing rapidly. Again - if you get into this, support both! 

- Bring Meshtastic if you are looking for “bring a radio, it just works” for roaming groups - hiking, camping, etc.
- Use Meshcore if you are looking to contribute to a resilient city/region network. Consider adding a repeater node in your neighborhood. This is something I’m doing.

Each person in your family should have one of these devices and you should also find out what your local or regional mesh uses for settings. These sites tell you about the recommended networks and radio settings for best results.

* Seattle area: [Puget Mesh](https://pugetmesh.org/)
* Oregon: [The best Meshtastic network in Oregon](https://meshoregon.com/)
* Portland area: [Join the PDX Meshtastic Users Discord Server!](https://pdxmesh.com/)

If it sounds like a lot to buy double the number of devices to support both approaches, it kinda is. The good news is that when you have solid internet access, it’s relatively easy to change from one method to the other. If the internet goes down though, you’re stuck with whatever you put on the radio last. For me, this means redundancy and maintaining devices that can communicate both ways, Meshtastic and Meshcore. This also means I can travel to regions where one method is preferred over the other.

### Using Meshtastic and Meshcore to communicate
When you get your first LoRa radio, you’ll want to perform the following steps (many of which you can find instructions online to do and are out of scope for this document given how frequently things change). Read getting started guides on both the Meshtastic and Meshcore websites for more up-to-date instructions. However, the basic steps are these:

1. Decide whether you want the radio to be Meshtastic or Meshcore.
2. Upgrade the firmware to the latest stable version
3. Download the appropriate app for your phone and connect via Bluetooth to the radio
4. Configure your radio to use the preferred local settings (check your local mesh group)
5. Go through the process of discovering other nodes (radios, repeaters) in the network
6. Try your first message in the public channel to see if others hear you
7. Experiment with setting up private channels for your family or group
8. Label your radios! I recommend coming up with a naming convention and putting stickers on the radios, especially if you have both systems. Here is an example of my naming (not real names:)
   1. MT RobWest - L1 Pro 01 (includes MT for Meshtastic, and “L1 Pro” for the device I’m using, and “01” in case I add more of this type of radio)
   2. MC RobWest - SenseCap T1000 01 (includes MC for Meshcore)

#### Channels in Mesh
There are two types of “channel” in both systems: public and private. 

**Public channels are like a chat room**. Everyone talks with everyone. 

**Private channels** are set up by someone in a group and the information to chat within them is shared with the members of the group. This is *more* private and secure than most comms methods as the messages are encrypted and available only to people who are given the password (or “key”) to enter the group. 

However, it must be noted that messages transmitted across private channels still hop across other nodes because of the nature of the mesh. This means that you have *reasonable* privacy/secrecy, but this is not absolute. The encyption is pretty strong, but as with all encryption, there’s always a future where someone has figured out how to break into it. Don’t sweat too much - it’s good, but I’d be remiss in saying that the privacy/security is 100%.

Follow guides for setting up private channels in [Meshtastic](https://meshtastic.org/docs/configuration/radio/channels/) and channels vs. rooms in [Meshcore](https://idahomesh.org/meshcore-channels-rooms-and-dms/). 

Finally - **Don’t be intimidated!** Your first days with a mesh radio are easy. But the hobby is deep. Soon you’ll own 3 or 4 of these inexpensive devices and be thinking about adding a repeater to expand your community’s reach. Wait. This is me.

---
## Internet - Satellite and Others
If the grid goes down, the internet may too. If you can stomach it, get your hands on a Starlink for emergencies. However - be aware that this can be shut down by the company or government at any time. 

There is no decentralized alternative to the Internet yet. But, for natural disasters or non-political crises, it is likely that Starlink will be up and running. Be sure you have a power source to run the Starlink. If you can afford the device, it’s a good thing to have. They are also awesome to have if you enjoy camping/RV life and you can share with your neighbors.

Pro tip: you can put your Starlink on “pause” and pay a minimal feel month-to-month when you don’t need it, and then easily update to a full data plan when you do.

---
## Gear Recommendations

In the lists below, I’ve started each section with what I myself have bought or acquired. Be aware, I like things on the nerdier side, so please feel free to buy what I have, but I’ve also listed other less nerdy options here too. I’m also still learning and still experimenting with different models. 

This is one of the toughest sections - because the “best” version of device “X” is the one you get the most use out of. For the most part, though, I am aiming for the lowest cost item with my required features. It isn’t too expensive to get started, but know that once you do, you may find yourself with a burning desire to get MORE.

Occasionally, I have included Amazon links here for universal ease, but most of these can be purchased elsewhere to avoid Amazon. Here are some less fraught shops from which to buy (I’ll expand this list as I go). NOTE that in many cases I have not personally shopped here, but saved you a bit of searching only.

* GMRS/Ham
  * [Radioddity](https://www.radioddity.com/) - highly respected site
  * [myGMRS.com Store](https://shop.mygmrs.com/)
  * https://theantennafarm.com/
  * [Walcott Radio](https://www.walcottradio.com/gmrs-radios-c-499_460_664.html) - a lot of CB stuff, but has GMRS too.
  * [Gigaparts](https://www.gigaparts.com/) - lots of hams/GMRS folk buy their stuff here
* LoRa/mesh
  * [Seeed Studio - LoRa & Meshtastic & 4G](https://www.seeedstudio.com/LoRa-and-Meshtastic-and-4G-c-2423.html) - Make great turnkey radios
  * [Meshtastic, LoRa, IoT & WiFi Solutions from RAKwireless & ALFA Network](https://store.rokland.com/)

### GMRS Radio Recommendations
#### Handheld Radios (“HTs” in the community)

In most cases, you’ll want to buy a different antenna specifically tuned for GMRS. The ones that come with most units are OK, but there are many better options that will extend your range.

When shopping for GMRS (or Ham) handhelds, here are some questions that might influence you to buy one product over another. You may not need any of this. I look for features like these, but some features mean radio operation will be more complicated:

> [!TIP] 
> 1. Do I want something that is simple and just works, or something to tinker with?
> 2. Do you eventually want to get into ham radio? Can it be unlocked? (reminder you need licenses for both GMRS and Ham to use both and some radios are not legal for use on GMRS.)
> 3. How many buttons do I need to learn?
> 4. How easy is it to program?
> 5. Do you want the ability to monitor and transmit on two different frequencies simultaneously?
> 6. Is it Repeater-capable? Most GMRS radios are, but check! Repeaters are a big advantage to GMRS, and extend your range to regional options.
> 7. Can I program channels easily? Is it Chirp-compatible - allows you to program the radio channels using a standard program on your laptop
> 8. Does it have USB-C charging? For the love of all that is holy - don’t buy one that has a different charging type.
> 9. Is it IP67 rated? IP67 rating means it can be submerged in water up to 3 ft deep for 5 minutes. If you expect rugged conditions, consider something with this.
> 10. Bluetooth listening connection - do you want to be able to listen and talk using your BT headphones? Connect AirPods or a speaker?
> 11. Number of “channels” - don’t be fooled. **There are only 22 real GMRS channels**. Radios advertise other channels, but they are really just specially configured versions of these 22.

#### Handheld Radios ($17-35 to get started. More when you get addicted.)
* **Versatile Option for every day** 
  * ✅ [Tidradio TD-H3 Plus](https://www.amazon.com/sspa/click?ie=UTF8&spc=MTo3NjAyNDIxMTcwMzQ3MzUxOjE3NzAzMjEwODM6c3BfYXRmOjMwMTA4MTAwNTUyNTUwMjo6MDo6&url=%2FTIDRADIO-TD-H3-Plus-Bluetooth-headphone-connectable-Programming%2Fdp%2FB0F2T7YLQS%2Fref%3Dsr_1_1_sspa%3Fcrid%3D21R6DHWRYPVL9%26dib%3DeyJ2IjoiMSJ9.PXV6UiLY857DPhQfpuKCtQpx6PeTvrxxK-wXntWjZw5nxmIUvYfzfCxLRjPC1fxJyZ3vcjURA3TCFtBDAsksK_yHkkptuiEvg7hPArMed32A2yLYn52cP_bQHQJpoUt1pQfuDy6vtapCIUCE-5qC2Fi1u_BgL0BKrDlv8gyyYnudlGlLDSG1BeOi-xV9Rxuarlzw_zCEk87MqsEJPYDqE4vkItqDBCcXOnDCoWWlxe8.IcLcf22uFW-yk-RA8oQPjtxsE97eAoyETHPg7VcR4tQ%26dib_tag%3Dse%26keywords%3Dtidradio%2Btd-h3%2Bplus%26qid%3D1770321083%26sprefix%3Dtidrad%252Caps%252C190%26sr%3D8-1-spons%26sp_csd%3Dd2lkZ2V0TmFtZT1zcF9hdGY%26psc%3D1) - This is the bundle I bought. I really like these.
  * Pros 
    * I like that it can change personas and be either a Ham radio or GMRS radio.
    * About $35 per radio, easily bought in kits with additional antennas, batteries and extra accessories.
    * if you have multiple TD-H3 radios, you can use “SMS” texting between them
  * Cons
    * More complex to set up for the first day. Once you do though, pretty easy to operate in GMRS mode. Worth it for me, since I can always switch to Ham frequencies. Happy to help you set it up!
* **Rugged Outdoors Waterproof.** 
  * Tidradio TD-H9 - this is one I plan on getting because it is IP67 rated, includes GPS and is more rugged. For camping.
  * BTECH GMRS-PRO or Baofeng UV-9G - another good option
  * Rocky Talkie Expedition Radio. IP67 waterproof. NOAA channels. This is the rich person’s GMRS radio. Nothing super-special about it compared to the ones above but people like them. Dead simple to use.
* **Cheap but still cool.** 
  * Baofeng G-15 - Note: GMRS only! Cannot be unlocked I don’t think. Buy a better antenna right away. Buy it if you don’t want any Ham capabilities.
* **Cheap, Standard, Everyone has one.** 
  * Baofeng UV-5G Plus GMRS - the OG “cheap chinese radio”. Good for beginners who want a little more tinkering. HUGE user community. 
  * Baofeng UV-5R mini - can be unlocked to talk on GMRS, but not certified to do so.
* There are loads of others. They get more expensive.

#### GMRS Mobile Radio for the car/van, maybe the home ($100+)
* [TBD](https://shop.mygmrs.com/collections/mobile-radios). I plan to buy one eventually. Good brands are Retevis and Wouxun for balance between price and capability. Look for something that’s going to run in your car, but you can also plug it in at home.

### Amateur (Ham) Radios
Ham radios are out of scope for the most part in this document, since that’s a very large topic with a lot of variety based on how you want to use it. But if you just want to buy something on your journey to getting licensed, here are some.
* Handhelds
  * Baofeng mini uv-5r mini - very popular brand
  * Tidradio TD-H3 Plus - this is the one I have. See above in GMRS section
  * [Gigaparts HT Radios](https://www.gigaparts.com/radio-gear#?Category1=Radios&Category2=Amateur+Radio+Transceivers&search_return=all&Category3=Ham+HT+Radios)
* Mobile (car/RV and home)
  * [Gigaparts Mobile Ham](https://www.gigaparts.com/radio-gear#?Category1=Radios&Category2=Amateur+Radio+Transceivers&search_return=all&Category3=Ham+Mobile+Radios)
* Ham Radio HF Basestation (HF radios are the ones that are capable of talking to other countries and the International Space Station)
  * HF Radio - WAY out-of-scope for this document

### LoRa Meshtastic / Meshcore Nodes
Almost all LoRa devices use the same small circuit boards and are just housed in different cases. If you enjoy DIY projects can buy a basic board for roughly $25 and then buy cases and batteries, etc. If you want something easy to use and already assembled here are some ideas.

> [!TIP] General note: since there are two competing protocols/systems - meshtastic and meshcore, as a hobbiest I plan to buy double the number of devices we would normally need for our family so I can have both. You’ll want to do some research about your local area to decide what’s best.  However, they are relatively cheap and I recommend getting both protocols going for flexibility.

Here’s an awesome site that is trying to catalog all the devices and antennas with places to buy them.
* [RF Index: Meshtastic Devices - Hardware Comparison](https://www.rfindex.com/meshtastic/devices)

Alternative to Amazon for LoRa devices: 
* [Meshtastic Partner Hardware](https://meshtastic.org/docs/getting-started/)
* [Meshtastic, LoRa, IoT & WiFi Solutions from RAKwireless & ALFA Network](https://store.rokland.com/)
* [Seeed Studio Bazaar, The IoT Hardware enabler.](https://www.seeedstudio.com/)

*Note: Most devices are sold as “meshtastic nodes.” However, Meshcore can be installed on most if not all Meshtastic devices. They are not interoperable. There are a few apps for your phone that are starting to support both, but you still need dedicated radios for each type.*

* Recommended: Portable nodes with and without GPS - requires phone connection.  Note: there are a metric ass-ton of these. Here are the best reviewed I’ve found:
  * ✅ I own two of these: [Wio Tracker L1 Pro](https://www.seeedstudio.com/Wio-Tracker-L1-Pro-p-6454.html).  One for Meshtastic, one for Meshcore. Long battery life (2-5 days), decent form factor. Works out of the box for Meshtastic. Easily flashed fo Meshcore.
  * ✅ I will have at least two of these too for my adult family members: [SenseCAP Card Tracker T1000-E](https://www.seeedstudio.com/SenseCAP-Card-Tracker-T1000-E-for-Meshtastic-p-5913.html?c_event_medium=product%3A%3Arecommend%3A%3AB%3A%3A114993633&c_event_id=1565072878%3A%3A5ef7dbdd%3A%3A114993633) - super simple form factor. About the size of a credit card. Can be put in a backpack or purse or attached with an optional carabiner. Has some downsides - the charging cable is non-standard and therefore easy to lose, but this is one of the only ‘waterproof’ personal nodes. Also plausible as an AirTag alternative that doesn’t rely on Apple devices.
    * Alternative I just saw: [WisMesh Tag](https://store.rokland.com/collections/rakwireless-products/products/wismesh-tag-from-rakwireless-mokosmart-meshtastic-compatible-card-sized-node-us915-mhz) - Gotta research this one.
  * [R1 Neo - Complete Meshtastic® Device with GPS](https://muzi.works/products/r1-neo-complete-meshtastic-device) - more expensive, but nice case. IP68 rated! Smaller battery.
  * [RAKWireless WisMesh Pocket](https://store.rokland.com/collections/rakwireless-products/products/wismesh-pocket) - a bit more expensive, but bigger battery. Well-reviewed and popular too.
  * [LowMesh Portable Solar Node](https://store.rokland.com/products/lowmesh-pocket-s-portable-solar-node-compatible-withmeshtastic-915-mhz) - integrated solar panel. No GPS, but uses your phone’s GPS if that’s needed. No external antenna. I am strongly considering this.
  * [Heltec MeshPocket](https://heltec.org/project/meshpocket/) Qi2 Magnetic Charging Power Bank, Meshtastic Compatible. It’s a powerbank. It’s a LoRa node. Charge your phone and send offgrid messages! This one is very attractive to me. No external antenna.
  * [LilyGo T-Echo](https://lilygo.cc/products/t-echo-lilygo) - nice little unit with removable antenna and an e-paper screen. A little expensive compared to the L1 Pro I have.
* Standalone Devices (no phone required)
  * [Lilygo T-Deck Pro](https://lilygo.cc/products/t-deck-pro-meshtastic), and T-Deck Plus- looks like a blackberry, because it comes with a keyboard and a more advanced user interface. Does not require a phone. On the expensive side, and sort of fit-for-purpose. I generally recommend using a portable node with your phone.
* Solar Repeater Nodes - for contributing to the regional network
  * ✅  [SenseCAP Solar Node P1-Pro](https://www.seeedstudio.com/SenseCAP-Solar-Node-P1-Pro-for-Meshtastic-LoRa-p-6412.html) - solar repeater node that comes with mounting equipment. I will be installing one of these on my roof to extend the Meshcore network in my area.  Consider doing the same!
  * [RAKWireless WisMesh Repeater](https://store.rokland.com/collections/rakwireless-products/products/wismesh-repeater-mini-reliable-coverage-expansion-for-smart-networks) - another solar repeater node.

### Antennas
This is a big topic. As you get into things, you’ll find yourself needing a variety of antenna types to support different use cases. For example:

- A short stubby antenna that lets you throw your radio in your backpack without fear of damage
- A long whip antenna to promote greater range
- A folding “tactical” antenna to improve range even more
- A magnetic mount antenna for your car/RV
- A fixed antenna for your house or a repeater location
- etc.

What is pretty evident in my experience is that the antennas that come with your radio when you buy it tend to work OK, but you get much better results when you upgrade to a better antenna.

Just know that you want to search for antennas that are tuned for your application. Good search terms are “GMRS Antenna” and “LoRa Antenna”.  Be sure to pay attention to what kind of connector your radio has on it (SMA or BNC) and whether it is male or female when buying. 

One technique I’m considering is buying adapters to convert all of my radios to BNC connectors for easier compatibility with the nicer antennas.

Here are some well-reviewed antennas and options.

- [The Signal Stick \(GMRS, Ham\)](https://signalstuff.com/shop/)
- [MyGMRS Antennas](https://shop.mygmrs.com/collections/antennas)
- [RFIndex: Compare Meshtastic Antennas](https://www.rfindex.com/meshtastic/antennas)
  
### Radio Bag/Box
Create a “radio bag” or “radio box” containing the following so it’s always ready and you have a way to organize your gear:

- Your comms devices
- Antennas for different use cases
- Extra batteries
- USB cables, power bricks
- Printouts (laminated as a bonus) of key information. Maybe this document?

Consider a waterproof case like a Pelican or similar. Look for an IP67 rating if you kayak or expect water to be a problem.

### Satellite Internet
* [Starlink](https://starlink.com/) - really the only game in town if cell providers are down. For as long as it lasts. DO NOT CONSIDER THIS NETWORK UNCOMPROMISED. Don’t share anything on this you wouldn’t share with someone at the grocery store. NOT PRIVATE, but clutch in an emergency.

### Power Sources and Generators
#### Solar Generators/Batteries
I like a solar generator like the ones made by Anker, Bluetti and Ecoflow. The best one to get is the one that meets your needs and budget. You can spend tons on these. Measure your estimated power needs during an emergency, and get the largest size that accommodates those.

I have a 2000 Wh Bluetti that I’ve had great success with. I paired this with 400W of foldable solar panels. I take this camping a lot and it has worked great. Others in my family have a similar setup with Ecoflow. Both are great options. Anker is putting out some super-cool stuff and if I had to buy again, I’d consider them strongly.

I also have a small 300Wh Jackery that was my first purchase in this realm. I still bring it, because it is VERY portable, and charges our small devices many times over before needing to sip from solar. It’s nice to have a smaller one that can easily be picked up in addition to a bigger one that stays in one place.

Generally, for a bigger one, I wouldn’t buy anything less than a 1000 Wh battery and would strongly suggest 2000Wh or more if you can afford it. I would pair that with at least 200W of solar or more. However, as battery capacity grows - weight goes up and portability goes down.

Keep an eye on Costco and black friday sales. These setups go on deep discount occasionally.

> [!TIP] Considerations:
> - What is your use case? Charge phones/radios? Run a fridge? Match your purchase to your need.
> - What’s the battery size? This directly affects what kinds of devices it will power, and for how long. It also affects how long it takes to recharge via solar.
> - How many outlets does it have? Does it have enough AC and USB outlets to meet your needs? Do you need a 30amp socket to run an RV?
> - Can you daisy chain additional batteries to the main unit to increase the amount of power you have in reserve? 
> - Can it be used as a power alternative for your house? (out of scope for this document!)
> - How much solar can the unit take? What voltage? Many units have a maximum input from solar. This will influence how many panels you need to buy and what kind.
> - How portable is the setup? Can you throw it into a car?
> - What is the battery technology? Look for LiFePO4 batteries if you can.

#### Electric vehicle V2L
If you have an electric vehicle - check to see if it has AC outlets or “V2L” (vehicle to load). These batteries are huge and can power things in an emergency for a long time.

#### Gas Generators
Gas generators are also fantastic and reliable, but consider that gas might become scarce during times of crisis. They are also noisy and gross.

Again - the redundancy approach is best here. If you end up with both solar and gas generators, you’ll be more covered. But this gets expensive.

Also - pro tip - be sure to keep your battery charged from the mains in your house so it’s always ready.

# Conclusion
Phew. That is a lot. Thanks for reading this far! Keep an eye on the GitHub for updates as I learn more.


