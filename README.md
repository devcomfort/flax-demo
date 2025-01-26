# flax-demo

Flax 프레임워크에 적응하기 위해 다양한 예시를 구현하는 것을 목표로 합니다.
모든 모델에 대해 다음의 과정을 순차적으로 수행할 계획입니다:

1. 데이터 준비
2. 모델 구성
3. 학습
4. 평가

학습을 위해 구현할 모델 및 과제는 다음과 같습니다:

1. AutoEncoder - 차원 축소
2. CNN - 이미지 분류 (MNIST)
3. Convolutional AutoEncoder - 이미지 차원 축소 및 복원 (MNIST)
4. 위의 모델들을 chex, optax, orbax와 함께 타입 선언, 체크포인트, 최적화기 등을 구성하기