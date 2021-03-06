# UFO Sightings - Module 11 Data Analytics

## Cheryl Berger

### Overview
Dana's UFO Fact Finder webpage and interactive data table are working well. Given all the available data, she would like to expand the functionality of the webpage by adding  additional criteria to filter the data.  Dana would like the user to be able to filter on any combination of 5 fields: date, city, state, country, and shape of the UFO sighted. To perform the analysis, the following resources were used:

Files: data.js, app.js and index.html
DataTools: JavaScript, ECMScript, Python, and HTML
Software: Visual Studio Code v1.64.0

### Results
Describe to Dana how someone might use the new webpage by walking her through the process of using the search criteria. Use images of your webpage during the filtering process to support your explanation.

#### Create the JavaScript file to set-up the webpage and filter the data on user input. 

##### Adopt the code from the lesson to add the data file as a variable and locate the table referneces.  Then create a function to build a data table containing all objects in the data file, appending each row with the new values. 
![image](https://user-images.githubusercontent.com/94234511/153777106-7fd758d6-317f-456b-b7f9-4301a6094df9.png)

##### Attach an event listener to listen for changes to each filter based on input from the user
![image](https://user-images.githubusercontent.com/94234511/153777136-65a3e594-1d79-44ca-b831-d71cbdd80620.png)

##### Using the new filter update the filters and rebuild the table using the new data
![image](https://user-images.githubusercontent.com/94234511/153777167-218f298b-b1a7-4931-b655-6214d8cf9d98.png)

#### Create the HTML file to display the webpage and datatable for the user 
##### Setup the webpage features, the title was changed from "Document" to "UFO Fact Finder"
![image](https://user-images.githubusercontent.com/94234511/153740774-e64e45bc-fba9-47a9-8051-ce5b0a153b27.png)

##### Refactor the lesson code to create the additional filters.  Add a new class, list-group-item and include the labels for each filter criteria: Date, City, State, Country, Shape
![image](https://user-images.githubusercontent.com/94234511/153740793-28c96fbf-ae7d-4da5-a346-c787d3cc0ab1.png)
Update the HTML file to add the script for the data files to the HTML file after the last <div> 
![image](https://user-images.githubusercontent.com/94234511/153777332-3175bf63-c7d5-48fe-8c2c-d6e3ff3861a0.png)

#### To perform a search
There is a description of how to perform a search, with images. 

##### Open the index.html file in web browser
![image](https://user-images.githubusercontent.com/94234511/153778562-e4c154cc-c277-41b8-b94f-9cf006bf757d.png)

##### Select a date filter and input the filter criteria in the box
![image](https://user-images.githubusercontent.com/94234511/153778629-d817e0a6-bed7-4830-803f-21b5990da843.png)
 
##### Press Enter to see the filtered results

 
#### Filter UFO sightings on multiple criteria
 
##### Select 3 filters
![image](https://user-images.githubusercontent.com/94234511/153779884-ddfe91b6-f90c-4d6d-8565-64e485518db7.png)

##### Press Enter to see the filtered results
 

### Summary

#### Summary of UFO Fact Finder WebPage
 
Dana's new webpage now allows the user to filter on other criteria to perform a more focused analysis of specific areas or UFO shapes associated with the reported sightings for the duration of time captured in data.js. One of the drawbacks of this webpage is that the reader is expected to know something about the key:value pairs and would need access to the data file or prior knowledge of the contents. 
  
#### Additional recommendations for further development

##### Recommendation #1
It would be more clear to the user if the placeholder field were not pre-populated as it is not immediately obvious that these are fillable fields.  Adding a "reset" or "clear filters" button may encourage more queries by the user if it is clear how reset the inputs. 
 
##### Recommendation #2
The information contained in the datafile may not be available to the user. Adding drop-down menus for each field may allow the user a quick method to identify available inputs to filter the data.
  
