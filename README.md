# german-traffic-signs-classification

## Project Description
This project focuses on building a deep learning model to classify German traffic signs using convolutional neural networks (CNNs). The dataset used for training and testing the model is the German Traffic Sign Recognition Benchmark (GTSRB) dataset. The goal is to create a robust model capable of accurately identifying various traffic signs, which is crucial for real-world applications such as autonomous driving and road safety systems.

## Project Requirement
To run this project, you need the following prerequisites:

- All the external libraries are already present itn Google Colab just need to import them.
- Access to the German Traffic Signs dataset, which can be obtained from the provided [link](https://www.kaggle.com/datasets/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign).
- Knoeledge of deep learning concepts, particularly CNNs.
- Experience with image preprocessing techniques such as grayscale conversion, histogram equalization, and normalization.

## Project Files
The project includes the following files:

German Traffic Signs Dataset: Contains training, validation, and test data in pickle format (train.p, valid.p, test.p).
Signnames.csv: CSV file containing the mapping of class labels to sign names.
German_trafficsign_Classification.ipynb: Contains the Python script used for data preprocessing, model building, training, and testing (traffic_sign_classification.py).

## How to Run Files
1. Clone the data using the provided Git URL: git clone https://bitbucket.org/jadslim/german-traffic-signs or [kaggele ink](https://www.kaggle.com/datasets/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign).
2. Navigate to the project directory: cd german-traffic-signs.
3. Install the required Python libraries if not already installed: pip install numpy matplotlib keras opencv-python pandas.
4. Execute the Python script traffic_sign_classification.py to preprocess the data, build, train, and evaluate the CNN model.
Once the model is trained, you can use it to classify new traffic sign images by following the provided code examples.


## Results Discussion
The trained CNN model demonstrates promising performance in classifying German traffic signs, achieving high accuracy on both the validation and test datasets. By preprocessing the images and implementing data augmentation techniques, the model can effectively generalize to unseen traffic sign images. The ability to accurately classify traffic signs is essential for enhancing road safety and enabling intelligent transportation systems. The project highlights the importance of deep learning in solving real-world problems and lays the foundation for further research in the field of computer vision and autonomous driving.
