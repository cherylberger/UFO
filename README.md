# UFO Sightings - Module 11 Data Analytics

## Cheryl Berger

### Overview
Dana's UFO Fact Finder webpage and interactive data table are working well.  Given all the available data, she would like to expand the functionality of the webpage by adding  additional criteria to filter the data.  Dana would like the user to be able to filter on any combination of 5 fields: date, city, state, country, and shape of the UFO sighted. To perform the analysis, the following resources were used:

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
 ![image](https://user-images.githubusercontent.com/94234511/153777426-45565fc5-6072-4b95-bf22-05c8ea0b4e98.png) 

##### Select a filter
 ![image](https://user-images.githubusercontent.com/94234511/153777456-fafcdd34-444f-443f-aacf-c1b39a732878.png)
 
##### Press Enter
  Input the filter criteria and press Enter on the keyboard
  ![image](https://user-images.githubusercontent.com/94234511/153777544-80091cb2-fd27-46b9-8ab8-b2a0e91a31ae.png)

##### Show dataTable

#### For example, 
Filter UFO sightings on multiple criteria
##### Select 3 filters
##### Press Enter
##### Show dataTable

### Summary
In a summary statement, describe one drawback of this new design and two recommendations for further development.

#### Drawback of this webpage
The reader is expected to know something about the key value pairs and would need access to the data file or prior knowledge of the contents. 
  
#### Additional recommendations for further development

##### Recommendation #1
Add a clear filters button
  
##### Recommendation #2
Add drop-down menus to allow the user input to match the available data
