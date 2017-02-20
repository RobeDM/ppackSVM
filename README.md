# ppackSVM
Ppack SVM for apache Spark

To compile:

    sbt clean package

    spark-submit --packages amplab:spark-indexedrdd:0.4.0 target/scala-2.11/ppackubuntu_2.11-1.0.jar TEST ../SVM_spark_2017/data/adult_train 0.001 10 500 output.txt 123 ../SVM_spark_2017/data/adult_tes
