<img src="https://raw.githubusercontent.com/madd86/awesome-system-design/master/media/logo.png" align="center" width="850">
<p align="center">
  <a href="https://github.com/sindresorhus/awesome">
    <img alt="Awesome" src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg" />
  </a>
</p>
If you appreciate the content 📖, support projects visibility, give 👍| ⭐| 👏

A curated list of awesome System Designing articles, videos and resources for distributed computing, AKA Big Data.

Whether you're preparing for an interview or you want to design a distributed/microservice oriented application, this list will definitely help you achieve that.

Attention: Stars on GitHub does not reflect usage or popularity for every item here listed.

Inspired By [Awesome-BigData](https://GitHub.com/onurakpolat/awesome-bigdata/blob/master/README.md)

Started By Gabriel Leon de Mattos

## Contents

[Articles](#articles)

[Books](#books)

[Videos](#videos)

[Tools](#tools)

* [Relational Database](#Relational-Database-Management-System)
* [NoSQL](#NoSQL)
* [Distributed File Systems](#Distributed-File-Systems)
* [Resource Management](#Resource-Management)
* [Stream Processing](#Stream-Processing)
* [Message Broker](#Message-Broker)
* [Load Balancers](#Load-Balancers)
* [Hadoop Ecosystem](#Hadoop-Ecosystem)
* [REST Framework](#REST-Framework)

[Bonus](#bonus)

# Articles

## Introduction / Interviews 

- [System Design Primer](https://GitHub.com/donnemartin/system-design-primer) - [109k ⭐] - Awesome compilation of resources, including Anki flashcard decks.

- [System Design Interview Questions - Concepts you should know](https://www.freecodecamp.org/news/systems-design-for-interviews/) - A curated list of topics to introduce you to system design.

- [Grokking the System Design Interview](https://www.educative.io/courses/grokking-the-system-design-interview) - [Paid 💵] - Grokking System Design preparation is one of the most talked about course. The best thing about it is the design of applications it suggests rather than explanations of what each tool is supposed to do.

- [System Design in Software Development](https://medium.com/the-andela-way/system-design-in-software-development-f360ce6fcbb9) - Basic article on the topics of system design and architecture.

- [System Design](https://www.interviewbit.com/courses/system-design/) - Introductory interview preparation resources.

- [Design Pattern for Distributed Systems](https://www.codemag.com/Article/1909071/Design-Patterns-for-Distributed-Systems) - Article talking about some patterns as well as some technologies to be considered.

- [System Design Roadmap](https://roadmap.sh/system-design) - Step by step guide to System Design.

## Advanced 

- [Distributed Computing](https://en.wikipedia.org/wiki/Distributed_computing) - Wikipedia article broadening the view of distributed system design.

- [Fallacies of Distributed Computing](https://en.wikipedia.org/wiki/Fallacies_of_distributed_computing) - Wikipedia article introducing the topic of fallacies of distributed computing and its effects.

- [Fallacies of Distributed Computing Explained](http://www.rgoarchitects.com/Files/fallacies.pdf) - In depth explanation of the fallacies mentioned above.

- [CAP Theorem](https://www.ibm.com/cloud/learn/cap-theorem) - IBM Article about CAP Theorem, Microservices and NoSQL DBs. 

- [Pattern: Microservice Architecture](https://microservices.io/patterns/microservices.html) - Good article talking about Microservice architecture as well as its drawbacks.

- [Taxonomy of Distributed Systems](https://www.cs.rutgers.edu/~pxk/rutgers/notes/content/01-intro.pdf) - 11 Page lecture classifying distributed systems and specifically why we need them.

- [Top 10 Secure Coding Practices](https://wiki.sei.cmu.edu/confluence/display/seccode/Top+10+Secure+Coding+Practices) - Brief article talking about good practices for code securities.

- [Scalable Web Architecture and Distributed Systems](http://www.aosabook.org/en/distsys.html) - Good article about distributed systems as well as some of the potential tools.

---

# Books

- [Designing Distributed Systems: Patterns and Paradigms for Scalable, Reliable Services](https://www.amazon.com/Designing-Distributed-Systems-Patterns-Paradigms/dp/1491983647) - [Paid 💵] - Book that talks about disitributed systems as well as lightly demonstrating some code of what it looks like.

- [Designing Data Intensive Applications](https://www.amazon.com/Designing-Data-Intensive-Applications-Reliable-Maintainable/dp/1449373321/ref=pd_lpo_14_t_0/140-0179130-4076567?_encoding=UTF8&pd_rd_i=1449373321&pd_rd_r=e1f26397-6b89-4ffe-923f-21ad2d124b7a&pd_rd_w=7kW0U&pd_rd_wg=HYohZ&pf_rd_p=7b36d496-f366-4631-94d3-61b87b52511b&pf_rd_r=FC1XXD2Q6DDAJ4Z1RN2K&psc=1&refRID=FC1XXD2Q6DDAJ4Z1RN2K) - [Paid 💵] - Goes in depth to explain various resources we use when working with distributed systems, as well as how it came to be and what problems it aims to solve.

- [The System Design Manual](https://systemdesignmanual.com/) - [Paid 💵] - Covers the core aspects of distributed systems, like: network fundamentals, the theory underpinning distributed systems, architectural patterns of scalable systems, stability patterns that harden systems against failures and operational best-practices on how to maintain large-scale systems with a small team.

- [Building Microservices](http://ce.sharif.edu/courses/96-97/1/ce924-1/resources/root/Books/building-microservices-designing-fine-grained-systems.pdf) - [Free 👍] - Awesome book that talks about designing sytem architecture with microservices in depth, includes most relevant topics in this regard.

- [Monolith to Microservices](https://www.nginx.com/resources/library/monolith-to-microservices/) - [Free 👍] - Written by the same author as the one above, this book will cover the migration from Monolith to Microservices, it's recommended you start by the previous book.

- [Distributed Systems (3rd Edition)](https://www.distributed-systems.net/index.php/books/ds3/) - [Free 👍] - Great overview of and in-depth introduction to distributed systems. Recommended for intermediate level readers.
---

# Videos

A collection of videos based on distributed systems.

## Introduction / Interviews

- [Gaurav Sen - System Design Series](https://www.youtube.com/watch?v=xpDnVSmNFX0&list=PLMCXHnjXnTnvo6alSjVkgxV-VH6EPyvoX) - Good resource for people who want to learn more about system design, introduces the topic in a very easy to understand way.

- [Tech Dummies - System Design Series](https://www.youtube.com/watch?v=mhUQe4BKZXs&list=PLkQkbY7JNJuBoTemzQfjym0sqbOHt5fnV) - Another introduction to system design.

- [Mock System Design Interview at Google](https://www.youtube.com/watch?v=q0KGYwNbf-0) - Overview of what an interview on system design would look like from the perspective of a flawed but close fulfilling of the requirements. Key thing here is how the interaction with the interviewer goes.

- [Google Preparation Guide](https://www.youtube.com/watch?v=Gg318hR5JY0) - A quick video explaining how they interview.

- [System Design Interview](https://www.youtube.com/c/SystemDesignInterview/) - YouTube channel focussed on content specific to system design interviews, with detailed explanation of a variety of problems.

- [Intro to Architecture and System Design Interviews](https://www.youtube.com/watch?v=ZgdS0EUmn70) - A youtube video with Jackson Gabbard with good info about system design interviews.

- [System Design Introduction for Interview](https://www.youtube.com/watch?v=UzLMhqg3_Wc) - Tushar's intro to System Design.

- [Distributed Systems](https://www.youtube.com/playlist?list=PLOE1GTZ5ouRPbpTnrZ3Wqjamfwn_Q5Y9A) - This is an introductory course in Distributed Systems made by Chris Colohan. He got PhD from Carnegie Mellon, then spent 10 years working at Google building distributed systems. 

- [The Easy Way](https://www.youtube.com/channel/UCVZfU1sp66H9d4sdYx4iNkQ) - Up and coming channel with easy to understand videos about Distributed Systems.

- [System Design by SDE Skills](https://www.youtube.com/playlist?list=PLBtMh4xfa9FHSMKKgPZcPfoPbZmND5PC-) - Good resource for people who are preparing for System Design interviews, there are multiple system design mock interviews and deep dives.

- [System Design by CodeKarle](https://www.youtube.com/watch?v=EpASu_1dUdE&list=PLhgw50vUymyckXl3D1IlXoVl94wknJfUC) - Another great free resource, a list of commonly asked interview questions.

## Advanced

- [The evolution of Reddit Architecture](https://www.youtube.com/watch?v=nUcO7n4hek4) - Overview of how Reddit system design scaled. 
- [6.824 Distributed Systems by MIT](https://www.youtube.com/playlist?list=PLrw6a1wE39_tb2fErI4-WkMbsvGQk9_UB) - Graduate level course on distributed systems from MIT (2020).
- [CSE138 Distributed Systems by UCSC](https://www.youtube.com/playlist?list=PLNPUF5QyWU8O0Wd8QDh9KaM1ggsxspJ31) - Undergraduate course on distributed systems from UCSC (2020).

# Tools

- A collection of most commonly used tools for distributed systems

## Relational Database Management System


- [MariaDB](https://mariadb.org/) - MariaDB is a fork of MySQL server.

- [MySQL](https://dev.mysql.com/) - Widely used relational database.

- [PostgresSQL](https://www.postgresql.org/) - Relational database that has been gaining popularity.

- [SQLite](https://www.sqlite.org/index.html) - Another widely used database that is built into all mobile phones and most computers.

- [Sql Server](https://www.microsoft.com/en-us/sql-server) - Widely used relational database.


## NoSQL

### Cache (Key-Value)

- [Apache Ignite](https://GitHub.com/apache/ignite) - [3.3k ⭐] - In memory caching with ACID properties.

- [Couchbase](https://developer.couchbase.com/open-source-projects) - Inspired by memcached, adding features such as replication and persistance.

- [Oracle Coherence](https://GitHub.com/oracle/coherence) - [126 ⭐] - High scaling, low latency in-memory caching.

- [Memcached](https://GitHub.com/memcached/memcached) - [10.2k ⭐] - One of the first in-memory caching database, high performing and multi-threaded.

- [Redis](https://GitHub.com/redis/redis) - [44k ⭐] - Widely used in-memory caching database with many added features such as persistent storage and supporting strings, lists, sets, hashses, streams, bitmaps, etc. 

### Store (Key-Value)

- [Apple FoundationDB](https://GitHub.com/apple/foundationdb) - [10k ⭐] - Multi-model (many data types in a single database), ACID key-value store. Easily scalable and fault tolerant.

- [Cosmos DB](https://docs.microsoft.com/en-us/azure/cosmos-db/introduction) - Microsoft's globally distributed, multi-model database service. Eastically and independently scale throughput and storage. SQL, MongoDB, Cassandra, Tables, Gremlin, and Spark APIs.


### Document Store

- [CouchDB](https://GitHub.com/apache/couchdb) - [4.6k ⭐] - ACID compliant NoSQL document-store DB, provides a RESTful HTTP API for reading and updating database documents.

- [MongoDB](https://www.mongodb.com/) - One of the most popular 'NoSQL' database for general purpose.

- [RethinkDB](https://GitHub.com/rethinkdb/rethinkdb) - [23.8k ⭐] - Document-store DB.

- [ElasticSearch](https://GitHub.com/elastic/elasticsearch) - [49.9k ⭐] - Widely popular 'NoSQL' database for fast and scalable search engines.

- [Cosmos DB](https://docs.microsoft.com/en-us/azure/cosmos-db/introduction) - Microsoft's globally distributed, multi-model database service. Eastically and independently scale throughput and storage. SQL, MongoDB, Cassandra, Tables, Gremlin, and Spark APIs.

### Wide Column Store

- [Amazon DynamoDB](https://aws.amazon.com/dynamodb/) - Key-Value and Document database, highly performant, scalable and secure.

- [Google Bigtable](https://cloud.google.com/bigtable) - Scalable and performant 'NoSQL' database for large analytical and operational workload.

- [Cassandra](https://cassandra.apache.org/) - Facebook-born project very fast, easily scalable, with option to include consistency with each operation. 

- [Scylla](https://GitHub.com/scylladb/scylla) - [4.9k ⭐] - 'NoSQL' data store using seastar framework, compatible with Cassandra.

- [HBase](https://GitHub.com/apache/hbase) - [3.6k ⭐] - Modeled after Google's Bigtable and written in Java. Developed as a part of Apache Hadoop project and runs on top of HDFS or Alluxio. (See [Hadoop Related](##hadoop-related))

- [Cosmos DB](https://docs.microsoft.com/en-us/azure/cosmos-db/introduction) - Microsoft's globally distributed, multi-model database service. Eastically and independently scale throughput and storage. SQL, MongoDB, Cassandra, Tables, Gremlin, and Spark APIs.

### Graph

- [Amazon Neptune](https://aws.amazon.com/neptune/) - Fast, reliable and fully managed graph database service.

- [ArangoDB](https://GitHub.com/arangodb/arangodb) - [10k ⭐] - Flexible database for documents, key-value, graphs. Uses its own query language, AQL.

- [Neo4j](https://GitHub.com/neo4j/neo4j) - [7.9k ⭐] - Good support for a graph db, ACID compliant and flexible.

- [Cosmos DB](https://docs.microsoft.com/en-us/azure/cosmos-db/introduction) - Microsoft's globally distributed, multi-model database service. Eastically and independently scale throughput and storage. SQL, MongoDB, Cassandra, Tables, Gremlin, and Spark APIs.

## Distributed File Systems

- [HDFS](https://hadoop.apache.org/) - Hadoop File System is a a widely popular choice among its big data competitors, providing high throughput access.

- [Lustre](http://lustre.org/) - File system for computer clusters.

- [CephFS](https://ceph.io/) - Unified, distributed storage system. 

- [GlusterFS](https://www.gluster.org/) - Scale-out NAS file system.

- [MooseFS](https://moosefs.com/) - POSIX-compliant distributed file system.

- [XtreemFS](http://www.xtreemfs.org/) - Fault tolerant file system.

## Resource Management 

- [Kubernetes](https://kubernetes.io/) - Highly popular way to deploy, manage and automatically scale a cluster of containers on bare-metal or virtual servers.

## Stream Processing

- [Apache Samza](http://samza.apache.org/) - Build stateful applications that process data in real time from multiple sources, including Kafka. Easy and inexpensive multi-subscriber model, can eliminate backpressure and has reliable persistency with low latency.

- [Apache Flink](https://flink.apache.org/) - Based on the concept of streams and transofrmations. Uses maven, handles batch tasks as data streams with finite boundaries. Low latency, high throughput.

- [Amazon Kinesis Streams](https://aws.amazon.com/kinesis/data-streams/) - Durable, scalable, real-tme service. Collects gigabytes of data per second from hundreds of thousands of sources, including database event streams, website clickstreams, financial transactions, etc.

- [Azure Stream Analytics](https://azure.microsoft.com/en-us/services/stream-analytics/) - Real-time analytics service that is designed for mission-critical workloads.

## Message Broker

- [Amazon MQ](https://aws.amazon.com/amazon-mq/) - Open source message broker from Amazon.

- [Apache ActiveMQ](https://activemq.apache.org/) - It's a multi-protocol, java based messaging server. 

- [Apache Kafka](https://kafka.apache.org/) - Widely popular message broker with low latency for data streaming.

- [RabbitMQ](https://www.rabbitmq.com/) - Widely popular lightweight 
message broker written in erlang that also supports multiple messaging protocols.

- [IronMQ](https://www.iron.io/mq) - Very fast and highly scalable messaging broker. (not open source)

- [Apache Pulsar](https://pulsar.apache.org/) - Created by yahoo, also highly scalable, low latency, geo-replication and multi-tenacy. 

- [Kestrel](https://github.com/twitter-archive/kestrel) - Written in Scala and speaks the memcached protocol. It works much like Kafka. 

- [Azure Service Bus](https://docs.microsoft.com/en-us/azure/service-bus-messaging/service-bus-messaging-overview) - A fully managed enterprise integration message broker.

## Load Balancers

### Open Source Software

- [SeeSaw](https://GitHub.com/google/seesaw) - [5.1k ⭐] - Used by Google, developed in Go, linux-based virtual load balancer server.

- [HAProxy](https://www.haproxy.org/) - Widely popular option, provides high-availability, proxy, TCP/HTTP load balancing. Used by Reddit, Imgur, MaxCDN, GitHub, AirBNB. 

- [Zevenet](https://www.zevenet.com/products/community/#repository) - Supports L3, L4 and L7. Easy install with a docker repo. Supports advanced health-check monitorining.

- [Neutrino](https://neutrinoslb.GitHub.io/) - Used by eBay, built with Scala and Netty. Supports round-robin and least-connection algorithms.

- [Nginx](https://www.nginx.com/) - Wait, isn't Nginx a web server? Yes, the open source does support basic level of content switching and request routing. Plus edition supports load balancing, WAF, monitoring, etc.

- [Openresty](https://github.com/openresty/openresty) - Nginx + Lua, perfect combination.

### Hardware

- [F5](https://www.f5.com/services/resources/glossary/load-balancer) - Robust hardware load balancer option, supporting multiple protocols (IP, TCP, FTP, UDP, HTTP).

- [TP-Link](https://www.tp-link.com/) - Cheaper alternative that works as a load balancer.

- [Barracuda](https://www.barracuda.com/products/loadbalancer) - One of the top choices for load balancing when it comes to in-house servers. Top security measures built in, comprehensive reports and monitoring outbound traffic for data loss prevention.

### Cloud

- [Amazon Elastic Load Balancing](https://aws.amazon.com/elasticloadbalancing/) - Popular choice for amazon customers, supports lambda functions, highly scalable.

- [Google Load Balancing](https://cloud.google.com/load-balancing) - Popular choice for google customers, comes with auto-scaling feature, very fast, has intergrated CDN.

- [Cloudflare Load Balancing](https://www.cloudflare.com/load-balancing/) - Scalable load balancing by Cloudflare, feature fast failover and a dashboard.

- [DigitalOcean Load Balancing](https://www.digitalocean.com/docs/networking/load-balancers/) - If you're a digitalocean customer, this is a good option, very cheap, regional availability, scalable, easy to deploy among your other droplets.

- [Azure Load Balancing](https://docs.microsoft.com/en-us/azure/load-balancer/load-balancer-overview) - Popular choice for Microsoft's Azure customers. Supports internal and external traffics, ipv6, monitorining and the standard load balancing set of features.

##  Hadoop Ecosystem

<img src="https://raw.githubusercontent.com/madd86/awesome-system-design/master/media/hadoop-ecosystem.png" align="center" width="330">

### Dashboard
- [Ambari](https://ambari.apache.org/) - Dashboard that integrates most of hadoop related technologies for easy management and executions.

### Data Ingestion

- [Sqoop](https://sqoop.apache.org/) - Efficiently transfer data between Hadoop and structured datastores such as relational databases.

- [Flume](https://flume.apache.org/) - Distributed, highly available and efficient in collecting, aggregating and moving large amounts of log data. 

- [Apache Kafka](https://kafka.apache.org/) - Widely popular message broker with low latency for data streaming.

### Workflow Scheduler

- [Oozie](https://oozie.apache.org/) - Create workflows in xml to execute jobs (from other hadoop-ecosystem applications) in steps, allows for parallel execution as well. 

### Query

- [Hive](https://hive.apache.org/) - Query hadoop stored data in SQL.
- [Pig](https://pig.apache.org/) - Scriping language that looks like SQL to query hadoop data.

### Processing

- [Tez](https://tez.apache.org/) - Solves a similar problem to Spark and MapReduce, it's more efficient than MapReduce because it calculates the most efficient way of doing it.
- [Map Reduce](https://hadoop.apache.org/docs/current/hadoop-mapreduce-client/hadoop-mapreduce-client-core/MapReduceTutorial.html) - MapReduce, as the name implies, maps data and reduce the results. 
- [Spark](https://spark.apache.org/) - Powerful data processing to not only process data like Tez (and MapReduce), it can process streams of data in real time, apply regression analysis algorithms in ML and much more. 
- [Apex](https://apex.apache.org/) - *Retired project, it's a YARN-native platform that unifies stream and batch processing. 

### DB

- [HBase](https://GitHub.com/apache/hbase) - [3.6k ⭐] - Modeled after Google's Bigtable and written in Java. Developed as a part of Apache Hadoop project.

### Resource Management

- [YARN](https://hadoop.apache.org/docs/current/hadoop-yarn/hadoop-yarn-site/YARN.html) - 'Yet Another Resource Negotiator', works like a kernel to manage computer resources across the clusters. 
- [MESOS](http://mesos.apache.org/) - Works like a Linux Kernel by managing CPU, memory, storage and other resources across the cluster. 


## REST Framework

- [Gin](https://github.com/gin-gonic/gin) - [40.6k ⭐] - Blazingly fast microservice framework using Golang, high throughput capacity.

- [Phoenix](https://github.com/phoenixframework/phoenix) - [15.5k ⭐] - Distributed processing, easily scalable, support for channels and live chat. This framework - written in Elixir, uses BEAM and Erlang, very efficient for large scale systems and supports high throughput.

- [Express.js](https://github.com/expressjs/express) - [49.6k ⭐] - Fast node.js rest api that can perform well under many scenarios.

- [Rails](https://github.com/rails/rails) - [46.2k ⭐] - Written in Ruby, Rails delivers quick apis from prototype to production in an efficient manner.

- [Play Framework](https://github.com/playframework/playframework) - [11.6k ⭐] - Very fast, high throughput framework written in Scala/Java that is RESTful by default.

- [Flask](https://github.com/pallets/flask) - [51.6k ⭐] - A lightweight Python Microframework for fast prototyping and production. 

- [FastAPI](https://github.com/tiangolo/fastapi) - [22.7k ⭐] - A lightweight Python Microframework inspired in Flask but more modern, using Python async.

- [Django REST](https://github.com/encode/django-rest-framework) - [18.4k ⭐] - Written in Python, Django Rest is a powerful and flexible REST API. The efficiency and time to market resembles Rails.

- [ASP.NET Core MVC](https://docs.microsoft.com/en-us/aspnet/core/mvc/overview?view=aspnetcore-3.1) - A rich framework for building web apps and APIs using the Model-View-Controller design pattern in C# or F#. Number 6 on [TechEmpower Composite Benchmarks](https://www.techempower.com/benchmarks/#section=data-r19&hw=ph&test=composite) for web frameworks.

- [Fastify](https://github.com/fastify/fastify) - [15.4k ⭐] - A Node.js web framework highly focused on providing the best developer experience with the least overhead and a powerful plugin architecture.
