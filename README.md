# Pytorch_YOLOv4_Deepsort
 YOLOv4/YOLOv4-tiny and Deepsort

![demo](demo.gif)

## Download
### Deepsort
Download [ckpt.t7](https://drive.google.com/drive/folders/1xhG0kRH1EX5B9_Iz8gQJb7UNnn_riXi6) and copy to deep_sort_pytorch/deep_sort/deep/checkpoint/

### Yolov4
Download [yolov4.cfg](https://raw.githubusercontent.com/AlexeyAB/darknet/master/cfg/yolov4.cfg) and copy to yolov4/cfg/

Download [yolov4.weights](https://drive.google.com/open?id=1cewMfusmPjYWbrnuJRuKhPMwRe_b9PaT) and copy to yolov4/weights/

**OR**
### Yolov4-tiny

Download [yolov4-tiny.cfg](https://raw.githubusercontent.com/AlexeyAB/darknet/master/cfg/yolov4-tiny.cfg) and copy to yolov4/cfg/

Download [yolov4-tiny.weights](https://github.com/AlexeyAB/darknet/releases/download/darknet_yolo_v4_pre/yolov4-tiny.weights) and copy to yolov4/weights/

## Tracking sources

Tracking can be run on video formats

Yolov4
```bash
python3 track.py --config_detection ./yolov4/yolov4.yaml video_path
```

Yolov4-tiny
```bash
python3 track.py --config_detection ./yolov4/yolov4-tiny.yaml video_path
```
