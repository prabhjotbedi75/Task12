# Task12

RMQ:  
Install and configure 1 node RMQ cluster version 3.8.9 \n
The RMQ cluster should be on TLS and have a username/password 

Data should be persisted on disk

Add 2 more nodes to the cluster without restarting RMQ service on first one 

Create a vhost and a user with read-write permissions to the vhost

Create 2 queues (DATA, DATA_SIDELINE) on the above created vhost   

Testing : 

Create a publisher and consumer for the DATA queue 

Publish 100 messages to DATA queue  

Aerospike:

Install and configure 1 node Aerospike cluster community edition 

The AS cluster should have a username/password

Data should be persisted on disk 

Add 2 more nodes to the cluster without restarting AS service on first one Create a namespace Orders 

Testing: 

Write a program using an AS client to write and read the data from AS 

The namespace should have the following sets (buyer details, product details)

Each set should have 3000 records. 

The records should have an expiry of 24h
