# biden-judicial-nominees
 Interactive map that displays the judicial nominees of President Joe Biden for each district court. The data was scraped from press releases of the White House website using BeautifulSoup and regex. The map was built using geo json.

## How I did it:
1. Went to the White House website and looked for press releases on Biden's judicial nominees. 
2. Scraped the White House website using BeautifulSoup and created a list of the judicial nominees in different states including jurisdictions outside the U.S. such as Puerto Rico. The press releases were not uniformly formated so I had to reconfigure the regex every now and then.
3. Used a federal courts geo jscon map template to visualize the data. For this map, I chose to use the color purple to represent women as the project initially sought to map out the female nominees of the Biden administration.
4. A separate repo was made to upload the map on github pages. 
