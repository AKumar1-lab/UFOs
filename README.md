## UFOs
Module 11 - UFO Sightings using JavaScript

Completed by Angela Kumar

## Purpose

Use JavaScript, HTML, CSS to create a custom webpage that showcases different UFO Sightings around the world.

## Overview

JavaScript is a well-established coding language that was designed to enhance HTML. It is the backbone of many popular visualization libraries, such as Plotly, and is often used to create custom dashboards. JavaScript also provides a high level of customization: the dashboards built to deliver visual data, such as maps or graphs, can be as simple or complex as needed. HTML and Bootstrap skills will also be utilized.

## Resources

Data Source: ufo_startercode.js; data.js; index.html; nasa.jpg;
Software: JavaScript; Visual Studio Code; Bootstrap; CSS;

## Background
The original assignment was to filter for the date.

<img width="936" alt="Basic Image of Webpage" src="https://user-images.githubusercontent.com/85860367/132939065-a48d5b8c-57b2-4f42-9e08-088d9668d9e8.PNG">

Dana’s webpage and dynamic table are working as intended, but she’d like to provide a more in-depth analysis of UFO sightings by allowing users to filter for multiple criteria at the same time. In addition to the date, add table filters for the city, state, country, and shape.

## Deliverables

### Deliverable 1: Filter UFO sightings on multiple criteria.

Using JavaScript and HTML,modify the code in your index.html file to create more table filters. In addition to the date filter you created in this module, add filters for the city, state, country, and shape, as shown in the following image:

<img width="934" alt="Reformat Image of Webpage" src="https://user-images.githubusercontent.com/85860367/132939403-f638fb08-e0d8-4c55-a34d-7a73de8a03f1.PNG">

* The list element that creates the button is removed, and there are five list elements for filtering in the index.html file. 
* The event listener is modified to detect changes to each filter in the app.js file. 
* The updateFilters() function saves the element, value, and the id of the filter that was changed. 
* The filterTable() function loops through all of the filters and keeps any data that matches the filter values. 
* The webpage filters the table correctly based on user input. 

### Deliverable 2: A written report on the UFO analysis (README.md)

Overview of Project: Explain the purpose of this analysis.  

The purpose of the analysis was to create a webpage that includes a table with the UFO array given.  The original module assignment was to filter the date only; however the challenge assignment was to add the other 4 elements: date, city, state, country and shape to filter the data in the table.

Results: Describe to Dana how someone might use the new webpage by walking her through the process of using the search criteria. Use images of your webpage during the filtering process to support your explanation.  

The table was very large; and having the filters helped limit how much data was needed by date, city, state, country, and shape or a combination of all or any.  To ensure that the filters worked, I was testing the following combinations date 1/1/2010 and state "ar" or "ca".   The image below is what I had selected:

These are the steps:
1) One would select the open field of their choice as the placeholder suggests.
2) Selecting "enter" after the input or using the "filter" button that was added back.
3) Results should be provided in the table format as listed in the screenshot.
4) It would be suggested to add a "reset" or "clear" button to clear the previous search.

<img width="936" alt="Filtered Image of Webpage" src="https://user-images.githubusercontent.com/85860367/132939418-a0365a99-a1aa-456a-acbd-70b502ca8b06.PNG">


## Summary
One drawback of this new design:  This only had data that was given as of January 2010; it would have been good to see a year or a dynamic webpage where the data was real-time.  Another drawback, was that the webpage was on the localhost server, it limited access to users and visibility.  It was suggested to use Github pages, however once posted, the code, access, visibility were no longer private. Anyone with internet/browser access can view the webpage and all of the components.  

Recommendations for further development:  Adding the filter button back helped give the user engagement of clicking a button to filter the data. Adding a reset or clear button would also be helpful. Fixed Headers and a scrollable feature within the table would also be helpful for those searches that yield a larger result such as the state "ca".  I may even suggest a dropdown selection for the following elements: city, state, country and shape. 

This assignment was challenging; especially when the code was reformatted to include all elements. Ensuring that the semicolons and tags were in the right places for the code to run was definitely a learning process. 
