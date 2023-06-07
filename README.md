# DATA ANOMALY DETECTION IN WIRELESS SENSOR NETWORKS USING β-VARIATIONAL AUTOENCODER
Anomaly detection is the process of identifying data instances that drastically
deviate from the majority of data instances. Anomaly detection is a key challenge to ensure
the security in Wireless Sensor Networks. The detection of such anomalous data is
required to reduce false alarms. The aim of this project is to detect anomalies in wireless sensor network datasets such as Intel Berkeley Research Lab(IBRL) and The Intelligent Sensors, Sensor Networks &Information Processing(ISSNIP) dataset. Data imbalance is the major challenge in machine learning
models that is resolved in the proposed model using deep learning technique. Here the anomalies are detected using β-variational autoencoder which ooutputs the reconstructed input and calcultes the loss. The loss is a combination of KL divergence and renconstruction error where β is included to the KL divergence term. The threshold is set as the average of the train loss. The data instances with loss above the threshold are classified as anomalies. This deep learning model was found to perform well when tested with different percentage of anomalies.![FPA-ISSNIP](https://github.com/Harini-19Z317/Variational-Autoencoder/assets/74368671/fc539703-e9e8-4e7f-984a-eb8f6bd1b58c)
![FPA-IBRL](https://github.com/Harini-19Z317/Variational-Autoencoder/assets/74368671/4782925b-1b3b-4fe4-9869-6efeae19565a)
![FAR-ISSNIP](https://github.com/Harini-19Z317/Variational-Autoencoder/assets/74368671/e3571a19-bc43-4250-afb9-f7bd29a47087)
![FAR-IBRL](https://github.com/Harini-19Z317/Variational-Autoencoder/assets/74368671/089ea4ce-e751-4dee-9dc3-400116a8e5bf)
