# GFMath: Picking Fairy Talents (Fervor vs Damage 2)

By /u/BigStupidJellyfish_, [Youtube](https://www.youtube.com/channel/UCXYXbrsfJJfvE5LJ9Bnu_fQ). [Back to home](https://big-stupid-jellyfish.github.io/gfmath/).

[Album of plots](https://imgur.com/a/n1q74k9).

Fairy calibration is hell, so it's best to get a good talent and stick with it. Damage 1/2 and Fervor have the widest utility and thus are almost always considered the best talents to have. The ROF boost of Aim on your rifles might be nice, but when you don't have rifles in your team, it's worthless. If you get the choice between these 3 talents, which one should you take?

![](https://i.imgur.com/6cfgGps.png)

Here's a quite zoomed-in view of the cumulative damage each talent deals, relative to Damage 2.
If the total relative damage is greater than 1 at some time, that talent is better than Damage 2 for fights of that length.

![](https://i.imgur.com/tRMvBjZ.png)

However, the absolute differences in performance are quite small - here's the same chart, but zoomed out and over 60 seconds.

Just by looking at the talents, it's clear that Damage 2 is best for short fights and Fervor for long/boss fights with it ramping all the way up to a 33% damage boost after 16 seconds. The main purpose of this plot is to show the specific breakpoints when Fervor becomes better than damage 1/2.

Using Damage 2 as the "reference" talent, Fervor starts off dealing 1.1/1.15 = 95.6% of what Damage 2 does. After 8 seconds, it starts increasing, passing Damage 1 9.77 seconds in and Damage 2 at 14.66 seconds in. After the first 20 seconds of the fight, Fervor will have boosted damage by 3.5% overall compared to Damage 2.

Extending this even further out, after 60 seconds, Fervor will be above Damage 2 by 11.66% (the theoretical maximum at infinite time is 1.1^3 /1.15 = 1.1573 = 15.73% more).

This is all assuming the echelon does *constant* damage over time, which is obviously not the case in a real battle considering all the different skills out there.
To get an idea of how skills change things, here's the simulator numbers for total damage dealt by two arbitrary generic teams:

STAR/M4/AN/45/P22/Artillery:

| Time | Damage 2 | Fervor | Change w/ Fervor |
|--|--|--|--|
| 8s | 99568 | 95624 | -3.96% |
| 12s | 174389 | 174245 | -0.08% |
| 20s | 284300 | 295609 | +3.977% |

WA/SVD/Px4/Five-Seven/Mk23/Artillery:

| Time | Damage 2 | Fervor | Change w/ Fervor |
|--|--|--|--|
| 8s | 134436 | 128629 | -4.32% |
| 12s | 246406 | 246408 | ~0% |
| 20s | 416843 | 435808 | +4.55% |

Rather imprecisely, it looks like Fervor starts to pass Damage 2 closer to 12 seconds in.
This is lower than the constant-damage assumption's time because of skills (like HGs) kicking in around 6-14s making Fervor's higher multiplier at 8 seconds and beyond more valuable, and Damage 2's higher early multiplier less valuable.
Early burst damage skills like Vector's molotov on the other hand would push things further in Damage 2's favor.

To put that to the test - let's say that, rather than damage being constant, it's 1 for time<6s, 1.75 for 6-14s, and 1 afterwards (75% is used as a fairly typical self-buff skill).

![](https://i.imgur.com/f8Wncl9.png)

We end up with this plot for the first 20 seconds - now, Fervor passes Damage 1 at 9.2 seconds and Damage 2 at 12.5 seconds.
This of course is still a massive simplification but shows the general principle.

So, all-in-all: there's no precise time when Fervor becomes optimal as no team has constant damage through the fight.
I would consider 12-15 seconds being a reasonable general timeframe for which Fervor starts to win out.
Fervor also has nice interactions with stuff like AS Val mod and Python, which is not accounted for here.
On the other hand, for something like Core 8 strikers, the extra edge Damage 2 gives in the first 4-6 seconds could save your tanks a lot of health.
