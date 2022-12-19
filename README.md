# FastGAN

## 개요
### 존재하는 이미지를 합성하여 존재하지 않는 이미지를 생성하기 위해 여러 GAN model들을 찾던 중 
### 여러 이미지의 style을 뽑아 새로운 이미지를 만들어내는 StyleGAN2 Model을 찾아 훈련을 진행 해봤으나 부족한 컴퓨팅 리소스 때문에 Model 사용에 어려움을 겪고
### 다른 GAN Model을 찾던 중 다른 GAN Model들과 비교적 적은 컴퓨팅 리소스를 이용하여 더 적은 시간안에 훈련 가능한 Model 인 FastGAN을 발견하여 해당 모델로 직접 훈련을 진행해 봄

## Model 훈련 환경 : ubuntu(18.04), vscode,  python, pytorch, cuda 11.3 
## 사용한 데이터 : Impressionist_Classifier_Data(https://www.kaggle.com/datasets/delayedkarma/impressionist-classifier-data)
## 훈련 시간 : 약 3일
