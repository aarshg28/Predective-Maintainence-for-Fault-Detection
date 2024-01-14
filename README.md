# Predective Maintainence For Fault Detection In Industry 4.0
The area of predictive maintenance has taken a lot of prominence in the last couple of years due to various reasons. With new algorithms and methodologies growing across different learning methods, it has remained a challenge for industries to adopt which method is fit, robust and provide most accurate detection. Fault detection is one of the critical components of predictive maintenance; it is very much needed for industries to detect faults early and accurately. Predicting the life condition of a component is so crucial for industries that have intent to grow in a fast paced technological environment. 
Recent studies on predictive maintenance help industries to create an alert before the components are corrupted. Prediction of component failures, companies have a chance to sustain their operations efficiently while reducing their maintenance cost by repairing components in advance. To predict and be ahead of all these scenarios we imply Artificial Intelligence (AI) and Deep Learning using long short-term memory (LSTM) neural networks to predict when an aircraft engine might require to be serviced or replaced.  
In this project Long Short-Term Memory (LSTM) networks has been performed to predict the current situation of an engine.  LSTM model deals with a sequential input data. Training process of LSTM networks has been performed on large-scale data processing engine with high performance. For these predictions we require a dataset of previous aircraft historical data having 21 sensor values of each aircraft. Aircrafts have three different settings = set1, set2, set3 so that we can manipulate the data and find out the relation / trend in the data so that our system gets capable of predicting remaining useful life (RUL) of an aircraft engine.

Overview: 
1. Built a Machine Learning project by performing Predictive Analysis on dataset from NASA's repository, extracting 21 sensor values and three pilot preference settings.
2. Implemented robust data pre-processing techniques, addressing null values and applying scaling with Scikit-Learn's Min- Max scaler for neural networkcompatibility.
3. Designed and implemented a neural network architecture, featuring LSTM layers with 100 and 50 units, and employed dropout for mitigating overfitting.
4. Achieved a stellar 96% accuracy in predicting Remaining Useful Life (RUL) of Aircraft Engines, leveraging Keras with TensorFlow backend. Evaluated model performance using metrics like MAE, R-squared, precision, and recall for comprehensive analysis
