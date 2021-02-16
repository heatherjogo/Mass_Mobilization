**Columns included in feature set:**

|Feature|Type|Description|
|---|---|---|
|protestnumber|int|Number of protests that year in specific country|
|protesterviolence|int(binary)|Indicates whether protester enacted violence|
|pop_total|float|Population of country where protest takes place|
|pop_density|float|Population density of country where protest takes place|
|prosperity_2020|float|Prosperity index of country the year protest takes place|
|region_Africa|int (binary)|Country is in Africa|
|region_Asia|int (binary)|Country is in Asia|
|region_Central America|int  (binary)|Country is in Central America|
|region_Europe|int (binary)|Country is in Europe|
|region_MENA|int (binary)|Country is in the Middle East/North Africa|
|region_North America|int (binary)|Country is in North America|
|region_Oceania|int (binary)|Country is in Oceania|
|region_South America|int (binary)|Country is in South America|
|protest_size_category_Less than 50|int (binary)|Number of participants <50|
|protest_size_category_50-99|int (binary)|50 - 99 participants|
|protest_size_category_100-999|int (binary)|100 - 999 participants|
|protest_size_category_1,000-4,999|int (binary)|1,000 - 4,999 participants|
|protest_size_category_5,000-9,999|int (binary)|5,000 - 9,999 participants|
|protest_size_category_10,000-100,000|int (binary)|10,000 - 100,000 participants|
|protest_size_category_Over 100,000|int (binary)|Number of participants >100,000|
|protester_id_type_civil_human_rights|int (binary)|Indicates participants are civil/human rights group|  
|protester_id_type_ethnic_group|int (binary)|Indicates participants are ethnic group|
|protester_id_type_locals_residents|int(binary)|Indicates participants are local residents|
|protester_id_type_pensioners_retirees|int (binary)|Indicates participants are pensioner/retirees|
|protester_id_type_prisoners|int (binary)|Indicates participants are prisoners|
|protester_id_type_protestors_generic|int (binary)|Indicates participants are generic group|
|protester_id_type_religious_group|int (binary)|Indicates participants are from religious group|    
|protester_id_type_soldiers_veterans|int (binary)|Indicates participants are soldiers/veterans|
|protester_id_type_students_youth|int (binary)|Indicates participants are students/youth|
|protester_id_type_victims_families|int (binary)|Indicates participants are families of victims|
|protester_id_type_women|int (binary)|Indicates participants are primarily groups of women|
|protester_id_type_workers_unions|int (binary)|Indicates participants are union members or workers|
|labor_wage_dispute|int( binary)|Protest motivation is labor & wage disputes|
|land_farm_issue|int (binary)|Protest motivation is land and farming conflict|
|police_brutality|int (binary)|Protest motivation is police brutality|
|political_behavior_process|int (binary)|Protest motivation is political behavior or process|
|price increases_tax_policy|int (binary)|Protest motivation is tax increase/tax policy|
|removal_of_politician|int (binary)|Protest motivation is removal of politician(s)|
|social_restrictions|int (binary)|Protest motivation associated with social restrictions|

**Other columns in original dataset that were not included in our final model:**

|Feature|Type|Description|
|---|---|---|
|id|int|Unique protest id number|
|country|object|Country of protest|
|ccode|int|Unique code for country|
|location|object|Description of where protest takes place within country|
|sources|object|Media outlets that reported on protest|
|notes|object|Description of protest|
|participants_number|int|Estimated number of participants|
|start_date|object|Recorded start date of protest|
|end_date|object|Recorded end date of protest|

**Columns included as target variables:**

|Target|Type|Description|
|---|---|---|
|accomodation|int (binary)|State response includes accommodation of protester demands|
|arrests|int (binary)|State response includes arrests of protesters|
|beatings|int (binary)|State response includes beating protesters|
|crowddispersal|int (binary)|State response includes crowd dispersal|
|ignore|int (binary)|State ignores protesters and protest demands|
|killings|int (binary)|State response includes killing protesters|
|shootings|int( binary)|State response includes shooting protesters|
|violent_response|int (binary)|State response includes one or more violent response (beatings, shootings, killings)|
