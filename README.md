# Lazard LCOE model

Investment firm Lazard has published the 12th version of their [Levelized Cost of Energy assessment](https://www.lazard.com/media/450784/lazards-levelized-cost-of-energy-version-120-vfinal.pdf).

It has then been cited in an antinuclear report, and now I keep arguing over these numbers on Reddit with people who think we should ditch nuclear energy altogether because renewables appear so much cheaper in Lazard's estimates.

Even though there are plenty of reasons to not deduce such things from these figures, the first of which being that LCOE doesn't account for many things, I was still surprised by such a large discrepancy. So, knowing nothing about finance, I decided to reproduce their model in Python, because I'm much better at it than at Excel. I can reproduce their numbers pretty accurately, except in a single case (the high estimate of Gas Combined Cycle). I will comment on it on my blog soon.