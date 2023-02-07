# Gastrointestinal_Classification_Project
In this project, we aim to classify different types of anomalies in the human gastrointestinal tract through endoscopic imagery.
The KVASIR data set was used for this task, which consists of 8,000 annotated images in 8 different classes of anomalies, each class containing 1,000 images.
The classes are : 
dyed-lifted-polyps, normal-cecum, normal-pylorus, normal-z-line, esophagitis, polyps, ulcerative colitis, and dyed-resection-margins. The KVASIR dataset and the required libraries can be easily downloaded from this link https://datasets.simula.no/kvasir/#download.
The proposed methods in this project involve the use of three different deep learning models: VGG, ResNet, and ViT Transformer. Each model was trained and tested on the same dataset to compare their performance in accurately classifying the class of gastrointestinal disease.
The first step in the process was to select a pre-trained model and fine-tune it to fit our specific task. Then, the model was trained on the dataset to make predictions. Finally, the model's performance was evaluated by testing it on a set of unseen data.

The deep learning framework Keras was used, along with Numpy and Scikit-learn for numerical processing and machine learning, and Matplotlib for plotting.
