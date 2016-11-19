# Change in Turnout by Ward in Philadelphia 

This repository contains the data and analysis for the BuzzFeed News article, "[Data Shows Sharp Drop Among Black Voters In Philadelphia](https://www.buzzfeed.com/johntemplon/this-chart-shows-philadelphia-black-voters-stayed-home-costi)," published November 18, 2016.

## Data

The data for this analysis came from two sources:

- __The U.S. Census__. The [`data/census`](data/census) contains two files: `Table G001` and `Table P3` from the 2010 Census for all blocks in Philadelphia. `Table G001` contains metadata about each block, including political ward, while `Table P3` contains the counts of the population by race for each block.

- __Philadelphia Election Data__. The [`data/elections`](data/elections) contains two files with ward-by-ward voting results for the 2012 and 2016 election. You can download the latest [2016 election results](http://www.philadelphiavotes.com/en/resources-a-data/live-election-results) and the [2012 election results](http://www.philadelphiavotes.com/en/resources-a-data/ballot-box-app) on the Philadelphia City Commissioners page.

In addition, there is a JSON map of Philadelphia in [`data/maps`](data/maps).

## Analysis

The full analysis [can be found here](notebooks/philadelphia-map-and-analysis.ipynb). The "Analyze Race by Ward" section shows the code behind graph and the Pearson's r correlation presented in the article. The "Map Turnout by Ward" section generates the ward-by-ward turnout change map.

## Questions / Comments?

Please contact John Templon at john.templon@buzzfeed.com.

Looking for more from BuzzFeed News? [Click here for a list of our open-sourced projects, data, and code](https://github.com/BuzzFeedNews/everything).