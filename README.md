# create_calendar_for_low_tides
I wrote this code to build calendars on google calendar but it should also work on any platform that accepts the Microsoft outlook format for calendar./n
First, go to tidesandcurrents.noaa.gov and select the nearest coastal station/n
then, click 'click here for annual published tide tables'
select the appropriate year
select .xml under the 'format' drop down menu
save file as 'mry_tides_annual2021.xml' with the appropiate year
*or instead name the file whatever you want and tweak the code to fit your filename
create a Jupyter notebook in the same location that the .xml file was saved
copy the code
you will need to update the tides_year variable to match the year
run the code
a csv file named 'google_cal_tides2021.csv' *or appripriate year* will be saved in the same destination folder that the .xml file and .ipynb file were saved
this .csv file is formatted the same way that Microsoft Outlook formats its calendar items and will import to google calendar
