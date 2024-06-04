## Network Traffic Anomaly Detection

This repository implements unsupervised learning techniques for anomaly detection in network traffic data. It utilizes two powerful methods: Isolation Forests and Autoencoders. These techniques aim to identify unusual patterns potentially indicative of security breaches or system malfunctions.

**Project Setup**

1. Clone this repository:

```bash
git clone https://github.com/Praneesh-Sharma/Anomaly-Detection-in-Network-Traffic.git
```

2. Install dependencies:

```bash
conda activate network-traffic-anomaly-detection
```

**Dataset**

The project utilizes the KDD Cup 1999 dataset, a widely used benchmark for intrusion detection systems. You can download the dataset from the following source:

* [KDD Cup 1999 Data](https://www.kaggle.com/datasets/galaxyh/kdd-cup-1999-data)

**Usage**

This repository provides scripts for training and evaluating both Isolation Forests and Autoencoders on network traffic data. 

**Algorithms**

* **Isolation Forest:**

    * Offers efficiency for high-dimensional data (common in network traffic).
    * Robust to outliers (network traffic can have spikes or fluctuations).
    * Might not provide detailed explanations for anomalies.

* **Autoencoder:**

    * Excels at recognizing complex data patterns (subtle anomalies).
    * Requires careful hyperparameter tuning (network architecture and training parameters).
    * Needs a significant amount of training data.


This project was assigned to me during my role as a Summer Intern at Celebal Technologies
