# 2021_AI_heart_diease_datathon_subject1

# efficientnet기반 유넷사용
https://github.com/qubvel/segmentation_models

유넷 필수 라이브러리 버전

python 3
keras >= 2.2.0 or tensorflow >= 1.13
keras-applications >= 1.0.7, <=1.0.8
image-classifiers == 1.0.*
efficientnet == 1.0.*

![image](https://user-images.githubusercontent.com/81897022/147854464-26c460d9-7a16-4259-84e2-b91eabed12de.png)


colab 사용.
https://drive.google.com/drive/folders/1ZBjXiY53j7IX4nC71vV_066d_AgoWhqc?usp=sharing

![image](https://user-images.githubusercontent.com/81897022/147854468-08d3dc8f-d347-4d96-860f-169d5fb542f5.png)

![image](https://user-images.githubusercontent.com/81897022/147854470-c7381562-551a-4b88-9fcd-0a9dac983776.png)


17등으로 마감

입상 컷 1.89 (A2C / A4C 각각의 (Jaccard index + Dice Coefficient)의 평균

PLML팀 점수 1.858 

대략 2%정도 차이를 보였음.

아쉬운 점.

1. 기간이 짧아서 모델 앙상블을 고려하지 않은 점.

2. augmentation에서 좌우 이동만을 고려한 점.

3. 심초음파 CT이미지에서 HU(Hounce field Unit)를 고려하지 않은 점.









