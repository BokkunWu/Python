<em>Is there a correlation between nyc rent prices and the distance it is from the subway station? </em>  
  
The main goal of this was just to create a scatterplot with the prices of apartments and the distance it is from the closest subway station and see how that affected the price.

Apartment Data was webscraped using Dataminer from Streeteasy(8/21/2020), 1107 rows.  
MTA subway location data was from the NYC.gov website.

<h2>Project Steps: </h2>  
  
<ol>
<li>Scrape Streeteasy  </li>
<li> Convert the addresses from the scraped data to their coordinates using geopy package  </li>
<li> Convert coordinates from string to a tuple  </li>
<li> Create new columns in the df to house station name and distance to the station   </li>
<li> Use a nested for loop to check the apartment listing with all stations and see which one is the closest before moving to the next apartment  </li>
<li> While in the loop, populate the station name/distance rows  </li>
<li> Remove potential outliers  </li>
<li> Plot
</ol>
