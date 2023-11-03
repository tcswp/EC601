Google Maps API project

Routing applicatoin that finds the least stressful routes to destination using the Google Maps API.

This application will help drivers avoid heavily congested routes, routes with many pot holes and uneven bumpy roads, and excessively long traffic lights.

This will:
	reduce road rage
	reduce carbon emissions by less waiting in bumper-to-bumper traffic
	reduce car idling (useless wear and tear)
	promote better mental health for those who commute to the city


Since the majority of mobile phone users are ok with being spied on by their smartphone applications, it can listen to users and use that information to perform sentiment analysis of their words when they are driving. More curse words, groans, and sighs signifies a stressful route. It can also use the phone accelerometers to detect big bumps, and of course gps and system time for route duration.

The application can act as a dispatcher, sending drivers on different routes to spread out the traffic.

The app can make note of the routes it sent drivers on with the best sentiment and cache those routes

Google Maps API can show traffic data in general area but not for a particular route.
A possible workaround would be to compare route duration with duration_in_traffic variables provided by the API.  If duration_in_traffic > duration that means you have a heavier traffic than usual. Use route options such as avoid highways to compare all the routes to determine the best option.