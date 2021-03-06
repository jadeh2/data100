# Data Science Reflection 1

## Deep Learning Methods in Identification Techniques
Deep learning is a subset of machine learning that utilizes models such as deep belief nets, autoencoders, and recurrent neural networks (RNN). This relatively new technique in data science allows the computer to make adjustments according to large datasets by sifting information through numerous hidden layers and is “self tuning” in order to closely mimic how a human brain functions. A specific model and method in the realm of deep learning is the use of convolutional neural networks (CNN), a training algorithm that is primarily applied to visual learning. 

Deep neural networks employ CNN’s to classify images by inputting an image, distinguishing its importance from other objects/ images, and then differentiating and comparing the images among the dataset. This method is especially important for facial recognition and identification and with the rise of this means of identification for access control, crime prevention, and credentials; CNN’s are vital to its function. 

A prevalent example of face identification is in social media sites such as Facebook, which utilizes the facial recognition system called “DeepFace”. With millions of users and faces in its data, Facebook is able to recognize faces of users’ friends and tag them in photos without having the user input any information about the person in the photo or search up their name. Another example is in “iCloud photos” in Apple products. In iCloud photos, the neural network is able to distinguish each person's face in a photo and categorize the data, creating specific folders of people in the photos.  

The CNN works by first identifying the faces in the photo by creating a histogram of oriented gradients (HOG), a feature descriptor that processes images and creates a face pattern. The HOG creates this facial pattern by identifying certain facial landmarks, such as the distance between the eyes, length and width of the face, shape of the eyes and nose, ect. Additionally, in order for the computer to recognize a face at different angles, it utilizes the "face landmark estimation" algorithm, which creates 68 different points on the face that will distinguish the facial features and these points can be warped or distorted to identify the face at different angles. The CNN then collects the data and compares it to existing data, which contains information about facial features, and then assigns this face to a name. Although there are some problems with facial identification, such as race bias and low accuracy in poor light conditions; facial identification is a new and more efficient approach to access control in phones and facilities and will most likely continue to improve with time as CNN’s and other data science methods become more refined. 




## Works Cited
Geitgey, A. (2018, November 07). Machine Learning is Fun! Part 4: Modern Face Recognition with Deep Learning. Retrieved September 11, 2020, from https://medium.com/@ageitgey/machine-learning-is-fun-part-4-modern-face-recognition-with-deep-learning-c3cffc121d78

Cherradi, A. (2020, May 05). Face Recognition using Deep Learning. Retrieved September 11, 2020, from https://towardsdatascience.com/face-recognition-using-deep-learning-b9be73689a23

Ahamed, Hafiz & Alam, Ishraq & Islam, Md. (2018). HOG-CNN Based Real Time Face Recognition. 10.1109/ICAEEE.2018.8642989.

-, E., By, -, &amp; Editorial. (2020, July 01). Different types of Deep Learning models explained. Retrieved September 11, 2020, from https://roboticsbiz.com/different-types-of-deep-learning-models-explained/



