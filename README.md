# Chicago-L-station


<h2>1. Which stop has the highest average ridership per day, and what is it?</h2>

The station with the highest average ridership per day was Lake/State with an average ridership per day of 13,662 


<img src="https://raw.githubusercontent.com/diegoleonardoro/bronx_tourism/master/Screen%20Shot%202021-05-17%20at%209.16.59%20PM.png" >


<h2> 2. What’s the standard deviation for the Washington/Wabash stop? What’s your hypothesis for why?</h2>

The standard deviation of the Washington/Wabash stop is 3,961. This is a high standard deviation considering that it is around half the daily.
This is a very broad standard deviation, and as we can see in the chart below, most of the data is 1 or 2 standard deviations below the average, suggesting that the Washington/Wabash stop was probably being renovated and had to be shut down during certain times. 

<img src="https://raw.githubusercontent.com/diegoleonardoro/bronx_tourism/master/Screen%20Shot%202021-05-17%20at%209.25.55%20PM.png" >

Please see the only Python notebook of this repository to see the process for these calculations and also other data wrangling steps that I took. The Python notebook may need to be reloaded several times, as it is long.

<h2>Choose a specific business and tell us which business you chose. Imagine you’re helping that business owner in Chicago and s/he is looking to open a new location.</h2>

I chose a theatre that showcases independent and foreign movies called Landmark's Century Centre Cinema. This theatre currently has a location in 2828 North Clark Street at Diversey. I analyzed the provided L train ridership data to understand transit patterns of the are where the theatre currently has a location. 

I also analyzed data from the United States Census Bureau to have a better understanding of the demographics of the zipcode where the zipcode is located and also zipcodes with theatres that are comparable to Landmark's Century Centre Cinema. 

Finally, I also looked into data of applications for restaurant licenses, provided The City of Chicago open data portal to have a better idea on how economically vibrant specific zipcoes are.

I did the data wrangling with Python (pandas, numpy, Nominatim and Google Maps Api for geolocation)

To present the data I used pure JavaScript d3.js. Please find the repository for this in the following link: https://github.com/diegoleonardoro/diegoleonardoro.github.io

For a project like this, I would like all the analysis to be displayed on an interactive website where the client can explore the data in different ways. To have a better idea on how I envision presenting the data to a potential client, please visit the following link to see the d3.js charts that I made: 

https://diegoleonardoro.github.io/


