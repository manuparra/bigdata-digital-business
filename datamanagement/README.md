# Data management in Big Data environments

![imagen](https://user-images.githubusercontent.com/7033451/220340857-10ac789f-2a3f-4ce5-8aa5-7aa796f7ebcc.png)

- [Data management in Big Data environments](#data-management-in-big-data-environments)
  * [Cloud computing or my laptop ?](#cloud-computing-or-my-laptop--)
- [BigData programming languages](#bigdata-programming-languages)
- [Platforms we will work with during the course](#platforms-we-will-work-with-during-the-course)
  * [Google Colaboratory](#google-colaboratory)
  * [Databricks](#databricks)
- [R as BigData tool](#r-as-bigdata-tool)
- [Starting BigData with R: Data management](#starting-bigdata-with-r--data-management)
  * [An example with SparkR](#an-example-with-sparkr)
  * [An example with Sparklyr](#an-example-with-sparklyr)
  * [Main operations in Data Management](#main-operations-in-data-management)
  * [Lets play with Databricks](#lets-play-with-databricks)

Databricks and Google Colab are both popular environments for working with big data, particularly in the context of data science and machine learning.

Databricks is a cloud-based platform that provides a unified analytics engine for processing and analyzing large datasets. It includes a number of tools and features for working with big data, such as Apache Spark for distributed data processing, Delta Lake for data storage and management, and MLflow for managing machine learning workflows.

Google Colab, on the other hand, is a cloud-based platform for running Jupyter notebooks that provides free access to computing resources, including GPUs and TPUs. It allows users to write and run Python code and includes a number of pre-installed libraries for working with big data, such as TensorFlow and PyTorch.

Both Databricks and Google Colab offer a number of benefits for working with big data, including:

- Scalability: Because they are cloud-based, these environments can easily scale to handle large datasets and computing workloads.
- Collaboration: Both platforms offer features for collaborating with other users, such as sharing notebooks and code.
- Access to resources: Databricks and Google Colab provide access to powerful computing resources, such as GPUs and TPUs, which can be used for accelerating machine learning and data processing tasks.

## Cloud computing or my laptop ?

There are several key differences between working with BigData in a cloud computing environment versus working with it on a local computer:

- Scalability: Cloud computing environments are designed to be highly scalable, which means they can easily handle large volumes of data and computing workloads. In contrast, a local computer may have limited resources and may struggle to handle very large datasets.
- Cost: Setting up a local environment for working with BigData can be expensive, as it may require purchasing high-end hardware and software licenses. In contrast, cloud computing platforms typically offer pay-as-you-go pricing, which can be more cost-effective for businesses that don't have the budget to invest in expensive hardware upfront.
- Flexibility: Cloud computing platforms offer more flexibility in terms of where and how data can be processed. For example, users can easily spin up new instances of virtual machines to process data in different geographic locations, or they can take advantage of cloud-based storage solutions to store and access data from anywhere.
- Security: Cloud computing platforms typically offer advanced security features to protect against data breaches and other types of cyber threats. However, businesses must still take precautions to ensure the security of their data when using cloud services.
- Skillset: Working with BigData in a cloud computing environment requires a different skillset than working with it on a local computer. Users must be familiar with cloud computing platforms, as well as the specific tools and services they offer for processing and analyzing data.

# BigData programming languages

There are several programming languages and features that are commonly used for BigData work, including:

- Java: Java is a popular programming language for BigData processing and analysis, due to its scalability and compatibility with the Hadoop ecosystem. Java-based tools such as Hadoop MapReduce and Apache Spark are widely used in BigData applications.
- Python: Python is another popular language for BigData work, thanks to its ease of use and wide range of data processing and analysis libraries, including NumPy, Pandas, and Scikit-learn. Python is also compatible with Hadoop and Spark, making it a versatile choice for BigData applications.
- SQL: Structured Query Language (SQL) is a standard language for managing and querying structured data in databases. Many BigData platforms, such as Apache Hive and Apache Phoenix, support SQL-based querying, making it a valuable skill for BigData analysts and engineers.
- Scala: Scala is a programming language that combines functional and object-oriented programming paradigms. It is particularly well-suited for BigData work, thanks to its compatibility with the Apache Spark platform and its support for distributed processing.
- R: R is a language and environment for statistical computing and graphics. It is widely used in BigData applications for data analysis and visualization, thanks to its extensive range of statistical and graphical libraries.

In addition to these programming languages, there are several key features and tools that are important for BigData work, such as:
- distributed processing, 
- parallel computing, and 
- data visualization

# Platforms we will work with during the course

## Google Colaboratory

Commonly known as Google Colab, is a cloud-based data science and machine learning platform that allows users to write and run Python code in a Jupyter notebook environment. It provides free access to a virtual machine with pre-installed packages and libraries for data analysis and machine learning, eliminating the need for users to install these tools on their local machines.

Some key features of Google Colab include:

- Jupyter notebooks: Google Colab provides a Jupyter notebook environment, which allows users to write and execute Python code in a web-based interface.
- Free GPU and TPU access: Google Colab provides free access to GPUs and TPUs, which can greatly accelerate the training of machine learning models.
- Collaboration: Users can share their notebooks with others, allowing for easy collaboration on data science projects.
- Cloud storage: Google Colab provides access to Google Drive, allowing users to easily store and share data and notebooks in the cloud.
- Pre-installed packages: Google Colab comes pre-installed with many popular Python packages and libraries, including NumPy, Pandas, Scikit-learn, and TensorFlow.

Overall, Google Colab provides a convenient and accessible platform for data analysis and machine learning, particularly for those who may not have access to high-performance computing resources on their local machines.

## Databricks 

Databricks is a cloud-based big data processing and analytics platform designed to handle large-scale data processing and machine learning workloads. It is built on top of Apache Spark and offers a collaborative workspace for data engineers, data scientists, and business analysts.

Some key features of Databricks include:

- Unified analytics platform: Databricks offers a unified platform for data processing, data analytics, and machine learning. It includes built-in tools for data visualization, data exploration, and model building.
- Apache Spark: Databricks is built on top of Apache Spark, an open-source big data processing engine that can handle large-scale data processing and machine learning workloads.
- Collaboration: Databricks provides a collaborative workspace for data engineers, data scientists, and business analysts. It includes built-in tools for version control, collaboration, and sharing.
- Scalability: Databricks is designed to scale horizontally, which means that it can handle large-scale data processing workloads without requiring significant changes to the underlying infrastructure.
- Security: Databricks provides built-in security features, including role-based access control, encryption, and network isolation.

# R as BigData tool

R is a powerful programming language and software environment for statistical computing and graphics. While R is often associated with traditional statistical analysis, it can also be used for big data processing and analytics.

There are several reasons why R can be a good choice for big data processing:
- Data manipulation and analysis: R has a rich set of libraries and packages for data manipulation and analysis. This makes it easy to perform complex data transformations, filtering, and aggregation operations on large datasets.
- Machine learning: R has a growing set of libraries and packages for machine learning, including algorithms for classification, regression, clustering, and more. These packages can be used to build models on large datasets and perform predictive analytics.
- Visualization: R has powerful tools for data visualization, including ggplot2, lattice, and others. These tools can be used to create high-quality plots and visualizations of big data.
- Community support: R has a large and active community of users and developers who contribute to its development and provide support through forums, blogs, and other resources.

When it comes to big data platforms for R, there are several options available:
- Apache Spark: Apache Spark is a popular big data processing engine that can be used with R. The sparklyr package provides an interface for using Spark with R, making it easy to process large datasets in a distributed manner.
- Hadoop: R can be used with Hadoop, a popular open-source big data platform. The rhdfs and rhbase packages provide interfaces for using Hadoop Distributed File System (HDFS) and Hadoop Database (HBase) with R.
- Amazon Web Services: Amazon Web Services (AWS) provides several big data platforms that can be used with R, including Amazon EMR (Elastic MapReduce), which provides a managed Hadoop cluster, and Amazon Redshift, a cloud-based data warehousing service.
- Microsoft Azure: Microsoft Azure provides several big data platforms that can be used with R, including HDInsight, a managed Hadoop cluster, and Azure Machine Learning, a cloud-based machine learning platform.

# Starting BigData with R: Data management

## An example with SparkR

A large dataset stored in a distributed file system such as Hadoop Distributed File System (HDFS) and we want to perform some data management tasks on it using SparkR. 

We first need to start a Spark session using SparkR and load the dataset into a Spark DataFrame. We can do this as follows:


```
# Load SparkR package
library(SparkR)

# Start a Spark session
sparkR.session()

# Load data into Spark DataFrame
df <- read.df("hdfs://path/to/dataset.csv", source = "csv", header = TRUE)
```

Once the data is loaded into the DataFrame, we can perform various data management tasks such as selecting columns, filtering rows, and aggregating data. Here are some examples:


```
# Select columns
selected_cols <- select(df, "col1", "col2")

# Filter rows based on a condition
filtered_rows <- filter(df, df$col1 > 10)

# Group data by a column and compute a summary statistic
grouped_data <- agg(df, "col1" = "sum", "col2" = "avg")

```

Finally, we can save the processed data back to a distributed file system:


```
# Save DataFrame to HDFS as Parquet file format
write.df(grouped_data, "hdfs://path/to/output.parquet", source = "parquet", mode = "overwrite")

```

## An example with Sparklyr

Suppose you have a large dataset in a distributed Spark cluster, and you want to perform some data manipulation tasks on it using R. You can use the sparklyr package to connect to the Spark cluster and manipulate the data using familiar R syntax.

First, you need to install the sparklyr package and load it into your R session:

```
install.packages("sparklyr")
library(sparklyr)
```

Next, you need to connect to your Spark cluster using the spark_connect() function. This function takes several arguments to specify the configuration of your Spark cluster, such as the Spark master URL and the number of executor nodes.

```
sc <- spark_connect(master = "spark://localhost:7077", version = "2.4.3")
```

Once you're connected to the Spark cluster, you can load your data into a Spark DataFrame using the spark_read_csv() function. This function takes several arguments to specify the location of the data, the file format, and any other configuration options.

```
my_data <- spark_read_csv(sc, "path/to/my/data.csv", header = TRUE, infer_schema = TRUE)
```

You can then perform various data manipulation tasks on the Spark DataFrame using the dplyr syntax, which is supported by sparklyr. For example, you can filter rows based on a condition using the filter() function:

```
filtered_data <- my_data %>% filter(column_name > 10)
```

You can also group the data by one or more columns using the group_by() function:

```
grouped_data <- my_data %>% group_by(column_name)
```

Finally, you can write the processed data back to the Spark cluster using the spark_write_csv() function:

```
spark_write_csv(filtered_data, "path/to/filtered_data.csv")
```

## Main operations in Data Management

1. Data import/export: This involves reading data from external sources such as CSV, Excel, or SQL databases, and exporting data in various formats. R provides several packages such as readr, readxl, RMySQL, and many more to import data, and write.csv or write.xlsx to export data.
2. Data cleaning: This involves identifying and correcting errors or inconsistencies in the data, such as missing values, duplicates, or outliers. R provides several packages such as dplyr, tidyr, and stringr that can be used to clean the data.
3. Data transformation: This involves manipulating the data to create new variables, aggregate data, or merge datasets. R provides several packages such as dplyr, tidyr, reshape2, and plyr that can be used for data transformation.
4. Data visualization: This involves creating plots and charts to better understand the data and identify patterns or trends. R provides several packages such as ggplot2, lattice, and base graphics for data visualization.
5. Data modeling: This involves building statistical models to make predictions or identify relationships between variables. R provides several packages such as lm, glm, randomForest, and many more for data modeling.

## Lets play with Databricks

Go to Databricks and create an free account.

Once created, you will see the next:

<img width="1243" alt="image" src="https://user-images.githubusercontent.com/7033451/220207960-3cfb126c-69ca-476c-8709-b98ebf1748ca.png">

Now it is time to create computing resources:

<img width="1243" alt="image" src="https://user-images.githubusercontent.com/7033451/220208128-c2f57d22-7d29-4dbc-9c8e-b152cd9b61c7.png">

Select version, name and features:

<img width="1243" alt="image" src="https://user-images.githubusercontent.com/7033451/220208219-ddfdc567-7567-4452-978d-405769e1bbd0.png">

After that, go to the main screen to create a new notebook:

<img width="1243" alt="image" src="https://user-images.githubusercontent.com/7033451/220208605-5c915df5-dcba-4dbd-9cf5-b0938dc1af63.png">

To work with the NoteBook, please go to the next link:

https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/1518758568839157/751086991269155/6568879399845276/latest.html







