# Spark-Word-Count
Spark word count using Scala

Install Spark

Open a terminal and enter below commands

sudo apt update

wget https://dlcdn.apache.org/spark/spark-3.2.2/spark-3.2.2-bin-hadoop3.2.tgz

tar xvf spark-3.2.2-bin-hadoop3.2.tgz

rm spark-3.2.2-bin-hadoop3.2.tgz

sudo mv spark-3.2.2-bin-hadoop3.2/ /opt/spark 

sudo tee /etc/profile.d/spark.sh <<'EOF'

export SPARK_HOME=/opt/spark

export PATH=$PATH:$SPARK_HOME/bin:$SPARK_HOME/sbin

EOF

Go to top right corner and select power button -> power off

Log in to remote desktop again. Now your spark path is set and you can type "spark-shell" in terminal to access spark.\ You can access spark by typing absolute path "/opt/spark/bin/spark-shell" also.
