# What is Exploratory Data Analysis?

If you are someone who is interested in becoming a [Data Scientist](https://ericwarren9.github.io/2023/08/22/First-Blog-Post.html), you have probably heard the term "exploratory data analysis" a couple of times before. But what exactly does this term mean or is there a correct process of doing this analysis correctly?

According to [the National Institute of Standards and Techology](https://www.itl.nist.gov/div898/handbook/eda/section1/eda11.htm), **exploratory data analysis** is an approach or philosophy for data analysis that employs a variety of techniques (mostly graphical) to

* maximize insight into a data set;
* uncover underlying structure;
* extract important variables;
* detect outliers and anomalies;
* test underlying assumptions;
* develop parsimonious models; and
* determine optimal factor settings.

In simple terms, I would describe exploratory data analysis as the necessary first step all data scientists should use when initially getting data. This process should be looking at trends, correlations, outliers, centers (medians and/or means), and spreads (ranges and standard deviations). All models made to quantify any of these things should be fairly simple where you are not spending a ton of resources and time. This step should be helpful in determining what model you should use to answer your question(s) about the data but also if you need to further manipulate your data to get a more accurate result. For example, should I create a new variable to analyze that comes from two existing variables I wanted to examine or should I scale my variables due to a large range of values? This is our goal with exploratory data analysis. In essence, our goal is to paint a picture of what our variables are and what is the best practice for using them when doing our in-depth analysis.

To get to our goal, I believe it is important to do these simple steps.

1. Understand the purpose of the data. Ask the person who gave you the data or do some background research on how the data was collected and what its intended purpose is. This will help you understand some potential key indicators.
2. Categorize our data. Is this data numerical or character? Are there a lot of missing values in our data set? This is important to distinguish so we know best practices moving forward.
3. Identify your summary statistics. Look for the quartiles of our variables. What is the average? What is the spread? This might help us understand if we should [standardize our variables](https://www.statlect.com/fundamentals-of-statistics/linear-regression-with-standardized-variables#:~:text=A%20variable%20is%20standardized%20by,mean%20and%20unit%20standard%20deviation.) or if we should expect variables to be relatively close to each other. We should also be able to identify any potential outliers.
4. Find correlations. Do other variables resemble the variable(s) we want to examine? If so, is there a chance this could help us in our future modeling?

After doing all of this, we should have a better understanding of how our data looks and be able to brainstorm some possible appropriate models that can used to analyze our data. As said earlier, it is important to be looking at trends, correlations, outliers, centers (medians and/or means), and spreads (ranges and standard deviations). As data scientists, we should take note of anything that seems unusual as this will help us in our future endeavors with accurately modeling and representing our data. As I think there isn't a set method one should do when performing exploratory data analysis, I would recommend the steps I outlined above as these set "rules" will make the rest of analysis much easier. Articles like [this one from Shopify](https://shopify.engineering/conducting-exploratory-data-analysis) detail very similar techniques as I have outlined before. I guess if I had one major takeaway from this blog, it would be to take your time with this process as exploratory data analysis can dictate the direction and success of your analytics project. 

If you have any questions or comments, feel free to connect with me on [LinkedIn](https://www.linkedin.com/in/eric-warren-960037203/) or connect me via [email](mailto:ericwarren09@yahoo.com) and I would be happy to elaborate more on how important exploratory data analysis is and how to improve your techniques with it.
