# Tensorflow Distributed Training Demo
With this project, we achieved distributed TensorFlow training within Snowflake Container Runtime ML Notebooks!. While Snowflake's out-of-the-box setup doesn't directly support distributed TF, we leveraged a hidden superpower: the underlying Ray cluster. 🚀

Ray is an open-source framework for those unfamiliar, making it easy to scale Python applications, including machine learning workloads. Using Ray, we can effectively distribute our TensorFlow training across multiple nodes, significantly speeding up the process.

We adapted the example of the 
Penguin Classification Problem
TensorFlow custom training walkthrough

This opens up exciting possibilities for training large-scale TF  models directly within Snowflake. I am incredibly thankful to Garrett Frere for his collaboration and help in making this possible. 
