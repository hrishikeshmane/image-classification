# image-classification

This app uses a Mobilenet V1 model sitting on Firebase to run inference on various images provided to it and predict the subject of the image.

The model has been pretrained and saved in a frozen .pb form, and converted into .tflite using https://www.tensorflow.org/lite/convert .

It downloads the model on first use in order to cut down dpace taken by the app, and so that any changes to the model can be directly delivered to the user without the need for manual updates.


![Screenshot 1]("https://github.com/boronhub/image-classification/blob/master/screenshots/Screenshot_20191224-171739_MLKit%20Custom%20Model.jpg?raw=true")
![Screenshot 2]("https://github.com/boronhub/image-classification/blob/master/screenshots/Screenshot_20191224-171750_MLKit%20Custom%20Model.jpg?raw=true")
