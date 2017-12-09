# Analysis On Health Issue using PIG

## ABSTRACT
This project addresses the problem of analysis on health issues;
This data set includes provider data for hip/knee and some other complication measures and the Agency for Healthcare Research and Quality(AHRQ) measures of serious complications.

This data is taken from various hospitals over the many states of United States, the data provides the id, hospital name, city, state, zip code, country name, phone number, measure name, compared to national, start date and end date. 

By analyzing this data we can take good measures for next coming years.

The aim of this project is to find out which and all hospital with particular diseases have been reported and count the number of diseases that have been reported over all.

## SUMMARY
I am doing Analysis on Health issues across United States by using data from data world. For fetching the data we can either use Apache Flume or download the available dataset from the internet.

After Fetching the data from data world, it would be loaded directly to HDFS.

Next step deals with using the dictionary file to filter the data people who are affected with Pressure sores or Blood stream infection after surgery and counting number of people affected with these issues. 
At last I have generated the data and stored or loaded the results back to local System.

I used Pig tool because Apache Pig is a dataflow language that is built on top of Hadoop to make it easier to process, clean and analyze "big data" without having to write vanilla map-reduce jobs in Hadoop.

## REFERENCES
www.infoworld.com/category/big-data

