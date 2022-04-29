Objective: Apache Spark is data processing framework that works faster than the traditional Hadoop framework which uses MapRequest API. Spark uses RDD (Resilient Distributed Databases) to handle data. This way, the data is organised in a uniform way inside the memory and is fault tolerant. Spark performs in memory computations and thats the reason for its immense speed. Spark also supports various API's for example, the Pyspark API is built on Apache Spark.

We took a bank operations dataset from the internet which is available on our GitHub repository. We used jupiter/pyspark-notebook which is a Docker Image to create a virtual environment that can run spark. We particularly used DataFrame API of Apache Spark to run SQL queries. We noticed that the execution of the queries were very fast.

Technology and Tools: Docker, Jupyter-Notebook

Libraries: pyspark, findspark, numpy ,pandas


To run the files:

    docker pull jupyter/pyspark-notebook
    docker run –it –p 8888:8888 jupyter/pyspark-notebook

Made by: Shantanu Goyal (2019UCS2026), Sujal Goel (2019UCS2014) and Anureet Kaur(2019UCS2037)
