# Azure Flow Logs to Neo4j
I was reviewing large amounts of Azure flow data for threat hunting. Kabana was running slow for what I needed. So, I pushed the information to Neo4j and had a default dashboard in Neodash made.

![image](https://user-images.githubusercontent.com/50241257/215509472-7a5731c7-de70-4baa-bf40-5b235f22c97d.png)

Take all data needed export to csv. All nodes have to be unique and contigous. Your relationships can store data that is non contigous and unreliable (such as encrypted bytes are dashes and would cause an error).


### There are two main cell blocks in this example
1. Push all sessions as source and destiantion from csv, and types are all hosts.
2. Clear the database to rerun the the above.


### Notes
* This is a good way to vizualize large amounts of flow data for a specific event to draw information from all the data. 

* This also includes a dashboard template for neo dash. If you have known queries you would want to run against the data such as port break down in a pie chart or top amount of bytes by source. 

 
### Contact
***If you have issues and need help reach out to colleybrb@gmail.com

[MIT](https://choosealicense.com/licenses/mit/)
