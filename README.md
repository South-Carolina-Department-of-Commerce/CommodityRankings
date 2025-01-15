These rankings are for 2024 through November. (Latest data)
The state export commodity data is measured in Export Value in US $'s.
There are two ways of viewing commodity exports:
Haromonized System (HS) and NAICS
HS is usually preferred over NAICS for Commodity level data.
There are 98 commodities.
Within each commodity are many sub-level specific commodities and even sub-sub level specific.
For this excercise I only look at the top-level 98 Commodities.

Instructions for how to get reproduce:

Step 1: Access Census USA Trade, log in. 

You're now in Data Source Selection. 

Step 2: Click on State Export Data (Origin of Movement) HS.

You get prompted the screen where you select States. Manually click on each state, avoid territories and D.C. 

Step 3: Select the Timeframe

Click on Time, check the box for 2024 (Through November)

Step 4: Select Commodities

Click on Commodity. 
Unfortunately, you can't click on All Commodities. That gives you an aggregated sum. Check off on each box 01:99
Leave Country and Measure alone. 

Step 5. Download

Now click on "Report" at the top. 
Click on the green down arrow at the top. 
You get prompted with selecting to download in XML format (excel) or csv. 
Download in XML (longer process but easier)
The problem with downloading in csv format is that when you open it up, the entries, cells, the data, or whatever you want to call it gets formatted differently than you would expect. 

Step 6. Open in XML

You should get Excel to open the data. Three worksheets should appear. 
Click on the sheet that contains the data. 

Step 7. 
Clean and Reformat
The objective here is to reformat and download a csv that we can use to code.
The first row of the excel sheet should contain the column headers, "State", "01 Live Animal..", "02..", etc.
In other words delete, copy, or paste, so that the table looks the way as described.

Step 8. Download as CSV

Step 9. Use the python script and run the code.

Here, edit the file path so that it matches your directory. 
Also edit the path at the end of the script so it downloads on your computer.

