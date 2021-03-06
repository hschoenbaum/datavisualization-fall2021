## Data Assignment 3

We first cleaned this data set tracking lime scooters in D.C.

[Lime Scooter data ORIGINAL](https://data.lime.bike/api/partners/v1/gbfs/washington_dc/free_bike_status.json)

[Lime Scooter data FINAL](https://github.com/hschoenbaum/datavisualization-fall2021/blob/main/Lime%20scooters%20data%20final%20as%20CSV.csv)

We decided that the first data set might not be useful to the project, so we also cleaned a second data set from the Vision Zero program tracking traffic collisions in D.C. 

[Vision Zero collision data ORIGINAL](https://github.com/hschoenbaum/datavisualization-fall2021/blob/main/Vision%20Zero%20Collision%20Data%20ORIGINAL.csv) 

[Vision Zero collision data FINAL](https://github.com/hschoenbaum/datavisualization-fall2021/blob/main/Vision%20Zero%20Safety%20Data%20Clean.csv)

(Note: Github is saying the .csv files are too large to view. We saved the clean Excel and .csv files if you are having trouble viewing and would like us to send them to you another way)

### Steps to clean our data sets
* First we downloaded the data in a .csv file. 
* We looked at the data and decided on which headers we wanted.
* We then transposed the data so it would be thin and not thick (more rows, fewer columns). 
* We determined that the blank fields should stay blank and did not need to be filled in with an N/A.
* We filtered the data set to figure out which categorizations the original data set had included.
* We then filtered the original data into those separate categories (For the first data set: Bike/scooter IDs, IOS numbers, lattitude, longitude, rental URIS; For the second data set: lattitude, longitude, object ID, global ID, request ID, user type, request type, request date, status, street segment ID and comments) and put that data into it's own respective sheet on Excel.
* Then, in a final sheet, we placed the data from each individual category into a column with a header so we could identify each independent scooter and its geographic data.
