The Battle of Neighborhoods: Finding the Best Location for an African/Caribbean Store and Restaurant in Toronto, CA

Introduction/Busi:

The purpose of this project is to find the best location or neighborhood for an African/ Caribbean store or restaurant. In recent times, immigration of Africans and Caribbean to Canada especially the Toronto region has increased significantly. This project will interest entrepreneur trying to setup Afro-Caribbean store and restaurant to capitalize on this increase in population while maximizing sales and profit by situating the store or restaurant in a less competitive neighborhood. The idea is to categorize the neighborhood into clusters and apply the Foursquare API to find the neighborhood with the least number of Afro-Caribbean stores or restaurants. An efficient and easy way will be to use Foursquare explore tool to obtain a list of existing stores in our clusters and then recommend a distant location to capture others and newer market that might be too far from the existing locations. Another method will be to use the demography of Toronto and try to find where most Africans and Caribbean dwell, go to school and work. However, the later method is a mere common sense without any Data insight and extensively manual.

Data:

As mentioned earlier we will be using the Foursquare API data for different neighborhood in Toronto. Foursquare is a location data provider with information about all manner of venues and events within an area of interest. Such information includes venue names, locations, menus and even photos as well as Free Wi-Fi locations. For each neighborhood selected, we will use a radius of 500 meter and a limit of 100 locations. The data retrieved from Foursquare contained information of venues within a specified distance of the longitude and latitude of the postcodes. The information obtained per venue as follows: Neighborhood, neighborhood latitude, neighborhood longitude Venue, name of the venue, venue latitude, venue longitude, venue category For the Neighborhood data will be scrapping the data from the Canadian neighborhood Wikipedia page https://en.wikipedia.org/wiki/List_of_postal_codes_of_Canada:_M Some of the Python libraries that will be used in the Data wrangling include:

a. Pandas: For creating dataframe

b. Scikit Learn: For importing k-means clustering

c. Matplotlib: Python Plotting Module

d. Folium: Python visualization library would be used to visualize the neighborhoods cluster distribution of using interactive leaflet map

e. JSON: Library to handle JSON files

f. Geocoder: To retrieve Location Data
