# The U.S. Election throughout History


## Overview
This is a final project of WPI's 2016 Fall class CS573 Data Visualization.

In this project, we attempt to show the evolution of the two-party system across the country, since 1920.


## URL
We’ve heard much from the media of Election 2016, but what does the data say, about the US elections over the history? [Join us](https://ViennaChen.github.io/WPI_DV_Final_Project/index.html) to explore the data stories behind all things election! 


## Demo
We create a two minute screen-cast with narration showing a demo of your visualization. Please find viz_demo_record in this repository.


## Description
- Demo Wrap-up

  * Firstly, with the red or blue dots on the timeline, we could quickly and easily figure out the winning party of each election. With the detailed # of votes and proportional stacked bar underneath, it could help us have a more quantitative view. That’s the national level understanding.
  * Then, we could go a step further to look at the states, a hue US map gives a straightforward feeling of how “red” or “blue” (or voting for other party, like in 1924, 1948 and 1968) a state is. Besides, when mouse over a state, its name, # of electoral votes (EV) and % of votes among parties can all be checked in the tooltip. Moreover, by clicking on the state, we could find out how it contributes to the final EV, as the relevant “state block” would obviously pop out in the EV stack bar.
  * As we know, on the 2016 Election Day, some battleground states came up with unexpected results. To catch such shift, we prepare the cartogram on the right. By looking back at each state’s voting results of two consequence elections, we could see how its political opinion swings. This, together with the last bulletin point, is the state level picture.
  * What’s more, there are always people who are interested to see more beyond the electoral result facts, like the historical as well as financial background at the certain time to help them digest the electoral results. Also, we do feel it is beneficial to provide such information. So by providing key events happened before the election (like economy had been in recession before 1992, while was recovered when 1996 election came), the media endorsement for party as well as the annual GDP and unemployment rate, we hope these in addition to the result data, could stimulate people’s thoughts to dig the possible correlation between the results and some factors.

- Data

  * [Dave Leip's Atlas of U.S. Presidential Elections](http://uselectionatlas.org/), which is our main data source that includes the voting statistics for every election by state level
  * [American Presidency Project: Presidential Election Data](http://www.presidency.ucsb.edu/elections.php), from which we grabbed the GDP data
  * [Labor Force Statistics from the Current Population Survey](http://data.bls.gov/pdq/SurveyOutputServlet),from which we obtained the unemployment rate data
  * [Newspaper presidential endorsements](http://noahveltman.com/endorsements/), where we excerpted the endorsement of top 10 US newspapers (by circulation)


- Code Structure

Generally speaking, `Utils` includes the interaction code and `Chart` includes all the static charts; with `run()` function, they could be connected and executed together.

For the detailed actions and charts involved in this project, please find the process book and the code for reference.


- Library

`D3.js` is the only library we leveraged for this project.


## Reference
- [There Are Many Ways to Map Election Results. We’ve Tried Most of Them. - by NYTimes](http://www.nytimes.com/interactive/2016/11/01/upshot/many-ways-to-map-election-results.html?_r=0)
- [LIVE RESULTS AND MAPS Election Results 2016](http://graphics.wsj.com/elections/2016/results/)
- [42 States Shifted to the Right in 2016](http://www.nytimes.com/interactive/2016/11/09/us/elections/states-shift.html?_r=0)
- [How Trump Can Influence Climate Change](http://www.nytimes.com/interactive/2016/12/08/us/trump-climate-change.html?smid=tw-nytimes&smtyp=cur&_r=1)
- [Simple D3JS Dashboard](http://bl.ocks.org/diethardsteiner/3287802)
