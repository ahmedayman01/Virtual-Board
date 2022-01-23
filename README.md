## Virtual Board
<p align="justify">
  The virtual board project is aimed towards the educational domain in order to make it easier for instructors  to express concepts by drawing and writing with relative ease using hand gestures.
</p>


## Requirements
- [x] Pytoch-GPU==1.10.0
- [x] OpenCV==4.5.4





## Dataset

[![Downloads](https://img.shields.io/badge/Download-Data-blue)](https://drive.google.com/file/d/1TiianKUdUa5eHt4Wn1GlNZWqQ_jVR9jY/view?usp=sharing)

We had to generate our dataset which is around 3500 images using a python script to generate it. But we had to label the dataset manually which was time-consuming so we started using our model to try to predict the bounding boxes points for our new data images and print the annotation as text but we had to check the sanity of the prediction manually to ignore bad data. We also added more images from other datasets found that served our approach and of course, we did tons of augmentation.


## Real-Time!
To run in real-time simply clone the repository and download the weights file and then run the ```real-time.ipynb``` file. 


## Output
Here is the output of the fingertip detection model.

<p align="center">
  <img src="https://youtu.be/cVkBTcestMA">
</p>

## Contact Me!
<p>
  If you have any queries or concerns, please feel free to contact me.
</p>
