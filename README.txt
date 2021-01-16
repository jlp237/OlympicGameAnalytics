Data structure of the csv files. 

athlets.csv

features:  id,name,nation,date_of_birth,sex

Data Types: 

id: int
name: String
nation: String
date_of_birth: String(DD/MM/YYYY)
sex: String

Data Range: 

id: [1:82]


sport_events.csv

features : year,athlete_id,round,rank,time_in_seconds,speedkmh

Data Types: 

year: int (YYYY)
athlete_id: int
round: String
rank: int
time_in_seconds: float
speedkmh: float


Data Range: 

year: [2000:2016]
athlete_id: [1:82]
rank: [0:12] 
time_in_seconds: [1.429:11.805]
speedkmh: [10.030:71.273]

Notes: 

Rank: 0 = Disqualified 