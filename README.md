﻿# Project-Analyzing_Electric_Vehicle_Charging_Habits
## Overview
As electronic vehicles (EVs) become more popular, there is an increasing need for access to charging stations, also known as ports. To that end, many modern apartment buildings have begun retrofitting their parking garages to include shared charging stations. A charging station is shared if it is accessible by anyone in the building.

With increasing demand comes competition for these ports — nothing is more frustrating than coming home to find no charging stations available! In this project, you will use a dataset to help apartment building managers better understand their tenants’ EV charging habits.

### `charging_sessions`
- `garage_id` - Identifier for the garage/building  
- `user_id` - Identifier for the individual user  
- `user_type` - Indicating whether the station is `Shared` or `Private`  
- `start_plugin` - The date and time the session started   
- `start_plugin_hour` - The hour (in military time) that the session started   
- `end_plugout` - The date and time the session ended   
- `end_plugout_hour` - The hour (in military time) that the session ended   
- `duration_hours` - The length of the session, in hours  
- `el_kwh` - Amount of electricity used (in Kilowatt hours)  
- `month_plugin` -  The month that the session started   
- `weekdays_plugin` - The day of the week that the session started  



## Goal
Based on the given data, the goal is to help apartment building managers by analyze their tenants’ EV charging habits using PostgreSQL.

## Tasks
- What is the number unique users per garage?
- What day in the week has the most popular shared start times?
- How long is the charging duration of shared users?
