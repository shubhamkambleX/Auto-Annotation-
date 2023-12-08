# Auto-Annotation-
Example Annotate all pet food Images (Whiskas food for cat) in the input directory and its done. Each and every image with a whiskas images having cat in the directory containing images of all sorts which have a cat image are filtered and the annotation is performed.

The Auto-Annotate tool provides auto annotation of object detected for the objects in the images inside some directory based on the labels. Auto-Annotate is able to provide automated annotations for the labels defined in the COCO Dataset and also supports Custom Labels. This tool is built on top of Faster-R-CNN to support auto annotation for each instance of an object segment in the image. 

Flows goes 
Image Directory ---> Auto Annotate (Label Whiskas Cat Food) ----> Annotations+ .txt files (with co-ordinates)
I have Implemented in Jupyter Notebook but you can create your environment and install all the packages.
-- jupyter notebook steps
1) Required Packages
!pip install torch torchvision

2) import packages
   import warnings
   warnings.simplefilter("ignore")
  import os
  import torch
  import torchvision.transforms as T
  from torchvision.models.detection import fasterrcnn_resnet50_fpn
  from PIL import Image, ImageDraw

Thats its 
Ready to run the code ......
