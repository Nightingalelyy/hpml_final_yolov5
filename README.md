# hpml_final_yolov5


Created by 

Yuyang Liu --yl8019@nyu.edu

Jiaxin Wang --jw7420@nyu.edu


This project mainly resolve the problem of using yolo model to track the person and vehicles in the video. Our goal is to scale the accuracy when the video is in the poor light condition.


run the following command to install requirement:

```
cd yolov5
pip install -qr requirements.txt
```

Our retrained model direction: /yolov5/model_enhanced.pt


To start with our trained model weight, run the following command under the direction /yolov5:

```
python detect.py --data data/mycoco.yaml --weight model_enhanced.pt --conf 0.25 --source data/videos/test_night_3.mp4
```

If you want to test your own video, place your video under data/videos, and change the name 'test_night_3.mp4' into your own video name





