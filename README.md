# Digital-Signal-and-Image-Management-project
In the following project dedicated to Digital Signal and Image Management, different approaches have been studied for 3 different types of problems:
# • Processing of one-dimensional signals:
it is a task of speaker recognition, which speakers to be recognized are the 3 members of the group. The problem was tackled by training a simple fully-connected neural network with one-second clips of different recordings belonging to the 3 speakers to be recognized.
# • Processing of two-dimensional signals:
it is a face recognition task, which faces to be recognized are also in this case those of the members of the group. The approach to the problem was based on the OpenCV library for face detection and subsequent training of a convolutional neural network through transfer learning and fine tuning. Face recognition was subsequently implemented in real-time on the screen, which demonstrated robustness even in different light conditions, expressions and different angles.
# • Content based image retrieval:
in this last part, the goal was to return 10 faces more similar to a face given as input, extrapolating them from a large dataset of celebrity photos. To achieve the goal, the OpenCV library for face detection was used a second time, the faces were used to train an autoencoder, from which the encoding part to be used as a feature extraction for the photos was extracted. To find the most similar faces, the distance between the features of the various photos of the dataset and the query was measured.

# Software 
We used python for this project.
# Team 
Mattia Boller m.boller@campus.unimib.it 

Raffaele Moretti r.moretti8@campus.unimib.it 

Silvia Ranieri s.ranieri7@campus.unimib.it
