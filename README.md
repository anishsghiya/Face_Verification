# Face_Verification

Using HaarCascade frontalface xml file from the OpenCV. OpenCV already contains many pre-trained classifiers for face, eyes, smile etc. 

Now using this detector we detect the faces in the picture.

Now using the triplet loss function and facenet model we get the closeness of the embeddings for the input new image with that of all the embeddings generated from the database of images provided.
