# 1. Installation related environment
```shell
git clone https://github.com/hx-0614/ShipYOLO.git
cd ShipYOLO
pip install -r requirements.txt
```


# 2. Train
Pre training model yolov4.weights.
```shell
python train.py --rect
```


# 3. Test
```shell
python inference.py    # change ".pth" to deploy ".pth"

python test.py
```


# 4. Detect
```shell
python detect.py
```


# 5. Citation
```shell
...
```
## Acknowledgements
[https://hub.fastgit.org/WongKinYiu/PyTorch_YOLOv4](https://hub.fastgit.org/WongKinYiu/PyTorch_YOLOv4)<br />

