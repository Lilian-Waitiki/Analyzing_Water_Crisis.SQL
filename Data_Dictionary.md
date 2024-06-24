<br>The tables used in this analysis are:
<br>1. The `employee` table that contains the following columns:
<br>- `assigned_employee_id`: Unique ID assigned to each employee.
<br>- `employee_name`: Name of the employee. 
<br>- `phone_number`: Contact number of the employee. 
<br>- `email`: Email address of the employee. 
<br>- `address`: Residential address of the employee.
<br>- `town_name`: Name of the town where the employee resides. 
<br>- `province_name`:Name of the province where the employee resides.
<br>- `position`: Position or job title of the employee

<br>2. The `visits` table that contains the following columns;
<br>- `record_id` Unique ID assigned to each visit
<br>- `location_id`: ID of the location visited.
<br>- `source_id`: ID of the water source visited. 
<br>- `time_of_record`: Date and time of the visit.
<br>- `visit_count`: Number of visits made to this location.
<br>- `time_in_queue`: Time spent by people waiting for water in a queue at the location.
<br>- `assigned_employee_id`: ID of the employee who visited the location.

<br>3. The `location` table that contains the following columns;
<br>`location_id`: Unique ID assigned to each location
<br>`address`: Address of the location.
<br>`province_name`:Name of the province where the location is situated.
<br>`town_name`: Name of the town where the location is situated

<br>4. The `water_source`: table that contains the following columns;
<br>-`source_id`: Unique ID assigned to each water source. INT
<br>-`type_of_water_source`: Type or category of the water source. Can be: tap_in_home, tap_in_home_broken, well, shared_tap, river.
<br>-`Number_of_people_served`: Number of people served by this water source.
