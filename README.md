# face_Recognition
We are using ‘Mobilenet SSD’ because it has less inference time and very good accuracy.
Our current machine model was trained on 280 images with 5 different classes and it was ruined for
around 20k epoch with a loss in the range of 1-1.5.
And the generated graph was saved as “frozen_inference_graph.pb” along with “lapmap.pbtxt”.
To run and test the model please use google colab link in the file name
#“Tensorflow_Face_Recognition.ipynb”
#Follow this steps to run this file:
1.Open this file using google colab as mentioned above.
2.Upload the frozen_inference_graph.pb file into the google colab
3.Upload the lapmap.pbtxt file into the google colab.
4.Upload the image file into the google colab.
5.Run all the cells to see the results.
ACCURACY:
We are using mobilenet ssd for low inference time and we are recognizing person only if it has an
accuracy above or equal to 99%.
