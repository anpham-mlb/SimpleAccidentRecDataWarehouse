## Purpose
Build a database for the Victorian Roads and Safety (VicR&S) Department to analyze accident details such as location, date, time and events to reduce the number of accidents in the road.

For each accident, information is stored (e.g. name, contact number, date of commencement, current branch of work) about a police officer responsible for monitoring the events, cause of the accident). In addition, to identify a specific accident, each accident is assigned a unique accident number. On the other hand, accidents can be caused by many vehicles (for example collision between two vehicles). All vehicles were owned or may not be the same as the driver at the time of the accident. Therefore, the VicR & S database stores information about the vehicles involved in the accident(i.e. car number, model, vehicle type and vehicle manufacturer), vehicle owner information (i.e. owner name, owner's address, owner's contact number) and information about the driver at the time of the accident (the driver's name, the driver's address, the driver's contact number, the driver's license number and the date the driver started the vehicle) . In addition, for each accident, the serious damage of each vehicle was recorded.

### Step 1
Build an ER diagram from collective data of accidents

### Step 2
- Create the operational database based on the E/R Diagram using SQL.
- Develop a accident star schema (figure 2).
- Create the fact and dimension tables using SQL.

## Result
From the data warehouse, users are able to know some information such as:
- The total number of accidents happening by different locations and by different lighting periods (daytime: 6AM - 5:59PM and nighttime 6PM - 5:59AM).
- The total number of accidents by each vehicle model.
- The number of vehicles involved in every accident event on different locations.
- The number of accidents taken care of different police officer branches.
