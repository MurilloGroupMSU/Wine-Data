Sorry, there is *no* dataset here! I hope you are not disappointed.... 

I do hope to get something here soon. For now, I'll tell you this summary. In the attached paper, a statistical analysis of Grange wines is carried out. The analysis discussed in the paper is based on a previous analysis of Bordeaux wines (see [here](http://www.liquidasset.com/orley.htm) and the attached paper). In the Bordeaux study they found that the log of the price was linearly related to wine age, temperature during growing season and two measures of rainfall: 

log(price) = c1xage + c2xtemp + c3xrain(prior) - c4xrain(during).

Those two measures are interesting: price scales with dryness _during_ the growing season but wetness _prior_ to the growing season. So, if you have a good weather prediction model, here is the model you need to know which wines to invest in. The same idea is applied to Grange wines to find a similar result. Comparisons of the resulting regressions are made between the two regions, suggesting that specific weather patterns are indicative of the world's best wines.

Both of these papers are interesting from a wine and regression perspective, but I suspect the data used to find the correlations will never be available. Nevertheless, from a data science point of view it is interesting to see what they did and compare with the studies that do provide data (such as the Portuguese and Italian datasets).

Meanwhile, you can examine Grange prices [here](https://www.wickman.net.au/Grange_Prices.aspx); get me a case while you are at it?
