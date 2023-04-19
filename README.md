# FastGAN

## 개요
### 존재하는 이미지를 합성하여 존재하지 않는 이미지를 생성하기 위해 여러 GAN model들을 찾던 중 
### 여러 이미지의 style을 뽑아 새로운 이미지를 만들어내는 StyleGAN2 Model을 찾아 훈련을 진행 해봤으나 부족한 컴퓨팅 리소스 때문에 Model 사용에 어려움을 겪고
### 다른 GAN Model을 찾던 중 다른 GAN Model들과 비교적 적은 컴퓨팅 리소스를 이용하여 더 적은 시간안에 훈련 가능한 Model 인 FastGAN을 발견하여 해당 모델로 직접 훈련을 진행해 봄

## Model 훈련 환경 : ubuntu(18.04), vscode,  python, pytorch, cuda 11.3 
## 사용한 데이터 : Impressionist_Classifier_Data(https://www.kaggle.com/datasets/delayedkarma/impressionist-classifier-data)
## 훈련 시간 : 약 3일(72시간 이상)

## 훈련 후 생성한 이미지
![0](https://user-images.githubusercontent.com/104478563/232967325-3bc8e5f3-57c3-4cba-9e73-66b4ac6e94d3.png)
![0](https://user-images.githubusercontent.com/104478563/232967430-a4c4709d-bb82-4d36-8ff2-b322a9b3482d.png)
![19](https://user-images.githubusercontent.com/104478563/232967448-6af1dd4d-b527-4475-9eb1-04b0f396ac15.png)
![40](https://user-images.githubusercontent.com/104478563/232967464-9c23885d-0138-4547-ba10-8c021557006d.png)
![36](https://user-images.githubusercontent.com/104478563/232967468-76e403d6-c758-44b2-8729-b0a106f8b039.png)
![47](https://user-images.githubusercontent.com/104478563/232967470-0d4514d0-d317-4d72-9393-e3cbeada4368.png)
![56](https://user-images.githubusercontent.com/104478563/232967485-b9ada17f-4666-49a6-8970-103b4e950a32.png)
![48](https://user-images.githubusercontent.com/104478563/232967495-4d4348da-e556-4451-b5bd-39cc6278b02b.png)
![131](https://user-images.githubusercontent.com/104478563/232967531-8c05a7e0-9d06-48da-8d6e-f07e0e78abc9.png)
![160](https://user-images.githubusercontent.com/104478563/232967554-fd70949a-d691-47b1-a8d7-b3224c5bb8a7.png)

## 기존 이미지에 다른 이미지의 스타일을 합성한 이미지
![style_mix_69000](https://user-images.githubusercontent.com/104478563/232967657-d77fe601-56cc-448a-a4b3-4f71d2ba1afb.jpg)
![style_mix_69450](https://user-images.githubusercontent.com/104478563/232967677-69332874-0b06-4458-8844-d86ced1c208e.jpg)
![style_mix_69900](https://user-images.githubusercontent.com/104478563/232967685-44cb0967-2bf2-42e1-beec-66a0d41c208b.jpg)
![style_mix_69550](https://user-images.githubusercontent.com/104478563/232967689-4ae7a150-2390-4b5f-b312-ccc84b89e274.jpg)
![style_mix_69600](https://user-images.githubusercontent.com/104478563/232967692-37dbd91b-5392-4f5c-87a5-17a043171e54.jpg)
![style_mix_69650](https://user-images.githubusercontent.com/104478563/232967697-e1b29ced-cee8-467e-9ff6-d066ca2f8b0a.jpg)
![style_mix_69350](https://user-images.githubusercontent.com/104478563/232967718-e2182422-7da5-4774-87e3-e55f9b957915.jpg)
![style_mix_69150](https://user-images.githubusercontent.com/104478563/232967731-8c92c8e1-99be-4156-977b-768839568e5a.jpg)
