# UFOs
## Overview
The purpose of this project is to create a dynamic webpage for UFO sitings using javascript, html, and css. This webpage will have a title, synopsis, table of UFO data, and filters for that table. The dynamic element is the filters. The user will be able to filter for key values of the UFO data. These include date of occurance, city, state, country, and shape. The table also includes duration of occurance and any notes. Lastly, there will be discussion of drawbacks of the webpage and recommendations for future development.

## Resources
Software: Javascript, HTML, css, bootstrap 4.0.0, VS Code 1.70.2
Data: [Data.js](static/js/data.js)

## Results
When running the [webpage](index.html) in your browser you can view the UFO Finder. The top section has the title and blurb about relevancy of the UFO sitings. In order to filter the data in the below table, see the filter search box that looks like this:

![](static/images/Filter_Table.PNG)

If I use the date box, I can filter the UFO sitings based on date. For example if I were to type `1/13/2010` into the filter search it would yield:

![](static/images/Date_Filter.PNG)

You can use any combination of filters so long as the input in the text box has a matching value in the UFO table. An example of using multiple filters is if I wanted to know all the UFO sitings from California on January 10th, 2010. I would type `1/10/2010` in the date box and `ca` in the state box. The table only uses state abbreviations.

![](static/images/Date%26State_Filter.PNG)

Keep in mind that you cannot filter on the duration and comments, but those fields can still be viewed in the table after filtering using any of the valid filters.

## Summary
### Drawbacks

