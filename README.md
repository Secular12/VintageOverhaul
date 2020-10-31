# Vintage Overhaul Mod

## Extended Crop Growth
Since, by default, there are 12 days per month (144 per year). To convert real world days to in game days it is (Real Word Days x 0.394). 0.395 is 144 / 365.25

* **Cabbage** ~51.22 igd (80-180 rwd; ~130 rwd) originally 6.5 igd
* **Carrot** ~29.55 igd (70-80 rwd; ~75 rwd) originally 4 igd
* **Flax** ~39.4 igd (90-110 rwd; ~100 rwd) originally 4.2 igd
* **Onion (dry bulb)** ~54.175 (100-175 rwd; ~137.5 rwd) originally 3.6 igd
* **Parsnip** ~44.128 igd (16 weeks; ~112 rwd) originally 6 igd
* **Rice** ~53.19 igd (4-5 months; ~135 rwd) originally 4.2 igd
* **Rye** ~53.19 igd (fall-midwinter; 135 rwd) originally 5 igd
* **Soybean** ~47.28 igd (90-150 rwd; ~120 rwd) originally 5.4 igd
* **Spelt** ~41.37 (Mid April-late July; ~105 rwd) originally 4.4 igd
* **Turnip** ~17.73 (30-60 igd; ~45 rwd) originally 3 igd

Since the increases time are roughly 10 times the original the tickGrowthProbability was decreased from 0.05 to 0.005. This is when the game will ask random block, every 50ms, if they would like to do something, and most crops will have a 0.005% chance to randomly jump up a growth level.