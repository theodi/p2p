---
layout: default
title: Methodology
link: /methodology/
menu: top
---

## Data

We received the data in its raw format (the loan book) from each of the three P2P lenders. All R code is available on [GitHub](https://github.com/theodi). As a prerequisite for merging we harmonised the data, for example, by changing the unit for interest rates (percentage points instead of units).

Further, we had to exclude a total of 20,916 observations, that is loan parts. Given the large amount of loan parts this represents only 0.15% of the sample. Most of them were omitted due to missing postcodes. In fact, some of the P2P lenders do not validate UK postcodes, which meant we also excluded some foreign postcodes. We also excluded postcodes of the Isle of Man (IM), the British Forces (BF), Guernsey (GY) and Jersey (JE) as these areas are not part of the United Kingdom.

Notice that the number of lenders and borrowers are *conservative* estimates. This is because, we use loan ID and lender's postcode as a proxy for unique agents in the P2P market. There might be cases where two different lenders live in the same postcode or where the same person or company took out more than one loan. Especially the latter, however, is extremely unlikely because of the short time period of our sample.

## <span id="weights">Weights</span>

To calculate regional or area statistics, which are not counts or sums, we have to use a **weighed average**. The reason for this is the unequal number of loan parts per loan. If we were to calculate a mean over data with the loan part at its lowest unit (which we need for the flows), the statistics would be dominated by those loans which appear most often, i.e. have many loan parts. Weighting adjusts for this bias.

The weights are derived in a standard fashion: taking the inverse of the number of loan parts per loan and adjusting them to a mean of 1. The weights are well-behaved with a skewed distribution towards small weights because of loans that are highly syndicated. 

### <span id="statistics">The mean and median in statistics</span>

You may have heard the old *bon mot*: “Bill Gates walks into a bar. On average everyone is a millionaire.” In fact, this would even work with a football stadium. (Do the math: His wealth is reported at $72.7 billion for 2013.)

The mean, colloquially known as the average, is not robust against outliers. Values which are a lot larger or smaller can seriously distort the mean. This is a problem because often we are interested in the **typical value**. The median is often preferred with financial data, for example income in the UK. Most people earn something between £20,000 and £40,000 per year, so we would consider this the typical value. However, some very successful people such as Wayne Rooney have an income which has one or two more zeros – the mean is skewed upwards unlike the median.

**What is the median?** It is the value "in the middle". Imagine you know everyone's income, sort it by size and then count until you are half way. The corresponding value is the median.

Do not use this knowledge for the dark side. You may be tempted to suddenly report the median value, for example if you had three grades 15%, 80% and 82%. The average (median) here is 80%, which sounds a lot better than the usually reported mean of 59%. 
