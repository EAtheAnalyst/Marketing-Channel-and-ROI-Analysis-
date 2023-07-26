# Marketing Channel and ROI Analysis 
In today's competitive business landscape, understanding customers' behavior and optimizing customer acquisition strategies are crucial for sustainable growth. This data analysis project aims to uncover valuable insights that can inform decision-making and improve business strategies.
### Overview of the Dataset

In this step, I will start by summarizing the dataset, including its size, column names, and any missing values. I will calculate basic statistics to gain an understanding of the dataset's overall characteristics

The first five rows of the dataset

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/ff929500-4b73-43d7-805e-9e8eb17e8a11/Untitled.png)

After reading and loading the dataset, I computed basic statistics for the numeric columns: 'cost', 'conversion_rate', and 'revenue'. These basic statistics give us a preliminary understanding of the dataset's characteristics and serve as a starting point for further exploration and analysis

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/e4b4eb96-fbb1-40a7-b747-78f3da705851/Untitled.png)

### **Distribution of Numeric Variables**

I examined the distributions of numeric variables, such as 'cost', and 'revenue'. By visualizing these distributions, I can determine their shapes, ranges, and identify any outlier

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/92d46c0d-11b6-4118-96c9-37645c893dad/Untitled.png)

We can see that the 'cost' variable contains 4 unique values and has a relatively balanced distribution around an average value of 200, with moderate variability.

As for the 'revenue' variable, it has been categorized into 11 bins. From it's histogram, we can conclude that this variable has a relatively narrow range and moderate variability (most observations clustered around the mean).

### **Distribution of Categorical Variables**

To understand the distribution of the categorical variable 'channel', I created a visual representation, such as bar chart. This allowed me to observe the proportions of customers acquired through different channels, identify the most common and least common channels, and assess the balance of the data

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/b7c2551b-60ee-46a4-801f-1f7722bdfc96/Untitled.png)

The counts for each channel appear to be relatively close to each other. This suggests that the customer acquisition efforts were distributed somewhat evenly across these channels.

### Grouping and Aggregating Data

Aggregating the data allows us to calculate summary statistics and gain insights into the average performance of different groups.

I aggregated the data by the acquisition channel to analyze the performance of each channel. For example I calculated the average 'cost', 'conversion_rate', and 'revenue' for each channel to understand which channels are most effective.

1. Average Cost per Channel

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/d87d7ebe-a51f-4333-911c-5f338cf65fd6/Untitled.png)

From this analysis, I observe that paid advertising has the highest average cost. On the other hand, social media, email marketing, and referrals have relatively lower average costs.

1. Average Conversation Rate Per Channel

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/60f3b8bb-2ee1-4833-98d7-d3135d58018e/Untitled.png)

Social media has the highest average conversion rate, indicating that it may be a more successful channel for acquiring customers who convert into revenue. Referral also has a relatively high conversion rate. Paid advertising and email marketing have the lowest average conversion rates, implying that they may require further optimization or targeting strategies to improve conversion rates.

1. Average Revenue Per Channel

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/c96593d6-49bc-4504-a143-a28e1657336a/Untitled.png)

The aggregation result suggests that each channel plays a significant role in generating revenue, with email marketing being the highest contributor. It implies that allocating resources and focusing efforts on these channels may be beneficial for maximizing revenue generation.

### Return on Investment (ROI)

Return on Investment (ROI) is a financial metric used to evaluate the profitability and efficiency of an investment. It measures the return or gain generated from an investment relative to its cost.

I created a new column ROI using 

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/dd2e4c61-fd97-4781-ba68-2c55000fd8ae/Untitled.png)

### ROI by Channel Analysis

Now I performed ROI by Channel Analysis which will allow me to assess the profitability of investments made through different acquisition channels.

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/b9945d5f-a7a8-438c-8615-2f4b90474c5f/Untitled.png)

Based on the analysis, email marketing appears to be the most effective channel in terms of generating returns, followed by referral and social media. Paid advertising, on the other hand, seems to have a lower ROI compared to the other channels.

### ROI and Other Variables Analysis

Performing ROI and other variables analysis can provide valuable insights into the relationship between profitability and various factors such as conversion rates, costs, and revenue

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/e5305bf5-70ca-478f-8bd1-752082b159ae/Untitled.png)

The correlation matrix suggests that cost and revenue have the strongest relationships with ROI. Higher costs are associated with lower ROI, while higher revenue is associated with higher ROI. The conversion rate alone does not show a significant correlation with ROI.
