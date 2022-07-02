# Home-Surveillance-System-using-Computer-Vision
I have created a face recognizer using convolutional neural networks to recognize the authorized person's faces. I have trained the model on 50 different images of 2 persons using google colab. The accuracy is more than 85%

The CNN model architecture is as follows:

Conv: 16 filters, 3x3 kernel; MaxPooling: 2x2 

Conv: 32 filters, 3x3 kernel; MaxPooling: 2x2 

Conv: 64 filters, 3x3 kernel; MaxPooling: 2x2 

Dense: 512 nodes  

Dense: 1 node (output)

