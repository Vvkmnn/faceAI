# faceAI

[image1]: ./images/obamas_with_keypoints.png "Facial Keypoint Detection"
[image2]: ./images/obamas_with_shades.png "Facial Object Creation"

My submission for the Computer Vision capstone project in the [AI Nanodegree program!](https://www.udacity.com/ai) In this project, we’ll combine your knowledge of computer vision techniques and deep learning to build and end-to-end facial keypoint recognition system. 

Facial keypoints include points around the eyes, nose, and mouth on any face and are used in many applications, from facial tracking to emotion recognition. Your completed code should be able to take in any image containing faces and identify the location of each face and their facial keypoints, as shown below:

![Facial Keypoint Detection][image1]


### Setup

Built via Anaconda's Python 3, TensorFlow, and Keras!

```
git clone https://github.com/udacity/AIND-CV-FacialKeypoints.git
cd AIND-CV-FacialKeypoints
conda create --name aind-cv python=3.5 numpy
source activate aind-cv
conda install tensorflow
conda install keras
pip install -r requirements.txt
```

