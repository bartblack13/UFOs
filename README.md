# UFOs
JavaScript, BootStrap, HTML and CSS


## Overview of Project: Explain the purpose of this analysis.
The goal of this project was to continue gaining exposure to JavaScript, BootStrap, HTML, and CSS.  To do this I helped a friend, named Dana, build a dynamic webpage by inserting javascript in to an HTML page (see Figure 1).
<br><br>
![This is an image](https://github.com/bartblack13/UFOs/blob/main/Resources/webpage.png)<br><br>
**Figure 1 - Website screenshot** <br><br>

The webpage included a table presenting UFO sighting data that could be filtered by date.  The webpage was then updated by altering the index.html file (see Figure 2) to allow users to filter the data by date, city, state, country, and shape of the UFO, in the incident report.  I used Bootstrap and CSS to style the page by adding: 
* a navigation bar, 
* a jumbotron container with background image, 
* article title and short article, 
* the filter form, 
* the table with data, 
* and background color for the body of the website
<br><br>
![This is an image](https://github.com/bartblack13/UFOs/blob/main/Resources/filters%20code.png)<br><br>
**Figure 2: List ("li") tags with four new search forms** <br><br>


## Results: Describe to Dana how someone might use the new webpage by walking her through the process of using the search criteria. Use images of your webpage during the filtering process to support your explanation.
The website is designed so that initially the table loads with all of the data. The user can then scroll down towards the bottom and use the filter forms, located to the left of the table to filter the data by date, city, state, country, and/or shape of the UFO.  Any combination of the search criteria can be used.  For instance, a search can be performed using the date and then the state.  In Figure 3 and 4, I filtered using 1/13/2010 as the first criteria, which yielded three results.  I then added an additional filter, by setting the state equal to "fl" (Florida).  The data should filter automatically once the criteria is entered and the user pushes "tab", "enter", or clicks outside the box.  The user can reset the table and clear the filters by clicking "UFO Sightings" at the top of page, in the left corner, or by simply clearing the input forms.
<br><br>
![This is an image](https://github.com/bartblack13/UFOs/blob/main/Resources/filtered%20by%20date.png)<br><br>
**Figure 3: filtered on date (1/13/2010) only** <br><br>


<br><br>
![This is an image](https://github.com/bartblack13/UFOs/blob/main/Resources/filtered%20by%20date%26state.png)<br><br>
**Figure 4: filtered on date (1/13/2010) and state (fl - Florida)** <br><br>


## Summary: In a summary statement, describe one drawback of this new design and two recommendations for further development.
One draw back of the new design is the simple task of clearing the form and resetting the table.  Although a user can click the "UFO Sightings" at the top of the page, this is not intuitve, since it just appears as a title or random bit of text.  A button would be helpful.  Also locating it below, near the form, would make more sense and keep the user from having to scroll to the top everytime to reset the data.  In additon, it would be nice to add a function and button to export the filtered tables as a csv file, so users could do their own analysis.  The data is also displayed in chronilogical order, with the most recent sighting being at the bottom.  Having the data listed in reverse chronological order would be nice.  The data also only covers a short range of dates, and does not include anything recent.  Adding an ability to scrape new data would be great, as well as adding recent news articles.
