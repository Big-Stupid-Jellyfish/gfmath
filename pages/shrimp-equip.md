---
layout: default
title: GFMath: Equipping SR-3MP for any situation
---

# Equipping SR-3MP for any situation

By /u/BigStupidJellyfish_ \| [Youtube](https://www.youtube.com/channel/UCXYXbrsfJJfvE5LJ9Bnu_fQ). [Back to home](https://big-stupid-jellyfish.github.io/GFMath/).

As I got to thinking on the best ways to visualize rifle accuracy against the infamous armored evasive enemies at night we'll see in Isomer, I got sidetracked with a thought on Shrimp, the subject of many accuracy-related discussions.
This one's a bit simpler, so I'll try and keep the writeup short and sweet.

![](https://i.redd.it/g8o87j6bueu41.png)

Based on the total accuracy buff your Shrimp is receiving and your target's evasion, pick the sight in the corresponding color band.
With a wider range of evasion values visible and some enemies overlaid:

![](https://i.imgur.com/YLSVDt7.png)

The key thing to keep in mind when deciding on your equipment is that you need to know what you're shooting at. The evasion of your targets massively influences the effectiveness of each setup. Find that out by looking up the map and enemy group on [this handy site I may mention once or twice in these posts](https://gf.hometehomete.com/en/maps/).

Most guides I've seen list some rules of thumb that should work well if you want a generic configuration, but this is for if you want a bit more specific visual comparison and don't mind swapping equipment mission-to-mission.
Remember: VFL = crit scope, EOT = damage/acc scope, ITI = acc scope.
These are all assumed to be maxed out, as is your Shrimp.
Once you know what evasion you're facing, and your effective accuracy buff, just find which sector you fall in.
To convert enemy evade debuffs to their equivalent accuracy buff, I recommend [this writeup](https://gfl.matsuda.tips/post/Accuracy).

As a quick reference, here's a few notable enemies and their evasions.

| Enemy | Evasion |
|-------|---------|
| CT Unarmed Zombies | 3 |
| Most vespids/rippers | 11-15 |
| CT Armed Zombies | 13 |
| 10-4E Cyclops | 15 |
| 8-4E Dragoons | 15 |
| CT Chapter 2 Rodeleros | 20 |
| 6-4E Alchemist | 22 |
| Core 8 Brutes | 24 |
| Core 8 SWAP Strikers | 24 |
| Core 8 Strelets | 43-45 |
| 7-4E Dreamer | 50 |
| 8-4E Dreamer | 60 |
| 10-3E Scouts | 80 |

Any given enemy (Strelets, for example) can have different evasion stats for each map, so don't assume these are the only values out there.

This should be obvious, but at night you absolutely need a PEQ unless everything has 0 evasion.
And don't fall into the trap of using suboptimal ARs to buff her accuracy/damage - ultimately, most of your damage output will and should come from your ARs, so that's your first priority.
ROF buffs may slightly alter things, so when in doubt you can always simulate your specific setup.

![](https://i.imgur.com/w9NEw1n.png)

Bonus: an earlier visualization where I made a set of charts in increments of 25% acc buffs that plotted her DPS as a function of evasion.
Ultimately all the extra lines don't add much information, but at least that one contains some example enemy pictures/evasion values.
You can also see exactly how much her DPS falls of as evasion increases.

![](https://i.imgur.com/qZ0nvM6.png)

Even before that was a semilog plot but that wasted way too much space between 0 and 1 evasion.
Because brute forcing problems is easier than thinking them through, the final plot in the image above was made by calculating the DPS curve like in these pictures at each value of accuracy buff and finding the crossover points, and plotting those.

The calculations assume SL10 skill, 27.5% fairy aura damage buff (2\* Artillery), and 12% damage 1 talent.
