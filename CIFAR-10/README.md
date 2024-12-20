# Deep-Neural-Network_3

## 숙제 3

### CIFAR-10

+ CIFAR-10 데이터셋을 사용하여 다층 퍼셉트론 또는 Wide & Deep 모델을 구축하고, 텐서보드를 활용하여 모델 학습 과정을 시각화한다
+ 또한 모델 성능 향상을 위해 Early Stopping과 ModelCheckpoint 콜백을 사용한다

절차:
1. CIFAR-10 데이터셋 불러오기 및 관찰하기
2. 데이터 전처리 (이미지를 1차원 벡터로 평탄화, 정규화 등)
3. 데이터셋을 학습/검증/테스트 세트로 분할
4. 다층 퍼셉트론 또는 Wide & Deep 모델 구조 정의
  + 다층 퍼셉트론: 입력층, 은닉층(활성화 함수 포함), 출력층
  + Wide & Deep: 와이드 부분(범주형 특성)과 딥 부분(수치형 특성) 병렬 구조
5. 모델 컴파일 (손실함수, 메트릭 등 설정)
6. 텐서보드 콜백, EarlyStopping 콜백, ModelCheckpoint 콜백 설정
7. 모델 학습 및 텐서보드에서 시각화 (손실, 정확도, 계산 그래프 등)
8. 검증 세트에서 모델 평가
9. 테스트 세트에서 최종 모델 평가
10. 최적의 모델 가중치를 저장

주의 : 
+ 신경망 구조는 다층 퍼셉트론 또는 Wide & Deep 모델로 한정