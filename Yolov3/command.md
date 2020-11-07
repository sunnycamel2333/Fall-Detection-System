# Command Lines

+ entering virtual env

```shell
workon myvenv
```



+ for detecting

```shell
python detect.py --source ./images --cfg ./cfg/yolov3-binary.cfg --weights ./weights/best.pt --names data/data_input.names
```



```bash
python3 detect.py --source ...
```

- Image:  `--source file.jpg`
- Video:  `--source file.mp4`
- Directory:  `--source dir/`
- Webcam:  `--source 0`
- RTSP stream:  `--source rtsp://170.93.143.139/rtplive/470011e600ef003a004ee33696235daa`
- HTTP stream:  `--source http://112.50.243.8/PLTV/88888888/224/3221225900/1.m3u8`