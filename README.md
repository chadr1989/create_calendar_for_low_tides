# create_calendar_for_low_tides
I wrote this code to build calendars on google calendar but it should also work on any platform that accepts the Microsoft outlook format for calendar.<br>
The parameters give below average low tides between the hours of 8AM-9PM on weekends and US holidays and 4PM-9PM on all other days<br>
First, go to <a href="tidesandcurrents.noaa.gov">tidesandcurrents.noaa.gov</a> and select the nearest coastal station<br>
then, click 'click here for annual published tide tables'<br>
select the appropriate year<br>
select .xml under the 'format' drop down menu<br>
save the provided Jupyter notebook in the same location that the .xml file was saved<br>
download appropriate Python libraries if necessary<br>
run the code<br>
prompt will open to select the .xml file you just saved<br>
a csv file named 'Monterey_lowest_tides2021.csv' *or appripriate station,year* will be saved in the same destination folder that the .xml file and .ipynb file were saved<br>
this .csv file is formatted the same way that Microsoft Outlook formats its calendar items and will import to google calendar
