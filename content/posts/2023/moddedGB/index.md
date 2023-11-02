---
title: "Modding the Gameboy Advanced (Re-upload)"
date: 2023-06-01T22:45:41Z
draft: fasle
---

### Some background
It’s no surprise to anyone in my social circles that I’m a massive gamer, so by the law of attraction, my best friend happens to be a gamer himself, particularly a Nintendo fan. He’s been collecting games and consoles for a while, and while we both fuel each other’s collections, I wanted to get him something unique and special but still in line with our personalities and usual gifts. We were walking down the street one day, discussing our childhood and first real exposure to gaming. With my friend being Chinese, I was particularly invested in the discussion and the difference in experiences we both had, considering that most games from 2000 until 2015 were banned within mainland China. I found out that his first console, like many others, was the Game Boy, and he shared some funny anecdotes about how his grandfather managed to sneak the Game Boy from Hong Kong and how an entire classroom would share a single game cartridge.

It was from there that I had the idea to modify a Game Boy and present it as a gift on his next birthday. I figured it would be a nice little introduction to electronics and thought that documenting the process would show the love and labour that went into it! After doing a bit of research into modding retro handhelds, I decided on the Game Boy Advance as it seems to be a popular choice within the modding community and, as a result, is a well-documented process.

### What you'll need for the mods
It should go without saying, but you’ll need a Game Boy Advance, you’ll also need to purchase some additional parts (some of which are optional). I purchased the below parts; however, I would recommend that you read on before pulling the trigger on purchasing anything. Now that I have experience to draw from, I would have done things differently.

![Parts for the mod](BagParts.JPG)

Firstly, the core of this console mod, without a shadow of a doubt, is the IPS display. It’s probably the reason you should be modding the console in the first place. After doing a bit of research, I opted to get the Funnyplaying IPS V2 screen with flex ribbon. From what I can tell, the screen offers the greatest visual clarity and vibrancy; however, there are alternatives that can perhaps offer a more retro look, like the AGS-101 or Retrosix CleanScreen.

![Purchased items](Parts.png)

I purchased all my parts from ZedLabs, but Retrosix and Retromodding are also great for sourcing new parts.

As you can tell from the above, I purchased a replacement speaker and audio amplifier.

{{% notice tip %}}
if I were going to attempt these mods again, I would recommend that you swap the Retro-Tobot mod out for something more beginner-friendly like the CleanAmp Pro, as there is more documentation surrounding the installation of the amp. The solder points are more or less the same for both amps; however, I made some mistakes as this was my first project requiring soldering, and the alignment of the amp proved to be quite tricky. It was a learning experience.
{{% /notice %}}

Given the above information, you’ll also require the appropriate tools (again, depending on the parts you’ve purchased).

* A tri-wing screwdriver (Y0.6)
* A Philips screwdriver (PH00)
* A soldering iron, flux, solder, etc. are only technically required for any audio mods.

### Installing the mods

![Before mods](BeforePhoto.JPG)

After having tested to confirm your Game Boy is working, etc., de-shelling the Game Boy is pretty straight-forward. Turn the console over and remove the battery cover. You’ll notice seven screws on the back. I’ve circled the Tri-Wing screws in red and the Philips screws in green.

![Highlighted screws](HighlightedScrews.png)

Simply unscrew these screws, and the backplate of the console should detach from the rest of the console to reveal the internal motherboard.

![Backplate removed](BPremoved2.JPG)

Once you’ve removed the backplate, you’re almost ready to remove the motherboard. Lift the tabs on the locking mechanism that hold in the current screen’s ribbon cable, which I’ve circled in red below. Also take note of the number of pins your board has; this is usually printed on the board (circled in green). I ended up having to use a 32-pin board after failing to solder the speaker mods properly.

![Highlighted latches and pins](HightedLatches.png)

Once you’ve unlocked the ribbon cable from the motherboard, There will be Philips screws holding the board onto the front plate. Unscrew these screws.

![Highlighted internal screws](MBscrews.png)

Now you can gently remove the motherboard from the console’s shell.

![Console's motherboard](MotherBoard.JPG)

At this point, I had attempted to solder the board and its speaker. You can attach various speaker mods if you’ve got the soldering experience; however, I ultimately ended up ruining the board pictured above. If you see further pictures showing a 2-volt speaker, It can be ignored.

The screen can be assembled pretty easily; there is a small FPC that connects the new ribbon and the screen itself. Given how small this was, I had difficulties photographing this process. My camera wouldn’t focus. I did manage to find the below photo online, though, which should give you an idea of what you are doing. Just be careful that you’ve properly aligned the connectors when you apply pressure, as these parts are fragile and easily broken.

![FPC connector](FPC.png)

![The motherboard and screen assembled](MBandIPS.JPG)

The beauty of the screen mod is that you don’t necessarily need to solder. So more or less, with the new case I purchased, I just had to ensure that the screen was properly aligned and installed. As shown below, you’ll notice that the ribbon has both a 32-pin and a 40-pin connector. Given that I had to get a new board, I had to fold down the 40-pin connector and fold the 32-pin connector upward in place of the 40-pin.

![Screen installed on new front plate shell](ShellIPSInstalled.JPG)

After that, it’s a really simple assembly. Just pop in the buttons and silicon pads, run the above disassembly steps in reverse, install the stick-on glass screen cover and any other cosmetic stickers, and carefully put everything back together. You should be left with a stunning end product.

![Lights Off](LightsOff.JPG)

### The before and after

![Before](OriginalScreen.JPG)

![After](AfterPhoto.JPG)

I feel that the results speak for themselves, and it was a nice project at least to introduce me to soldering and electronics. I’ll likely do some similar projects in the future, but for now, I hope this makes a nice gift and becomes a treasured piece of his collection!
