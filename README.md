# Hand-Written-digit-recognition
Hand written digit recognition using Mnist dataset 

hand written documents recognition has always been a fascinating topic for machine learning scientists. Mnist dataset is one of such dataset, it is a hand written digit dataset which consists of 60,000 images.  it is one of the largest datasets of hand written digits availble.

I used tensorflow, Keras and Matplotlib for this project.

Because it is a widely used dataset so data is already cleaned, But the data is not normalized so I normalized the data using tensorflow keras normaliziing function. Then I built a sequential model in which first I added a flatten layer to flatten the 2 dimensional images then I added 2 dense layers of 64 and 128 neurons. adam optimizer with loss function sparse_categorical_crossentropy was used. I ran this model for maximum of 50 epochs with a capability to stop early if loss stops decreasing, this was done using the keras callback function Earlystooping. I tried different hyper parameters including different number of neurons and different optimizers. I got a training accuracy of 98% and test accuracy of 97%.  u
