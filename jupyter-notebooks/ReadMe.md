Before to start
===

모델 훈련 과정을 직접 실행해보기 위해선 실험 환경을 준비해야합니다. 
본 실험을 진행한 간략한 스펙은 다음과 같습니다.
- OS: Window 10 (64bit)
- CPU: Intel Core i7 9700
- GPU: NVIDIA GeForce GTX 1080 Ti (GPU Memory: 11GBytes)
- Memory: 32GBytes

또한, 주요 모듈 버전은 다음과 같습니다.
- **python 3.6, pytorch 1.5.0 for cudatoolkit=10.2**
- CUDA 10.2, cuDNN 7.6.5 for CUDA 10.2 (사용하는 GPU에 따라 달라질 수 있으나, 본 모델을 실행하기 위해 10.0 이상을 설치하는 것을 추천)


훈련에 앞서 반드시 GPU 메모리가 충분한지 확인하기 바랍니다. 실행을 할 수 없는 경우를 위해 .ipynb에 코드 실행결과를 같이 기록했으니 참고하시기 바랍니다.

Contents
===

1. [실험 환경 설치](./1_setting_environment.ipynb)
2. 학습 데이터 전처리
3. 모델 자세히 설명
4. 모델 학습, 성능 테스트
5. 결과 시각화