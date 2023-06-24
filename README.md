# agricultural_data

The data domain is completely artificial and generated uniquely for each student, based on real-world principles and
relationships. You will prepare, explore and model this data.
We consider (Step 1: Problem Formulation) agricultural data that has (hypothetically) been collected for a number of location
and crop types recorded over a period of years. Although the number of data points is not large, you have been asked to
investigate the relationship between various attributes and outcomes to see if there are general relationships that could be
modelled, and then used to improve or predict future crop choices and outcomes.
Some of the specific questions that you need to investigate, and some that you may choose to investigate, are presented in later
tasks.
As you have been provided (Step 2: Acquisition) with a unique set of data files just for you, you do not need to capture the data
yourself. You will have to deal with some typical issues of preparing historical data.
The data files were emailed to you as three (3) separate .csv files within a single zip file. You will need to prepare (Step 3:
Preparation) this data into a single “data_clean.csv” file and follow the requirements stated later in Task 1. 
When you complete Task 1, your clean output data should have the features described in Table 1. 

 ![1](https://github.com/HasanthaKarunachandra/agricultural_data/assets/32540627/bc2900b8-02b0-415a-9e79-bccb3cd03963)

(1) The exact type of damage and the reason for crop damage is not recorded. It might be due to external factors (disease,bugs, fires), but might correlate to temperature or rain data. Excessive hot or cold might damage crops. Extended wet
or dry periods during the growing season might stunt growth. When there is “Crop Damage” this is likely reflected in 
the yield being lower than historical trends.  
(2) The exact units of the “Yield” have not been recorded by the client but the investigation will continue without it. It
might be “bushels per acre” or a similar production metric. 

![2](https://github.com/HasanthaKarunachandra/agricultural_data/assets/32540627/7ad06998-f12c-403f-9576-31cf47865c40)



Data Notes:
• The reason for the two “env” files is that older temperature and rainfall data was recorded in degrees Fahrenheit and
inches. This is stored in data_1_env.csv and will need its values converted so that if can be combined with later values
from data_2_env.csv which already has the wanted degrees Celsius and millimetre (mm) units.

• The crop observations were stored in a separate file (data_3_crop.csv) by staff members each year (“observer”). This
data will need to be matched with the combined environment data (data_1_env.csv and data_2_env.csv files). There
should be a unique crop observation entry for each valid year and location in the “env” data, but check if this is the
case.

• It is known that some values are missing, but it is believed this only occurred accidentally when some entries were
partially duplicated. You should try to confirm this, and if it has occurred, deal with missing data appropriately.

• It is possible that some of the continuous values are outside of the sensible expected range. You need to confirm if this
has occurred or not and deal with it appropriately if needed. What is “sensible” has not been indicated so you will need
to make and record appropriate assumptions for this. 


