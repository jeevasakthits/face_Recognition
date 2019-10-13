# face_Recognition
We are using ‘Mobilenet SSD’ because it has less inference time and very good accuracy.
Our current machine model was trained on 280 images with 5 different classes and it was ruined for
around 20k epoch with a loss in the range of 1-1.5.
And the generated graph was saved as “frozen_inference_graph.pb” along with “lapmap.pbtxt”.
To run and test the model please use google colab link in the file name
#“Tensorflow_Face_Recognition.ipynb” 
<br>
<br>

#Loss Function<br>
Lloc is the localization loss which is the smooth L1 loss between the predicted box (l) and the ground-truth box (g) parameters. These parameters include the offsets for the center point (cx, cy), width (w) and height (h) of the bounding box. This loss is similar to the one in Faster R-CNN

<br>
<br>
Follow this steps to run this file:<br>
1.Open this file using google colab as mentioned above.<br>
2.Upload the frozen_inference_graph.pb file into the google colab<br>
3.Upload the lapmap.pbtxt file into the google colab.<br>
4.Upload the image file into the google colab.<br>
5.Run all the cells to see the results.<br><br><br>
ACCURACY:<br>
We are using mobilenet ssd for low inference time and we are recognizing person only if it has an
accuracy above or equal to 99%.
