# InteriorNet-Layout
![2222](https://user-images.githubusercontent.com/52377012/162350602-266d2592-b63b-4514-b1d5-fa1b92f17185.PNG)


You can download this dataset here:https://drive.google.com/drive/folders/1ZblfLKvBlGFs3-Z7RZ8Gi2B0wv_svaMo

Base on [InteriorNet](https://interiornet.org/) dataset, we selected 8219 pictures and annotated as a room layout estimation dataset named InteriorNet-Layout. The proportion of training set, validation set, and testing set is about 8:1:1, including 6534, 833, 852 pictures, respectively. The resolution of each image is 480× 640 pixels and data types are RGB images, original depth map, the depth map of the layout plane, layout semantic segmentation map, the camera intrinsic matrix, 3D coordinates of layout keypoints, graph, and original surface normal maps. The semantic labels of the ceiling and floor are 0 and 1 respectively. Vertical walls are labeled from 2 to 6 (the maximum number of vertical walls in the dataset sample is five), based on their relative position to the left boundary of the image.

# Related project
Base on this dataset, we perform to work to tackle the task of room layout estimation:
1. [2D room layout estimation of general rooms based on undirected graph](https://github.com/Hui-Yao/2D-graph-layout-estimation)
2. [3D room layout estimation of general rooms based on ordinal semantic segmantation](https://github.com/Hui-Yao/3D-ordinal-layout-estimation)
