# ROS를 이용한 군집로봇 지능형 보안 시스템
<img src="https://user-images.githubusercontent.com/47744119/194744159-7ec813aa-9d10-45e1-b72f-c323748b1db6.png"  width="400" height="400"/> &nbsp;<img src="https://user-images.githubusercontent.com/47744119/194744299-4e6f567c-bff5-4451-aeda-3047ed204873.png"  width="600" height="400"/>

## 📝 Description

CCTV와 다수의 로봇을 연계하여 침입자를 추적하고 좌표를 전송하고 침입자가 시야에서 사라진 경우 추적 알고리즘에 활용하여 침입자가 카메라 시야밖에서 갈 수 있는 제한된 구역의 퇴로를 막고 순찰하여 침입자를 찾아내어 운용자에게 침입자의 위치를 알려주는 보안 시스템입니다.

## 📷 Preview
https://www.youtube.com/watch?v=gBajEavedIs

## 📋 Functions

- Lidar와 Encoder motor를 통해서 자율주행이 가능한 자체제작 로봇
- 서보 모터를 이용한 180 회전이 가능한 자제제작  CCTV
- YOLO를 이용한 객체인식 및 물체 탐지
- A* 알고리즘을 활용한 두 좌표간의 최단 거리
- Pyqt5로 제작한 모니터링 GUI 제공
- SLAM을 이용한 Map 제작
- 거리센서를 이용해서 Map에 침입자 좌표 표시
- 다수의 로봇을 제어 할수 있는 서버
- 침입자 탐지시 발동하는 추적 알고리즘
- 침입자 발견시 관리자 핸드폰으로 알림 제공 서비스
