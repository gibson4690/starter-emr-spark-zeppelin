# starter-emr-spark-zeppelin
Tutorial for quick starting Amazon EMR with Spark and Zeppelin Notebook.

1. Data: Download "HT..metadata.dat" from http://archive.ics.uci.edu/ml/datasets/gas+sensors+for+home+activity+monitoring#. Rename to s3inputfile.dat.

2. Log in to AWS Management Console. https://aws.amazon.com/console/

3. Add S3 storage. (add tag "spark-zeppelin-demo")

4. Add resource group by tag "spark-zeppelin-demo"

5. Create EMR cluster. Check pricing - https://aws.amazon.com/emr/pricing/. Add tag "spark-zeppelin-demo"

6. Create Zeppelin notebook:
