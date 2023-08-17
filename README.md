# ECG-Signal-Classification-Using-Deep-Learning
 Project Description:
This project revolves around the analysis and categorization of electrocardiogram (ECG) heartbeats. ECG is a pivotal tool in understanding the rhythm and functionality of the heart. The data utilized in this project comes from the renowned Massachusetts Institute of Technology-Beth Israel Hospital (MIT-BIH) arrhythmia database, which is widely recognized for its precise annotations by expert cardiologists.

🔍 Objective:
The primary aim is to build a model capable of classifying heartbeat signals into one of the five categories - Normal, Supraventricular ectopic, Ventricular ectopic, Fusion, or Unknown. Given the imbalance in the dataset, an essential step involves preprocessing to ensure that our model is not biased.

💡 Key Features:

Data Visualization: Conducted extensive exploratory data analysis to understand the distribution of heartbeat categories.
Preprocessing: Implemented undersampling to tackle the imbalanced nature of the dataset.
Model Building: Constructed a Convolutional Neural Network (CNN) leveraging TensorFlow and Keras to capture the intricate patterns in the ECG signals.
Model Evaluation: Evaluated the model's performance using various metrics such as accuracy, precision, recall, and F1-score. Visualization tools like 3D charts and doughnut plots were utilized for a more intuitive understanding of the model's performance.
🔗 Dataset:
The dataset consists of ECG signals categorized into five classes. The recordings in the MIT-BIH database are of 30 minutes duration each and have been sampled at 360 Hz.

🛠 Technologies Used:
Python, Pandas, TensorFlow, Keras, Matplotlib, Plotly, Seaborn
