# **nosql-challenge**
In this module challenge, we needed to create a MongoDB database housing UK restaurant data imported from json files. Some of the attributes of each restaurant in the database were name, address, atitude and longitude and hygiene score. 

After populating the database with the data, we needed to modify some of the data in the database. These modifications included inputting data, changing data types of fields, and deleting data. Because I ran some cells in the Jupyter notebook used to setup the database more than once, the entry/document for the restuarant "Penang Flavours" was created twice. Therefore, I needed to delete one of the entries for "Penang Flavours." Additionally, I was unaware that the longitude and latitude fields were within the geocode field, so when I initially tried to change the data types of longitude and latitude to the Double data type, I accidentally created two new fields, longitude and latitude as standalone fields. Therefore, I deleted these two new fields. 

Then, I performed some simple analysis, in accordance with the directions of the assignment. The analysis was comprised of querying establishments that matched certain criteria and turning the results into dataframes. These criteria were establishments that 
<li> have a hygiene score of 20 <li\>
<li> are in London and have a RatingValue greater than or equal to 4 <li\> 
<li> are closest to Penang Flavours, have a rating value of 5, and have the lowest 5 hygiene scores <li\>
<li> have a hygiene score of 0 and grouped by LocalAuthority <li\>


### **External Code Sources**
<li> Code used to delete fields (attributes) <li\>:

https://www.geeksforgeeks.org/how-to-remove-a-field-completely-from-a-mongodb-document/


