Research with Ethan Cappelleri, presented at [Saberseminar 2026](https://about.samcowan.net//Papers/ABS-Challenge-Opportunity-cost.pptx)

This project proposes a way to calculate the present run value of future ABS challenge opportunities, with a dynamic programming/backtracking method somewhat similar to the binomial tree method of options pricing.

To do this we also modeled league average challenge behavior using logistic regression models (separate batter and fielder models) estimating whether a pitch would be challenged given game state, pitch location, and number of challenges left.

This addresses a gap in the baseball literature on ABS, as Tom Tango's initial approach to opportunity cost assigns a static value of 0.2 runs to every lost challenge; we find that the actual value is lower and varies with inning and number of challenges left.
![[Pasted image 20260902122608.png]]
![[Pasted image 20260902122642.png]]