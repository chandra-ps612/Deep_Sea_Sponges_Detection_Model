# Deep_Sea_Sponges_Detection_Model
For training graph, please go through this link: https://wandb.ai/chandra-ps/YOLOv5?workspace=user-chandra-ps
* sea_sponges dataset contains total of 118 images that is further divided in train and val sets. Images are annotated in yolo format.
* Why i choose yolov5 for sea_sponges detection?
please go through this link: https://medium.com/augmented-startups/yolor-or-yolov5-which-one-is-better-1b1ed297e10
# Model training details:
* Used Transfer Learning method to train model
* batch_size: 16
* img_size: 640
* epochs: 100
* weights: yolov5s.pt
* Inference has been done on youtube video.