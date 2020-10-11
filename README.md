# UFOs

## Overview of UFOs analysis

The purpose of this project is :
* To create a table and organize UFO data that is stored as a JavaScript array.
* To have the ability to filter the table based on different criteria like date, city, state, country and shape.

## Results

The steps to use the different **Filter Search** criterias in the UFOs new webpage can be found below.

### A. Search by single criteria :

Single criteria search can be performed by entering value in one of the search boxes like date, city, state, country or state.
After entering the value, we have to press enter to see the table filtered for the entered value.

#### Search by date :

The *Date* to be filtered has to be entered in the box next to *"Enter the Date"* and <Enter> to find the table filtered for the *Date*.

The example below can be seen for the date **1/4/2010**.
  
![Date Search Criteria](https://github.com/anupoonja/UFOs/blob/main/Challenge/static/images/A-Date.png)

#### Search by city :

The *City* to be filtered has to be entered in the box next to *"Enter a City"* and <Enter> to find the table filtered for the *City*.

The example below can be seen for the city **san diego**.
  
![City Search Criteria](https://github.com/anupoonja/UFOs/blob/main/Challenge/static/images/A-City.png)

#### Search by state :

The *State* to be filtered has to be entered in the box next to *"Enter a State"* and <Enter> to find the table filtered for the *State*.

The example below can be seen for the state **ny**.
  
![State Search Criteria](https://github.com/anupoonja/UFOs/blob/main/Challenge/static/images/A-state.png)

#### Search by country :

The *Country* to be filtered has to be entered in the box next to *"Enter a Country"* and <Enter> to find the table filtered for the *Country*.
  
The example below can be seen for the Country **in**. Where the table is empty. As there are no entries.
  
![Country Search Criteria](https://github.com/anupoonja/UFOs/blob/main/Challenge/static/images/A-country.png)

#### Search by shape :

The *Shape* to be filtered has to be entered in the box next to *"Enter a Shape"* and <Enter> to find the table filtered for the *Shape*.
  
The example below can be seen for the shape **fireball**.
  
![Shape Search Criteria](https://github.com/anupoonja/UFOs/blob/main/Challenge/static/images/A-shape.png)

### B. Search by combination of two or more cretirias : 

Two or more criteria search can be performed by entering values in two or more search boxes. After entering the values, we have to press enter to see the table filtered for the entered value.

The example below has the two search criterias entered city: *round rock* and state: *texas*.

![Two Search Criteria](https://github.com/anupoonja/UFOs/blob/main/Challenge/static/images/B.png)

### C. Search entering all the fields : 

All criteria search can be performed by entering values in all the search boxes. After entering the values, we have to press enter to see the table filtered for the entered value.

The example below has all the search criterias entered date: *1/1/2010*, city: *el cajon*, state: *ca*, country: *us* and shape: *triangle*.

![All Search Criteria](https://github.com/anupoonja/UFOs/blob/main/Challenge/static/images/C.png)

### D. Search with no criteria :

If *none* of the critierias are entered, the whole data will be displayed in the table. As seen in the image below.

![Default Criteria](https://github.com/anupoonja/UFOs/blob/main/Challenge/static/images/D-None.png)

## Summary

The design is very good. However there are few drawbacks. One of the drawbacks is that the valued enetered are case sensitive.

Two recommendations for further development are:
* Make the values enetered non-case sensitive.
* The table can be improved to accept different sightings, right it back to the data.js and display it in the table along with other data.

