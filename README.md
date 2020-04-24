make sure to:
- [ ] upload original data sets
- [ ] upload analyzed excel files to show work to derive data insights
- [ ] check [github template](https://github.com/jhu-business-analytics/midterm-project-template)

# How Voter Turnout (for Older Adults) in the 2020 Election Could Be Impacted by the COVID-19 Pandemic in Maryland
It is vital that we understand the implications of the pandemic on the election to best know what measures can and should be taken to adapt voting systems to protect the most vulnerable and allow as many eligible voters to participate under the circumstances.
// TODO when done at end 
* 2-3 sentences that explain your “business question” and some high-level findings and suggestions. Tell the reader a little bit about your business question, why this is important, a high-level finding, and the future implicateions of your findings. Make this short and captivating so that the user wants to continue reading about this topic and what you’ve done. 

**Original Question: //TODO**

## Background
As the 2020 National Election approaches and the novel coronavirus continues to spread across the country, COVID-19 presents many challenges to voting efforts beyond the already existing factors. Measures to prevent the further spread of COVID-19 have led to cancelled events of all kinds- from sports seasons to campaign rallies, concerts to canvassing. To date, 16 states have already restructured or rescheduled their presidential primaries [(1)](https://www.nytimes.com/article/2020-campaign-primary-calendar-coronavirus.html).

Unlike the primary elections, however, the date of the general election is set by federal law which means that postponing it would not only be a tremendous political ordeal, but would also potentially result in social upheaval. However threatening this pandemic, we cannot let it interrupt out democratic process and disenfranchise voters. While it is still unclear how the United States will find itself in just a matter of months, we must start preparing now for what is sure to be an unprecedented and logistically challenging general election. 

In 2016, only 60% of eligible voters participated in the US presidential election [(2)](http://www.electproject.org/2016g). While total voter turnout for Maryland in the 2016 general election was 72%, voter turnout in Baltimore City was only slightly better than the national average at 62% [(3)](https://elections.maryland.gov/elections/2016/turnout/general/Official%20by%20Party%20and%20County.pdf).

Older adults and those with underlying conditions are at higher risk for severe illness as a result of COVID-19 [(4)](https://www.cdc.gov/coronavirus/2019-ncov/need-extra-precautions/people-at-higher-risk.html). This is particularly concerning when considering voter turnout because older Americans are historically much more likely to vote. In 2016, citizens 65 years and older voted at higher rates (70.9%) than 45-64 year olds (66.6%), 30-44 year olds (48.7%), and 18-29 year olds (46.1%) [(5)](https://www.census.gov/newsroom/blogs/random-samplings/2017/05/voting_in_america.html).
Maryland citizens over 65 years old are even more likely to vote  with 2016 turnout reaching 76.7% [(6)](https://elections.maryland.gov/press_room/2012_stats_general/2012_general_voter_turnout_by_age.pdf). 

In Maryland, citizens who are registered to vote can vote for the general election in one of three ways:
* Early Voting, in-person between October 22nd and 29th between 8am-8pm.
* Absentee ballot, mailed ballot by election day. 
* Election Day, in-person at assigned polling place. 
With a state-wide shelter-in-place and social distancing guidelines of keeping people 6ft apart, in-person voting will most likely decrease which places more importance on mail-in absentee ballots. We've already seen this happen in several primaries [(7)](https://www.npr.org/2020/03/16/815504537/voting-amid-coronavirus-what-you-need-to-know).


## Solution

### 2016 Presidential Election Analysis

To analyze what voting methods citizens across Maryland were more likely to use in the 2016 General Election, we will be using [Maryland's Official Turnout Statistics for the 2016 General Election in Maryland by Party and Precinct](https://github.com/CamilaCamacho/baltimore_voter_turnout/blob/master/Official%20by%20Party%20and%20Precinct.csv).
Excel file with analyzed data found [here](https://github.com/CamilaCamacho/baltimore_voter_turnout/blob/master/MD%20Vote%20Method%20Frequency%20Analysis.xlsx). 

Maryland has a total of 1,989 precincts and the number of eligible voters and turnout percentage for each precinct varies widely. The following histograms show the popularity of different methods of voting across all Maryland precincts. 

#### Frequency of Voting on Election Day
Across all precincts in Maryland, there is a wide distribution of number of votes on Election Day. For 2016, about 17% of precincts received between 800 to 1,000 votes, 48% receivied less than 800 votes, and 35% received more than 1,000 votes.
![Polls Histogram](https://github.com/CamilaCamacho/baltimore_voter_turnout/blob/master/histograms/Polls%20Histogram.png)

#### Frequency of Early Voting 
For Early Voting period of October 22nd-29th 2016, there was an average number of 440 votes collected per precinct. This right-skewed histogram shows that about 74% of precincts received less than 600 votes during Early Voting with about 28% of precincts receiving between 0 to 200 votes. This shows that Early Voting is not all that popular across Maryland. 
![Early Voting Histogram](https://github.com/CamilaCamacho/baltimore_voter_turnout/blob/master/histograms/Early%20Voting%20Histogram.png)

#### Frequency of Absentee Voting
Throughout Maryland, absentee voting was very uncommon in the 2016 election. About 90% of precincts reveived between 0 and 200 votes, only 1 precinct received more than 600 absentee ballots, and there were no precincts that reveived more than 800 absentee ballots. When we break this down further, we see a right-skewed histogram showing that 68% of precincts received less than 100 absentee ballots. 
![Absentee Histogram](https://github.com/CamilaCamacho/baltimore_voter_turnout/blob/master/histograms/Absentee%20Histogram.png)
![Detailed Absentee Histogram](https://github.com/CamilaCamacho/baltimore_voter_turnout/blob/master/histograms/Absentee%20Histogram%20(Detailed).png)

#### Geo-Map of Voter Turnout
Out of curiosity, we also wanted to look at voter turnout to provide context on our analysis. The data presented here is by county for the 2016 General Election. As can be seen, St. Mary's County and Howard County has amongst the highest rate of voter turnout. Baltimore County and Talbot County had some of the lowest.
![Voter Turnout Map](https://github.com/CamilaCamacho/baltimore_voter_turnout/blob/master/Figures/VoterTurnout.png)

### Impact of COVID-19 in Maryland
Given recent trends, it is also extremely important to place our analysis within the context of the COVID-19 pandemic. As this is a highly unprecedented time, it is likely that much of the factors involved in voter turnout will be even more impacted. Specifically, this is diffuclt for the older population, age groups above 65 years old. 

#### Geo-Map of Percent Infected by Corona Virus
At a first glance, Maryland is certainly better than many other states in terms of limiting the community-wide spread of corona virus amongst its counties. From the map, it can be noted that Queen Anne's and Talbot Counties have amongst the highest percent of cases as 04/20/2020 with the highest being about 0.4% of the total population of the county, irrespective of age, gender, or race. 
![Percent Infected Map](https://github.com/CamilaCamacho/baltimore_voter_turnout/blob/master/Figures/PercentInfected.png)

#### Geo-Map of County Risk Number
From basic logical reasoning, it can be ascertained that COVID-19 certainly impacts the older age group of people above 65 years old. To assess how COVID-19 would impact the upcoming election, we wanted to see for each county what the impact would be given its population of citizens above 65 and percent of infected population. Amongs all of Maryland, we normalized both of these value and took the product to obtain a risk metric. Here, a higher value of the risk metric illustrates a county which has higher relative number of cases and higher relative population of citizens above 65 years old. The county with the highest risk number here was Talbot County, followed by Queen Anne's County and Baltimore County. 
![Risk Map](https://github.com/CamilaCamacho/baltimore_voter_turnout/blob/master/Figures/RiskNumber.png)

#### Educational Attainment and Income in the 65 and Up Age Group
Since our main topic of exploration is "How Voter Turnout (for Older Adults) in the 2020 Election Could Be Impacted by the COVID-19 Pandemic in Maryland," we also analyzed income and education data of adults 65 and up in select Maryland counties.As seen in our Geo-Map of voter turnout, Howard County boasts the highest rate of voter turnout. To no one’s surprise, Howard County also boasts one of the highest median household incomes ($81,844) and some of the highest percentages of Bachelor’s and Graduate Degree Holders in the 65 and up age group (24.6% and 26.4%, respectively. That is over HALF the elderly population in Howard County!).

From our analysis, we found a correlation between median household income, educational attainment, and voter turnout in the 65 and up age group. Generally, as educational attainment falls, so too does median household income, and voter turnout. Thus, from our analysis, a political organization need not focus on areas like Howard county, but instead, areas like Allegany and Garrett counties, which have lower educational attainment, lower income, and lower voter turnout compared to other counties. 

Traditionally, lower household income/lower educational attainment areas are less likely to come out to vote. Although the correlation between income/educational attainment and voter turnout cannot be fully explained, educational attainment and income tend to go hand in hand. It is important to note that higher income does not necessarily cause people to vote, but rather, voting is a costly activity in terms of time, information, access to transportation, etc. In terms of education, greater educational attainment usually makes it easier for people to consume and digest political media (education usually = more informed decision).

Given the current coronavirus pandemic, the age 65 and up group voter turnout is most likely to be affected. While it is important to focus on garnering the votes of youngsters who will eventually be the leaders of the future, according to our findings, in 2016, citizens “65 years and older voted at higher rates (70.9%).” Thus, the 65 and up age group is an important focus group for any political organization.

![HSDiplomaDataVisualization](https://github.com/CamilaCamacho/baltimore_voter_turnout/blob/master/Maryland65AndUpEducationData/HSDiplomaGED.PNG)

[Link to Income Data Visualization](https://github.com/CamilaCamacho/baltimore_voter_turnout/blob/master/65AndUpIncomeDataByCounty/IncomeVisualization.JPG)

Also note that Baltimore County is somewhat of an anomaly when it comes to voter turnout. Baltimore county's voter turnouts leaves much to be desired, and yet, according to income and education data, the 65 and up group stand in the middle of the pack (compared to 65 and up groups in other counties). Perhaps Baltimore county is kind of a subset of Baltimore's mindset, in that, despite good levels of education and average household income, Baltimore county residents feel hopeless and ignored. Baltimore county has issues with incarceration and crime, so these factors may also play a role in low voter turnout.

#### How will Voter Turnout for Older Adults be Impacted by the COVID-19 Pandemic in Maryland?
Based on our analysis, we do not think voter turnout (for older adults) in areas like Howard or Montomgery county will be affected. However, we think that voter turnout in less well-to-do counties like Allegany and Garrett will fall. A few links below detail the disenfranchisement and plightof low income voters:

- https://www.theatlantic.com/politics/archive/2014/01/why-are-the-poor-and-minorities-less-likely-to-vote/282896/
- https://www.npr.org/2018/09/10/645223716/on-the-sidelines-of-democracy-exploring-why-so-many-americans-dont-vote

Often times the poor and low-educated, especially in elderly groups, feel disenfranchised or feel that their vote does not matter. It's a never-ending doom loop that persists to this day. 

With this in mind, with coronavirus affecting primary dates and voting across the country, we've explored possible ways to keep voting turnout in older adults similar to pre-coronavirus levels. Although there isn't a clear solution to this issue, mail-in-voting with increased voter engagement (which can certainly be affected by fraudulent or corrupt politicians), can be a potential solution in poorer, less-educated counties like Allegany and Garrett. While traditional voting requires time, transportation, and a whole slew of barriers to vote in person (for the elderly: mobility issues, disability, etc.), mail-in-voting is still somewhatc difficult for elderly populations, but does not require as many resources to vote. Furthermore, politicians can engage 65 and up voters by means of mail, encouraging them through flyers, ads, etc. to ensure that 65 and up voices will be heard and counted for. It is up to the politicians to make the 65 and up group feel valued and inspired to vote, particularly in counties like Allegany and Garrett, which may see even lower voter turnout this year due vto coronavirus.

## Future Suggestions
The voting system needs to change, period. Hopefully within the next few months, we will see mail-in/absentee voting become the main method of voting. Traditional voting methods have become far too corrupt and serve to block off minority and low income voters. Due to coronavirus, it is likely that the disenfranchised and low income folks, especially in the 65 and up age group, will choose not to vote in fear of coronavirus if traditional voting methods were to continue. In the next year and next few years to come, it is up to politicians to engage their most prized voting group by means of ads, mail, etc. This engagement needs to be pushed into counties like Allegany, instead of trying to win the favor of elderly voters in rich counties like Howard or Montgomery. It will be a delicate balancing act that politicians need to investigate.

In light of the coronavirus pandemic, voting methods need to change. The GOP is using traditional voting methods during this pandemic to crush and oppress voices. Voting is certainly a political game, and many Americans just don't seem to be interested in voting. In the eyes of a democractic party organization, it is clear that traditional methods of voting can be easily corrupt and prone to fraud, and can also block traditionally democratic populations (low income voters for example) from voting. Next, as a democractic organization, it would be interesting to start a community-driven grassroots campaign to not only expose GOP evils but to also encourage suppressed voices (like low income elderly) to vote. In sum, rally for other modes of voting during this pandemic, and try to engage potential voters. 

In counties like Talbot, Queen Anne's and Baltimore, which face the highest risk of coronavirus infections, we can think of voting like a long-term game. Perhaps it is too late to be focusing on the elderly populations who are at risk in these counties. But in the eyes of the democratic party, this coronavirus pandemic can be a stepping stone to cementing democratic votes down the line in future elections. Now is the time to aid the elderly, whether that be through encouraging them to stay home, providing financial relief, and through other means. The coronavirus pandemic can be used to cement seeds of influence in certain focus groups/populations, and a couple of years down the line, we could see elderly age groups voting blue if the Democrats play their cards right.

If traditional voting methods are to continue, politicians and leaders can try to increase the popularity of absentee voting, which is historically an unpopular voting method in Maryland. Yes, there are many obstacles to absentee voting as well, including your vote getting "lost," and that some Americans, particularly the elderly, feel "pride" in voting at a polling location. Fundamentally, America needs to change, and the only way a major change cna occur is if politicians spend the time and resources to make a difference.


* Now that you told us what needs to happen for your problem as a result of your analysis, how does this come into play in the next 6 months? Year? Ten years? SEE ABOVE ^
* What would you recommend happens in this industry/situation from an organizational, policy, leadership, or some other type of shift or pivot? This is similar to a conclusion, but also gives a clear call-to-action to the designated group/people who can do something about your original business question. This section should be about one paragraph. SEE ABOVE ^
