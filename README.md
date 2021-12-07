# 2021_AI_heart_diease_datathon_subject1

# 유넷 모델사용
https://github.com/qubvel/segmentation_models
해당링크참조

유넷 모델 필수 라이브러리 버전

python 3
keras >= 2.2.0 or tensorflow >= 1.13
keras-applications >= 1.0.7, <=1.0.8
image-classifiers == 1.0.*
efficientnet == 1.0.*

colab에서 사용.
코랩에서는 그냥 train.ipynb파일을 실행시키면 문제 없음

이외 window환경으로 사용할 시 requirements.txt 참조.

dataaugmentation.ipynb를 활용하여 dataaugmentation
A2C_train.ipynb, A4C_train.ipynb를 활용하여 전처리, 학습, 테스트를 진행함

위에서 설명한 패키지 설치가 완료되었으면

A2C_train.ipynb, A2C_train.ipynb에서 
![image](https://user-images.githubusercontent.com/81897022/144899331-d8078e96-c7a8-4432-9b2f-60e3daf0192f.png)
위에서 테스트하고자 하는 파일에 맞게 파일경로 입력
(대회에서 제공했던것처럼 폴더하나에 정답과 이미지가 함께있고 이름이 같아야함)
(A2C/ A4C는 별도의 폴더)
(제공했던 파일 구성에 맞게 전처리 코드를 짰음)



#for train이라 적혀 있는 것을 제외하고 모두 실행시키면 파일 가장 하단에서 테스트 결과를 확인할 수 있습니다.
(예외로 if use A2C , if use A4C라고 적혀있는 파일은 모델 조건에 맞게 실행을 해야합니다)

![image](https://user-images.githubusercontent.com/81897022/144963030-d9819ccb-8957-41bf-9bff-2ab735a7d60a.png)

예시파일






A2C모델은 기본적으로 TRAIN이미지가 3채널입니다. 
A4C모델은 기본적으로 TRAIN이미지가 4채널입니다.




모델을 더 잘 만들고 싶은 마음에 깔끔하게 코드를 짜는데 시간을 할애하지 못했습니다.
양해 부탁드립니다.

문제시 연락주시면 빠른 해결 가능합니다.

//

