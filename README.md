# Data-science-capstone
Coursera_Capstone let me introduce the contacts of the capstone project through a scenario. Say this is you, and you live on the West side of the City of Toronto in Canada. You love your neighborhood mainly because of all the great amenities and other types of venues that exist in the neighborhood. Such as gourmet fast food joints, pharmacies, parks, grad schools, and so on. Now say you receive a job offer from a great company on the other side of the city with great career prospects. However, given the far distance from your current place, you unfortunately must move if you decide to accept the offer. Wouldn't it be great if you're able to determine neighborhoods on the other side of the city? There are exactly the same as your current neighborhood, and if not, perhaps similar neighborhoods that are at least closer to your new job. So in this capstone project, I hope to equip you with the necessary skills to do so. And not only that, but at the end, you will have the opportunity to be creative and come up with your own idea or problem to solve using location data. For example, you can choose to compare different neighborhoods in terms of a service. Search for potential explanation of why a neighborhood is popular. The cause of complaints in another neighborhood, or anything else related to neighborhoods. Hence the name of the capstone project will be the battle of the neighborhoods. So what you will learn to do is, given a city like the City of Toronto, you will segment it into different neighborhoods using the geographical coordinates of the center of each neighborhood. And then, using a combination of location data and machine learning, you will group the neighbourhoods into clusters like this.

# Sources of data and methods to extract them
Sources of data and methods to extract them
This Wikipedia page (https://en.wikipedia.org/wiki/Category:Suburbs_in_Kuala_Lumpur) contains a list of neighbourhoods in Kuala Lumpur, with a total of 70 neighbourhoods. We will use web scraping techniques to extract the data from the Wikipedia page, with the help of Python requests and beautifulsoup packages. Then we will get the geographical coordinates of the neighbourhoods using Python Geocoder package which will give us the latitude and longitude coordinates of the neighbourhoods.
After that, we will use Foursquare API to get the venue data for those neighbourhoods. Foursquare has one of the largest database of 105+ million places and is used by over 125,000 developers. Foursquare API will provide many categories of the venue data, we are particularly interested in the Shopping Mall category in order to help us to solve the business problem put forward. This is a project that will make use of many data science skills, from web scraping (Wikipedia), working with API (Foursquare), data cleaning, data wrangling, to machine learning (K-means clustering) and map visualization (Folium). In the next section, we will present the Methodology section where we will discuss the steps taken in this project, the data analysis that we did and the machine learning technique that was used.

