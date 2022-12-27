ARFoundation ImageTracking
<br>이미지 트래킹

![image](https://user-images.githubusercontent.com/26645827/209616237-138ee880-2014-4963-8213-d76b4bd37b84.png)

-Variable
<br>Dummy : 
<br>![image](https://user-images.githubusercontent.com/26645827/209616265-c2aaeea3-e89e-4897-910f-bdcd41854de7.png)
마커를 놓쳤을때 오브젝트가 위치할 곳

Contents : 
트래킹된 마커 위에 띄울 오브젝트
<br>![image](https://user-images.githubusercontent.com/26645827/209616152-46dd9678-8632-40a6-843f-36cf98b1015a.png)
Contents 오브젝트에 Visualizer.cs 추가

Scanning Effect : 카메라에 비춰진 이미지가 ReferenceImageLibrary에 등록된 이미지일 때 이미지 위에 일정시간동안 띄울 오브젝트
Marker Title : 이미지가 Tracking이되지 않고있을때 UI에 띄워둘 이미지(Tracking이 시작되면 사라짐)
