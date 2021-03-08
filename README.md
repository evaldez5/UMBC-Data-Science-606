# Network Intrusion Detection System with Machine Learning Approach
### Capstone Data 606

### Author: Edwin Valdez (M.S.P. Data Science- University of Maryland Baltimore County) 

#### Project Overview

This project aims to create a Network intrusion Detection System (NIDS) with machine learning capabilities. The system would monitor and detect malicious activity on the network that can lead to future attacks. The system would perform a classification approach with the neural network algorithm that would be able to predict if the network is malicious or normal. NIDS is a solution to the current increasing network attack issues to devices that can further damage a company. Many companies rely on services over the internet with the use of applications and transactions online. Therefore, this model system aims to provide another layer of protection/detection from possible network attacks that can affect those services. 

#### Logistic to implement
* The Network Intrusion Detection System (NIDS) would be implemented using a Neural Network algorithm using a pre-label dataset with network traffic containing normal and malicious activity. 
* Since we are dealing with large network traffic datasets, the neural network algorithm would be able to take the feature of those network traffic data (over 49 features) to predict if the activity is normal or abnormal (Malicious). 

#### Data Description
* For this project, we are going to use a pre-label dataset from the IXIA PerfectStorm tool in the Cyber Range Lab of the Australian Centre for Cyber Security (ACCS) with the title UNSW-NB15
* The dataset contains around two million network traffic records with 49 features to describe the network activity
* The dataset label is divided by normal and abnormal activity. In addition, there is a sub-attack-category that shows nine different attack categories: Fuzzers, Analysis, Backdoors, DoS, Exploits, Generic, Reconnaissance, Shellcode, and Worms. 
* Here is Graph showing the distribution of network attacks available in this datasets

![image](https://github.com/evaldez5/UMBC-Data-Science-606/tree/main/Images/grap_distribution.JPG)


##### Reference
Abdelhameed M, Dr. Nour M. ( Nov. 14, 2018) The UNSW-NB15 Dataset Description [Data set] . The University of New South Wales. https://www.unsw.adfa.edu.au/unsw-canberra-cyber/cybersecurity/ADFA-NB15-Datasets/
Cuelogic Technologies. ( May 13, 2019). Evaluation of Machine Learning Algorithms for Intrusion Detection System. Medium. https://medium.com/cuelogic-technologies/evaluation-of-machine-learning-algorithms-for-intrusion-detection-system-6854645f9211
Almseidin, M., Alzubi, M., Kovacs, S., & Alkasassbeh, M. ( 2020). Evaluation of Machine Learning Algorithms for Intrusion Detection System. Mutah University, Amman,Jordan. https://arxiv.org/ftp/arxiv/papers/1801/1801.02330.pdf
Ahmad, Z., Khan, A., Shiang, C., Abdullah, J & Ahmad, F. ( Oct. 16, 2020) Network intrusion detection system: A systematic study of machine learning and deep learning approaches. Wiley Online Library. https://onlinelibrary.wiley.com/doi/full/10.1002/ett.4150
MLK. (Oct. 30, 2019) Animated Explanation of Feed Forward Neural Network Architecture. MLK making AI simple. https://machinelearningknowledge.ai/animated-explanation-of-feed-forward-neural-network-architecture/
Sharma, Bikash. ( Sept. 4, 2019) Evaluating a Machine Learning Model. Skyl.ai.  https://blog.skyl.ai/evaluating-a-machine-learning-model/




