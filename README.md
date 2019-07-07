
# Citi-Bike-Analysis

![alt text](https://d21xlh2maitm24.cloudfront.net/nyc/Annual-Membership-Image.png?mtime=20170331121650)


A analysis for the New York Citi Bike Program, in which responsible for overseeing the largest bike sharing program for 200,000+ data points in the United States
 in order to generate business insights in terms of visulize the peak time in both summer and winter period and the top start location in New York City and Jersey City, New Jersey
 
* Click [here](https://public.tableau.com/profile/nidhi1905#!/vizhome/CitibikesAnalysis/PeakHours?publish=yes) to view the completed dashboard




## Data Source
![alt text](Images/citibikedata.png)

This [Citi Bike Data](https://www.citibikenyc.com/system-data) has been processed to remove trips that are taken by staff as they service and inspect the system and any trips that were below 60 seconds in length 
(potentially false starts or users trying to re-dock a bike to ensure it's secure).

<table class="hide-while-loading table table-striped">
<tbody id="tbody-content">
<thead>
<tr>
<th>Name</th>
<th>Date Modified</th>
<th>Size</th>
<th>Type</th>
</tr>
</thead>
<tr>
<td>&nbsp;<a href="https://s3.amazonaws.com/tripdata/JC-201905-citibike-tripdata.csv.zip">JC-201905-citibike-tripdata.csv.zip</a></td>
<td>June 11th 2019</td>
<td>910 KB</td>
<td>ZIP file</td>
</tr>
<tr>
<td>&nbsp;<a href="https://s3.amazonaws.com/tripdata/JC-201904-citibike-tripdata.csv.zip">JC-201904-citibike-tripdata.csv.zip</a></td>
<td>May 6th 2019</td>
<td>847 KB</td>
<td>ZIP file</td>
</tr>
<tr>
<td>&nbsp;<a href="https://s3.amazonaws.com/tripdata/JC-201903-citibike-tripdata.csv.zip">JC-201903-citibike-tripdata.csv.zip</a></td>
<td>Apr 15th 2019</td>
<td>609 KB</td>
<td>ZIP file</td>
</tr>
<tr>
<td>&nbsp;<a href="https://s3.amazonaws.com/tripdata/JC-201902-citibike-tripdata.csv.zip">JC-201902-citibike-tripdata.csv.zip</a></td>
<td>Mar 4th 2019</td>
<td>480 KB</td>
<td>ZIP file</td>
</tr>
<tr>
<td>&nbsp;<a href="https://s3.amazonaws.com/tripdata/JC-201901-citibike-tripdata.csv.zip">JC-201901-citibike-tripdata.csv.zip</a></td>
<td>Feb 11th 2019</td>
<td>506 KB</td>
<td>ZIP file</td>
</tr>
<tr>
<td>&nbsp;<a href="https://datawrapper.dwcdn.net/cZMp8/5/">City Bike Daily Ridership and Membership Data :data-cZMp8.csv</a></td>
<td></td>
<td>3 KB</td>
<td>CSV</td>
</tr>
</tbody>
</table>




## Findings 


### (1) Total trips were 16 Mn over the period Jan to May 2019 . Riderships increased significantly in the month of march along with the 3-day pass purchase and 24 - hour pass purchase


![alt text](https://github.com/nidhirt/Citi-Bike-Analysis-/blob/master/Images/24%20hour%20passes%20Vs%203%20Days%20passes.png)
![alt text](https://github.com/nidhirt/Citi-Bike-Analysis-/blob/master/Images/Monthwise%20Trips.png)


### (2) The 1st and 2nd peak hours during a day would usually be 6-7 AM and 5-6 PM

![alt text](https://github.com/nidhirt/Citi-Bike-Analysis-/blob/master/Images/Peak%20start%20times%20in%20a%20day.png)
![alt text](https://github.com/nidhirt/Citi-Bike-Analysis-/blob/master/Images/Peak%20stop%20times%20in%20a%20day.png)

### (3) Popular stations were Grove St Path, Hamilton Park, Sip Ave,Harborside, 
![alt Text](https://github.com/nidhirt/Citi-Bike-Analysis-/blob/master/Images/Popular%20stations%20end.png)
![alt Text](https://github.com/nidhirt/Citi-Bike-Analysis-/blob/master/Images/Popular%20stations%20start.png)


### (4) Oldest Stations

The oldest average age station is Dey ST followed by Jeresy and 6th St , VAN Vorst park, astor place
![alt text](https://github.com/nidhirt/Citi-Bike-Analysis-/blob/master/Images/AVERAGE%20AGE%20STATION.png)



### (5) Bikers birth year and Trip duration
 Bikers with birth year in 1970 and 2000 clock the highest trip duration
 ![alt text](https://github.com/nidhirt/Citi-Bike-Analysis-/blob/master/Images/TRIP%20DURATIONS.png)
 



