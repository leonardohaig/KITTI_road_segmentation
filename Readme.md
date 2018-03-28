# KITTI Road Segmentation

KITTI (Karlsruhe Institute of Technology and Toyota Technological Institute at Chicago)
vision benchmark suite provides data for several tasks relevant to autonomous driving. One of the tasks is to detect the road/lane in [images](http://www.cvlibs.net/datasets/kitti/eval_road.php "image data"). 

This code uses a custom U-Net architecture for road segmentation in the image, i.e, estimating pixels that correspond to the road/lane. 

# Prediction

U-Net's prediction on the test data are shown below. The predicted pixels for road/lane are shown in red.

#### Predictions for unmarked lane
![](https://github.com/rsenth/KITTI_road_segmentation/blob/master/test_image/uu_000002.jpg "Logo Title Text 1")

![](https://github.com/rsenth/KITTI_road_segmentation/blob/master/test_image/uu_000032.jpg "Logo Title Text 1")

    
            
           
           
#### Predictions for marked lane
![](https://github.com/rsenth/KITTI_road_segmentation/blob/master/test_image/um_000015.jpg "Logo Title Text 1")

![](https://github.com/rsenth/KITTI_road_segmentation/blob/master/test_image/um_000057.jpg "Logo Title Text 1")

          
         
                  
                  
            
            

#### Predictions for multiple lanes
![](https://github.com/rsenth/KITTI_road_segmentation/blob/master/test_image/umm_000017.jpg "Logo Title Text 1")

![](https://github.com/rsenth/KITTI_road_segmentation/blob/master/test_image/umm_000056.jpg "Logo Title Text 1")
