# Business Analyst-Case-Study

# Table of Contents

1. [Company Overview](README.md#Company-Overview)
2. [Project Objective](README.md#business-task)
3. [Scenario](README.md#scenario)
4. [Processing and Cleaning](README.md#processing-and-cleaning)
5. [Analysis and Viz](README.md#analysis-and-viz)
6. [Observations](README.md#observations)
 
# Company Overview

In 2016, Cyclistic launched a successful bike-share offering. Since then, the program has grown to a fleet of 5,824 bicycles that
are geotracked and locked into a network of 692 stations across Chicago. The bikes can be unlocked from one station and
returned to any other station in the system anytime.

Until now, Cyclistic’s marketing strategy relied on building general awareness and appealing to broad consumer segments.
One approach that helped make these things possible was the flexibility of its pricing plans: single-ride passes, full-day passes,
and annual memberships. Customers who purchase single-ride or full-day passes are referred to as casual riders. Customers
who purchase annual memberships are Cyclistic members.

Cyclistic’s finance analysts have concluded that annual members are much more profitable than casual riders. Although the
pricing flexibility helps Cyclistic attract more customers, Moreno believes that maximizing the number of annual members will
be key to future growth. Rather than creating a marketing campaign that targets all-new customers, Moreno believes there is a
very good chance to convert casual riders into members. She notes that casual riders are already aware of the Cyclistic
program and have chosen Cyclistic for their mobility needs.

Moreno has set a clear goal: Design marketing strategies aimed at converting casual riders into annual members. In order to
do that, however, the marketing analyst team needs to better understand how annual members and casual riders differ, why
casual riders would buy a membership, and how digital media could affect their marketing tactics. Moreno and her team are
interested in analyzing the Cyclistic historical bike trip data to identify trends.

# Project Objective

Cyclistic offers two service models: "casual" riders who purchase individual passes and "member" riders who subscribe annually. The company operates in Chicago and boasts a fleet of approximately 6000 bicycles across 700 stations.

The primary objective for future growth and long-term success lies in maximizing the number of annual members, which ensures financial stability and promotes customer retention. By uncovering valuable insights, effective marketing strategies can be developed to successfully convert casual riders into loyal annual members.

# Scenario
As a junior data analyst within the marketing analysis team at Cyclistic, a bike-share company in Chicago, I have assumed the responsibility of delving into the usage patterns of casual riders and annual members. The director of marketing firmly believes that the company's future triumph hinges upon maximizing the count of annual memberships. Consequently, our team is committed to comprehending the distinctions in Cyclistic bike usage between these two rider categories.

Our ultimate aim is to formulate a fresh marketing strategy that effectively converts casual riders into loyal annual members. However, before we can proceed, it is crucial to obtain approval from Cyclistic executives. To accomplish this, our recommendations must be supported by compelling data insights and presented through professional data visualizations.

# Ask
Three questions will guide the future marketing program:
1. How do annual members and casual riders use Cyclistic bikes differently?
2. Why would casual riders buy Cyclistic annual memberships?
3. How can Cyclistic use digital media to influence casual riders to become members?

# Prepare
I will utilize Cyclistic's historical trip data from Jan 2022 to Dec 2022, which is accessible for download from divvy_tripdata. The dataset has been provided by Motivate International Inc. under a specific license agreement.

This publicly available data allows for analysis and identification of trends regarding the usage of Cyclistic bikes by various customer types. However, it is important to note that data privacy concerns prevent the usage of personally identifiable information of riders. Consequently, we cannot establish connections between pass purchases and credit card numbers to determine if casual riders reside in the Cyclistic service area or if they have bought multiple single passes.
# Clean and Process Data

**The cleaning process involved:**

- Identifying missing start and end station names using the following query.

- Verifying other columns using the following query.

- Identifying negative and zero ride duration values using the following query.

**Data Snippet**
This is what the data looks like. (Pre Cleaning)
![image](https://github.com/RefikAB/Cyclistic-Case-Study/blob/main/Rider%20Data%20for%20Cleaning.png)



# Observations
1. How do annual members and casual riders use Cyclistic bikes differently?
A common observation is that casual riders are using the bike rentals for leisure and tourism purposes while annual members use it predominantly for commuting purposes.
![image](https://raw.githubusercontent.com/RefikAB/Cyclistic-Case-Study/main/HourlybarGraph.PNG)

In the following graph, it shows that annual members tend to take shorter - duration bike rides and casual riders tend to use bikes for slightly longer while traveling less distance. Because of this we can infer that annual members use the bikes to commute to and from work as well as using bikes as an alternative to driving.
![image](https://raw.githubusercontent.com/RefikAB/Cyclistic-Case-Study/main/duration%26distance.PNG)

![image](https://github.com/RefikAB/Cyclistic-Case-Study/blob/main/member%26casualTrends.png)
![image](https://raw.githubusercontent.com/RefikAB/Cyclistic-Case-Study/main/seasonBarGraph.PNG)

**Next Steps**
Moving forward, there are some things I think Cyclystic should do if they want to convert casual riders into annual members.

- Direct marketing efforts toward engaging users during the winter months.
- Encourage more community building events (i.e. group rides) during weekdays to engage those who have historically only ridden on the weekends.
- Expand geographical limits of the fleet to include more neighborhoods in the surrounding downtown area.

# Plan of Action & Recommendations
Now that  the disparities between casual and member riders have been recognized and tailored, marketing strategies can be devised to effectively convert casual riders into members.

- **Timing of Marketing Campaigns:** Targeted marketing campaigns can be scheduled during the spring and summer seasons, focusing on tourist and recreational locations that are popular among casual riders.
  
- **Seasonal and Weekend Memberships:** Recognizing that casual riders are most active on weekends and during the summer and spring, offering seasonal or weekend-only memberships can cater to their specific preferences and increase their likelihood of becoming members.
  
- **Promoting Longer Rides:** Since casual riders tend to use their bikes for longer durations compared to members, incentivizing them with discounts for longer rides can serve as a powerful motivator. Additionally, this approach may also encourage existing members to extend their riding durations, further enhancing their engagement with the platform.
