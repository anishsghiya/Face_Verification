# Face Verification
The project aims to detect as well as recognise faces present in the frame of reference. The Google Colab link to the implemented notebook can be found at [this link](https://colab.research.google.com/drive/1x1Xj-kfntrzYv3yoqSkl1K_BuJajbi-v?usp=sharing)

# Requirements
The Haar Cascade Frontal Face xml file can be found at [this repository](https://github.com/opencv/opencv/blob/master/data/haarcascades/haarcascade_frontalface_default.xml)

The FaceNet model is used for classification Original Paper can be found [here](https://arxiv.org/abs/1503.03832). 

Implementational details related to the use of FaceNet can be found [here](https://github.com/nyoki-mtl/keras-facenet)

# Pipeline
1. Convert to image to Grayscale
2. Using the Haar Cascade Classifier to detect the faces.
3. Using FaceNet model to generate embeddings.
4. Define Triplet Loss function


# Author
Anish S Ghiya (@anishsghiya)
