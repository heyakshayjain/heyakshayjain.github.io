


Data Warehouse vs Data mart vs Data lakes. honestly, These terms always confuse me, and I am never able to remember the definition of these terms. Hence, I think they all are the same.
But Wait!! They are not the same Today I will Explain them in the easiest way possible.
So, I'm going to take some real-life examples to try and relate with these terms' functionality which will then help you to understand them easily and Bonus!! you won't forget again easily.
So We'll first take the Data warehouse then Data Marts and lastly Data Lake.

# Data Warehouse


 ![Imagine Data Warehouse like a Library](https://www.zuar.com/blog/content/images/size/w2000/2020/04/data-mart.jpg)

Imagine Data Warehouse like a Library.

*Explanation* - The library stores all types of books systematically right.
Similarly, Data Warehouse integrates data from different sources and stores them in a systematic manner.
data Warehouse supports data mining, AI and machine learning, OLAP, and front-end reporting.
And finally, data warehouses and BI help organizations improve data quality, speed business insights, and improve decision-making, all of which can result in competitive gains.
 

# Data Marts

 
![Data Mart are like Vegetable Mart or any specific shop](https://images.theconversation.com/files/43092/original/54qnb7hj-1393940322.jpg?ixlib=rb-1.1.0&q=45&auto=format&w=1200&h=1200.0&fit=crop)

Data Marts are like a Super Mart or Shop selling some specific things to their customers.

*Explanation -* Mini mart or shops sells specific stuff like vegetable shop sells vegetables to their customers.
Similarly, Data Marts are specialized solutions used to store data for specific purposes like the HR department needs Employee data So there will be a data mart developed for the HR department.
A data mart Is an isolated part of the larger enterprise data warehouse that is specifically built to serve a particular business function, purpose, or community of users. Is designed to provide specific, timely, and rapid support for making tactical decisions. And typically has a star or snowflake schema. Data Mart is much like a data warehouse, except it has a smaller, tactical scope. Data warehouses broadly support the strategic requirements of the enterprise. Data marts are lean and fast compared to data warehouses, which can be very large, and hence, can be slower.

 

# Data Lake

 
![Data Lake](https://miro.medium.com/max/1400/1*G-R4fhGC60t4ULXg9W7Yig.jpeg)

Data Lake as the name suggests is a repository of data that contains structured,semi-structured, and unstructured data in its native format. You do not need to define the structure and schema of data before loading the data into the data lake. You do not even need to know all the use cases for which you will be analyzing the data. A data lake exists as a repository of raw data, straight from the source to be transformed based on the use case for which it needs to be analyzed, which does not mean that a data lake is a place where data can be dumped without governance. Scalability is another data lake benefit.-   By retaining data in its original format, data lakes save organizations time that would have been used to define structures, create schemas, and transform the data.

## Lets's talk about all three together

Let’s compare data lakes with data warehouses: When it comes to data, in a data lake, data is integrated in its raw and unstructured form. A data warehouse is different. Here all data has already been processed and conformed to standards prior to loading to the warehouse. Talking about schema, when using data lakes, you do not need to define the structure and schema of the data before loading it into the data lake. A data warehouse on the other hand requires strict conformance to schema and therefore a schema needs to be designed and implemented prior to loading the data. How does data quality differ when looking at data lakes and data warehouses? In data lakes, the data might or might not be curated, for example, raw data. And data is agile and does not necessarily comply with governance guidelines. In comparison, the data in data warehouses is curated and adheres to data governance. Here, we are looking at users of data lakes and data warehouses. Data scientists, data developers, and machine learning engineers are the typical users of data lakes. Data warehouses, on the other hand, are mainly used by business analysts, and data analysts.

> If you have suggestions or want to get in touch with me Just hit me with an email - heyakshayjain@gmail.com

   

