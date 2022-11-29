# UFOs 

## Overview of the Project
<p align="justify">The purpose of this project was to build a table using data stored in a JavaScript list. After that, the goal was to create filters to later place the table in a HTML file. Finally, the objective was to edit and make more appealing the HTML using CSS.</p> 

## Results
<p align="justify">In the web page created there are many components. First there is the heading that displays the title of the web page. Also, there is a subheading that shows a catch phrase with a background image. Below, information about the UFOs and their sightings is displayed. At last, the table with the filter options are shown.</p> 

<img width="958" alt="WebPage" src="https://user-images.githubusercontent.com/111388644/204369585-87357c0a-fd1a-449c-b6cf-77a3335d188e.png">

For there to be filters in the table the HTML file was changed. The filters for city, state, country, and shape were added using the correct *id* for each one of them.

<img width="427" alt="1" src="https://user-images.githubusercontent.com/111388644/204369686-c0117171-ce31-4de0-ae1f-b27334356135.png">

In order to get the filters to work, the file *app.js* had to be edited as well. A variable to keep track of al the filters was created as well as a function to update the filters. 

<img width="436" alt="2 0" src="https://user-images.githubusercontent.com/111388644/204369738-e84a9849-93d6-4971-906a-c620c02ca76c.png">

Then, an *if-else* statement was made to filter the added value, or to clear the filter from the filters object. 

<img width="379" alt="3" src="https://user-images.githubusercontent.com/111388644/204369799-68debe59-4c8c-4d60-9b6b-89fa8afdbb56.png">

A for loop was written to loop though all the filters to keep the data that matches the filter value. By doing this, the filters in the web page appear to the user. With these filters any person that visits the online site can write their own inputs in the blank spaces in order to expect specific results, like the ones shown below. 

Here are some examples to show that the filters work correctly. 

First of all, the image below shows how the table looks without writing any input in the filter section. 

<img width="939" alt="4" src="https://user-images.githubusercontent.com/111388644/204640360-56126de7-65d5-41f3-b829-762ca22a38cf.png"> 
<br/>
The second image displays the way the table would look if you the user was to write a specific date, in this case *1/13/2010*

<img width="938" alt="5" src="https://user-images.githubusercontent.com/111388644/204640752-cf418e72-245a-4e3f-9a99-af4d7211b9ce.png">
<br/>
The third image shows the result for searching a certain date, state, and country.

<img width="936" alt="7" src="https://user-images.githubusercontent.com/111388644/204640928-c3dac766-e589-4ac3-9e92-f8f645c9e695.png">
<br/>
In the fourth image it is visible that the filtered was used on the shape *sphere*

<img width="935" alt="8" src="https://user-images.githubusercontent.com/111388644/204641109-ed0df4be-fef6-436a-b310-bd835a00e0cf.png">
<br/>
Finally, the last picture shows the output of filtering the table by date, city, state, country, and shape.

<img width="936" alt="6" src="https://user-images.githubusercontent.com/111388644/204641251-9efbf327-03de-4c9c-903d-66273bebe755.png">
<br/>

## Summary
<p align="justify">The web page is functional and because it has been modified using CSS is more appealing than how it would be without those changes. Even though this is true, there is still a drawback. 
That disadvantage that could be improve is the color of the design. Although the UFOs site is attractive and clean, it still needs to be much more appealing. For example: by changing the colors of the background and the font to more vibrant and warmer colors the page would be instantly more engaging.</p> 

Another recommendation would be to add a different background depending on the filtered shape, or any other id. This would make the table even more dynamic and fun for the people to use. 
