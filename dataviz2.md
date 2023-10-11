| [home page](https://merlinwijaya.github.io/tswd-portfolio/) | [visualizing debt](dataviz2.md) | [critique by design](critique-by-design.md) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |


# Assignment: Visualizing government debt

## Part 1: Working with web-based visualization tools and data
<iframe src="https://data.oecd.org/chart/7b81" width="860" height="645" style="border: 0" mozallowfullscreen="true" webkitallowfullscreen="true" allowfullscreen="true"><a href="https://data.oecd.org/chart/7b81" target="_blank">OECD Chart: General government debt, Total, % of GDP, Annual, 2019</a></iframe>

## Part 2: Working with Flourish
This grid of line charts shows the debt-to-GDP ratio of the OECD countries over the period 1995-2021. Please note that due to incomplete data for certain countries, there may be starting gaps in the line charts.

<div class="flourish-embed flourish-chart" data-src="visualisation/14954541"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

## Part 3: Create your own visualization
The audience may not be able to tell whether the ratio is in a favorable range based on the line charts in Part 2. As a result, I created a heatmap and divided the debt-to-GCP ratio percentage into four categories, as shown in the legend.  A good debt-to-GDP ratio, as defined by economists, is typically below 60% (National Debt, 2023). This indicates that a country's debt is relatively low compared to its economic output, signifying financial stability.

I used diverging hues to demonstrate successive colors with varying extreme points. Since a range of less than 60% is still regarded as good, I utilized two different shades of blue: darker blue for countries with less debt (less than 30%) and lighter blue for countries on the cusp of the 60% barrier (30-60%). On the other hand, I use red for ratios greater than 60% to signal that they have a high debt-to-GDP ratio. These colors were generated using Adobe Color Wheel. I also chose blue and red for color-blind people to be able to distinguish, rather than the more popular green and red.

With this heatmap, the audience is not only able to compare the value over the period of time between countries but also able to get insight into the countries' financial stability based on debt-to-GDP ratio values.

References:
National debt (2023) The American Leader. Available at: https://theamericanleader.org/problems/national-debt/ (Accessed: 10 September 2023).	


<div class="flourish-embed flourish-heatmap" data-src="visualisation/14963943"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

