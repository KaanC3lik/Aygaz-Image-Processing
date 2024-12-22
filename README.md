# Aygaz-Image-Processing  
Animal Classification CNN Project  

This project uses a Convolutional Neural Network (CNN) to classify images of 10 different animal classes.  

## Dataset Used  
- **Source:** Animals with Attributes 
- **Classes:** Collie, Dolphin, Elephant, Fox, Moose, Rabbit, Sheep, Squirrel, Giant Panda, Polar Bear  
- **Images per Class:** 650 images  
- **Image Size:** Resized to 64x64 pixels  

## Technologies and Libraries  
- **Programming Language:** Python  
- **Libraries Used:**  
  - Data Processing: NumPy, Pandas  
  - Image Processing: OpenCV, PIL  
  - Modeling: TensorFlow/Keras  
  - Data Splitting and Encoding: scikit-learn  
  - Data Augmentation: Keras ImageDataGenerator  

## CNN Model Structure  
- Three convolutional layers
- Max pooling layers  
- Flatten layer  
- Fully connected layer 
- Output layer: Softmax activation function  

## Project Steps  
1. **Dataset Preparation:**  
   - 650 images were selected from each class.  
   - Images were normalized, and classes were one-hot encoded.  
2. **Data Splitting:**  
   - The dataset was split into 70% training and 30% testing.  
3. **Data Augmentation:**  
   - Rotation, shifting, and zoom were applied to enhance the training data.  
4. **Model Training:**  
   - The model was trained using the Adam optimizer for 20 epochs.  
5. **Testing with Manipulated Images:**  
   - Test images were modified to simulate distortions.  
6. **Color Correction:**  
   - Distorted images were corrected using color stabilization techniques, and the model was re-evaluated.  

## Kaggle link
https://www.kaggle.com/code/kaanc3ik/aygaz-image-processing/edit
