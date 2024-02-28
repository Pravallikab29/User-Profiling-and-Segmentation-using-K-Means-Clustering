# User-Profiling-and-Segmentation-using-K-Means-Clustering

User profiling refers to creating detailed profiles that represent the behaviours and preferences of users, and segmentation divides the user base into distinct groups with common characteristics, making it easier to target specific segments with personalized marketing, products, or services.

All the columns in the dataset:

- User ID: Unique identifier for each user.
- Age: Age range of the user.
- Gender: Gender of the user.
- Location: User’s location type (Urban, Suburban, Rural).
- Language: Primary language of the user.
- Education Level: Highest education level achieved.
- Likes and Reactions: Number of likes and reactions a user has made.
- Followed Accounts: Number of accounts a user follows.
- Device Usage: Primary device used for accessing the platform (Mobile, Desktop, Tablet).
- Time Spent Online (hrs/weekday): Average hours spent online on weekdays.
- Time Spent Online (hrs/weekend): Average hours spent online on weekends.
- Click-Through Rates (CTR): The percentage of ad impressions that lead to clicks.
- Conversion Rates: The percentage of clicks that lead to conversions/actions.
- Ad Interaction Time (sec): Average time spent interacting with ads in seconds.
- Income Level: User’s income level.
- Top Interests: Primary interests of the user.

Segmenting users into distinct groups for targeted ad campaigns. Segmentation can be based on various criteria, such as:

- Demographics: Age, Gender, Income Level, Education Level
- Behavioural: Time Spent Online, Likes and Reactions, CTR, Conversion Rates 
- Interests: Aligning ad content with the top interests identified

To implement user profiling and segmentation, can apply clustering techniques or develop personas based on the combination of these attributes. This approach enables the creation of more personalized and effective ad campaigns, ultimately enhancing user engagement and conversion rates.

Selecting a subset of features that could be most indicative of user preferences and behaviour for segmentation and apply a clustering algorithm to create user segments

Based on the cluster analysis, can summarize and naming the segments as

* Cluster 0 – “Weekend Warriors”: High weekend online activity, moderate likes and reactions, predominantly male, age group 25-34, income level 80k-100k.

* Cluster 1 – “Engaged Professionals”: Balanced online activity, high likes and reactions, predominantly male, age group 25-34, high income (100k+).

* Cluster 2 – “Low-Key Users”: Moderate to high weekend online activity, moderate likes and reactions, predominantly male, age group 25-34, income level 60k-80k, lower CTR.

* Cluster 3 – “Active Explorers”: High overall online activity, lower likes and reactions, predominantly female, age group 25-34, income level 60k-80k.

* Cluster 4 – “Budget Browsers”: Moderate online activity, lowest likes and reactions, predominantly female, age group 25-34, lowest income level (0-20k), lower CTR.

The chart is useful for marketers to understand the behaviour of different user segments and tailor their advertising strategies accordingly.

For example, ads targeting the “Weekend Warriors” could be scheduled for the weekend when they are most active, while “Engaged Professionals” might respond better to ads that are spread evenly throughout the week.
