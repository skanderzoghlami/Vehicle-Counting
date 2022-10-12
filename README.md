# Vehicle-Counting


Vehicle-Counting is an implementation of an object tracker and counter where we use YOLO for object detection and classification.

The model is capable of detecting and classifying cars, Motorbikes and trucks from images and Videos.

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install the opencv library.

```bash
pip install opencv-python 
```
You also need to download the weights for the [YOLOv3](https://pip.pypa.io/en/stable/) model.
```bash
wget https://pjreddie.com/media/files/yolov3.weights
```

## Usage
The YOLOv5 model is used to count objects in an image, you can use it directly on google colab.

The YOLOv3 model is also used for counting objects in an image but also for realtime detection, you can see how it works by installing the model's weights and running it locally.

You can also put a video in the same folder and run :

```bash
python vehicle_count.py
```

## License
[MIT](https://choosealicense.com/licenses/mit/)
