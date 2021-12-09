## About Me
Currently working as a trader in the securitized products space. Coding has recently become a hobby of mine in my time off. 
Would love to collaborate with anyone currently in HFT in the fixed income markets.

The optimizer for DFS comes from https://www.nicksniche.net/ and the fantasy football pandas exploration comes from https://www.fantasyfootballdatapros.com/.

Shoutout goes to both Nick and Ben for helping me learn. Please check them out/support them!

## Fixed Income
The files located in the finance are some real world examples of how fixed income portfolio managers will compare their holdings to that of the benchmark. For the newly initiated, a benchmark is a basket of securities that the portfolio manager is trying to beat in terms of performance. This is easier said than done and a lot goes into the decision making process. These are very high level examples but a lot of grad/undergrad classes do not include basics such as this.

## Index and Portfolio Statistics
The holdings vs benchmark file is a simple comparison of the percentage amount that is held in the portfolio vs that of the benchmark. In the example provided, you can see the portfolio is underweight the index vs the 2.0% coupon but overweight in other areas. How you want to manage this portfolio is to ask yourself the question, "Where do I want to be underweight vs overweight the index in terms of coupon. Do I think the 2.0% coupon will underperform the index? Then I want to make sure I am underweight. Will the 3.0% coupon outperform? Then I want to be overweight." However, this is an incredibly simple example, as security selection (are the specific bonds the index owns better or worse than the ones I own?) is very important. Every bond is different, but you want the best bonds.

The portfolio statistics file is comparing some important metrics of your holdings to the index. We can see this portfolio is shorter on duration vs the index but is also less negatively convex and has a higher yield than the index. The reason for being short the index is a factor of a rate call. Will rates go higher or lower in the future? Higher in the future means you want to be short duration and vice versa for lower. You can be neutral the index as well. Day over day changes depending on the securities can cause duration to drift.
