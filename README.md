# Enhanced-Fetal-Brain-Anomaly-Classification-using-Deep-Learning
I have developed a Project in Python using Jupyter Notebook for the enhancement of ultrasound images to classify fetal brain anomalies using deep learning

Early neurological illness detection and treatment can be greatly assisted by identifying fetal brain abnormalities. Ultrasound has significantly aided in the challenging task of prenatal diagnosis of congenital brain abnormalities. Still, it remains less researched than Magnetic Resonance Imaging due to the images being faint or inconclusive. 

This work presents a novel deep-learning methodology to classify fetal brain conditions as either normal or anomalous, prefaced by ultrasound image enhancement and segmentation. The proposed method first enhanced the ultrasound images to improve the visibility of abnormalities, followed by segmentation of only the cranium and brain. Due to the presence of noise in ultrasound images, segmentation poses a significant challenge. Hence, I implemented a new and innovative approach, which yielded the desired outcome. The enhanced and segmented images were then segregated into 3 brain planes (namely Trans-cerebellum, Trans-thalamic, and Trans-ventricular) followed by using a convolutional autoencoder. During the training process, the convolutional autoencoder model was provided with a labelled dataset (split into 4:1 for training and validation) and achieved a remarkably low Mean Squared Error (MSE) value of 0.00297. 

Additionally, the training and validation loss curves steadily decrease and overlap after the 15th epoch, indicating that the model is learning and generalizing well. These impressive results demonstrate the high efficiency and fit of the model. Subsequently, the model was tested on a set of 2949 unlabelled fetal ultrasound images which were successfully classified as either abnormal or normal. By automating the detection of abnormalities, this method can assist healthcare professionals in making accurate and timely diagnoses, leading to improved patient outcomes. 

Keywords: Fetus; Brain Anomaly; Deep Learning; Ultrasound Image Enhancement; Classification 

Datasets: FETAL PLANES DB: Common maternal-fetal ultrasound images data set obtained from Zenodo, a well-known research data repository, and is publicly available which serves as a valuable resource for this project.(https://zenodo.org/record/3904280/files/FETAL_PLANES_ZENODO.zip?download=1)

