# Sw1tchblade-exec

## Before you begin
This **will** break your custom controls. This **does** move some vanilla controls around. 
e.g. Q is inspect and F is (a faster) quickswitch. 
You can, of course, edit these to your liking. Some of the controls will be easier to edit than others.

Some features are very delicately woven together, and will break numerous functions if you're not careful.
Make changes in small batches with the game in a empty bot comp game in the background for maximum 90 games to test.

###### Please Note:
*There is a bug I've noticed while making this Autoexec that causes the game to go into some low power state, it seems*
I'll go from 300 frames averages to 70 and my fans won't spin up. This only seems to happen when I let the game background for a while. 
In any case, this isn't because of the Autoexec, but a CSGO bug which I can't control. It will not stop you from making and testing changes.

Now, on to the good stuff. 

# Features

- 'Notifications' [Huge Kudos to /u/festinuz of reddit for the original script. It's amazing.] (https://www.reddit.com/r/GlobalOffensive/comments/42rq9u/a_quick_guide_on_how_to_print_info_toggles_damage/)
  - Volume control with on-screen display.
  - Voice volume, on-screen.
  - Mute State Display
  - Notifications Toggle
- Buybinds (That are only active when you hold a certain key, and show what key does what on screen. *Uses Notifications for latter*)
- Crosshair switcher (With a little finagling, you can add, remove, change or replace crosshairs to easily switch on a whim.)
- Info Clan Tag, and a Fake (You know "I'm reloading..." "I'm running" before your name" *Requires you join a number of clans to work*)
- Quick Nade binds. ZXC and LALT for Smoke, Flash, HE and Molly respectively. 4 will now select Decoy when you have it, and preform normally otherwise.
- Bomb Find/Drop Key (Uses in game hints on CT to show you where the bomb is as long as you're on the right site. On T it switch to the bomb while holding, and throws it when you release. 
- Viewmodel file for easy editing and replacing with your own, executed every time. 
- Netgraph with scoreboard
- Radar Size adjuster, hold Capslock to Zoom out
- Taunts that are only active when you press a key. No more accidental flaming. 
- Easter Eggs

# Installation 

This process can be both very easy, and very cumbersome. It depends on a number of factors. 
These are:

- Your preexisting autoexec, customizations. Crosshairs, viewmodels, etc. 
- Your willingness to either update the files, or update your muscle memory.
- Your aptitude on a computer. 

This isn't meant to be off putting or rude, but I've spent countless hours frustrated getting this to work
how it does, so if you break it you'll feel a similar if not increased frustration.

## If you want to install as is, it's rather simple

- These instructions will be updated shortly with github download and unpacking specifics

## If you want to change controls, this is where it get's bumpy. 

Some keys are easy. Very simple binds. Others, are nested within other files because they have very specific functions tied to them.
And example of this, is M. 
M is both your Team Equipment view toggle, and a taunt when holding the taunt key. Because CSGO isn't the most robust, having these two states exist is error prone. 
When you want to, say, change it from a Team Equipment View toggle to voice chat, you don't simply change one line. 
You have to goto the taunts.cfg, find where M's script is, and change the first and the last line to match. 
But, this example is the most complicated because it also contains code that is required to keep other parts of the script functioning as intended. 
If you read the explanation there you'll understand more, but the short version is I like that insult. I don't want to remove it for the sake of "ease"
so I simply made it work with everything else, albeit at the cost of my time and energy and making it harder for you to move stuff around. Ah well. 

**If you've scripted in Source games before, you should have no problem figuring this stuff out and making it work for you. She's fickle, but so worth the wait.**

*More specific examples will be provided at a later date.*