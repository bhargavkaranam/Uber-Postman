# Book an Uber from Postman

Book an Uber from Postman! No access to your phone but want to book an Uber? Here's the solution, Postman comes to the rescue. Import the collection and the environment. Get an access token from the Uber dashboard and you're good to go!

Import both the collection and environment into Postman and follow these steps.

**Steps to follow**
1. Login to the Uber API dashboard and create a new application. You can generate a temporary access token from the dashboard and use it. 
2. Copy the access token and use it in the environment variable `accessToken`
3. Next, go to (https://opencagedata.com)[OpenCageData] and get an API Key and use it in the `geoLocationApi` environment variable.
4. Final step, promise. Set your pickup and drop location in the respective environment variables.
5. Now run this collection from Postman Runner and Postman will book the cheapest cab for you. More features to be added.

For more details - 
(UberAPI)[https://developer.uber.com/docs/]
(Geolocation API)[https://opencagedata.com/api]
