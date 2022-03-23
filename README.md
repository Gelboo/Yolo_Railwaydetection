# Yolo_Railwaydetection


# install packages
pip install -r requirment.txt </br>
wget -O yolo-coco/yolov3.weights http://pjreddie.com/media/files/yolov3.weights

# Sources-links
## How Yolo Works:
https://www.section.io/engineering-education/introduction-to-yolo-algorithm-for-object-detection/

https://pyimagesearch.com/2018/11/12/yolo-object-detection-with-opencv/


## How to Run
### For image execution
``` python yolo.py --image images/car_railway_5.jpg --yolo yolo-coco```
### For Video Writing
```python yolo_video.py --input videos/overpass.mp4 --output output/overpass.mp4```

### For Video Streaming & Writing
``` python yolo_video_streaming.py --input videos/overpass.mp4 --output output/overpass.mp4 ```

### For Real Life (Using the camera, on the laptop, or connected)
``` python yolo_real_time.py --output real_detection_out.mp4 ```