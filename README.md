# synthetic_speech_classification
## 1. 프로젝트 요약
### 1-1. 설명
합성 음성이 주어졌을 때 합성 방법에 따라 분류하고, 만약 가지고 있는 카테고리에 없는 분류 방법을 사용한 것이라면 unknown으로 분류하는 모델을 MATLAB 또는 Python을 이용하여 개발한다. 잡음, 압축과 같은 변형이 있는 합성 음성에서도 강건한 성능을 보여야 한다.
### 1-2. 개발 규모
- 인원 : 3명
- 일시 : 2022.01 ~ 2022.03
### 1-3. 개발환경
- MATLAB
- Python : Librosa, Tensorflow

## 2. 프로젝트 구현
### 2-1. Melspectrogram 추출
![known-unknown Melspectrogram](https://github.com/Ohsechan/synthetic_speech_classification/assets/77317210/546e74d0-5112-4320-ac59-e2a7235968a0)
### 2-2. CNN 모델 구조
![CNN 모델 구조](https://github.com/Ohsechan/synthetic_speech_classification/assets/77317210/7089838e-3790-4167-8291-a3aa6cc84869)
### 2-3. Sequence Diagram
![시스템 구성도](https://github.com/Ohsechan/synthetic_speech_classification/assets/77317210/3c87e113-889b-4381-8dac-2d16ecddde9e)
