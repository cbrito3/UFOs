# UFOs

## 1. Overview of Project: Explain the purpose of this analysis.
Dana asked to help her provide a more in-depth analysis of the UFO sightings based on the webpage we created earlier. She wants to provide users to ability to filter for multiple criteria selections at the same time and not only by date. She has asked to include filters such as city, state, country and shape. To do this, we will update our index.html as well as our app.js. 

## Deliverables:
* Deliverable 1: Filter UFO sightings on multiple criteria
* Deliverable 2: A written report on the UFO analysis that includes results and summary in (README.md)

## 2. Results: Describe to Dana how someone might use the new webpage by walking her through the process of using the search criteria. Use images of your webpage during the filtering process to support your explanation.
* Filter UFO sightings on multiple criteria:
  - The list element that creates the button is removed, and there are five list elements for filtering in the index.html file. 
  - The event listener is modified to detect changes to each filter in the app.js file. 
  - The updateFilters() function saves the element, value, and the id of the filter that was changed. 
  - The filterTable() function loops through all of the filters and keeps any data that matches the filter values. 

* In addition to the date search criteria, the updated webpage will include filters for city, state, country and shapre. 
  - For example in this picutre we can see how the search criteria will look for the user:

![UFO%20sighting%20webpage](https://github.com/cbrito3/UFOs/blob/main/Static/UFO%20sighting%20webpage.png?raw=true)


## 3. Summary: In a summary statement, describe one drawback of this new design and two recommendations for further development.
One of the drawbacks of this new design for users is that the initial letter for every entry such as in city have to be in lower case letters, this can cause frustration as people would have to go back and change the first letter in case they thought upper case initial might work just fine. 

The two recommendations I would give to further development of the webpage would be:
  1. Add a new filter for "Duration", this could allow users to look for data that are less than 10 minutes or more than 5 minutes, etc. 
  2. Another thing that could make this page user friendly is to add "clear" option box so users can clear the data they are looking for and continue their search for other information. 
