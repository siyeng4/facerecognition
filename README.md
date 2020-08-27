# facerecognition
# Introduction

In the project, the goal is to utilize modeling and algorithms to identify the facial expressions of people, so as to classify and organize them. Facial expression recognition is a very important and necessary link in the development of AI. Social security systems, mobile payment facial recognition systems, car autopilot character recognition systems and robotic service systems, among many other aspects of people’s lives, will use facial expression recognition knowledge and technology. Furthermore, recognizing facial expressions requires humans to have very complex logical thinking and a certain degree of familiarity. The cost of these identifications is considerable. If AI can identify facial expressions more accurately and quickly with specific frameworks and sophisticated algorithms, then computers will be able to record, store and analyze facial images on a large scale at low cost, greatly accelerating social development.

# Data
The dataset was obtained from a facial expression recognition challenge in kaggle. It consists of two variables: “emotion” and “pixels”. Each "pixels" value was converted to a 48x48x1 numpy array in order to predict "emotion" as an input to a convolutional neural network.

Variables:

"emotion" (#s in 0-6)
"pixels" (48x48x1 3D arrays)
Data was also normalized and augmented to boost model performance. All data was normalized by dividing pixel values by 255. Augmentation techniques -- flipping, rotating, padding, and re-cropping the images -- were applied to 200 random samples of the training data.

Final dataset:

total (36,087)
training (28,909)
validation (3,589)
testing (3,589)
