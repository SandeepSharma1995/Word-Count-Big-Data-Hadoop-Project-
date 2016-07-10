# Word-Count-Big-Data-Hadoop-Project-
Word Count: To count the Occurence of a each word in a Text file using Hadoop Framework.

To Run:
#Step 1:Make jar file of the project 
#Step 2: Copy this jar file into Hadoop
#Step3:Copy the input file into HDFS:
Command:
hadoop fs -copyFromLocal  /Local_address_path /HDFS_address
#Step4:To Run it on the Apache Hadoop Framework:
Command:
hadoop jar /jar_file_address /input_file_addredd /output_file_name

To view the Output:
hadoop fs -cat /output_file_part_name
