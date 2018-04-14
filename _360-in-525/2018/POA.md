---
layout: single
title: 360-in-525. POA in Progress
permalink: /360-in-525/2018/POA/
sidebar:
  nav: "lMenu-360-in-525"
header:
  overlay_color: "#5e616c"
  overlay_image: /assets/images/DISP-research-1600x524.jpg
  caption: 
excerpt: '360-in-525 Minutes Course Set in Data Sciences, Spring 2018, Uppsala -- Learn data sciences from domain experts and its mathematical foundations while getting your hands dirty with real data.<br /><br /><br />{::nomarkdown}<iframe style="display: inline-block;" src="https://ghbtns.com/github-btn.html?user=lamastex&repo=scalable-data-science&type=star&count=true&size=large" frameborder="0" scrolling="0" width="160px" height="30px"></iframe> <iframe style="display: inline-block;" src="https://ghbtns.com/github-btn.html?user=lamastex&repo=scalable-data-science&type=fork&count=true&size=large" frameborder="0" scrolling="0" width="158px" height="30px"></iframe>{:/nomarkdown}'
---
{% include toc %}

# POA - 360-in-525

**Plan of Action (POA) is in progress** The final POA may change. 
{: .notice--danger}


## 000 - LOGISTICS

	- set up Meetup (only allow people registers access to information)
	- get datbricks account and upload content for 360-in-525-01
	- check out how to give wireless access to people without UC wireless

## 360-in-525-0 
  - TBA depends on 05 being 1 or 2 days (DOODLE if it is 2 days else use May 31). 
  - Lecture Plan
    - Do a full day of X-lectures (and some explicit tree arithmetics if time permits) to understand the Theorems in [YatracosThis](http://lamastex.org/preprints/20180405_MDEYatracosThis.pdf) 
    - (Optionally, depending on audience C++ skills) dive from within docker into: [https://github.com/lamastex/mrs2/tree/master/companions/mrs-1.0-YatracosThis](https://github.com/lamastex/mrs2/tree/master/companions/mrs-1.0-YatracosThis) **Pre-Action:** Gloria needs to write a README on how to run the example on Table I in [YatracosThis](http://lamastex.org/preprints/20180405_MDEYatracosThis.pdf).

## 360-in-525-1: Introduction to Apache Spark for Data Scientists on **April 20 2018**
  - from first couple weeks of [SDS-2-2](https://lamastex.github.io/scalable-data-science/sds/2/2/) contents (tightly couplable with needed extensions down the road)
  - IN PROGRESS
<!---	- HEAVILY REUSE FROM SDS-2-2 (but repackage into scalable-data-science/360-in-525-01/) 
	- make folder 'scalable-data-science' in 'Workspace' and upload 360-in-525-01.dbc
        - but see db-Dub content and HEAVILY reuse existing notebooks... Also re-read Mattei's definitive guide but keeping RDDs real from start!

official goals/outlines:
This is a one-full-day workshop (1 hp) on April 20 2018 on Apache Spark, one of the most widely used open-source and commercially friendly software for analysing big data in industry and academia. A crash course in Scala, the language of Apache Spark, will be followed by introduction to resilient distributed datasets (RDDs), their transformations and actions, Spark DataSets and DataFrames, SparkSQL. We will have brief teasers on ML Pipelines, Streaming and GraphX as they will be covered in-depth in the sequel modules (concepts will be fortified by auto-graded homework assignments).
--->

## 360-in-525-2: Social Media and Big Data on **April 26 2018**

<!---
This is a two-full-days workshop (2 hp) on April 26-27 2018. Prerequisites: 360-in-525-1 or Introduction to data Science (the Fall 2017 UU inter-faculty course). The first day will be an introduction to the domain by Professor Simon Lindgren, a digital sociologist from Umea and the second day will build towards making one’s own twitter experimental designs in real-time. This module will introduce you to topic modeling and other simple pipelines in natural language processing.
The course will give you the basic skills needed to go further and investigate the influence, if any, of micro propaganda machines (as shown below) or other similar opinion engineering operations, for instance. 
--->

### 000-090 of 360 Minutes: What is digital sociology? by [Simon Lindgren](https://www.linkedin.com/in/simon-lindgren-0a656160/) 

#### Fika break 30 minutes - sponsored by []()

### 091-180 of 360 Minutes: A look into relevant EU laws of relevance.
  - [Amelia Andersdotter](https://www.linkedin.com/in/amelia-andersdotter-906b8357/) will do lectures on relevant law:
    * Data protection, where's it come from, what's the point?
    * So what's personal data? (rules of thumb)
    * New rules: profiling (art 22 GDPR). what's that about?
    * Ethics for scientists: the Swedish approach, cost, what's the idea?
    * Using public records does not absolve you from GDPR responsibilities (necessarily)!
  - Raazesh Sainudiin will discuss enforceability issues and ``cloud operations on sovereign soil'' issues:
    * an excursion into the EU Commission's Memorandum of Understanding with IT companies signed in 2016/7
      - wrip from HateTransmissionNetwork (make non-confidential subset public here for leture outline; live via web searches a dn string chasing... with local backups)

### Lunch
  - you can buy sandwiches or have a full meal in cafes nearby.

### 181-270 of 360 Minutes: The English Civilizing Process: London's Old Bailey and the evolution of English law
  - On *inferential thinking* for digital sociology and humanities
  - What is the Data? Why did people support the printing and archiving of court proceedings in London's Old Bailey Court? etc.
  - Illustrating *inferential thinking* on the ``English Civilizing Process'' from [Old Bailey Online](https://www.oldbaileyonline.org/) dataset as XML files:
    - for example, did capital punishment for offence types really change between 1673 and 1911 in London?
  - Fusing *inferential thinking* with *computational thinking* in one place:
    - It's time to *lock and load* into your own [databricks Community Edition at [https://community.cloud.databricks.com/](https://community.cloud.databricks.com/) and play with data parsing from raw xml files in order to get the data that went in as input to the inferential thinking process above using the following databricks notebook. 
    - [https://lamastex.github.io/scalable-data-science/sds/2/2/db/033_OBO_LoadExtract/](https://lamastex.github.io/scalable-data-science/sds/2/2/db/033_OBO_LoadExtract/) 

#### Fika break 30 minutes - sponsored by [?]()

### 271-360 of 360 Minutes: Getting your hands dirty to visually explore on Jupyter for digital socilogy
  - Simon Lindgren Jupyter notebook based stuff with twitter data, networks visual, Nlp etc.
    - **NOTE:** There is no software requirements from students as we will abstract away the code and just focus on what each code cell executed by Simon is doing for gaining insights of interest to digital humanities. *We will learn Python-on-Jupyter in 360-in-525-4*.
    - Just relax and enjoy Simon's live show!


## 360-in-525-2: Social Media and Big Data on **April 27 2018**

Using Apache Spark details for more *inferential thinking* with *computational thinking* at terabyte scale...

### 000-090 of 360 Minutes: 
#### Fika break 30 minutes - sponsored by []()
### 091-180 of 360 Minutes:
### Lunch
### 181-270 of 360 Minutes:
#### Fika break 30 minutes - sponsored by [?]()
### 271-360 of 360 Minutes:


## 360-in-525-3: Geospatial Analytics and Big Data on **May 3 2018**

### 000-090 of 360 Minutes: 
#### Fika break 30 minutes - sponsored by []()
### 091-180 of 360 Minutes:
### Lunch
### 181-270 of 360 Minutes:
#### Fika break 30 minutes - sponsored by [?]()
### 271-360 of 360 Minutes:


## 360-in-525-3: Geospatial Analytics and Big Data on **May 4 2018**

### 000-090 of 360 Minutes: 
#### Fika break 30 minutes - sponsored by []()
### 091-180 of 360 Minutes:
### Lunch
### 181-270 of 360 Minutes:
#### Fika break 30 minutes - sponsored by [?]()
### 271-360 of 360 Minutes:


<!---
This is a two-full-days workshop (2 hp) on May 3-4 2018. Prerequisites: 360-in-525-1 or Introduction to data Science. The first day will be done by domain experts from Uppsala University’s Department of Social and Economic Geography in order to introduce the basic problems and datasets of the field with hands-on lab tutorials in non-distributed geospatial analytics. The second day will be on distributed geospatial analytics over real datasets that can be scaled to petabytes (syllabus is jointly designed with experts in London’s big data industry). Topics include efficient distributed spatial joins, ingestion and representations of Open Street Maps that are conducive to pregel-style distributed vertex programs, SparkSQL and Spark Machine Learning pipelines with spatiotemporal GPS trajectories of multiple individuals.
--->




## 360-in-525-4: Mathematical, Statistical and Computational Foundations for Data Scientists on **May 11 2018**

This is a mathematically more careful (``deeper'' or ``advanced'' undergraduate) version of UC Berkeley's most popular freshman course:
 - [http://data8.org/](http://data8.org/) with the formula:
   - **computatioal thinking + inferential thinking  = data science** 
   - as talked about at the end [here](https://www.youtube.com/watch?v=ggq7HiDO0OU).


### 000-090 of 360 Minutes: 
#### Fika break 30 minutes - sponsored by []()
### 091-180 of 360 Minutes:
### Lunch
### 181-270 of 360 Minutes:
#### Fika break 30 minutes - sponsored by [?]()
### 271-360 of 360 Minutes:


## 360-in-525-4: Mathematical, Statistical and Computational Foundations for Data Scientists on **May 18 2018**

### 000-090 of 360 Minutes: 
#### Fika break 30 minutes - sponsored by []()
### 091-180 of 360 Minutes:
### Lunch
### 181-270 of 360 Minutes:
#### Fika break 30 minutes - sponsored by [?]()
### 271-360 of 360 Minutes:

## 360-in-525-4: Mathematical, Statistical and Computational Foundations for Data Scientists on **May 25 2018**

### 000-090 of 360 Minutes: 
#### Fika break 30 minutes - sponsored by []()
### 091-180 of 360 Minutes:
### Lunch
### 181-270 of 360 Minutes:
#### Fika break 30 minutes - sponsored by [?]()
### 271-360 of 360 Minutes:

## 360-in-525-5: Population Genetics and Big Data  on (( **May 31 2018**  AND **June 1 2018**) exclusive-OR (ONLY **June 1 2018**))

<!---
Two-full-day workshops (2 hp) on May 31 and June 1 2018. The first day will be on the basic theories in current population genetics and genomics. The second day will use ADAM and possibly Hail over Apache Spark. Prerequisite for May 31 is 360-in-525-4 or equivalent and for June 1 is 360-in-525-1 or Introduction to data Science. We will focus on Extract-Load-Transform operations and subsequent analysis for the 1000 genomes project.
--->