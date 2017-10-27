# ITMD465FinalProject
# Application Description
## What it does
This is a basic data analysis application, showing the amount of crimes in Chicago by year. There are two graphs on separate pages, the index page is a pie chart and the page2 html file is a bar graph. 

Since the original csv file was over 1 GB, and contained more than six million lines, displaying it would use a ton of resources.
## How it works
This uses a personally made comma separated values document in order to correctly visualize the data. Using D3JS, I created an svg for both pages. For the pie chart, the correct angle was found by summing up all the occurrences and getting each angle as a percentage. For the bar chart, the maximum of the y axis was set to the largest number. 
## Features
Since this is a basic data visualization. This shows a procedurally generated bar and pie chart, with an extra page showing an excerpt of the data.
## Libraries used
D3 JS – http://d3js.org/
jQuery – http://jquery.com/
## Development Tools
This site was developed using the Sublime Text editor on a Lenovo Thinkpad (i7 Second-Gen, 16GB RAM) running Windows 10.
## Special Startup instructions
1)	In order for the data display to work, you must disable same origin security:
  a)	Google Chrome / Chromium
    a.	Run with the --disable-web-security flag
    b.	In the windows run dialog enter:
      i.	chrome.exe --user-data-dir="C:/Chrome dev session" --disable-web-security
    c.	When running from a terminal (UNIX/Linux):
      i.	chromium-browser --disable-web-security --user-data-dir
    d.	When running from a terminal (Mac OSX)
      i.	open -a Google\ Chrome --args --disable-web-security
  b)	Mozilla Firefox/Nightly
    a.	In the address bar type “about:config” and click “I’ll be careful, I promise.”
    b.	Search for “security.fileuri.strict_origin_policy”
    c.	Double Click to change the Value to “false”
  c)	Safari
    a.	No way to change the Access Control Allow Origin policy.
  d)	Internet Explorer
    a.	No way to change the Access Control Allow Origin policy.
  2)	The dataset has been aggregated by me to count the amount of crimes per year. The original dataset I used is included in the zip file.
  3)	Otherwise there are no special procedures to start the website.
## Insights and issues
•	No matter how much I want to show/use the full dataset. I cannot because any browser I tested with crashed. It took some doing to even get the frequencies of crimes in different years.

•	D3JS documentation really didn’t work for me. Luckily I was able to use Stack Overflow and Bl.ocks to get a good head start on the code.

•	Libraries like this make me realize how easy my work has become thanks to someone else’s hard work. 


