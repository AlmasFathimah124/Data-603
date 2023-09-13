# Define Big Data with examples and types
## What is Big Data

   Big data is a set of large complex data that cannot be processed through traditional data processing tools.It comes in 
   increasing volumes and velocity of various different types.
   This data can be analysed to identify some trends and find meaningful insights to solve problems in business world.
## Examples of Big Data

- Streams of data generated on online through Facebook,Google,Youtube.
- Data generated from health care which includes details of patients and equipments and prescription.
- Information from manufacturing and retail stores about their customers,reviews and products
- Data from GPS, like traffic and weather alerts.
- Government sectors have huge amount of data like name,address of individuals and also information avout various policies.
- Transactional data produced in banking and financial services.
  
## Types of Big Data

## Structured Data

    Data is stored in a well defined format in the form of columns which can be easy to access.
    
    Ex:Tabular data from spreadsheets and databases
    
## Unstructured Data

    Data may be of different formats like texts,images,videos which can be difficult to access and process. 
    It comprises of 90% of big data.There might not be a specified format to process this data.

    Ex:Facebook,Google,Twitter has data various forms
    
## Semi-Structured Data

    It is a form of structural data but it doesn’t meet all the criteria of structured data.
    Semi structured data can be processed to structured data through NLP and other processes.

    Ex:XML

# 6 v's of Big Data
## Volume
  It refers to the huge amounts of data that is being generated from various sources especially from streaming 
  media,sensors which gives a lot of information.It has storage issues in the early days but now many sources are 
  available at affordable prices.It is difficult to process through normal query languages and traditional systems.
## Velocity
  The speed at which data is generated and flowed through databases systems. Now a days a lot of data is generated in 
  seconds from online resources.This kind of data has to be streamed and analyzed in real time.
## Variety
  Data generated from variety of sources.Like for example data can be of forms like texts,images,videos.It may contain 
  many errors in it and difficult process because we have to merge all the types of data into a specified format for 
  processing.Due to several linkages it is complex methodology.
## Veracity
  It is nothing but reliability and trust on the data that is accumulated. How much of the data we can trust without any 
  anomalies and discrepancies.We need to refine this data and process the data against some standard guidelines through 
  which we can conclude if the analysis is correct.It was introduced by IBM. Many statistical tools have been created to 
  deal with unreliable data.
## Value
  How much value we can generate from a given data.It should be greater than the cost of investment so that it create a 
  value in the market.Business leaders may think from the prospective of profits which may vary with technical associates 
  who have to take care of storage and processing.
## Variability
  The data that is not stable and is difficult to manage.It may have variations in data flow during peak seasons.It is 
  quite complex to process because a minor change in data may impact the entire decision.It can handled through cloud 
  computing.
    
## Phases of Big Data Analysis
   - Data Acquisition:
     
     Collection of raw data from various input sources such as sensors,Log files and storing it in a processable form.
   - Information Gathering and Data cleaning :
     
     Much of data gathered is of no use so we need to eliminate it.There might be some disturbances, or outliers during the 
     process of collection which need to be filtered.And data needs to be set in a format to analyse.
   - Data Integration and Aggregation and Representation:
     
     Data integration is the process of collecting data from many sources and merging it. The necessary data pre-processing 
     operations should be performed to generate a unified form of data.
     In Data Aggregation we merge data from various souces and remove redundancies.Integrating pieces of data into a single 
     form so that it can be processed.Sometimes during this process we may loose some data but it is easy to represent. 
     Data Representation : Data is aggregated and some conditions are applied on it to plot visuals. A human analyst must 
     use visual data representations to assess data, extract relevant information, and develop knowledge.
   - Query Processing Data Modelling and Analysis:
     
     Modern applications frequently face the difficulty of dealing with multiple datasets and data models, which can make 
     traditional Extract-Transform-Load (ETL) methods expensive and can lead to performance reduction when transforming 
     data into a single model. Furthermore, controlling and maintaining such pipelines can be time-consuming.So we use 
     query processing for optimization.
     
     The process of representing and conveying data needs through the data model is known as data modeling. Data models 
     propose and refine how data will represent real-world entities and events.They also specify the meaning and precision 
     of individual attributes and clarify relationships between entities.

     Modelling data in various forms like ER diagrams
     
     The process of analyzing, manipulating, and modeling data in order to extract value is known as data analysis.
   - Interpretation:
     
     The purpose of data interpretation is to perform and execute methods that use data analysis to provide meaning to 
     observable patterns.It is the final step and is used to for decision-making.

# Challenges of Big Data

## Heterogenity and Incompleteness:

    The data is generated from variety of sources like texts,images and videos which leads to heterogeneous data.While processing
    it may causes some inconsistencies.We may loose some information during interrelation or connection.Incompletness is nothing but
    missing information due to some disturbances in sensors while reading the data.Generally imputation is used to fill the null values
    with most frequent occurrences.

## Scale:

    As data is generated in huge volumes it is a complex task to store them.The volume is increasing so fast than the processor
    or CPU speed which poses a challenge.To store huge volumes of data we need a techniques like cloud computing.

## Timeliness:

    The velocity of big data is so fast that it becomes difficult to process the data which may cause a delay in the analysis.
    A detailed study of a problem is unlikely to be possible in real time. As a result, we must prepare partial findings ahead
    of time so that a tiny amount of incremental computing with fresh data may be employed to arrive at a speedy judgment.Index
    based searching algorithms are used to scan the data which reduces the speed.

## Privacy:

    During the process of collecting data there might be some issues of privacy.Some of the content may be sensitive.Data breaching
    and modification of content may cause violations.We can address this issues by using authentications,encryption and access
    controls and implementing necessary communication protocols.

## Human Collaboration:

    It is the interaction between humans and computers.Where we take into consideration things like feedback and guidance from experts.
    In some cases human ability to decipher things surpasses computer algorithms.So we need to consider inputs from humans as well when
    analysing some patterns.The challenge here is they may be from different locations,and different time-frame so it might be difficult
    to input this data.Each one may have different perspectives which may create conflicts.There may be some biased information as well
    which need to be carefully analyzed.Crowd-sourcing is one such example of this.For example Wikipedia it has several answers to a 
    single question.

## References

   1. Big data: A review. (2013, May 1). IEEE Conference Publication | IEEE Xplore. 
      https://ieeexplore.ieee.org/abstract/document/6567202
   2. Davenport, T., Barth, P., & Bean, R. (2012). How “Big Data” is Different . 
      https://www.hbs.edu/ris/Publication%20Files/SMR-How-Big-Data-Is-Different_782ad61f-8e5f-4b1e-b79f-83f33c903455.pdf
   3. George, G., Haas, M. R., & Pentland, A. (2014). Big Data and Management. Academy of Management Journal, 57(2), 321 – 326
   4. Rusu, O., Halcu, I., Grigoriu, O., Neculoiu, G., Sandulescu, V., Marinescu, M., & Marinescu, V. (2013). Converting 
      unstructured and semi-structured data into knowledge. 2013 11th RoEduNet International Conference. 
      https://doi.org/10.1109/roedunet.2013.6511736
   5. Seven V’s of Big Data understanding Big Data to extract value. (2014, April 1). IEEE Conference Publication | IEEE 
      Xplore. https://ieeexplore.ieee.org/abstract/document/6820689
   6. Syed, A., Gillela, K., & Venugopal, C. (2013). The Future Revolution on Big Data. International Journal of Advanced 
      Research in Computer and Communication Engineering, 2. 
      https://www.ics.uci.edu/~ddenenbe/248/Selected%20readings/Networking%20Part%20I/TheFutureRevolutionOnBigData.pdf
   7. Toward Scalable Systems for Big Data Analytics: A Technology tutorial. (2014). IEEE Journals & Magazine | IEEE 
      Xplore. https://ieeexplore.ieee.org/abstract/document/6842585
   8. Andrienko, G. (2010). A general framework for using aggregation in visual exploration of movement data. Cartographic 
      Journal, 47(1), 22–40. https://doi.org/10.1179/000870409x12525737905042
   9. Enabling query processing across heterogeneous data models: A survey. (2017, December 1). IEEE Conference Publication 
      | IEEE Xplore. https://ieeexplore.ieee.org/abstract/document/8258302?casa_token=Dztk894IfJsAAAAA:0HfzV_EZjXNbuSn5J- 
       mOVdsU8ot_T1XGyu4XJxJjhDCh84rQxm6Je2sV3aqVPtkBt3FEeYkNmiY
  10. Data Modelling - an overview | ScienceDirect Topics. (n.d.). Www.sciencedirect.com. 
      https://www.sciencedirect.com/topics/computer-science/data-modelling
  11. Seth, N. (2022, September 27). Difference Between Data Analysis and Interpretation - An Overview. Blogs & Updates on 
      Data Science, Business Analytics, AI Machine Learning. https://www.analytixlabs.co.in/blog/data-analysis-and- 
      interpretation/
  12. Jaseena, K. U., & David, J. M. (2014). Issues, challenges and solutions : Big Data mining. Computer Science & 
      Information Technology ( CS & IT ). https://doi.org/10.5121/csit.2014.41311
      




     
     

     





