# keypoint detection task

[A nice blog](https://towardsdatascience.com/human-pose-estimation-simplified-6cfd88542ab3)

# related works
* SOTA: https://paperswithcode.com/sota/keypoint-detection-on-coco
* Mask-RCNN
* CMU OpenPose: https://github.com/CMU-Perceptual-Computing-Lab/openpose
* Microsoft: https://github.com/microsoft/human-pose-estimation.pytorch/blob/master/README.md



# Datasets
## MPII Human Pose Dataset
* http://human-pose.mpi-inf.mpg.de

## COCO dataset
* http://cocodataset.org/index.htm#download
* download
  1. install Google Clound SDK
     ```
     curl https://sdk.cloud.google.com | bash
     source ~/.bashrc
     ```
  2. Make local dir
     ```
     mkdir val2017
  3. Synchronize using `gsutil`
     ```
     gsutil -m rsync gs://images.cocodataset.org/val2017 val2017
     ```
  

* [useful guide in korean](https://ukayzm.github.io/cocodataset/)
* related task
  * http://cocodataset.org/index.htm#keypoints-2019
  * http://cocodataset.org/index.htm#keypoints-2017
