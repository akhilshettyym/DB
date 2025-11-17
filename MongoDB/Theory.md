# MongoDB

- MongoDB is an open-source, NoSql document database used for modern applications, storing data in flexible, JSON-like documents called BSON instead of traditional tables.
- This approach provides a flexible schema, making it eaiser to handle unstructured or semistructured data and enabling rapid development and scalability.
- MongoDb is a general-purpose database that can hanbdle a wide range of appliactions, from social networks to big data and healthcare systems.
- BSON types is a Binary serialization format used to store docs and make remote procedure calls in MongoDB.

##### What is a schema - 
- A blueprint or model for how data is structured, either in a database or a conceptual framework.
- In DB, a schema defines the tables, fields, relationships, and other elements organize and govern data.

###### What is NoSQL - 
- A non-relational database that stores data in a flexible format other than traditional rows and columns of relational tables.
- It is basically used to handle large volumes of unstructured or semi-structured data, often associated with "BIG DATA" and real time web applications.

##### Organization of data.
###### Structured data :
- Data that conforms to a fixed schema or model, typically stored in relational databases with rows and columns.
- Highly organised and predictable.
- Less flexible as it must adhere to a predefined structure.
- Example - Spreadsheets(like Excel), SQL databases, and CSV files.

###### Unstructured data :
- Data that has no predefined organization and exists in its native format.
- Lacks a rigid structure , making it highly variable.
- Examples - Emails, audio files, images, and text docs.

###### Semi-structured data :
- Data that dosen't fit into the rigid structire of relational databases but has spome organizational properties like tags or markers to seperate data elements.
- Partially organized, offering more flexibility that structured data.
- More flexible than structured data, and simpler to scale.
- Example - JSON and XML files, HTML code, and email.

##### Key Features :
- Document-oriented : Stores data in flexible, JSON like docs instead of rigid tables, making it eaiser to model complex data and adapt to changes.
- Flexible schema : Allows for docs in the same collection to have different fields, supporting agile dev and varied data structures.
- Rich querying : Supports ad hoc queries with field, range, and regular-expression matching, along with a powerful, aggregation framework to perform data processing and summerization.

- Indexing : Uses various index types to speed up queries by avoiding full collection scans.
- Replicating : Creates and maintains copies of data on different servers( replica sets) to ensure high availability and fault tolerance.
- Scalability : Distributes data across multiple servers using sharding, allowing for horizontal scaling(scaling out) to handle large vol of data and traffic.
- Load balancing : Distributes the workload across servers, enhancing overall performance and reliability.

- Sharding - The process of breaking a large database into smaller, faster and more manageable parts called shards. By distributing these shards acorss multiple machines, sharding improves a systems scalability, performance and availability by reducing the load on any single server.
- Steps init :
horizontal partioning, Distribution, Parallel processing.

#### MongoD :
- Actual core engine of mongodb which runs all the logics in our system.
- It is the primary daemon process for the MongoDB database system. It functions as the core server process that manages data access, handles data requests from clients, and performs various background management operations necessary for the database to run.

#### MongoDB Compass :
- Official graphical user interface (GUI) for MongoDB, a tool allows user to visually explore, query, and analyze MongoDB databases without writing complex code.
- Provides user-friendly interface for tasks such as creating and updating docs, building aggregation pipelines, and monitoring database performance.

#### MongoDB SSH :
- Refers to connecting to a MongoDB databse through an SSH tunnel.
- Commenly employed when the MongoDB server is not directly accessible from your local machie, often due to security configs.

- By default MongoDB runs on 27017 port.