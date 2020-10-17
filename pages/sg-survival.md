---
layout: default
title: GFMath: Picking the Tankiest Shotguns
---

# Picking the Tankiest Shotguns

By /u/BigStupidJellyfish_, [Youtube](https://www.youtube.com/channel/UCXYXbrsfJJfvE5LJ9Bnu_fQ). [Back to home](https://big-stupid-jellyfish.github.io/GFMath/).

Note: I originally wrote this on 2020-July leading up to Isomer ranking, but the same ideas here can be useful against other enemies in the 30-60 accuracy range with low damage.
For general content, you should also keep in mind how much armor each SG has relative to the enemies' damage.

[Album of images](https://imgur.com/a/POHBYIl).

## Background

Word on the street is you need a few shotguns for ELID teams in Isomer ranking.
Most people say S.A.T.8 is the best, and for the rest just use whatever - after all, the zombies don't have that much damage so any shotgun can tank them.
But, even when choosing whatever, is there a slightly better pick?

---

The zombies we're expecting look something like this:

| Unit | ACC | DMG |
|--|--|--|
| Smasher (BOSS) | 60 | 32 |
| Unarmed | 60 | 7 |
| Armed | 30 | 26 |

Clearly, the minion zombies have low enough damage for any shotgun to handle it.
Different combinations of HP/eva however will let some shotguns perform better than others.

![Shotgun survivability](https://i.imgur.com/Fk0OKni.png)

Here, the number of hits each shotgun can take is plotted by enemy accuracy.
More hits tankable = better survivability.
In the case of Isomer ranking, the gas damage will greatly accelerate death compared to the listed numbers, but the overall proportion should remain about constant.

This plot assumes 100 affection/+10 max calibrated gold armor, and that all hits deal 1 damage.
No skills are considered (even ones that buff armor, evasion, or shields), so keep in mind that those will influence matters if the fight lasts long enough to trigger.
That said, SG skills usually don't come online until after 10 seconds when hopefully the main enemy force is already dead.
Notably, depending on the timing of S.A.T.8's shield, she can take very little to no damage per fight.

As a bar graph, sorted by survivability versus 60 accuracy:

![Shotgun survivability (bar form)](https://i.imgur.com/cZojBzE.png)

## Conclusions

Super-Shorty is actually pretty good versus 30 accuracy due to her high base evasion, but falls to the middle of the pack at 60.
S.A.T.8 overall has the best defensive stats.
M1887 and Dana are close behind, while Type97S and M1014 appear to be the top 4\* picks.
SPAS-12 and Elphelt have identical HP/evasion making them harder to make out in this plot.
RMB-93, NS2000, and USAS-12 take the bottom 3 overall spots in survivability.

S.A.T.8 gets the short end of the stick here (despite still being the overall best) because her shield isn't accounted for.
That is incredibly relevant with its insane ICD, so consider her survivability as being far higher in the field.

KSG and Super-Shorty have skills that boost their evasion and armor, giving them a further edge 10-16 seconds in.
Elphelt has a reasonably useful offensive skill at 10s (not link-dependent), and USAS's offensive skill kicks off immediately (link-dependent).

![](https://i.imgur.com/oXxDTfU.png)

Before you get too concerned about leveling specific shotguns, see the same plot but with a zero-scaled y-axis.
The actual difference in survivability isn't that major between most shotguns.
This also all assumes SG armor is sufficient to reduce all damage taken to 1.
Stuff like KSG and FP-6 will stack armor better, and Super-Shorty will have a tougher time hitting thresholds in some fights.

Perhaps RMB-93 should sit this one out, but otherwise you can probably just use what you have.

## Variations

![](https://i.redd.it/4jpr8ibixo851.png)

The original plot, with some images and overlapping lines.

![](https://i.imgur.com/LTxzyKu.png)

An extended survivability curve for 10-100 enemy accuracy.
The y-axis is not zero-scaled and is logarithmic for better visual separation.
As before, the absolute difference is pretty small.
