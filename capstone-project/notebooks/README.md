# Best-Locations-to-Site-Shopping-Malls-in-Lagos-Venues-Data-Analysis-of-Lagos-Neighbourhoods

Applied Data Science Capstone by IBM/Coursera

Introduction
This project is part of the final capstone project for Coursera’s IBM Data Science Professional Certification. Through this project, I will be sharing the methods and techniques to solve a business problem with the help of data science.

1.0 Business Problem <a name="business"></a>
Lagos is the most populous city in Nigeria and the African continent. Being an economic hub and major financial centre for all of Africa, Lagos has the fourth-highest GDP in Africa. Over 50% of Nigeria's industrial capacity is located in Lagos, with a variety of manufactured goods being produced in the city, including electronic equipment, machinery, foodstuffs, beverages, and chemicals.

The retail sector in Nigeria is based on the latent potential of Nigeria’s population, consequently, placing Lagos as the hub of Nigeria's retail market. Therefore, firms hoping to cater to that block of consumers in Lagos should explore innovative ways to reduce market friction and improve the shopping experience for the buyers.

Shopping malls can provide the best shopping experience and reduce the pressure on traditional markets which mostly lead to congestion of roads and public spaces. Moreover, shopping malls can enable social gatherings, entertainment, performances, product launches, promotions, and festivals.

By knowing which location is less condensed with shopping malls, investors and firms can easily make data-driven decisions when expanding their businesses within the state.

In this project, I aimed to:

Find an optimal location for a shopping mall in Lagos. Since there are a number of shopping malls in Lagos, I tried to detect locations that are already crowded with shopping malls, then spot locations that are less condensed with shopping malls.
Explore business opportunities across Lagos neighborhoods by identifying top venues in Lagos and the business activities within.
This project is particularly useful to property developers and investors looking to open or invest in new shopping malls in the financial capital of Lagos, Nigeria. This project is also viable as it has the potential to help the traffic congestion in the city.

2.0 Data Collection <a name="data"></a>
To solve the problem, the following data were required:

A list of LGA and neighborhoods in Lagos via Wikipedia defines the scope of this project which is confined to the city of Lagos.
The coordinates of Lagos state to be obtained using Google Maps API reverse geocoding.
Python Geocoder package/Google Maps for latitude and longitude coordinates of the neighborhoods in order to plot the map and also to get the venue data.
Foursquare API would be used as the prime data gathering source to get the venue data for the neighborhoods. Foursquare API has a database of millions of places, especially their places API which provides the ability to perform location search, location sharing, and details about a business.
Python Folium Package for map visualization.
Matplotlib for graphical visualization.

Moreover, I used the k-means clustering algorithm to create emerging clusters for the neighborhoods with top venues.






