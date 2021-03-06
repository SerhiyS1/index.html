<font size="6"><b>Blog Post 9/26/2020</b></font>

Since President Donald Trump's underdog win in the 2016 election, many Americans distrust election polling [1].  This phenomenon has caused me to evaluate my own judgment of election polling and ask questions such as "Should I trust the polls?", "Are polls accurate?", and "Which polls are more accurate than others?" Thus, this week's blog post focuses on pollster quality and incorporating pollster quality into my 2020 election predicitons.  First, I will investigate FiveThirtyEight's 2016 Pollster Ratings and then I will utilize 2020 data from the best 2016 pollsters to predict this election's results.

<font size="4"><b>Part 1: Which pollsters got 2016 right? </b></font>

President Trump's win came as a shock to many, so first, I wanted to identify which pollsters most accurately predicted 2016's election.  The first step in my methodology was to gather the 2016 FiveThirtyEight pollster ratings, which I downloaded from their official GitHub.  I cleaned the data set to include the poll ID, pollster, and FiveThirtyEight's grade for the pollster, which they grade on a scale of A+ to F.  I created a bar plot, below, that allows one to viualize the variation in pollster quality for the 2016 election.  

![](/pollsterratings.png)

It is evident that there was an extensive amount of variation in pollster quality in 2016, with the most common grades being C+, B-, B, and C.  Just 6 pollsters out of 372 received an A+ rating: Monmouth University, Field Research Corporation (Field Poll), Selzer & Company, Elway Research, Ciruli Associates, and ABC News/Washington Post.  I was impressed by the pollsters that received such high marks by 538 and wanted to investigate what these pollsters were reporting for the 2020 election.


<font size="4"><b> Part 2: What are 2016 star polls predicting for the 2020 election? </b></font>

Unfortunately, the dataset I had for the 2020 polls did not include all 6 of the star polls from 2016, and I thus used 2020 polls from just Monmouth University, ABC News/Washington Post, and Selzer & Company.  Since I wanted to predict the 2020 election popular vote, I cleaned my data to include only national polls.  Additionally, I only included polls that started on or after August 1, 2020 as a proxy for polls roughly 3 months before election day.  I then created a boxplot on top of a scatterplot, below, to demonstrate what the best polls from 2016 were reporting for the 2020 election.  

![](/starpollperformance.png) 

It is clear that these three A+ pollsters from 2016 are reporting a large popular vote lead for the challenger, former Vice President Joseph R. Biden Jr.  Biden's average among these polls is <b>51.7%</b>, while Trump's average is <b>42.0%</b>, a margin difference of <b>9.7%</b>.  

<font size="4"><b>Conclusions and Sources</b></font>

There are a few notable conclusions from these visualizations.  First, there is a lot of variation in pollster quality, but that does not mean that there are not excellent polls with great methodologies. Second, utilizing the 2016 star pollsters to predict 2020's election results in quite different result than our polls-only model in class; the average of the star polls is <b>Biden 51.7%, Trump 42.0%, for a margin of 9.7%, while the model in class reports Biden 49.6%, Trump 46.9%, for a margin of 2.7%</b>.  This is likely due to the fact that my average of star polls model only includes 7 different polls while our class' polls-only model included many more polls.  Additionally, I included polls from on or after August 1 while our class' model used polls that are within 6 weeks of election day, a period in which elections may tighten up.  More data is necessary to improve my model.

<b>This week's prediction: Biden win. </b>

Thank you for reading! You can follow my election modeling journey by checking this blog each Saturday through December.

To complete this blog post, I utilized a 2020 polls dataset from the Gov 1347: Election Analytics course website and a 2016 pollster grades dataset from FiveThirtyEight (https://raw.githubusercontent.com/fivethirtyeight/data/master/pollster-ratings/2016/pollster-ratings.csv).  


[1] https://thehill.com/hilltv/what-americas-thinking/423023-a-majority-of-americans-are-skeptical-that-public-opinion-polls
