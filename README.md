TurnSignal (New 2.1!)
=

![TurnSignal Icon](/Assets/_Res/turnsignal-v2.png)

A minimalistic, intuitive, visual, IN-GAME utility for keeping track of Cord Wrapping/Tangling in SteamVR.

---

### Please Note (!):
 TurnSignal 2.0 (and up) is a much needed optimization upgrade, it uses proper SteamVR auto-startup, less CPU cycles, and is all around better! Please Upgrade if you have not!

---
## ScreenShots - Updated for 2.0!

[How It Looks](https://gfycat.com/ImpressiveUnnaturalAmericansaddlebred)

[How It Works](https://gfycat.com/DemandingAdorableAntbear)

[The Menu](https://gfycat.com/EarlySnoopyChihuahua)

['Scale' Setting](https://gfycat.com/WhichSnoopyKite)

['Opacity' Setting](https://gfycat.com/GleamingGivingArchaeopteryx)

['Twist Rate' Setting](https://gfycat.com/FrequentHeartfeltAsianwaterbuffalo)

['Petals' Setting](https://gfycat.com/CompetentPlainCormorant)

['Use Chaperone Color' Setting](https://gfycat.com/ContentBlueBlueshark) 
(This one got straight up BORK'ed by the video compression, but the color, it really does match, I promise, if you could see it. Really.)

['Link Opacity and Twist' Setting](https://gfycat.com/HeartfeltLimpGoitered)

[Some Fun Stuff ;3](https://gfycat.com/ThoroughThunderousAmurminnow)

---
## Download:

[Click here to go to releases!](https://github.com/benotter/TurnSignal/releases)

---

## Installation:
To 'Install', please download the 'latest' release from [here](https://github.com/benotter/TurnSignal/releases), extract from the .zip file to where-ever you want to keep the utility on your computer, and run TurnSignal.exe! 
 
 It should automatically register itself to start with SteamVR, and auto start/close with it from first launch on, but this is a toggle-able option, and can be freely disabled from the Dashboard Menu!

---
## Usage:

After launching the program, the window should be minimized automatically, if not, you can minimize it at your liking!

The settings menu to control Aspects of TurnSignal should be included in your SteamVR Dashboard as an Overlay, and the utility itself should be projected onto the floor of your environment.

The Newest Settings menu includes:

- A Button Toggle to enable/disable the tools in-game display
- A Button to Reset the utilities Rotation Tracking
- An Opacity Setting 
- A Scale Setting 
- A Twist Rate Setting for manipulating the twist-i-ness levels 
- A Toggle to auto-starting and closing the utility with SteamVR
- A Toggle to use Chaperone Color instead of white (real time too!) 
- A Toggle To Link Opacity and Twist'ed-ness together, so it shows clearer the more wrapped up your cord is.
- A Toggle to only display the Flower / Floor Overlay when the Dashboard is Open.

All settings are saved between app sessions, and shouldn't need to be set every time its launched.

The utility will still track rotations even when its toggled off from the dashboard menu, so if/when its toggled back on, it will still show turns as if was left on, with the turns intact.

-- Note -- The way Twist Rate affects the ammount of rotation the floor reacts to is actually measured from 0 - 10 (now user set Max) turns in either direction, and given as a 0.0 - 1.0 floating point, with 10 (or user number) turns used as 'max', but it can exceed this without problem, resulting in 'fun' floor shapes that have higher then 1.0 twist values. Just an FYI.

---
## About:

I had the idea for the utility (which originally used large arrows and a counter in the center, but That was Terrible) after playing, and watching people play, GORN on my HMD. 

Every time, when action got intense, the cord would inevitably get wrapped up and tangled, and get caught on legs, the controller, the like.

I figured it couldn't hurt to have a visual, in-game tool, to subtly alert you to your ammount of turns, without pausing to dashboard. It was also a very simple idea, with a very fixed feature set to complete it, so why not, eh?

### Part 2

After that, I posted the tool on reddit, and somone cross posted THAT on geogaf, and I got a whole lot of positive feedback, (which I thank everyone for <3!), and that drove me to dedicate a bit more time to it (Another Week), and now its basically rewritten from scatch.

### Part 3

After THAT, I reposted 2.0 on reddit, and got another good critical reponse, and more features have been added as a 'stream' of users making issues (yay!) has slowly begun forming!

---
## About - OpenVR Overlays in Newest Version of Unity

After fidling with Unity and the SteamVR plugin, I realized that somewhere in Unity's built-in support for OpenVR, it forces the appplication-type flag to be 'Scene' when what I needed is 'Overlay', or 'Background'. After searching and finding out others were mitigating the issue by just using older builds of unity, I decided to tackle the problem head on.


The result is I basically resupun my own OpenVR handler that works outside of Unity's built-in support, and is now completely free of the SteamVR Plugin! (Although I totes Copied out majority chunk of SteamVR_Utils to get them sweet transform operations!)

Its called OVRLay, and the entirety of its should be contained in the OVRLay folder under 'Assets', or in the unity package/archive in the root of the git.

Let me know if you find it useful or interesting!

---

I think thats that, Credit/CopyRight to Valve for OpenVR/SteamVR stuff. 

Thanks and credit to my friend Mason Halstead (141art) for The Icon asset!

Special thanks to [matzman666](https://github.com/matzman666) for giving me super-helpful resources for the SteamVR AutoStart App-Manifest, and Chaperone Color Retrivial Stuff, which he posted [Here!](https://www.reddit.com/r/Vive/comments/6oqspt/turnsignal_a_small_ingame_vr_utility_i_built_to/dkn6pj7/)

Feel free to message me for any questions/comments/feature-requests!