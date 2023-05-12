Cyclistic Case Study

Introduction
Cyclistic is a bike-share company based in Chicago with two types of customers. Customers whol purchase single-rid or full-day passes are know as casual riders, while those who purchase annual memberships are known as members.  Cyclistic's financial analysts have concluded that annual members are much more profitable than casual riders.  The directore of marketing believes the company's future success depends on maximizing the number of annual memberships.
Step 1:Ask
To identify potential opportunities for grownth and provide recommendations for Cyclistic bike team. Analyze historical bike trip data to identify trend.
1. How do annual members and casual riders use Cyclistic bike differently?
2. Why would casual riders buy Cyclistic annual memberships?
3. How can Cyclistic us digital media to influence casual riders to become members?
Step 2: Prepare
Cyclistic historical bike trip data is available for 12 months of the year 2022 which is publicly available.  The data is made available by Motiveate International Inc. under license. The data was downloaded and stored as .CSV file spreadsheets, which was then into a Google Cloud Storage bucket and uploaded into BigQuery for SQL exploration, cleaning, and analysis. The exploration of data determined:
1.Average trip duration casual 29 minutes and members 18 minutes.
2.The most popular day of the week for members was Wednesday and Thursday verses the most popular for casual was Saturday and Sunday.
3. There were about 212 duplicate ride_id however upon further examination it is determined that they were entirely different days and times and would not need to be addressed further.
4. There was a significal amount of NULL data in the areas of start_station_name, start_station_id, end_station_name, end_station_id, end_lat, and end_lng which would hinder the result of trying to find which region is the most popular with casual members.  However, in the analyze phase will work with what is available.
5. The ride length max of a casual member is 690 hours verses a member is about 26 hours.
6. The total number of trips 5,667,440
7. The number of trips under on minute for members was 43385 and casuals was 27924
Step 3 Cleaning of Data
Rides under a minute were removed before analyzation.
Step 4 Analyze
1.  Casual riders seem to use the bikes on the weekends for longer durations.  Perhaps charge casual riders an hourly rate which would increase revenue.
2.  Casual riders would be persuaded to purchase a membership for a package of 1 or 3 day weekend verses a annual membership.
3.  Digital media can be utilized at stations along bus and train terminals to encourage casual riders to try Cyclistic bikes which may influence them to become members.
4.  Digital media can also be utilized to offer incentives to casual riders to become members perhaps by offering a sign on bonus discount. 

