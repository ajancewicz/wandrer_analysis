# Wandrer scraper

January 2024
Amy Jancewicz

## Purpose
I wanted to quickly know which regions near me could be completed most quickly based on the remaining distance to level (and earn bonus points). For the purposes of this project, "levelling" is the gaining an achievement of moving to the next [Explorer Achievement Level](https://wandrer.earth/faq#:~:text=Explorer%20Achievement%20Points%20Bonuses%20are,double%20points%20for%20those%20miles.), described below:

> ### Explorer Achievement Points
> Percentage Completed | Points Bonus
> -|-
> 25% | 25% bonus
> 50% | 5% bonus
> 75% | 10% bonus
> 90% | 50% bonus
> 99% | 10% bonus

Additionally, I want to see where I could complete the most distance without having to drive or repeat streets.

## Approach
This code was designed in python, using Jupyter Notebooks. It pulls data from the [Wandrer](wandrer.earth) website, using access through my account using a payload.py file. Outputs include a table of the top regions where I can most quickly pass to the next level (25%, 50%, 75%, 90%, or 99% region completion), and a map with the top 20 regions that has the quickest opportunity to level with the highest Explorer achievement points.

## Next Steps
1. Improve map output coverage
2. Identify regions closest to my hubs (transit, activities, work)
3. Update worth score to account for Explorer Achievement points, rather than raw region miles.
