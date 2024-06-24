# OpenCV and Unity3D integration.
## A simple way to connect Opencv with Unity3D using socket.

## How to run

1. You need to install Unity3D (http://unity3d.com)
2. Install and configure Python and OpenCV (https://blog.csdn.net/qq_41627235/article/details/87692748)
3. Change the 3rd line of OpenCV/gameDemo.py to appropriate installation directory of OpenCv
4. Change 53th line if you want to track another part of human body not left hand, check [this image](https://github.com/Tongzhou-Yu/OpenCV_Unity_ObjectTracking/blob/main/pose_tracking_full_body_landmarks.png)
5. Change the 74th line if your webcam isn't working  
6. Run the OpenCV/gameDemo.py
7. Open the Unity3d Scene Unity3D/Assets/Scenes/socketTest.unity in Unity3D
8. Run the game and you will find the Unity's game object is following your left hand.  
