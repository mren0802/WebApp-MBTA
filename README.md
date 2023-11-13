# WebApp-MBTA
 This is the base repository for Web App Developement project. Please read [instructions](instructions.md). 

## **Project Overview**
### For assignment three, I created a MBTA Helper code that allows users to find the nearest MBTA station based on the place/location that they input into the Flask web framework. The system takes latitude and longitude coordinates of the inputted place from my personal Mapbox Geocoding API to search for the nearby stations. In addition to the station name, I also incorporated real time arrival data and wheelchair accessibility information for that nearest station through my MBTA API. To further enhance the user experience in my web application, I pulled in the OpenWeatherMap's API data to also give the user the weather information for their location of interest. A Flask web framework was created to seamlessly integrate these functionalities in one user-friendly interface for the user to input a location and receive information about the closest MBTA station, whether or not it is wheelchair accessible, the train's arrival times, and the current weather outside. 

## **Reflection**
### From a process point of view, I initially struggled with getting the MBTA Helper code to work because I was not writing the correct attributes for the coordinates, which caused me to get the error message as data was not pulling from Mapbox. After getting the attributes right after reading the Mapbox documentation, I still struggled with getting the code to run because I inputted Babson as the place name, not realizing that Babson was way too far from any MBTA station for MBTA api to even give me a station name. It made me think that my code was the issue, when it was just the location I had chosen. Upon figuring out the MBTA code, it was a smooth process to write the code for the Flask web application. However, if time permitted, I could have spent more time workng on making the web application look prettier and more seamless. I can also improve on making MBTA still extract data for the nearest station to Babson even if it's too out of proximity to actually get there within walking distance. 

### I worked independently on this project, so there was no division of team work. 

### From a learning perspective, the project provided valuable insights into API integration and the usage of Flask web framework. The APIs helped me to understand a lot about how I can implement and use APIs to solve real-world problems and make it applicable to the real life. Going forward, I now have more knowledge on how Flask works and it will be of great benefit for my final project to implement Flask into my code as well. As for ChatGPT, after the last assignment, I did some reflecting on my usage of it and for this project, I found almost no need to use it except to help me fix minor errors that I was running into because of indentation issues and small logic messups in incorporating an else statement to prevent errors. One other use of it was asking it simple questions on altering my code in terms of how do I change just my time for arrival time to red without changing the "arrival time" to red as well. 
  



