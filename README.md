# 🤖 Intelligent Robotics Project Collection

다양한 목적의 **지능형 로봇 시스템**을 모아놓은 종합 프로젝트 공간입니다.  


## 📁 프로젝트 목록

| 프로젝트명 | 설명 | 주요 기술 |
|------------|------|-----------|
| 🚗 **도로지킴이** | 불법 주정차 차량을 탐지하고 자동으로 대응하는 자율 로봇 시스템 | YOLO, ROS 2, TF2, Nav2 |
| 🦾 **요양보조로봇** | 요양 업무 종사자 협동 로봇 팔 | YOLO, ROS 2, TF2, Doosanrobot api |

## 🗺️ 폴더 구조 개요

ROBOT_PROJECT/
├── Transportation_robot
├── Patient_assistance
└── README.md # 통합 대문 


## 🧠 프로젝트 통합 철학

- **문제 기반 설계**: 실제 사회 문제(불법주정차 등) 해결을 위한 구조 설계
- **모듈화**: 각 프로젝트는 독립적으로 실행되면서도 필요한 경우 통합 가능
- **ROS 기반 통신 통합**: 공통 인터페이스와 메시지 구조로 협업 시스템 구현

## 🛠 기술 스택

| 분류        | 기술 구성                        |
|-------------|----------------------------------|
| **프레임워크** | ROS 2 (humble), OpenCV, Python |
| **AI 모델**   | YOLOv8                         |
| **환경**     | Ubuntu 22.04, VS Code           |
| **하드웨어** | TurtleBot4, Doosan-m0609, Depth Camera|

## ✨ 기여 및 확장 방향

- 각 프로젝트의 기능을 통합해 **더 큰 협업 시스템**으로 확장 가능
- 실제 환경 적용을 위한 **고도화 및 정밀 조정** 필요
- 시각화 도구(RViz, Foxglove)로 **디버깅 및 개발 효율 향상**

---

> 각 프로젝트 폴더 내에 있는 `README.md` 파일을 통해 상세 내용을 확인하실 수 있습니다.
>  
> 👉 [도로지킴이 자세히 보기](Transportation_robot/README.md)
> 👉 [요양보조로봇 자세히 보기](Patient_assistance/README.md)
