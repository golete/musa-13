---
layout: default

hv-loader:
  hv-chart-1: ["charts/hvplot01.html", "500"]
  hv-chart-2: ["charts/hvplot02.html", "500"]
  hv-chart-3: ["charts/hvplot03.html", "500"]
  hv-chart-4: ["charts/hvplot04.html", "500"]

---

# Visualizing retaliatory evictions in Philadelphia

The goal of this project was to visualize the different aspects that describe the phenomenon of retaliatory evictions in the City of Philadelphia.

Retaliatory evictions consist in the process where property owners, after failing to comply with some aspect of their rental agreement or the sanitary or basic building conditions in their rental properties, have a building violation filed against them by their renters and in return theaten to or evict them. Historically, this has become common practice for landlords throughout Philadelphia, especially in low-income neighborhoods, as they usually are legally represented in court and their renters [are not](https://whyy.org/articles/philadelphia-renters-dealing-with-major-issues-forced-to-lie-down-and-take-it-or-risk-eviction/).

To better understand this issue it is necessary to understand its distribution both in time and throughout the City of Philadelphia:

<div id="hv-chart-1"></div>

As well as comparing the evictions to the spatial distribution of Building violations filed across the city:

![Violations in Philly Map]({{ site.url }}{{ site.baseurl }}/assets/img/02.png)


Building violations can be further broken down by the type of violations that were filed, in order to understand the spatial distibution of specific violations and how are renters in different neighborhoods affected. It is noteworthy how certain violations, such as those related to plumbing, drainage or basic infrastructure of the house (like "Paint, windows, doors") are concentrated in the more disadvantaged neighborhoods in the the north east and south west of the city.

<div id="hv-chart-2"></div>

To make the correlation between the spatial processes of evictions and building violations even clearer, it is possible to compare side-by-side the evictions filed in 2018 with one of the most common violation types (and ever more relevant due to climate change): Rain protection.

<div id="hv-chart-3"></div>

As well as look at the spatial distribution of the 20 most common building violations issued in Philadelphia: 

<div id="hv-chart-4"></div>

From these building violations types, it is apparent that "Annual cert file alarm", "License - RES General" and "EXT A-CLEAN WEEDS/PLANTS" do not have much relation with the spatial distribution of evictions in the city. They are, respectively, the failure to keep a certification for all fire alarm systems on site for a period of three years, operating a rental property before obtaining a housing inspection license, and failure to mantain weeds or plant growth in excess of 10 inches.


## Notes

- The code that produced these visualizations can be found [here](https://github.com/golete/musa-13).
