# Installation

## Preliminaries

sudo apt install default-jdk scala git -y


## installation

wget https://downloads.apache.org/spark/spark-3.0.1/spark-3.0.1-bin-hadoop2.7.tgz
tar xvf spark-*

sudo mv spark-3.0.1-bin-hadoop2.7 /opt/spark

echo "export SPARK_HOME=/opt/spark" >> ~/.profile
echo "export PATH=$PATH:$SPARK_HOME/bin:$SPARK_HOME/sbin" >> ~/.profile
echo "export PYSPARK_PYTHON=/usr/bin/python3" >> ~/.profile




# Tensorflow
https://github.com/yahoo/TensorFlowOnSpark

https://medium.com/lifeomic/sparkflow-train-tensorflow-models-with-apache-spark-pipelines-74dca32f60f3

# Reference

https://github.com/yahoo/TensorFlowOnSpark
https://phoenixnap.com/kb/install-spark-on-ubuntu