Welcome to Vi haven.
1 introduction
I hope this small manual can help you understand the fun that can be had in Vi haven. It might take a while to get used to, but once you do get used to it some truely fun combat can be had.
The first thing to note about this game is that, if you treat it like a generic shooter sidescroller of the past few years, you won't like what you get. I have tried to make the game as unique as possible, and as a result, some features may seem different than normal.
1.1 note about viruses
Since this game is programmed in blastbay game toolkit you may get a virus warning on your computer or the file may be deleted. Please remember to add an exclusion in your antivirus and never exclude any more than you should. Most bgt virus signatures are trojans, so if you see a virus:win32/... or worse still, ransom:win32/... then my website has been compromised and you should get rid of the file now. This is very rare, but I will say it here for good habbit's sake.
2 first time
When you load the game, you will be given a generic random name. You are strongly advised to change it from the settings menu. There are a few other settings there, which you may want to change as well.
Then, you can log into the game. There are a few glitches which may cause a bgt runtime error. If you see them, report it to me as soon as possible with the stack trace via my email at the end of the document. Please remember to tell me what line the runtime error occured on, as that helps a lot and quite frankly should really really be included in the traceback itself.
3 playing the game
3.1 basics
The map is a 300-tile long 1-dimensional line. It's fairly basic right now, but it will get more advanced as time goes on.
You may hear a "bwuh?" sound as you move. This is an item. You should go over to where the sound is coming from and pick it up.
You may also hear a high-pitched "bip". This is a player. They may try to kill you, so stay alert!
Another sign a player is near is a repeated small whooshing sound moving from one side to another. This is usually sign of someone preparing for combat or "cushion collecting", flying across the map very fast using an air cushion (described later). Some of these may zoom past you and go on their way, whereas others may begin to flit from side to side, shooting you from above. Fewer still may fall to the groundd, causing a "pop" sound followed by a hissing. This means that the player has been killed by their carelessness when using the air cushion.
3.2 combat
Combat is very, very different in this game to the norm. If you simply spam the space bar while using a weapon, you will not be able to win. You must use various tactics at your disposal to defeat your opponents.
3.2.1 getting information
3.2.1.1 tracking
You can see where all of the players on the map are if you have lost your orientation. You can do this by pressing the f1 key.
3.2.1.2 beacons
As described above, the most sure-fire way to see where a player is is via their beacon sound, a high pitched "bip" that periodically sounds at a position in the stereo field that signifies where they are in relation to you.
3.2.2 offensive tactics
In order to defeat an enemy, you will need to attack them or confuse them. There are several ways to do this.
3.2.2.1 shooting
The way you will kill your enemy outright is by shooting them. First, select a weapon from your inventory or from the number row (inventory-based weapons will be deprecated or improved soon)
Then, press the space bar to fire it.
Each weapon has different values: the speed that they fire, the speed of their bullets, the distance their bullets can go, and the amount of damage they do.
3.2.2.2 disarming
Another great offensive tactic is disarming. It might take your opponent a while to react to the disarm and you can get in a few extra shots in that time.
To disarm, press d.
If you are successful, you will hear a wooden clanging sound as the weapon drops to the ground. It has a random chance to succeed, but there is more chance it will fail than succeed. 
3.2.3 defensive tactics
3.2.3.1 dodging
Dodging is a very very useful feature and the point from which all other elements come from.
To dodge, press the down arrow. Note that reaction times must be extremely quick (less than half a second, sometimes less than a third or even a quarter) to dodge.
If you succeed you will hear the bullet whiz past and embed itself in the ground, the weapon being parried, etc.
3.3 jumping
Jumping is another very useful feature. To jump, press the up arrow button.
You will leap upward, and in that time you can move very fast left or right. You can pick up items while jumping, too. 
This can be used to lunge in for the kill, or to leap away from a melee or ranged attack, or even to beat your opponent to that antibiotic you've been eyeing up lying forgotten on the ground.
Note that jumping has a cooldown of 3 seconds, so use your jumps wisely!
3.4 items
There are lots of items you can pick up in the game. Most of these items can be used from the inventory menu, by pressing i, while a few will be automatically activated.
3.4.1 health boosts
A health boost is a small pack which will be used automatically when picked up.
There are three types of health boosts:
mini health boosts, which give 75 health each,
normal health boosts, which give 150,
and super health boosts which give a massive 350 points of health each.
3.4.2 antibiotics
Antibiotics are a small pill that you can take whenever you like, that will provide you with an extraordinary amount of health. You will only ever be given one of these each time you log in to the game to start your inventory collection.
Use it wisely and make sure you don't waste it!
3.4.3 air cushions
Air cushions are special items that can be picked up while running around. They are quite powerful, but come with their drawbacks.
If you use one, you can press the up arrow to "jump in the air". Make sure to do this before you land, as it will restart your 0.8 second jump time. It lasts for 10 seconds and then it will wear off, at which point is the only safe time to land.
If you land before the air cushion wears off (either from falling due to something or from forgetting to jump in the air) the magic will backfire and you will be killed from the air cushion exploding.
3.5 chatting
To chat, press the slash key and type your message.'Once you typed the message, press enter.
3.5.1 commands
There are a few commands you can ues in the chat box. To type a command, press slash an extra time when you are in the chatbox, before you type your message.
Most commands are restricted, but you can use some. They are below:
3.5.1.1 private message (pm)
If you want to send a chat message to only one user, you can use the private message feature. To do this, type:
/pm <username> <message>
For example:
/pm wolfy Hey, you blithering idiot! Come and kill me, and don't tell anyone else, otherwise they might before I manage to kill you!
3.6 the event log
When important events occur, like chat messages, deaths, etc, they will be put in the chat log.
This can be navigated with the following keys:
dot (or full stop): move down one item in the log (toward the present)
comma: move up one item in the log (toward the past)
shift+dot: move to the most recent item in the log
shift+comma: move to the earliest item in the log
4 quick key rundown
4.1 menu keys
left/up: move back, or up, one item in the menu
right/down: move forward, or down, one item in the menu
page up/page down: currently unused; turn up or down the volume of the music
number row: move to that item in the menu
<alphabetical character>: move to the first item in the menu which starts with the key you pressed
home: move to the first item in the menu
end: move to the past item in the menu
Note: to get out of the inventory menu press home and then enter to go back. You can not click escape button in any menu, due to some bugs.
4.2 game keys
dot: move down in event log
comma: move up in event log
shift+dot: move to last item in event log
shift+comma: move to first item in event log
up arrow: jump
left/right arrow: walk left or right across the map line, respectively
up arrow: jump
down arrow: dodge
d: disarm
space: fire
i: inventory menu
c: see your location in relation to the farmost left point of the line
f1: see the location of all players
f2: see the message of the day
f3: ping pong with the server to test lag, displayed in milliseconds
slash(/): chat
one(1): melee weapon category.
two(2): pistol weapon category
three(3): ranged weapon category
escape: exit (it must be pushed 3 times quickly to exit)
5 rules
5.1 game rules
1. Cheating. Forbidden, in all forms. This includes but is not limited to - abusing bugs (report these to the admins so they can be fixed please), speed hacking/time manipulation (both fast and slow), 
autohotkey and automatic key presser/macro scripts, and tampering with random number generators or library files to gain unfair advantages.
2. Deliberate crashing or bug/loophole/exploit abuse. IIf you find abug, report it to the admins. Please don't try to reproduce bugs. This should be done in a secure environment in case any side effects occur.
5.2 chat rules
Note that chat rules can, and will, apply to private messages, provided one of those conversing through the system gives consent and uncovers their logs to staff
1. Equality. Treat all players on the game equally, regardless of staff rank or skill level, or more importantly, race, disability or any and all other forms of identity.
2. Spamming. Please do not post a message repeatedly, use the chat system repeatedly for split messages, or send any screen reader noise spam (asdfghjkl, aaaaaaaaaaaaaaaaaaaaaaaaaaa) or crash codes for any synthesizer (such as the hesday crash code for eloquence)
3: Harassment. We take all cases of harassment very seriously in VI haven. Some examples of harassment are sexual advances or flirtatious behaviour, bullying or repeated insulting, threats, or stalking. 
If you are being harassed, or know someone who is being harassed, on VI haven, then please report it to the admins immediately.
4. Information. Please do not give out or ask for your or anyone else's personal information on VI haven. This is strictly prohibbited. This information includes phone numbers, email addresses, social media information, residential details, and 	passwords
5.3 last note
Not every single rule can be outlined here. If an admin asks you to stop doing something, then stop. If you think an admin will ask you not to do something you're doing, don't do it, or ask if it is allowed.
6 contact
The only way to contact an admin at this time is to use our email.
The email is:
wbt.gamer.rory@gmail.com
7 legal notice
It is known that this game uses assets which are not allowed to be used. The developers are working to fix this as fast as possible and will provide frequent updates to the process as we go. In the meantime, we request the game be allowed to stay on the forum for now. The process of removing the sounds should take up to 28 days, and if you think you could help sound design, then email us with the information provided above. We believe that removing it from the forum outright would not be worth doing, since the sounds will all be legalized in short order, however if it must be removed, then I  (Sightless Wolf) apologize for what has been said here and retract the portion of the statement relating to such.
This section will be removed come the time when it is no longer necesary.
