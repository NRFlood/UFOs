# UFOs analysis with JavaScript

## Overview of UFO Analysis

The purpose of this project is to assist Dana in creating a table of UFO data out of a JavaScript array and make the table dynamic enough for the data to be filtered based on certain criteria being input by the user.  To complete this project, I helped Dana create an HTML file that will display the table in a well-organized easy to view format, and then leverage JavaScript and Bootstrap to enhance our HTML page and allow the page to be customized by generate five filters that would enable the user to select the Date, City, State, Country, and Shape of the UFO siting they were interested in. 

## UFO Table Results

The web page is now dynamic and can leverage the filters on the lefthand side to dive deeper into specific UFO sightings based on the event Date, City, State, Country, or Shape.  Each filter has a default value as seen in the image below.  

![](https://github.com/NRFlood/UFOs/blob/main/FilterDefault.PNG)

As few as one or as many as all five filters can be used to return more specific results.  For example, below the date filter has been changed to 1/7/2010 and the state filter has been changed to *ma* representing Massachusetts. Please note that the default values for any unused filters will remain in place but will not impact the table output.  

![](https://github.com/NRFlood/UFOs/blob/main/FilterExample.PNG)

The result of the filtered example above is this table seen below. 

![](https://github.com/NRFlood/UFOs/blob/main/TableExample.PNG)

These filters can now help any user narrow down their search to find the details around a specific UFO event or provide a broader view of UFO activity happening in a say certain city, like the one Dana is from in Oregon.  

## UFO Summary

Despite Dana's webpage now being more dynamic I think there is still opportunity to provide a better filtering experience.  One improvement might be to have certain filters be dependent on one another.  For example, in order for a user to use the City filter they would need to select the State filter first.  This would alleviate the possibility of a user getting results in two different cities that happen to be named the same (Ex. Glendale, CA & Glendale, CO) if they were able to use the city filter only. 

Another improvement might be to add a filter that allows you to search for key words within the *Comments* section of the table.  That would enable people to possibly find trends within the behavior of the different UFO sightings.  For example, the keyword "red" would return several events on different dates in different locations in which the person describing the instance called out the word "red", most commonly as it relates to lights they were seeing. Events described in similar ways across the world would definitely help identify trends as well.   
