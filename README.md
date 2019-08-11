# keypoint detection task

# Datasets

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
