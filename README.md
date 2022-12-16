# UFOs
UFO Sightings with JavaScript

## Purpose
1. Discuss the advantages and disadvantages of JavaScript "standard" and JavaScript version ES6+.
2. Describe the syntax of JavaScript and the best use cases.
3. Create and deploy JavaScript functions, including built-in ones.
4. Transform JavaScript functions into arrow functions.
5. Create and deploy forEach (JavaScript for loop).
6. Using JavaScript and HTML, create, populate, and dynamically filter a table.

## Overview 
The request from a client was to display a table organizing UFO data stored as a JavaScript array. The client wanted the ability to filter by multiple criteria creating a dynamic website.  The table was created using JavaScript, while HTML/CSS and Bootstrap were used to modify the aesthetics of the website. 

## Results:
### Welcome to UFO Sightings! 

![Pic 1](https://github.com/kimchung04/UFOs/blob/main/static/images/UFO_1.png)

### How the filters appear when first landing on the page:
![Pic 2](https://github.com/kimchung04/UFOs/blob/main/static/images/UFO_2.png)

### How the filters appear after being used: 
The result returns two matches when the suggested placeholder elements are used as filters. Make sure that everything is in lower case letters and that there are no spaces at the end of the text. To start the filter, click outside the input box or press enter. To reset the filter criteria, go to the top left of the website and click UFO Sightings.

![Pic 3](https://github.com/Baylex/UFOs/blob/main/static/images/working_filters.PNG)


## Summary: 

### Drawback:
To search, the user must have specific dates, cities, or shapes in mind. Some shapes, such as "light," may be less intuitive. The filters require lower-case spelling and do not accept spaces at the end. For example, the city used could not be typed as "elcajon", "el cajon_", or "El Cajon". "El cajon" is the only acceptable input.

### Recommendations: 
1. The next feature that should be added to the filters is a trim function that will catch spaces at the end of words and allow for upper and lower case. [Pic 4] (https://github.com/Baylex/UFOs/blob/main/static/images/trim.PNG)

2. A date range filter may be preferable to a single date. Typing 1/2010 did not return all of the January dates as expected. Perhaps UFO sightings are more common in a specific month rather than a specific day within the month. It is suggested that a filter function be added that includes a date range as the filter to aid in the investigation of UFO sightings.

![Pic 5](https://github.com/Baylex/UFOs/blob/main/static/images/date.PNG)


