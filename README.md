# NFT--Network-Analysis

# Description
This project uses Kaggle to Download a dataset and uses Python, and pandas to execute SQL Queries and it creates a network visualization.



https://user-images.githubusercontent.com/97313664/190279458-8a905708-f3e9-4fdb-8042-c84038075b42.mp4


# Explanation 

This uses mainstream which  stores all NFT data which is then stored on Kaggle as  SQL lite database
This code uses SQLite to import all of the datasets stored on Kaggle then proceeds, to use pandas and reads different parts of the database. 
It then proceeds to get a list of the 5 biggest projects and sorts it from the total volume after grouping it by the nft address.


![4th Display](https://user-images.githubusercontent.com/97313664/190279857-0590f34e-c8c0-49fb-bb50-d092a50d31c4.png)
 
 #  Explanation
 -The first Df gives you the top 5, the nft address, and  volume
After seeing the top 5, it displays a dictionary that allows you to get from the address to the name.
The dictionary gets a list from all of the nft projects and names
-It shows the nft amount and the address and the owners

![4th Display](https://user-images.githubusercontent.com/97313664/190279857-0590f34e-c8c0-49fb-bb50-d092a50d31c4.png)

![1st Display](https://user-images.githubusercontent.com/97313664/190280065-6c788dc9-9819-4b29-9e39-ee5ac153432e.png)
 
 # Questions, Thoughts put into digits
 
 - It also groups the top 3 owners grouping all of the projects

-It displays an edge table of how much is owned by most people

-The bigger the size of the node the more people who are involve the thicker the line represents the particular edge of more owners.
 
 ![3rd Display](https://user-images.githubusercontent.com/97313664/190280110-f5574e06-0131-4e0a-a4c8-bfd3362905b3.png)

![2nd Display](https://user-images.githubusercontent.com/97313664/190280113-3758c305-7f3a-42e7-b7df-4e41bda7d838.png)
