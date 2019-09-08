# yolov3_object_detection_OpenCV

1. clone the repo
2. download yolov3 weight from from https://pjreddie.com/media/files/yolov3.weights to yolo-coco folder 
3a. run for image
``` 
python yolo.py --image {images_path}/{imageFile}.jpg --yolo yolo-coco
```

3b. run for video
```
python yolo_video.py --input {input_videos_path}/{videoFile}.mp4 --output {output_videos_path}/{videoFile}.avi --yolo yolo-coco
```

n.b. --confidence {float value} --threshold {float value} if you wish to change confidence or threshold default values (.5 and .3)
