# World_Weather_Analysis
Module 6

You lean back from your desk and reflect on the project thus far. Not only have you successfully navigated a quick return to the geographic coordinate system and the Earth's geography, you also wrote code to generate 1,500 latitudes and longitudes. Now, as cool as this is, your clients aren't going to want information or suggestions provided to them in this format. So, it's time to get started on the next step in your project plan: match those coordinates up with cities.

Latitude and longitude—got it. Now it's time to code. You know you want to generate enough coordinates that you'll have a good covering of common travel destinations, so you'll need coordinates that are close to a city.

Your project planning document is prepared, approved, and pinned above your computer. You're ready to get going on the first step: creating a list of over 1,500 latitudes and longitudes.

But wait. Which one runs north to south? Latitude or longitude? And which one runs east to west? And how exactly do these work, again? As a professional in the world of data, you are no stranger to employing Google-fu when faced with a problem, so you decide to do a quick self-taught review.

Good thing you got your repo set up and out of the way prior to that kickoff meeting. This project is going to be no joke, but it should be a lot of fun.

At the most fundamental level, Jack needs help answering a question: How might we provide real-time suggestions for our client's ideal hotels? Your first task was to define what you meant by "ideal." So, over the course of the conversation, you narrowed that to hotels that were (1) within a given range of latitude and longitude and that (2) provided the right kind of weather for the client.


Basic Project Plan
Here's an outline of your project plan:

Task: Collect and analyze weather data across cities worldwide.
Purpose: PlanMyTrip will use the data to recommend ideal hotels based on clients' weather preferences.
Method: Create a Pandas DataFrame with 500 or more of the world's unique cities and their weather data in real time. This process will entail collecting, analyzing, and visualizing the data.
Your analysis of the data will be split into three main parts, or stages.

Collect the Data

Use the NumPy module to generate more than 1,500 random latitudes and longitudes.
Use the citipy module to list the nearest city to the latitudes and longitudes.
Use the OpenWeatherMap API to request the current weather data from each unique city in your list.
Parse the JSON data from the API request.
Collect the following data from the JSON file and add it to a DataFrame:
City, country, and date
Latitude and longitude
Maximum temperature
Humidity
Cloudiness
Wind speed
Exploratory Analysis with Visualization

Create scatter plots of the weather data for the following comparisons:
Latitude versus temperature
Latitude versus humidity
Latitude versus cloudiness
Latitude versus wind speed
Determine the correlations for the following weather data:
Latitude and temperature
Latitude and humidity
Latitude and cloudiness
Latitude and wind speed
Create a series of heatmaps using the Google Maps and Places API that showcases the following:
Latitude and temperature
Latitude and humidity
Latitude and cloudiness
Latitude and wind speed
Visualize Travel Data


When you get back to your desk, your first step is to write out a basic plan for how you'll write code that can do this fairly complex task.




Lastly, Christopher, the only place where there's room for improvement is your travel itinerary map, because you did not create all four required DataFrames for each city! Then, you did not retrieve the corresponding coordinates that would help you to create a direction layer map. On top of all of that, you were unsuccessful with managing to upload it as PNG as well! Despite the slip-up in deliverable four, all of the boxes were ticked for this homework. 
