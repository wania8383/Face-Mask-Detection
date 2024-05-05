# Face-Mask-Detection
**Problem Setup:** As various viral strains such as Covid, swine flu etc keep spreading. Also south asian countries have issues of smog. So there should be a system to detect if a person is wearing mask or not. The system can be implemented in the schools and shopping malls to stop spread of the epidemic and enhance protection of the citizens. 
Dataset: The Dataset has been downloaded from kaggle.The dataset is divided into two categories.
With Mask and Without Mask. I have 3,792 images of individuals with masks. I have 3,828 images of individuals without masks.
**Techniques: **
CNNs are the backbone of this project, particularly for the mask detection task. They are used both for training a model to classify images into "With Mask" or "Without Mask" categories and for making predictions in real-time.
Deep learning is employed using the MobileNetV2 architecture. MobileNetV2 is a lightweight CNN architecture that has been pre-trained on the large ImageNet dataset. By leveraging MobileNetV2, the project benefits from its feature extraction capabilities while fine-tuning the model for the specific task of mask detection.
Image Data Augmentation: The training data is augmented using random rotations, zooms, and flips. This helps the model generalize better and prevent overfitting on the specific training images.
Binary Classification: The model predicts the probability of a face wearing a mask or not wearing a mask. This is a binary classification problem where the target variable has two classes.
Face Detection: A separate pre-trained deep learning model based on the Single Shot MultiBox Detector (SSD) architecture is used to identify faces in the frame. This allows the mask detection model to focus only on the relevant regions of the image.
Real-time Video Processing: The project demonstrates how to use the trained model for real-time mask detection in a video stream. This is achieved by capturing frames from the video stream, applying face detection and mask classification, and then displaying the results on the screen.
**Description of Previous Work:**
The preexisting work was till training the model to detect face mask and using real time video processing to implement it.
**My Contribution:**
My contribution is i have implemented to detect if an individual is wearing masks or not on images. The model can detect if person wearing mask or not on provided images.
