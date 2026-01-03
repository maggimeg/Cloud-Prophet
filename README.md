Cloud Prophet is a machine learning-based system for predicting virtual machine (VM) performance in cloud environments.

It uses a cloud dataset from GitHub and extends its model through real-time testing with live datasets.

The system leverages Dynamic Time Warping (DTW) to identify application types and Pearson correlation to select highly correlated runtime metrics. 

These selected metrics are then input into three machine learning models: LSTM without DTW metrics, LSTM with DTW metrics, and GRU with DTW metrics. The GRU model, integrating both DTW and highly correlated metrics, enhances prediction accuracy.

Cloud Prophet optimizes VM performance by selecting the most relevant features for efficient cloud resource management. By incorporating advanced techniques like DTW and Pearson correlation, it ensures accurate performance predictions across various cloud applications.

