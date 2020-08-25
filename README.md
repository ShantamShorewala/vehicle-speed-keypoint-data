# vehicle-speed-keypoint-data

Code and dataset for the paper titled "Link Speed Estimation for Traffic Flow Modelling Based on Video Feeds from Monocular Cameras" accepted to IEEE Intelligent Transportation Systems Conference (ITSC) 2020. 

© 2020. The dataset is licensed under a CC BY-NC-SA 4.0 license. 

1. Keypoint detection for autorickshaws

This folder contains a set of images which contains cropped images of autorickshaws. For each image, the set of visible keypoints are provided in the annotation file. The order of points is : rear light (left), rear light (right), greenlow corner left, greenlow corner right, top corner rear left, top corner rear right, rear center, indicator light right, right mirror, right center pole top, right wheel, top corner front right, left mirror, left center pole top, top corner front left , indicator light left, left wheel, Wind shield(top left), Wind shield(top right), Wind shield(bottom left), Wind shield(bottom right), front bonet, head light left, Head light right.

All the images are contained present in the folder. The test and training split as well as the annotations are contained within the respective json files. The annotations follow the MPII Human Pose Dataset. 

2. Vehicle (autorickshaw) Speed Data

The speed clips are available at https://drive.google.com/drive/folders/14yoFaXutLRUCwUVm8Pum6-tPROHPzjvO?usp=sharing

The annotation file consists of three fields: link number, vehicle instance number in the link, corresponding speed (in m/s). Corresponding video files are named appropriately and the vehicle instances are marked in the order of their appearance in the scene.

3. Code (to be added soon)
