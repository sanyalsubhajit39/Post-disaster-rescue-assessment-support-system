# Post-disaster-rescue-assessment-support-system
IBM Call For Code 2019 in Shanghai
We(Jin Li, Yaoming Wang, Bowen Shi, Jixiang Luo)join this activity and make up this idea.

## Notice:
Since images or videos of post disaster are unaccessible for us by now, our models was trained with weakly related dataset. Thus, the performance of our model are uncertained. We use labeled image as the result of semantic segmentation model for the sake of presentation.

## Object Detection
In this section, What we do is just collecting the related images with dangerous objects, such as leakage wire, sharp item, corrupted house and so on. Then we feed them into the Watson for visual recognition on IBM cloud. Here is our outcome for classifying images and detecting objects:
* Image classification:
![avatar](./object dection/dt3.png)

## Semantic Segmentation: 

## Path Programming:
### Example
```
cd workspacce
```


* Image captured by drone:
![avatar](./PRM/road.jpg)



* Result of semantic segmentation:
![avatar](./PRM/ss.jpeg)


```
python ss-bmp.py
```


* Convert semantic picture to bitmap:
![avatar](./PRM/ss.bmp)



```
matlab
astart
```


* Bitmap with random sign:
![avatar](./PRM/allpath.jpg)



* The optimal path from source point to destination:
![avatar](./PRM/path.jpg)


