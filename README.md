## YOLOv5-Object-Detection

Annotated VisDrone Dataset (*YOLO Format*) ZIP - [Roboflow Download](https://app.roboflow.com/ds/9QdPSyMFYi?key=zWatFU59hD)

Jupyter Notebook command Snippet - 
```
!pip install roboflow

from roboflow import Roboflow
rf = Roboflow(api_key="VAo6gQydihnsxvd6qpr3")
project = rf.workspace("souvik-datta").project("yolov5-dataset-2")
dataset = project.version(1).download("yolov5")
```

**VisDrone Dataset** - It is collected by the AISKYEYE team at Lab of Machine Learning and Data Mining , Tianjin University, China. The benchmark dataset consists of 288 video clips formed by 261,908 frames and 10,209 static images, captured by various drone-mounted cameras, covering a wide range of aspects including location (taken from 14 different cities separated by thousands of kilometers in China), environment (urban and country), objects (pedestrian, vehicles, bicycles, etc.), and density (sparse and crowded scenes). [[Link to Original Repository]](https://github.com/VisDrone/VisDrone-Dataset)


References - 

```@ARTICLE{9573394,
  author={Zhu, Pengfei and Wen, Longyin and Du, Dawei and Bian, Xiao and Fan, Heng and Hu, Qinghua and Ling, Haibin},
  journal={IEEE Transactions on Pattern Analysis and Machine Intelligence}, 
  title={Detection and Tracking Meet Drones Challenge}, 
  year={2021},
  volume={},
  number={},
  pages={1-1},
  doi={10.1109/TPAMI.2021.3119563}}
  ```
