# YOLOMT

##
1.This is a multi-task model base yolo,detect human orientation,face pose and face landmark

<table>
<tr>
<th>train results</th>
<th>detect sample1</th>
  <th>detect sample2</th>
</tr>
<tr>
<td><img src="./.asset/results.png" width="540"></td>
<td><img src="./.asset/zidane.jpg" width="500"></td> 
<td><img src="./.asset/273271,6a240004c249873.jpg" width="500"></td> 
</tr>
</table>

2.More detection results can be seen in the. asset folder

<details>
<summary>demo</summary>

### 1.run

```bash
python detect.py --weights yolomt.onnx --source 0  # webcam 
                          img.jpg  # image
                          vid.mp4  # video
                          path/  # directory
                          'path/*.jpg'  # glob
                          'https://youtu.be/Zgi9g1ksQHc'  # YouTube
                          'rtsp://example.com/media.mp4'  # RTSP, RTMP, HTTP stream

```
