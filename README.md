# DL-personal

## What is this?
```
kt AIVLE 스쿨에서 배운 deep learning을 복습하기 위해서 진행해본 프로젝트입니다.
1. DNN1: ML에서 진행했던 스마트폰 가격 예측을 DNN으로 진행
2. DNN2: ML에서 진행했던 타이타닉 생존자 예측을 DNN으로 진행
3. CNN: 은하 모양 분류
```

## 2. 프로젝트 구성
### 2-1. DNN1
* 스마트폰 데이터
* ANN
* DNN

### 2-2. DNN2
* 타이타닉 데이터
* Layer와 Node를 바꿔가며 DNN 진행

### 2-3. CNN
* 은하모양 사진 data
* resnet50 모델로 학습, 분류 진행



## Datas

### CNN - 은하모양 
```
출처: https://www.kaggle.com/datasets/laurenkwong/galaxydat
```
1. edge <hr/>
![100143](https://user-images.githubusercontent.com/72953874/194913083-c39066a4-a91b-4952-b0a0-37161fa17563.jpg)
2. smooth <hr/>
![100078](https://user-images.githubusercontent.com/72953874/194913168-c0c17b22-6407-4ad3-b1d5-0e8f7cbd89ee.jpg)
3. spiral <hr/>
![100673](https://user-images.githubusercontent.com/72953874/194913223-f1bf5afd-a526-4aea-a975-ec120ef5a431.jpg)
4. other <hr/>
![367297](https://user-images.githubusercontent.com/72953874/194913598-fdc4190f-228c-4b7e-8391-b80f3f0c5416.jpg)

## Result
1. DNN - ML보다 높은 성능이 나오지는 못함
2. CNN - 데이터가 너무 많아 시간이 오래걸려 10epochs 밖에 돌리지못함. 결과적으로 val_data기준 0.735의 accuracy를 보여줌.
