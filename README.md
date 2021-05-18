# whosThatCricketer
Evolv challenge
for this challenge i used indian cricketer dataset from kaggle
for this i created a hybrid model containing cnn and ann. cnn is used for detecting features and scaling down the image for better prediction.
here my dataset had 783 images of 15 indian players which split into 9:1 for training and testing purposes.
accuracy achieved was 98.34% 
use case for this model will be we can took picture of the player and using haarcascades detect face and resize it to the dimensions (64,64,3) and the model 
should be able to find who is that cricketer.
another use case is that we can use webcam for feeding the images and ultimately prdicting how similar the image is to a part5icular cricketer.
