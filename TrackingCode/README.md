# 열화상 카메라를 사용한 딥러닝 얼굴인식 프로그램 (ResNet 기반)

※ 11/30일 부로 프로젝트 종료

## ResNet50 모델 사용중

ResNet50 architecture : 
https://iq.opengenus.org/resnet50-architecture/

---
### 사용중인 환경 : 
테스트 환경 : anaconda3(가상환경), VSCode
구동 환경 : Raspberry Pi

### 사용시 초기설정 필요)
Tensorflow 패키지 설치
>pip install tensorflow

OpenCV 패키지 설치
>pip install opencv-python

Dlib 패키지 설치
>conda install -c conda-forge dlib

cvlib 패키지 설치
>conda install tensorflow-gpu

>pip install cvlib

PIL 패키지 설치
>pip install image

---
## 변경 이력
1. Haar cascades
2. dlib 기반 five point model
3. ResNet50
