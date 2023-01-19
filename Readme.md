# Finding objects on the image
This project, Helps to find objects in an image, select them, and count them. This program can work with recaptcha

## Features
* Works with image
* Distinguishes 80 objects
* The user can specify which object to look for on the image

## Reauirements
Need to install all the requirements
`run libraries.bat` or
`pip install -r requirements.txt`

Names of possible objects:
```
'person', 'bicycle', 'car', 'motorbike', 'aeroplane', 'bus', 'train', 'truck', 'boat', 'traffic light',
'fire hydrant', 'stop sign', 'parking meter', 'bench', 'bird', 'cat', 'dog', 'horse', 'sheep', 'cow',
'elephant', 'bear', 'zebra', 'giraffe', 'backpack', 'umbrella', 'handbag', 'tie', 'suitcase', 'frisbee',
'skis', 'snowboard', 'sports ball', 'kite', 'baseball bat', 'baseball glove', 'skateboard', 'surfboard',
'tennis racket', 'bottle', 'wine glass', 'cup', 'fork', 'knife', 'spoon', 'bowl', 'banana', 'apple',
'sandwich', 'orange', 'broccoli', 'carrot', 'hot dog', 'pizza', 'donut', 'cake', 'chair', 'sofa',
'pottedplant', 'bed', 'diningtable', 'toilet', 'tvmonitor', 'laptop', 'mouse', 'remote', 'keyboard',
'cell phone', 'microwave', 'oven', 'toaster', 'sink', 'refrigerator', 'book', 'clock', 'vase', 'scissors',
'teddy bear', 'hair drier', 'toothbrush'
```

## How to input image and object (Example)
```
Path to image(recapcha): Result\input\bus1.png
What we are looking for: bus
```

```
Path to image(recapcha): Result\input\truck.jpg
What we are looking for: truck
```

```
Path to image(recapcha): Result\input\city.png
What we are looking for: car, person, traffic light
```
## This supports different file extensions
*.png, *.jpg/jpeg, *.webp, etc.
