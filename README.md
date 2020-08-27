# Face_Verification

Using Haar Cascade frontalface xml file from the OpenCV.Using this detector we detect the faces in the picture.

Embeddings for each of the faces in the database is generated.

Now using the triplet loss function and facenet model we get the closeness of the embeddings for the input new image with that of all the embeddings generated from the database of images provided.
