---
date: 2018-09-15
title: "frequently asked questions"
weight: 40
---

### Why are your estimates higher than the city's estimate of approximately 25,000 properties?

Simply put, we do not know where this number of 25,000 came from. A number of media reports over the years have used it, and it is cited in informal conversation, but we have seen no documentation as to who produced this estimate or how it was derived. This makes it hard to conclusively say why our numbers are larger.

### What about [stlvacancy.com's estimates](http://stlvacancy.com)? Why are your numbers higher than those?

There are a number of methodological differences between how we identify vacant properties and [stlvacancy.com](http://stlvacancy.com) does. On one hand, they have access to data that the city does not make public - tax delinquency information as well as board-up and mowing services to properties by the Forestry Division and the Building Division. On the other hand, we use Citizens' Service Bureau estimates, which [stlvacancy.com](http://stlvacancy.com) does not. 

Finally, we did not put a time limit on our data - if a property appeared to have a demolition permit completed in 2010 and had not had a new building permit issued since, we identified it as vacant. The same property may or may not appear on [stlvacancy.com](http://stlvacancy.com). If taxes have been paid on the property and for whatever reason Forestry has not mowed that lot, [stlvacancy.com](http://stlvacancy.com) would not show it as vacant.

This point raises a second difference in our goals. To date, [stlvacancy.com](http://stlvacancy.com) has focused on properties that are a burden to the city. We view vacancy more broadly as a social burden even if properties do not draw attention from the Forestry Department or another City agency.

On September 15, 2018 we updated our [data release](https://github.com/chris-prener/vacancy-data) to include files that are "cross-walked" between the [stlvacancy.com](http://stlvacancy.com). **Note that these data are from two different time periods.** They are released to provide a point of departure for those interested in exploring differences between the two estimates. Overall, there were 695 properties that are in the June [stlvacancy.com](http://stlvacancy.com) data release that are *not* in our data. This can be attributed to differences in both time period of estimate and methodology. There were a total of 25,598 properties that existed in both data sets, and an additional 23,095 that exited only in the prairie data. 

In our initial comparisons of the data, the single biggest unifying difference between our data and the [stlvacancy.com](http://stlvacancy.com) data is the inclusion of data from the Citizens' Service Bureau. There are an additional 13,000 properties not included [stlvacancy.com](http://stlvacancy.com) that had CSB calls for vacancy conditions with no subsequent building permits. Many of these properties had either (or both) multiple calls to the CSB over time or additional indicators of vacancy in our original data set.

We think the work that [stlvacancy.com](http://stlvacancy.com) and the vacancy collaborative are doing is both needed and welcome. In the long term, we are hoping that the multiple efforts to identify vacant properties in the city can help us produce a tighter estimate of vacancy and allow us to move on to more concrete discussions about solutions.

### What issues exist in the City's data?

Our estimate of vacancy was derived completely from public data. Like most public data sources, the data the City releases on their [open data website](https://www.stlouis-mo.gov/data/) has some issues. There are inconsistencies between different data sets in terms of how individual parcels are identified, and we spent a significant amount of time making sure that street addresses associated with parcels were matched to the *correct* parcel identification number (called a "handle"). 

Another issue, particularly with the Assessor's data, is that there are inconsistencies in how vacancy is defined. The [primary indicator](/approach17) of vacancy, the vacant lot indicator, does include false positives. We knew when we did the initial analyses that properties along some railroad and interstate highway right-of-ways were identified as vacant, and have learned since that some parking lots are also labeled vacant in this data set. 

This raises two questions - why is the City incorrectly identified vacant properties in tax data, and how can we figure out which ones are vacant and which ones are not? The short answer to both is that we don't know. Given the data we had, there was not a clear way to determine which properties owned by, for example, the [Terminal Railroad Association](https://en.wikipedia.org/wiki/Terminal_Railroad_Association_of_St._Louis) were vacant and which were along *active* railroad right-of-ways. Our upcoming January 2019 estimate of vacancy will take into account this issue with vacant properties, and we hope to have at least a partial solution to identifying these properties even if we are not able to explain why these properties are "vacant" in the Assessor's Data.

Another issue is that specific codes within particular data sources, like the demolition permits, are sometimes entered incorrectly. For example, we only used demolition permits that were pulled on the major structure on a given property. However, in the notes for some of these major structure demolition permits, we found that they were applied to a shed or garage incorrectly, or that they only involved the demolition of a porch. Again, we did our best to identify demolition permits that only applied to a major structure, but the permit and inspection data is entered by humans, which means that mistakes are inevitable.

### What issues might exist with the Citizens' Service Bureau Data?

We have two concerns with the CSB data. The first is that addresses may not be relayed by callers to the CSB accurately, and the second is that there is no "confirmation" that a call was valid. We take callers at their word that a vacancy situation exists. In the low estimate, the CSB call data was never the "deciding" factor; there was at least one other secondary indicator as well. This was done in part as a hedge against mis-identified properties. The high estimate reflects all properties that, among other indicators, had a CSB call with no subsequent building permits pulled.

### How do you think data quality issues affected your estimates?

Given what we noted above, it is almost certain that we have false positives in our data and that we also missed vacant properties. We are therefore circumspect when we talk about our data as *estimates*. Some initial checks regarding the incorrect identification of parcels as vacant by the Assessor's Office suggested to us that it may be biasing our low estimate up by several hundred parcels (out of 32,431). Again, our goal was not to determine a single "right" number for vacancy but to identify clustering. A change of several hundred parcels, particularly along the major railroad corridor through Downtown, Midtown, and south of Forest Park would not have a significant impact on our statistical models.

### What is missing from your data?

Aside from the data sources that are not publicly available but are used in [stlvacancy.com's](http://stlvacancy.com) estimates (Forestry and Building Division data as well as tax delinquency data), we did not use occupancy permit data. These are now more readily available and allow a potentially better source of "recent activity" than building permits. These data would allow us to trace occupancy of properties that are, for example, only vacant for temporary periods of time.

### What are your next steps?

Chris is planning to continue to carry this work forward with three goals:

1. Produce an updated January 2019 estimate that: 
    * refines the methodology used in 2017
    * adds in occupancy permit data if available
    * uses the [stlvacancy.com's](http://stlvacancy.com) to add additional indicators of vacancy
    * addresses issues with the Assessor's Office "vacant lot" indicator
2. Evaluate the impact of Citizens' Service Bureau data on our estimate of vacancy further. He is interested in understanding which properties attract attention of the CSB and which do not, and also model the likelihood of vacancy given CSB calls but absent other indicators of vacancy.

3. Explore the financial aspect of vacancy in St. Louis. What types of entities own properties that are vacant? Where are those entities based? To what extent are there national and regional flows of capital into St. Louis vacant properties?
