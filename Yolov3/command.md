# Command Lines

+ entering virtual env

```shell
workon myvenv
```





+ for trainning

```shell
python train.py --cfg ./cfg/yolov3-binary.cfg --device 2 --data ./images/data_input.data --epoch 300 --weights ./weights/yolov3.pt --batch-size 8
```



+ for detecting

```shell
python detect.py --source ./images --cfg ./cfg/yolov3-binary.cfg --weights ./weights/best.pt --names images/data_input.names
```



+ for deploying rstp

```shell
python detect.py --cfg ./cfg/yolov3-binary.cfg --weights ./weights/best.pt --names images/data_input.names --source rtsp://admin:passcode@192.168.1.108:554
```



+ for tensorboardX

```shell
tensorboard --logdir=runs
```

