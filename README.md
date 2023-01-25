# ML basics with Keras
## 케라스를 활용한 ML의 기초
이 레파지토리는 https://www.tensorflow.org/ 에서 제공하는 tutorial을 따라하며
텐서플로우에서 제공하는 딥러닝 코드에 대한 이해와 올바른 사용법을 익히기 위한 과정입니다.

# 실습해볼 내용
### 1. Basic image classification
 케라스에서 제공하는 fashion_mnist 데이터와 모델들을(Flatten, Dense, softmax) 활용한 이미지 분류 모델을 개발<br>
  : 모델의 개발을 통해 케라스에서 제공하는 모델의 사용법과 모델을 구성해보고 결과값을 확인해본다.
### 2. Basic text classification
 IMDB에서 가져온 25000개의 영화 리뷰 데이터를 활용하여 리뷰를 긍정과 부정으로 나누는 모델을 개발<br>
  : 텍스트 데이터의 벡터화에 대해서 알아보고 케라스의 Embedding, GlobalAveragePooling1D 레이어들을 활용한 모델 구성 및 테스트를 진행본다.
### 3. Text classification with TF Hub
 2번에서 진행한 IMDB의 영화리뷰를 사전학습이 진행된 TF-Hub의 임베딩 모델을 활용하여 모델을 설계<br>
  : TF-hub의 사전학습 모델에 대해 배워보고 적용해보는 시간<br>
   TF-Hub의 주소 : https://tfhub.dev/
### 4. Regression
 미국, 유럽, 일본의 일부 자동차 정보를 바탕으로 연료 사용량을 예측해보는 회귀 모델을 설계 및 모델의 변수와 layer 수가 예측에 미치는 영향을 확인해 본다.<br>
  : 1. 단일변수를 활용한 단순 회귀 모델 구성<br>
  : 2. 다중변수를 활용한 단순 회귀 모델 구성<br>
  : 3. 단일변수를 활용한 DNN 회귀 모델 구성<br>
  : 4. 다중변수를 활용한 DNN 회귀 모델 구성
### 5. Overfit and underfit
 모델의 크기에 따른 epoch에 따른 loss 값의 변화를 확인하며 overfitting 여부를 확인하고 weight 제한과 dropout을 통해 overfitting을 방지해 본다.<br>
  : 1. 레이어 수의 변화를 주며 layer의 수에 따른 overfitting 정도를 확인해 본다.<br>
  : 2. L2 정규화를 통한 weight 제한을 통해 overfitting이 해소되는 정도를 확인해본다.<br>
  : 3. Dropout을 통해 overfitting이 해소되는 정도를 확인해본다.<br>
  : 4. L2 + Dropout 을 통해 두가지 방식을 함께 사용했을 때의 변화를 확인해본다.
### 6. Save and load
  : 모델을 저장하고 로드하는 방법에 대해 배워본다.
### 7. Tune hyperparameters with the Keras Tuner
  : keras tuner의 하나인 Hyperband를 사용하여 learning_rate와 dense layer의 unit 수를 조정하며 최적의 하이퍼파라미터를 찾는 법을 실습해본다.
### 스터디를 위해 예제의 일부를 변형하거나 추가적인 코드를 사용될 수 있습니다.
이 레파지토리에서 실습해볼 예제의 출처는 아래와 같습니다 <br> https://www.tensorflow.org/tutorials
