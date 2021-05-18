# Unsupervised anomaly detection for EC2 CPU utilization

<b>Tech Stack</b>
<br/>
Plotly, altair, Sklearn (Isolation Forest, Local Outlier Factor)
<br/><br/>
<b>Objective</b><br/>
The goal of this project is to experiment with time-series data and identify data points which are seemingly unusual. Anomaly detection tasks are usually unsupervised due to the lack of labelled data available. Thus, we will be experimenting with different unsupervised models and creating visualizations to detect anomalous points. There are many use cases for anomaly detection, such as spikes in temperature of machines indicating overheating. In this notebook, we use real data of  EC2 CPU utilization from AWS CloudWatch.
<br/><br/>
<b>Dataset</b><br/>
EC2 CPU utilization from AWS Cloudwatch
https://github.com/numenta/NAB
<br/><br/>
<b>Brief Overview</b><br/>
We first do some feature engineering on the timestamps to generate the corresponding year, month, day, weekday, and hour of each datapoint. We then perform some visualizations to take a look at the trend of CPU utilization, and then perform unsupervised techniques to detect anomalous points
![anomalies](https://user-images.githubusercontent.com/31071751/118603208-35ecbb00-b7e6-11eb-81be-ac54de1a9f7e.JPG)


