# PySpark-Kafka

# Spark Streaming with Kafka
1.The streaming data is send to Kafka i.e producing messgaes to Kafka Topic.
2.The messages from Kakfa topic are consumed in Spark via 'readStream()' configuration.
3. The Quote and reason is calculated based on Age and BMI Business Rules and additional 10% discount is given to Females.
4. The Spark Dataframe is then written to another Kafka Topic
