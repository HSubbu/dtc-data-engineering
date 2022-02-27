# dtc-data-engineering
repo for data talks club de course 


## WEEK 5 ERROR

Module Not Found Error in Jupyter Notebook .

Even after installing pyspark correctly on linux machine (VM ) as per course instructions, faced a module not found error in jupyter notebook . 

The solution which worked for me(use following in jupyter notebook) :

!pip install findspark
Import findspark
findspark.init()

Thereafter , import pyspark and create spark context as usual
