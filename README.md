# A-case-study-project-on-bike-share-data
Analyzed dataset on how different users use bikes differently using Python. Demonstrated data handling, data profiling, data transformation and data analysis skills. Created a dashboard in Tableau using analysis results.

CASE-STUDY DOCUMENTATION

OBJECTIVE

How do annual members and casual riders use Cyclistic bikes differently?
to understand how casual riders and annual members use Cyclistic bikes differently. From these insights,
your team will design a new marketing strategy to convert casual riders into annual members.

SCENARIO

You are a junior data analyst working in the marketing analyst team at Cyclistic, a bike-share company. The director of marketing believes the company’s future success depends on maximizing the number of annual memberships. Therefore, your team wants to understand how casual riders(without annual membership) and annual members(with annual membership) use Cyclistic bikes differently. From these insights, your team will design a new marketing strategy to convert casual riders into annual members.

DATA SOURSES

data can be found at [https://divvy-tripdata.s3.amazonaws.com/index.html] this link. Data is organised on a monthly basis and we are using data for year 2021 all months. This dataset is publicly available and is reliable, cited, original. 

DATA PREPARATION

- Data Merging: originally data was distributed monthly in different datasets, then it is concatenated into a single dataset.

- Changing Datatypes: columns- started_at, ended_at converted to datetime64 datatype from object datatype.

- New Columns:
              1. ride_time[dtype = int] =  ended_at - started_at
              2. weekday[dtype = int]
              3. month[dtype = int]

-Columns Dropped: columns=['Unnamed: 0','start_lat','start_lng','end_lat','end_lng','source_file_name']


 TABLEAU DASHBOARD LINK-

#project dashboard link in Tableau

link :- https://public.tableau.com/app/profile/sachin.patel8488/viz/howcasualridersandannualmembersuseCyclisticbikesdifferently/Dashboard1

