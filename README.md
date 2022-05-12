# FiftyOne-YOLOv5-tutorial
A repo containing the starting code/dataset (from roboflow.ai) for visualizing the pred and ground truth together in Voxel-FiftyOne. 
This notebook can be used to view predictions with different confidence values which are extracted through trained model .pt file.
For visualizing the predictions and ground truth please follow the tutorial in colab notebook by running all cells sequentially.
This tutorial can be accessed through the following google colab notebook: https://colab.research.google.com/drive/1xqwIHnOyZBiieCwAYH8Rru7eSmRkzm3-?usp=sharing

## Asumptions (Either one of the following)
* Having the predictions also as in .txt format used by yolov5. 
* Having the yolov5 trained model weights as .pt file.

## Next 
* Integrate metrics such as object mkistakeness (missing ground truth boxes based on model predictions) and other available from Fifty-one
* Integarte LabelBox for relabelling mistakes

## Links
* https://voxel51.com/docs/fiftyone/user_guide/basics.html
* https://voxel51.com/docs/fiftyone/tutorials/evaluate_detections.html
