# Tensorflow Distributed Training Demo
Hey team! 👋 We successfully tested distributed (multi GPU) TensorFlow training within Snowflake Container Runtime 🎉

Snowflake's CR doesn’t come with Tensorflow, but it can easily be installed with pip. Our example highlights CR's open-source connectivity with preconfigured Ray and GPU infrastructure.. 

The differentiators for this work were the Snowflake [DataConnector](https://docs.snowflake.com/en/developer-guide/snowflake-ml/container-runtime-ml#optimized-data-loading) and [Ray](https://docs.ray.io/en/latest/ray-overview/index.html). Ray is an open-source framework for distributed computing and provides shared memory such as multi-GPU. DataConnector efficiently connects Snowflake data to Ray. We hope this example is helpful for others.

We adapted the example of the 
- [Penguin Classification Problem](https://github.com/MicrosoftDocs/ml-basics/blob/master/05a%20-%20Deep%20Neural%20Networks%20(TensorFlow).ipynb)
- [TensorFlow custom training walkthrough](https://www.tensorflow.org/tutorials/customization/custom_training_walkthrough)

This opens up exciting possibilities for training large-scale TF models directly within Snowflake CR. I am incredibly thankful to Garrett Frere for his collaboration and help in making this possible. If you have any feedback to improve this solution, feel free to share it with us.
