---
title: 'Thinking about why a single value has probability 0 in a PDF (Probability Density Function)'
description: 'Thinking about why a single value has probability 0 in a PDF (Probability Density Function)'
pubDate: 'Mar 03 2025'
heroImage: '/dices.jpg'
---

Suppose that we are working with a continuous interval of $[0, 1]$.

If we were to try to come up with the probability of a fixed real number, for example, "0.3", we wouldn't be able to assign it any value other than 0. The reason is, we have infinite numbers in the continous interval $[0, 1]$. By definition, even picking an **exact** number "0.3" is a discrete decision, which is impossible in a continous domain.

On the other hand, if we think of a smaller interval in $[0, 1]$, for instance $[0, 0.5]$, and try to assign a probability to picking one of the numbers in this interval, we can actually assign a probability other than 0. This makes sense, because the smaller interval $[0, 0.5]$ occupies a certain fraction of the the entire interval, in this case half of it. Therefore we could imagine giving a possibility to this smaller interval.

We can think of this latter case as assigning a probability to a discrete section of a continous interval, because we KNOW how many of these discrete sections would make up the entire interval, they occupy some space.

This weird logic is also analogous to points having zero width by definition, but when we put them side by side they can make a line with a positive width. A single "point" in the continous interval by definition has zero probability, but if we put even two such "points" side by side and build a new interval, we can have a positive probability for this new interval.

I guess it all boils down to the fact that we can't even measure anything exactly in our world, we can always be more precise but never EXACT (Unless we find out that we live in a discrete world in some way, which I can't vouch for yet 😀).