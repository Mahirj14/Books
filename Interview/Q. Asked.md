[[interview]]  #questions 


**If you have 10 input files but only 2 are critical and need immediate processing , 
how would you configure and orchestrate spark jobs for the remaining 8 files ?**

--> To configure and orchestrate Spark jobs for processing a mix of critical (2) and non-critical (8) input files,
you can use job prioritization and queueing mechanisms.

Spark provides a way to prioritize jobs using job scheduling queues.
You can set job priorities when submitting Spark applications. 
In this case, you want to prioritize the jobs for the critical files. 
You can submit high-priority jobs for the critical files and lower-priority jobs for the non-critical files.

> FORD

how to delete duplicates
python code for finding non numeric value in payment column

data profiling
data checks

how to handle 100gb data
what is coleasc/repartision
aws scinario based Qiestion
ETL data warouhouse , data lake, data mart

> sociate general

- i have 6gb json file but spark executor size in 3gb so have can i read that file without executor size change
- df convert to json data

- you have to write python code for string and count seqential value s = "abcabbba" higest in sequence abc means count 3. if reapeat that not count
- create session,  read df, withcolumn

```python
df = spark.createDataFrame(data=data2,schema=schema)
```



>nexgensis

- brodcastjoin
```python

joined_df = df.join(brodcast(small_df), df.value == small_df.id)

```



freqency table/cross table


> ford round 2

- star/snowfalk
- scd2 scripting in sql
- sql joins(inner,left,right,full)
- pyspark window function
- copay? writeoff? 
- commulative marks 
- redshift? architecture ? 
- write in redshift database

> coditas

- nested json
- flatten expose
- json/xml formate
- json pyspark scenario