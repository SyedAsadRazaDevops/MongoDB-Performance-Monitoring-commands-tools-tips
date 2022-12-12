### Best MongoDB Monitoring Tools and Services
# Top Solutions for MongoDB Performance Monitoring
There are two types of tools to pick from when it comes to MongoDB monitoring: built-in commands and fully-fledged observability solutions. Below I’ll compare both of them with their pros and cons to help you make the best choice for your use case.

## 1. Built-in MongoDB Monitoring Commands
MongoDB provides two very useful commands to check its health and status:

1- **mongostat**
You can use mongostat to get a quick overview of the MongoDB instance with information about the number of operations, usage, size, and network utilization.

2- **mongotop**
The mongotop command gives you information on MongoDB’s read and write operations, exposed in read time and printed by default, every second.

3- **serverStatus** returns the general status of the database,

4- **dbStats** returns the storage statistics for a selected database,

5- **collStats** returns the statistics on the collection level,

6- **replSetGetStatus** returns the status of the replica set from the perspective of local MongoDB server on which you will run the command.
