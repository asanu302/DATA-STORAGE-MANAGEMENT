# DATA-STORAGE-MANAGEMENT
Project on testing and comparing performance, speed  two different NOSQL database using bigdata using HBase and MongoDB

# About
The two database chosen for research purpose is MongoDB and
HBase and workloads was chosen with operational counts 0.2 million to 0.5 million.

# Performance test Design
1)Two workloads of different operation percentage is chosen for test count workload A and
workload B, their specification are
Workload A specification is divided in 50-50 in read and update operation respectively,
Read operation (A) =50% and Update (A)= 50%.  
2)Workload A specification is divided in 95-5 for read and update operation respectively,
Read operation (B) =95% and Update (B)= 5%.  
3)The two workloads are run on two database with different operational counts. 4 operational
counts are chosen 200K, 300K, 400K, 500K to understand the operational nature of
database with respect to time.  

# Visualisation  
1) And then these value
of 16 dataset having same data from same opcounts operation and value is fed in
visualization tool Tableau differently to create tabular form from which line chart data is
extracted for visualization purpose to make comparison on database performance.  
2) In Tableau total 6 graphs are prepared like 
OPcounts vs overall Throughput,   
Read operation vs Read average latency,  
Update operation vs Update average latency for workload A and
Workload B and checking performance of database.  
3) The values of average latency, read
operation, update operation, throughput is calculated and compared to check performance
of database. 
