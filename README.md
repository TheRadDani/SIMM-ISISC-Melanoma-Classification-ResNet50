# SIMM-ISISC-Melanoma-Classification-ResNet50

This GitHub repository contains the code for the detection and classification of 9 skin diseases: actinic keratosis, basal cell carcinoma, dermatofibroma, melanoma, nevus, pigmented benign keratosis, seborrheic keratosis, squamous cell carcinoma, and vascular lesion. The classification is based on a pretrained ResNet50 model and a Sequential model, with custom loops and distributed learning explored to increase training performance.

Dataset
The dataset used for this project is the International Skin Imaging Collaboration (ISIC) 2018 Challenge Dataset, which contains over 10,000 dermoscopic images of skin lesions from different populations, acquired with a variety of devices.

Preprocessing
The images were preprocessed using standard techniques, such as resizing, normalization, and data augmentation. A custom data generator was created to feed the images to the model during training.

Models
Two models were used for the classification: a pretrained ResNet50 model and a Sequential model. Both models were fine-tuned on the ISIC dataset using transfer learning techniques.

Training
To increase training performance, custom training loops were implemented using TensorFlow. Distributed learning was also explored to train the models on multiple GPUs.

Results


Conclusion
