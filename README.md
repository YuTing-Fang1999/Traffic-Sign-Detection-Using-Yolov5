# Traffic-Sign-Detection-Using-Yolov5

download
```
git clone https://github.com/YuTing-Fang1999/Traffic-Sign-Detection-Using-Yolov5.git
```
enter to yolov5
```
cd yolov5
```

camera
```
python detect.py --weights best1.pt --img 320 --conf 0.5 --source 0 --line-thickness 1
```
press ctrl+c to exit

test img
```
python detect.py --weights best1.pt --img 320 --conf 0.5 --source  test_img --line-thickness 1
```
results are saved in runs/detect/exp


video  
```
python detect.py --weights best1.pt --img 960 --conf 0.8 --source  test_img/1.mp4 --line-thickness 1
```

# Reference
Jocher, G. (2020). YOLOv5 by Ultralytics (Version 7.0) [Computer software]. https://doi.org/10.5281/zenodo.3908559
