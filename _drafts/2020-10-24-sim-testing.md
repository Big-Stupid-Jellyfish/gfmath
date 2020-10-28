# TARGET PRACTICE vs COMBAT SIM

A while back, I tried doing a few field tests to compare real battle performance with combat simulator predictions. Without the target practice system, this was rather time-consuming and costly and didn't give very good results.

Now that we do have a free way of testing teams, I thought I'd revisit that idea and see what I can find.

Note: I have yet to figure out what numbers the dummy settings translate to, so expect an episode 2 if I ever figure it out.

# Basic Dummy Bullying

Because I can't do much with "low" evasion, let's consider a lone dummy with 100k HP. If I create some team in a combat simulator and set it to a lone single-linked target with 0 eva/armor/etc, I can see at what time the team will have cumulatively dealt 100k damage. In theory, this should match up with the time in target practice on average.

![](plot-1-arsmg-dummy.png)

In addition to maxed-out fairies and plenty of oaths, all the top performers in the time-limited challenges have their formations pushed to the front.
Otherwise, some time is spent at the start of the battle walking towards the target.

Here, I conducted a test with the team pushed forward (using walk time=0 seconds in the sim) and with them on 14758 as normal (walk time=1 second in the sim).

With or without walk time, the performance lined up pretty closely with the sim.
In the forward formation, the actual team cleared the dummy on average 2.2% faster.
No trial here was slower than the theoretical time.
With the normal/backline formation, the actual team cleared on average 2.9% slower.
Again, the minimum time was always higher than the simulator time.

So: it would appear the walk time introduces some amount of error between reality and the simulator, but this difference is very minor and results were overall very consistent.
On the other hand, the target dummy does not move unlike most enemies.
It is possible that a hypothetical mobile dummy would approach the 1 second walk team sooner, resulting in a slightly faster kill and closer match to the simulator numbers.

# Advanced Combat Encounters
