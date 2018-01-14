# PySpark_ALS_MovieLens-
In this repository, I have two notebooks. First is implementing ALS on PySpark dataframes. Second is implementing ALS on PySpark RDD.


Comaprison between DatFrame and RDD Using PySpark
Time Consumed while using ALS() for recommendation:
     Dataframe take more time as compare to Rdd while using ALS().

ml use by Dataframe :
    from pyspark.ml.recommendation import ALS as ML_ALS

mllib use by RDD:
    from pyspark.mllib.recommendation import Rating,ALS as MLLIB_ALS 

RDD:
    RDD is stand for Resilent Distributed Dataset.
    RDD use collection and better for unstructured data.
    RDD is good when we dont want impose schema such as columns format
    RDD can be converted into Dataframe 

Dataframe:
    Dataframe is also a distributed collection of data.
    IN DataFrame data is organised into named column like a relational table.
    It is designed for large dataset processing.APIs of Dataframe are easy to use 
    similar to SQL language.
