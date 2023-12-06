# Google Maps API project

Routing application that finds the least stressful route to a destination using the Google Maps API.

This application will help drivers avoid heavily congested routes.

This will:
	* Reduce road rage
	* Reduce carbon emissions by less waiting in bumper-to-bumper traffic
	* Reduce car idling (useless wear and tear)
	* Promote better mental health for those who commute to the city

The Google Maps API can show traffic data in a general area but not for a particular route. Here I use the API duration variable, which is an estimate of the route duration based on historical data, and the duration_in_traffic variable which give an estimate of the duration taking into account live traffic. The goal is to find the route with the least traffic, not necessarily the shortest route. So one way to measure the traffic of routes is to get the absolute difference between the average duration and the live traffic duration. The result is roughly how long you will wait in traffic in each route. This application uses this measure to estimate the traffic in each route, choosing the route with the lowest.

Due to a credit card requirement to get an API key, I have not been able to test this.