# Choose An Italian Restaurant Location

<a href="github.com">Home</a>
I picked up a course on coursera, in which I learnt to use some interesting tools like how to plot markers on a map and how to do machine learning. Let me show you how to solve such a problem: Where to open an Italian restaurant.

For a restaurant, location is very important. Since location will decide how many potential customers will be and what price they will pay.

I used Foursquare data to find these two things. Foursquares is a very useful data source and free. You can apply an account as a developer on its website. 

In Foursquare Places API, we can Get Details of a Venue, in which includes price tiers and usersCount.

Here we try to find an ideal location with the following conditions: First, it clusters with other profitable Italian restaurants. Sometimes restaurants compete with each other. But if they form an Italian food area, people will first go to the area when they want to enjoy Italian food. Second, nearby Italian restaurants should be profitable, which means they should have good prices or large numbers of customers.

With these conditions, we will classify the Italian restaurants by price and number of customers with machine learning methods. According to the results, I will locate them on the map and find out where is the most profitable place to open an Italian restaurant.

The result may be useful for people to open their own Italian restaurant, or may lend some thoughts to other business location finding.
