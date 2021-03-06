# ML-study
#### 이 레포지토리는 머신러닝의 공부겸 필기노트겸 공유느낌으로 만등어진 곳입니다.  
> 내가쓰는 윈도우 기준으로 설명 맥은 알아서 하시길

# 목차
### 1. 머신러닝이란?    
### 2. 파이썬에서의 프레임워크 종류와 차이  
### 3. 설치방법  
### 4. 예제를 이용한 기본이해  

# 1. 머신러닝이란?
알아서 공부하세요  
[머신러닝 vs 딥러닝 vs 인공지능? A.I. 개념정리!-노마드 코더 Nomad Coders](https://www.youtube.com/watch?v=arbbhHyRP90)  
추후작성

# 2. 파이썬에서의 머신러닝 프레임워크 종류와 차이
## 1.프레임워크란?
이것도 알아서 공부  
[라이브러리? 프레임워크? 차이점 아직도 모름? 5분 순삭.-노마드 코더 Nomad Coders](https://www.youtube.com/watch?v=t9ccIykXTCM&t=280s)  
## 2.프레임워크의 종류

파이썬 머신러닝 프레임워크는 대표적으로 2종류가 있다.
1. pytorch
2. tensorflow

  ## 3.두프레임워크의 차이
[텐서플로우? 파이토치? 딥러닝 프레임워크 1분 정리!-
LG디스플레이_d군의 This Play](https://www.youtube.com/watch?v=wUswG02gfg0)  
추후작성

# 3.설치방법
### 기본적으로 아나콘다를 이용하고 주피터 노트북에서 실행시킬 것이다.

## 공통부분
## 1.아나콘다 설치하기 
검색해서 설치 ㄱ  
[아나콘다 설치하기](https://www.anaconda.com/products/individual)
## 2.가상환경 
### 1.가상환경을 만드는 이유
###  2.가상환경 만들기

## 1. 탠서플로우 캐라스 설치하기
원도우 검색창에 아나콘다 프롬포트를 검색해서 실행시킨다.

![image](https://user-images.githubusercontent.com/76804251/131643532-4587a99a-e05e-410f-a4a7-66cd20b6cae9.png)

pip를 우선 업데이트를 해줘야한다. 실행시킨 터미널에 입력
```
pip install --upgrade pip
```
![image](https://user-images.githubusercontent.com/76804251/131644061-5f0e26f2-dc84-4213-ba8e-088b69dd8c27.png)

pip 업그레이드가 완료가 되면 탠서플로우 설치 cpu와 gpu의 통합버전 공홈이 그럼
```
pip install tensorflow
```
케라스 
```
pip install keras
```

## 주피터 노트북 실행시키기

주피터 노트북 설치하기 똑같이 아나콘다 프롬포트에 명령어 입력
```
conda install notebook
```

설치가 완료되면 주피너 노트북 실행시켜확인해보기
```
jupyter notebook
```

주피터 노트북이 열리면 새로 파일을 만들어서 탠서플로우가 잘 깔려 있는지 확인하자
```
import tensorflow as tf
import keras
```
오류가 안뜨면 설치 성공
이제 설치된 버전을 확인해보자
```
tf.__version__
keras.__version__
```
