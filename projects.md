# Projects

We run a number of projects - some small, some larger - that aim to realise our ambitions to 
support small big data projects as spelled out in the [manifesto](manifesto.html).

## Lazy Evaluation Object Notation 

The aim of this project is to develop a new data representation for big data applications. 
The Lazy Evaluation Object Notation (LEON) format aims to provide a binary object notation 
that is functionally equivalent to JSON but is both faster to process and more space-efficient 
on disk. For big-data applications that tend to consist of large numbers of records that are 
similar in structure, the improvements can be significant.

## Big Data Streams

The Java Streams API provides a convenient way to formulate data processing piplines much like
those that would make up a job in a modern Big Data framework such as Spark. Unfortunately, all
operations happen in memory, so the size of the data that can be processed is limited to the 
size of a machine's memory (plus allocated swap space). This aim of this project is to replace
critical components in the Streams API to allow them to operate on disk instead, allowing larger
amounts of data to be processed. 

## Data Science Scorecards 

Data science endeavours often have huge management overheads. They may involve interdisciplinary
teams working with diverse data sources using evolving methods as well as complex infrastructures
and software systems to satisfy requirements of multiple stakeholders. The Social Data Science
Scorecard Deck is an agile project management tool addressing core individual aspects of a data
science project.

(__Ilia Lvov__)