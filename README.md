# UFOs
## Overview
Given a large javascript data file, the task was to create a dynamic webapge that allowed users to filter the data based on multiple criteria. The data in question contains categorized information about UFO sightings. The webpage application was built with HTML, JavaScript, and CSS.

## Results
The webpage was styled with CSS and some bootstrap components resulting in a clean and easy to read presentation. The table is created by Javascript and shows all data upon first visit to the website. There are containers to the left of the table that allow for user input to filter the data. 
<br><br>
**** overall pic
<br><br>
The "Filter Search" option is located to the bottom left of the page and allows the user to filter the UFO sightings based on date, city, state, country, and shape. The search can be based on a single search parameter or multiple parameters. The input must be typed as the example in the input box (all lowercase) with no extra spaces. An example of filter inputs can be seen below. <br><br>
**** insert filter pic
<br><br>
The user can hit enter after typing the search parameters or click outside of the boxes to view the results of the search to the left. The results matching the search parameters are presented in a clearly organized table to the right of the filter search.  <br><br>
*** insert table pic
<br><br>
## Summary
### Drawbacks
While this website does a good job of allowing users to search the data according to specific parameters, there is currently the drawback of those parameters needing to be typed exactly as they appear in the data. This could potentially cause a user to miss data due to a simple syntax error such as a space or inserting a zero in a date such as "01/01/2001" instead of "1/01/2001". <br>
### Potential Improvements
The input from users could be allowed to fit multiple formats that return the same matches for the results. Inputs that are capitalized or fully spelled out such as state, country, or date should still return the same information as long as they represent the same search parameter. <br>
Another improvement could be allowing searches for the comments of individual sightings. A user could be interested in finding sightings that contain information not based on anything that is already categorized such as "ball of fire" at the sighting in Alma, Az. This could provide an even more dynamic search for users. <br>

*** insert pic of comment