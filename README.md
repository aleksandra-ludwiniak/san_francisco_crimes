# san_francisco_crimes


The project for Social Data Analysis and Visualization course at DTU.


This project investigates crime incidents reported in San Francisco. Furthermore, a more in depth analysis of crimes reported in the Tenderloin district will be visualized since this district has a high amount of incidents reported. 

To analyze the crime in San Francisco an open source dataset containing incident reports in San Francisco from 2003 to may 2018 was used [https://datasf.org/opendata/](https://datasf.org/opendata/). Since the dataset does not contain incident reports from the entire 2018 year, this year was removed from the data. The dataset contain different types of crimes. In parts of this project we will investigate specific focus groups containing: Robbery, Assault, Sex offenses, Forcible, Kidnapping, Vehicle Theft, Arson, Burglary, Larceny/Theft, Vandalism and Stolen Property. 

The focus groups were separated into two categories; Violent Crimes and Property crimes. Where Violent crimes include; Robbery, Assault, Sex offenses, Forcible, Kidnapping and Property crimes include; Vehicle Theft, Arson, Burglary, Larceny/Theft, Vandalism and Stolen Property. Below is a bar chart of violent- and property crimes over the years in the Tenderloin district. The chart shows that during the years 2013-2015 both violent- and property crimes were at its peak. However, after these years the crimes seem to decrease. But without further investigation and the upcoming incident reports for the following years it is hard to say if this tendency is a continuing. 
![Bar_chart](/Assets/Bar_AnnualCrimes.png)

Now that we have seen the distribution of violent- and property crimes we will investigate where all reported incidents occurs. This is visualized with a heatmap over all the incidents in the Tenderloin district below. The heatmap shows that crime happens all over the district and the same with the distribution of hotspots. It is hard to pinpoint where it would be safe to stay which is also something the inhabitants feel. According the short article “SF's troubled Turk Street: City throws in towel” by C.W.Nevius 
[article](https://www.sfgate.com/bayarea/nevius/article/SF-s-troubled-Turk-Street-City-throws-in-towel-2354707.php)  the people that live there fear for their life and are even scared to go outside. Furthermore, the article describes that one area in the tenderloin district is far worse than in any other area. This area is the first block on Turk street which is indicated on the heatmap with a marker. The heatmap shows that that there is a hotspot in the area and according the article violent crime at this spot is 35 times higher than any other place in the city and 8 times higher than any other place in the Tenderloin district. 
![Heatmap](/Assets/Heatmap.png)

To show which crimes are most common in the Tenderloin district in comparison to other districts in San Francisco a bokeh plot where the charts are stacked on top of each other are shown below. Each district is represented by percent wise incidence of each crime over the total crime composition per district. It is clear that the Tenderloin district has higher percent wise drugs/narcotics incidence than any other district and that this is a problem in the area. According to the article by C.W.Nevius this is a known problem but however complicated to get rid of. It is clear that crime is a problem in this district. 

