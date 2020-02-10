# Bigdata2020UTM

## Syllabus contents
  ### Explain the impact of data today
   #### In the matter of "Big Data" there are many ways in which they can cause great impact on the data, but in principle it can be oriented towards the devices with technology that are now appearing, they are equipment that are constantly connected to a Wi-Fi network and so on they are linked to a database which is of infinite capacity, because we are not talking about a single device we are dealing with milies or even millions of devices which are in continuous contact with a server; all this to explain that with the creation of data collected day by day it is simultaneously affecting the way of seeing the data as points at which to join them to get information
   
  ### Explain the causes by which has been increased the data generation
   #### The way in which data is quickly generated over time increases and the value of this is reduced. If companies do not obtain the data in a truthful way they can be lost used in an erroneous way, and one of the main reasons why this happens is because at present thousands of devices are constantly generating data
  ### Define the Big data concept
   #### It is a term that describes the large volume of data, both structured and unstructured.
  ### Differentiate between two public and private data
   #### Public data can be consulted and modified by general users, private data can be viewed or consulted even until modified only by a group of users with special permissions
  ### Differentiate between structured data and unstructured data
   #### The sturged data are those that are commonly found in a database, organized by columns and rows with titles and an example of the unstudified data we can give as an example a code in binary language, we will see it in a framework of many data without a apparent order and messy   
  ### Differentiate between stored and moving data
   #### The moving data is found as packets that are in constant motion in some network and the stored data can be for example the files stored in a computer of a common user which are not going to be sent by a data network and are for use personal
  ### Explain the concept of data analysis
   #### Data analysis is used in large companies to debug the information collected and be able to use it in their favor
  ### Explain the impact of data analysis on organizations
   #### It improves the quality of the information to use it in favor, it can be seen as a way of treating water, having a large amount of liquid and passing it through a filter to give it a commercial usu or in favor of some process just as it could be used to make a better decision

# Other topics

### MapReduce
  #### It is a programming model that allows and supports the management of parallel processes
### Hadoop HDFS
  ####  It is a high capacity data processing system
### Apache Spark
  #### It is an open source programming model for storing and executing applications


## Github commands
#### $ git init: Create a new repository

#### $ git add [file]: Add a file to the repository to be saved

#### $ git log: Shows the versions of the commits made in the current repository

#### $ git reset [confirmation]: Reverses an erroneous confirmation and retains changes made locally

#### $ git status: Shows all changes made to the repository where it is located

#### $ git diff --estatus: Show file differences between the waiting area and the latest version of the file

#### $ git rm [file]: Deletes the file regardless of whether a previous commit was made0

#### $ git commit -m "[descriptive message]": Back up a previously added file with the "git add [file]" command
---
# Tarea1
---
## Life cycle of data analysis

### Business Understanding:
#### This initial phase focuses on understanding the objectives and requirements of the project from a business perspective, and then converting this knowledge into a definition of data mining problem. A preliminary plan is designed to achieve the objectives. A decision model can be used, especially one created using the decision model and the notation standard.

### Understanding the data:
#### The data comprehension phase begins with an initial collection of data and continues with activities to familiarize yourself with the data, identify data quality problems, discover the first ideas about the data or detect interesting subsets to form hypotheses to hide information. 

### Data Preparation:
####  The data preparation phase covers all activities to build the final data set (data that will be incorporated into the modeling tools) from the initial raw data. Data preparation tasks are likely to be performed several times and not in the prescribed order. Tasks include the selection of tables, records and attributes, as well as the transformation and cleaning of data for modeling tools.

### Modeling:
#### In this phase, several modeling techniques are selected and applied and their parameters are calibrated to optimal values. Generally, there are several techniques for the same type of data mining problem. Some techniques have specific requirements on the form of the data. Therefore, it is often required to go back to the data preparation phase.

### Evaluation:
#### At this stage of the project, you have created a model (or models) that seems to have high quality, from the perspective of data analysis. Before proceeding with the final deployment of the model, it is important to evaluate it thoroughly and review the steps taken to build the model, to ensure that it adequately achieves business objectives. A key objective is to determine if there is an important commercial problem that has not been sufficiently considered. At the end of this phase, a decision must be reached on the use of data mining results.

### Implementation:
#### Model creation is generally not the end of the project. Even if the purpose of the model is to increase the knowledge of the data, the knowledge acquired should be organized and presented in a way that is useful to the customer. Depending on the requirements, the implementation phase can be as simple as generating a report or as complex as implementing a repeatable data score (for example, segment assignment) or a data mining process.
---
## Types of statistics

### Inferential statistics:
#### Inferential statistics are produced through complex mathematical calculations that allow scientists to infer trends over a larger population based on the study of a sample taken from it. Scientists use inferential statistics to examine the relationships between variables within a sample and then make generalizations or predictions about how those variables will relate to a larger population.

### Descriptive statistics:
#### Descriptive statistics is the type of statistics that probably arises in the minds of most people when they hear the word "statistics." In this branch of statistics, the objective is to describe. Numerical measurements are used to report the characteristics of a data set. There are a number of elements that belong to this part of the statistics.

### APPLIED:
####  It is made up of the two kinds of previous statistics. Its objective is to deduce results on a universe, from a given sample. This type of statistics can be applied in any area that does not belong to it, such as history, psychology, etc.

### MATHEMATICAL STATISTICS:
#### It refers to the use of statistics but from a formal point of view, through the use of different branches of mathematics and probability theory. Its use is necessary because the data handled by mathematical statistics are random and uncertain.
---
## EDA
#### Exploratory Data Analysis (EDA) is an approach / philosophy for data analysis that employs a variety of (mainly graphic) techniques to:
1. Maximize knowledge of a data set;
2. Discover the underlying structure;
3. Extract important variables;
4. Detect outliers and anomalies;
5. Prove underlying assumptions;
6. Develop parsimonious models; Y
7. Determine the optimal factor setting.

### Techniques:
#### Most EDA techniques are graphic in nature with some quantitative techniques. The reason for the great dependence on graphics is that, by their very nature, the main role of EDA is to explore openly, and graphics give analysts an incomparable power to do so, attract data to reveal their structural secrets and be always ready. to get a new, often unsuspected, view of the data. In combination with the natural pattern recognition capabilities we all possess, the graphics provide, of course, unmatched power to carry it out.
---
## ETL
#### ETL is short for extract, transform, load, three database functions that are combined into one tool to pull data out of one database and place it into another database.
#### Extract is the process of reading data from a database. In this stage, the data is collected, often from multiple and different types of sources.

#### Transform is the process of converting the extracted data from its previous form into the form it needs to be in so that it can be placed into another database. Transformation occurs by using rules or lookup tables or by combining the data with other data.

#### Load is the process of writing the data into the target database.

### How ETL Works:
#### Data from one or more sources is extracted and then copied to the data warehouse. When dealing with large volumes of data and multiple source systems, the data is consolidated. ETL is used to migrate data from one database to another, and is often the specific process required to load data to and from data marts and data warehouses, but is a process that is also used to to large convert (transform) databases from one format or type to another.
---
## Data flow diagram
#### A data flow diagram (DFD) illustrates the flow and transformation of data for a particular business process. It is a visual representation of how data flows through a system, so you can clearly see where the data comes from, where it goes and how it is stored.

### Elements of a data flow diagram:
#### The processes are a circle or a square with a horizontal line along the top. A process is a business activity in which data manipulation and transformation occurs. Something happens to the data during a process.

#### The arrows represent the way data flows. Use the type of data that moves through the system as the name for the arrow.

#### An external entity is shown as a square. An external entity can be a person, a system or an application. It is where the data starts or ends.

#### The data stores are rectangles (sometimes with a vertical line in the symbol) and show where the required or produced data is stored in relation to the process.
---
