# K-Means-Clustering-of-Traffic-Collision-Data
Link: https://catalog.data.gov/dataset/traffic-collision-data-from-2010-to-present

Original Page: https://data.lacity.org/Public-Safety/Traffic-Collision-Data-from-2010-to-Present/d5tf-ez2w/about_data

This dataset reflects traffic collision incidents in the City of Los Angeles dating back to 2010. This data is transcribed from original traffic reports that are typed on paper and therefore there may be some inaccuracies within the data. Some location fields with missing data are noted as (0°, 0°). Address fields are only provided to the nearest hundred block in order to maintain privacy. This data is as accurate as the data in the database.

It has information on Victim Age, Descent, Gender, Address of the accident, type of area, date of reporting, time of collision and this was utilized in drawing several insights on frequency of collisions per hour of the day, location or gender. Then, after scaling the data, a KMeans clustering model was fit using different cluster numbers to assertain the ideal clusters required using the elbow method and it was decided that 3 clusters are the most ideal. 
