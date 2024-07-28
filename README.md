# Concurrency Tracker

##### Dashboard Link : (Since I don’t have a Microsoft company/business account I’m unable to host the dashboard so attaching an offline file here in GitHub). 

## Problem Statement

Since we are in a very early stage at JioCinema we just want to keep our self prepare for the volume of viewers watching a big event like world cup so we (Junior analyst) were told to keep a track on concurrency for T20 WC 2024 Final - IND v SA match and track concurrency of same since me and my colleague both of us were gathering various data like concurrency after every 10 mins / after particular instance like wicket, six, half century, last 3 overs, while trophy handover and many more such key instances.

So I decided to make use of this data and create some insights for the same.

## Steps followed

📅 Requirement Gathering - Discuss with manager and other team members what all data points should we capture and process further accordingly.

📊 Data Collection - Tracked whole match concurrency after every over / any instance like wicket, six, half century / DRS and many more we have maintained an excel sheet for same where we captured 4 parameters i.e time, over, instance & concurrency.

🔄 Data Transformation: Firstly I fixed the instances where there were same instance but the text written was in different format like for example for 4 runs it was written in multiple formats 
1st - 4 runs
2nd - four runs
3rd - four
4th - 4 runs - Virat Kolhi

So making such an instance as same unique instance is IMP so all this instance got replaced by simply 4 runs.
The data was captured in lakhs in data source so reading big numbers in lakhs doesnt looks good so converted all numbers into millions and added a prefix ‘M’ to it.

🎨 Visualization Blueprint - Created a blueprint of dashboard where check & tested whether all our required KPI’s and other features will adjust or not.

⚙️ Interactivity Features - Integrated 4 KPS’s concurrency, over, time  & instance, used line chart so that it will give an overall preview of an innings, detailed table with time, concurrency & detail instance.

## Insights

- There are 4 KPI’s in this dashboard, firstly concurrency (number of people watching a live event at a time), over, time & instance which will help us to gain insights accordingly and all KPI’s are linked with charts & tables.
- Average live match concurrency was 39.5 M and peak concurrency was 53 M compared to IPL’24 final average is (42.7% ⬆️) higher and peak is (43.6% ⬆️)
- Considering a pattern the number of viewers suddenly increases after a wicket or while a batsman hitting sixes & fours constantly, while a half-century / century so this will help the platform to make plans & strategies accordingly.


## Dashboard Snippets

#### Dashboard 1 - WC Final 1st Inning
![Dashboard screenchot 1](https://github.com/user-attachments/assets/3474c86e-c3fb-4d78-9ee8-128f30ee6a7e)

#### Dashboard 2 - WC Final 2nd Inning
![Dashboard screenshot 2](https://github.com/user-attachments/assets/4da492f4-fe58-4ac0-b606-63799b4d0893)

#### Table View
![Table View Screenshot 3](https://github.com/user-attachments/assets/dc8bc8d3-e9f3-4ec2-83c3-6fadeac4cc00)
