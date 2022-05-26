## Bubbleing-Tensorflow.js-Model

버블링(Bubbleing) 의 Tensorflow.js 모델 레포지토리입니다. model.json 파일과 가중치 파일이 탑재되어 있으며, raw githubusercontent 를 통해 해당 레포지토리에 접근하여 모델을 이용할 수 있습니다.

### ❓ raw githusercontent 란?
github 레포지토리를 데이터 저장소처럼 이용할 수 있는 기능으로, 레포지토리가 public 으로 설정되어 있는 경우 인터넷에 연결되어 있으면 언제든지 접속하여 데이터를 이용할 수 있습니다.

### :mag_right:raw githubusercontent 를 이용한 모델 로드 방법
1. 현재 레포지토리의 model.json 의 raw githubusercontent 주소인 https://raw.githubusercontent.com/PowerZolffGirl/Bubbleing-Tensorflow.js-Model/main/model.json 를 복사합니다. 이 주소로 입력시, 모델의 데이터와 result 에 대한 내용도 볼 수 있습니다.
2. tensorflow/tfjs-converter 라이브러리로부터 loadGraphModel 을 import 한 뒤, 아래와 같이 모델을 로드하는 코드를 통해 이용합니다.
<img src = "https://user-images.githubusercontent.com/78165538/170563485-c61aa242-4016-422d-9cde-cfd1d53daf84.png" width="700px" height="150px">
