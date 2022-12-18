# CustomerSegmentation
Analysis for Customer Segmentation, with EDA on a data set to determine what segments there are. Using algorithm K-Means Clustering using RFM (Recency, Frequency, Monetary)
# Customer Segmentation For Airlines
## Project Description
In this project we will make a customer segmentation for airlines company. Customer segmentation is a method of dividing customers into groups or clusters on the basis of common characteristics.
## The Need of Customer Segmentation
1. Help to identify the most potential customers,
2. Help managers to easily communicate with a targetted group of the audience,
3. Improves the quality of service, loyalty, and retention,
4. Improve customer relationship via better understanding needs of segments,
5. Provides opportunities for upselling and cross-selling,
6. Helps in identifying new products that customers could be interested in.
## Business Understanding
- Problem : Airlines company want to divide a broad target market of customer into smaller, and similar groups and design the marketing strategy for each group.
- Goals : Find the best marketing strategy for each groups
- Objective : Customer Segmentation
## Data Describing
- member_no : ID Member
- ffp_date : Frequent Flyer Program Join Date
- first_flight_date : Frist Flight Date
- gender : Gender
- ffp_tier : Tier of Frequent Flyer Program
- work_city : City
- work_province : Province
- work_country : Country
- age : Customer Age
- load_time : The date data was retrieved
- flight_count : Customer flight count
- bp_sum : Flight plan
- sum_yr_1 : Fare revenue
- sum_yr_2 : Votes prices
- seg_km_sum : Total disctance (km) traveled
- last_flight_date : Last flight date
- last_to_end : Distance of the last flight to the last airline company
- avg_interval : Averange time distance
- max_interval : Maximum time intervals
- exchange_count :Exchange amount
- avg_discount : Averange discount
- points_sum : Customer point
- point_notflight : Not used customer point There is 62988 data on dataset, with 15 numerical data, and 8 categorical data
## Profiling
- Platinum : This profile is for cluster 3 with new membership, high fligh distance, and high flight count
- Gold : This profile is for cluster 0 with new membership, moderate flight distance, and moderate flight count
- Silver: This profile is for cluster 1 with new membership, moderate flight distance, and moderate flight count
- Bronze : This profile is for cluster 2 with old membership, low flight distance, and low flight count
## Action Tip
- Platinum : Give customer more point benefits, voucher, or program such as to give a big discount when the customer reach some distance. We can use this group to trial on a new promotion.
- Gold : This group is group the secound most praticipants. We have to build more brand awarness to this group. Such as give a free trials services in term of some condition.
- Silver : This group is the group with the most number of participants, that's why we have to more focus to this group. We have to give more offers such as cashback or point that make the customer have a feeling or a rush to use the offers again in the airlines.
- Bronze : This group we should maintain communication, and give a promotion that such as discount or holiday voucher to get the customers back to use Airlines
