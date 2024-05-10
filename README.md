# ich-tf2bd-faq
A series of Frequently Asked Questions about the Team Fortress 2 Bot Detector made by someone unassociated with any version of it

### What is the Team Fortress 2 Bot Detector?

The Team Fortress 2 Bot Detector is a program that is used to detect bots and cheaters in Team Fortress 2. It was originally made by a group of people lead by Pazer. The original program has not been worked on in several years and [its repository](https://github.com/PazerOP/tf2_bot_detector) has since been archived. With Team Fortress 2 updating to 64-bit architecture, this version no longer works. The version that I use is a fork made by sleepy. You can find it [here.](https://github.com/surepy/tf2_bot_detector)

### How does it work?

You can find more detailed information on that in the above repositories. Put simply, it gets information from the in-game console and uses that along with curated lists of the Steam IDs of known bots and cheaters to call out those bots and cheaters if they're on the enemy team or to call votes against them if they're on your team.

### Wait, so it's a third-party program doing things for you in the game? Isn't that a cheat?

No. Again, there's more information on that in the above repositories but this program only uses console commands that anyone can use on any server. Nothing this program does is in violation of the Steam Subscriber Agreement. It is not a form of cheat. It will not get you banned.

### So how does it detect cheaters?

The program uses lists that contain the Steam IDs of the accounts of known cheaters and bots. There are different lists made by different people, but the entries in those lists are manual. When the person that curates a list runs into a bot or cheater, they mark that account as such. Because this is done using an account's Steam ID, they can't get around the mark by changing their account name or URL.

### What lists do you use?

Along with my own list (which I will not be publishing) and the official list (which comes with the program), I personally use the following lists:

* playerlist.biglist
* playerlist.megacheaterdb
* playerlist.sleepy
* playerlist.sleepy-bots-merged
* playerlist.sleepy-no-proof
* playerlist.trusted

You can find the biglist and the trusted list [here.](https://github.com/PazerOP/tf2_bot_detector/wiki/Customization) The rest can be found [here.](https://github.com/surepy/tf2db-sleepy-list)

### If these lists are curated by people, couldn't there be people that get marked as cheaters when they aren't cheating?

While that is possible, the lists above are lists that I trust to exercise great caution in marking someone as a cheater. I treat marking people for my own list the same way. If I don't see what I consider to be definitive, beyond-reasonable-doubt proof of someone cheating, I won't mark them as such and I trust that the lists above adhere to that same principle. Trust is a big part of using this program and of using different lists.

### Alright, this program seems pretty good. Should I use it?

I would certainly recommend it, though if you are going to use it I implore you to exercise great caution in marking people as cheaters. If you are unable to do so, I would recommend either not marking people at all and sticking to lists made by those you feel are trustworthy or simply not using the program at all.

### You were calling someone out for cheating but they were playing [insert non-Sniper class here]. How could they have been cheating?

You can cheat on any class. Beyond the obvious (wall hacks), there are aimbots for both hitscan weapons (anything that shoots bullets) and projectile weapons (anything that shoots non-bullets). There is also a cheat that effectively allows you to choose when you get random crits, meaning you can cheat with any weapon that has random crits. Fake lag exists and is pretty easy to spot (if someone is consistently stop-start teleporting around at a rate of about twice per second then they are probably fake lagging, especially if they have low ping). There are also some class/weapon-specific cheats, such as double-tap for the Force-A-Nature and auto-reflect for Flamethrowers. Just because someone isn't playing Sniper, doesn't mean they're automatically legit.

### You were calling someone out for cheating but I spectated them and they seemed legit. What gives?

Some cheaters toggle off when they are called out. Cheaters can also set their cheats to automatically toggle off when they're being spectated so it's harder to catch them. If someone is being accused of cheating but you don't see anything when spectating them, pay close attention to them when you're alive. Don't announce that you're doing this though, or they'll just toggle off for a bit to avert suspicion. Otherwise, read the answer to the question above regarding the lists being curated and the answers to the questions below regarding people claiming they aren't cheating and people claiming they are former cheaters.

### Your program tried to get me kicked even though I wasn't cheating! Why?

As I said, it is possible that there is an error in one of the lists, be it my own or someone else's. My list doesn't have many human cheaters marked, and with how cautious I am in marking people as cheaters it is highly unlikely that I falsely marked you as such. If you are marked on another list, I have no control over that. I can't get you removed from someone else's list, and I won't remove you from mine. If I'm calling you out as a cheater, feel free to ask which list you're on. It probably won't do much for you though, as the curators of the above lists are about as likely to remove you as I am.

### I used to cheat but don't anymore. How about removing me from the list?

If you get banned in a game for cheating, then make a new account and play on it for 6 months without cheating, then contact the devs saying "I've been playing legit on this new account for 6 months. I don't cheat anymore. Can I have my old account back?", you're not going to get the account back. In fact, I'd wager there's a decent chance your new account will be banned for ban evasion. If you've been caught cheating in the past then I have no reason to believe you've stopped.

### I have a question that isn't listed here!

It is likely that one of the above repositories contains the answer (make sure to check the wiki section for them in addition to the readme). If they don't then I probably can't answer it. I might be able to though! If we're in the same match, feel free to ask in-game. Otherwise make an issue in this repository with your question and I'll do my best to answer it, possibly adding it to this FAQ.

## That's all for now! May your matches be well-balanced and cheater-free!
