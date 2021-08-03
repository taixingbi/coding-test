### Hadoop

1. What are the basic differences between relational database and HDFS?

|| RDBMS  | Hadoop |
|-------------| ------------- | ------------- |
| Data Types	  | RDBMS relies on the structured data and the schema of the data is always known.  | Any kind of data can be stored into Hadoop i.e. Be it structured, unstructured or semi-structured.|
| Processing  | RDBMS provides limited or no processing capabilities.  | Hadoop allows us to process the data which is **distributed across the cluster in a parallel** fashion.|
| Schema on Read Vs. Write  | RDBMS is based on schema on **write policy** where schema validation is done before loading the data.  |On the contrary, Hadoop follows the schema on **read policy**. |

2. Explain “Big Data” and what are five V’s of Big Data?
* **Volume**: The volume represents the **amount of data** which is growing at an **exponential rate** i.e. in Petabytes and Exabytes. 
Velocity: Velocity refers to the rate at which data is growing, which is very fast. Today, yesterday’s data are considered as old data. Nowadays, social media is a major contributor to the velocity of growing data.
* **Variety**: Variety refers to the heterogeneity of data types. In another word, the data which are gathered has a **variety of formats** like videos, audios, csv, etc. So, these various formats represent the variety of data.
* **Veracity**: Veracity refers to the data in doubt or uncertainty of data available due to data inconsistency and incompleteness. Data available can sometimes get messy and may be difficult to trust. With many forms of big data, quality and accuracy are difficult to control. The volume is often the reason behind for the lack of quality and accuracy in the data.
* **Value**: It is all well and good to have access to big data but unless we can turn it into a value it is useless. By turning it into value I mean, Is it adding to the benefits of the organizations? Is the organization working on Big Data achieving high ROI (Return On Investment)? Unless, it adds to their profits by working on Big Data, it is useless.

3. What is Hadoop and its components. 
When “Big Data” emerged as a problem, Apache Hadoop evolved as a solution to it. Apache Hadoop is a **framework** which provides us various services or tools to **store and process Big Data**. It helps in analyzing Big Data and making business decisions out of it, which can’t be done efficiently and effectively using traditional systems.

4. What are HDFS and YARN?
* **HDFS** (Hadoop Distributed File System) is the **storage unit** of Hadoop. It is responsible for storing different kinds of data as **blocks in a distributed environment**. It follows master and slave topology.

  * **NameNode**: NameNode is the **master node** in the distributed environment and it **maintains** the metadata **information** for the blocks of data stored in HDFS like block location, replication factors etc.   
  * **DataNode**: DataNodes are the **slave nodes**, which are responsible for **storing data** in the HDFS. NameNode manages all the DataNodes.
**YARN** (Yet Another Resource Negotiator) is the processing framework in Hadoop, which manages resources and provides an execution environment to the processes.

*  **YARN**.   
   * **ResourceManager**: It receives the **processing requests**, and then passes the parts of requests to corresponding **NodeManagers** accordingly, where the actual processing takes place. It allocates resources to applications based on the needs.  
   * **NodeManager**: NodeManager is installed on **every DataNode** and it is responsible for the **execution** of the task on every single DataNode.

5. How is HDFS fault tolerant? 
When data is stored over HDFS, **NameNode replicates the data to several DataNode**. The **default replication factor** is **3**. You can change the configuration factor as per your need. If a DataNode goes down, the NameNode will automatically copy the data to another node from the replicas and make the data available. This provides fault tolerance in HDFS.

6 What is MapReduce?
Referred as the core of Hadoop, MapReduce is a programming framework to process large sets of data or **big data across thousands of servers in a Hadoop Cluster**. The concept of MapReduce is similar to the cluster scale-out data processing systems. The term MapReduce refers to two important processes of Hadoop program operates.
* **Application Manager**: It accepts job-submissions, negotiates the container for ApplicationMaster and handles failures while executing MapReduce jobs.
* **Scheduler**: Scheduler allocates resources that is required by various MapReduce application running on the Hadoop cluster.

### Spark
1. How is Apache Spark different from MapReduce?     

| Apache Spark  | MapReduce |
| ------------- | ------------- |
| Spark processes data in **batches** as well as in **real-time**  | MapReduce processes data in **batches** only  |
| Spark runs almost **100 times faster** than Hadoop MapReduce | Hadoop MapReduce is **slower** when it comes to large scale data processing |
| Spark stores data in the **RAM** i.e. in-memory. So, it is easier to retrieve it | Hadoop MapReduce data is stored in **HDFS** and hence takes a long time to retrieve the data |
| Spark provides **caching and in-memory data storage** | Hadoop is highly **disk-dependent** |


### Four Major Aspects of Spark Streaming
* Fast recovery from failures and stragglers
* Better load balancing and resource usage
* Combining of streaming data with static datasets and interactive queries
* Native integration with advanced processing libraries (SQL, machine learning, graph processing)




### Kafka

1.  Mention what is the traditional method of **message transfer**?
The traditional method of message transfer includes two methods
* **Queuing**: In a queuing (rabbitmq), a pool of consumers may read message from the server and each message goes to one of them
* **Publish-Subscribe**(producer-consumer): In this model, messages are broadcasted to all consumers
Kafka caters single consumer abstraction that generalized both of the above- the consumer group.

3) Mention what is the benefits of Apache Kafka over the traditional technique?

Apache Kafka has following benefits above traditional messaging technique

* **Fast**: A single Kafka broker can serve thousands of clients by handling megabytes of reads and writes per second
* **Scalable**: Data are partitioned and streamlined over a cluster of machines to enable larger data
* **Durable**: Messages are persistent and is replicated within the cluster to prevent data loss
* **Distributed by Design**: It provides fault tolerance guarantees and durability



4) Mention what is the meaning of broker in Kafka?

In Kafka cluster, broker term is used to refer **Server**.

### monitor pipelines
1. Latency—The time it takes for your service to fulfill a request
2. Traffic—How much demand is directed at your service
3. Errors—The rate at which your service fails
4. Saturation—A measure of how close to fully utilized the service’s resources are
