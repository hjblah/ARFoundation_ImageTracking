ARFoundation ImageTracking it made at UNITY version 19.4.0f1

![image](https://user-images.githubusercontent.com/26645827/209616237-138ee880-2014-4963-8213-d76b4bd37b84.png)

-Variable
<br>Dummy : Where the object will be located when the marker is missed
<br>![image](https://user-images.githubusercontent.com/26645827/209616265-c2aaeea3-e89e-4897-910f-bdcd41854de7.png)

Contents : Add Visualizer.cs to the object Contents object to float above the tracked marker
<br>![image](https://user-images.githubusercontent.com/26645827/209617666-6c530b5d-1918-42e9-a748-7a927e5f2b35.png)

Scanning Effect : Objects to float on the image for a period of time when the image reflected on the camera is a registered image in the "ReferenceImageLibrary"
<br>Marker Title : Image to be floated in UI when image is not being tracked (disappears when tracking starts)

<hr />
<br>When tracked for the first time, the ScanTimer increases, and after a certain period of time, objects in the index's Contents, such as Dummy, appear on the tracked image. If the marker is missed after tracking is completed, the object is moved to the location of Dummy and appears fixed.
