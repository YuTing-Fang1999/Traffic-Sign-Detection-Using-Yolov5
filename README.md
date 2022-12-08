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
python detect.py --weights best1.pt --img 320 --conf 0.5 --source 'test img' --line-thickness 1
```
results are saved in runs/detect/exp
