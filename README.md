<a href="https://www.youtube.com/watch?v=qxElChg70Ck">
  <img src="https://user-images.githubusercontent.com/45448731/101240773-bb971580-3734-11eb-8306-26d3920e593f.png"/>
</a>

▲클릭하시면 소개 영상을 볼 수 있습니다. 
<br><br>
 

[코드 실행 방법](https://github.com/minji-o-j/system-for-visually-impaired/blob/master/How%20to%20Use(%ED%95%9C%EA%B5%AD%EC%96%B4).md)

---
![HitCount](http://hits.dwyl.com/minji-o-j/system-for-visually-impaired.svg)
[　](https://github.com/ML-DL-Study/system-for-visually-impaired/compare/master...minji-o-j:master)

---
## 개발기간
20/04~20/12 

---
## 개발자
이름|Github|비고
----|---|---
김성현|[@Seong-Hyun-0224](https://github.com/Seong-Hyun-0224)|
김한솔|[@hansol0118](https://github.com/hansol0118)| 
윤대호|[@201810788](https://github.com/201810788)|~2020/06
이혜인|[@hyeinlee725](https://github.com/hyeinlee725)|~2020/08
정민지|[@minji-o-j](https://github.com/minji-o-j)|

---
## 프로그램 설명
- 

---
## 목적 및 필요성 
<img src="https://user-images.githubusercontent.com/61938029/101280932-6c71e300-380f-11eb-9f6b-617ac933f7ee.png" height="240px"/> <img src="https://user-images.githubusercontent.com/61938029/101280935-70056a00-380f-11eb-86fb-46cfe8078322.png" height="240px"/> <img src="https://user-images.githubusercontent.com/61938029/101280940-75fb4b00-380f-11eb-8fb5-95f6df5f094f.png" height="240px"/>
> 고장난 음향신호기, 찾기 힘든 음향신호기의 위치

-	시각장애인들은 점자 블록을 통해 횡단보도를 찾고, 음향 신호기를 통해 신호등의 불빛 색깔을 파악함

-	하지만 2020년 서울 강북구 시각장애인 음향신호기 조사 결과 부적합 판정 **45.9%** 정도로 제대로 설치되어 있지 않은 곳이 많음.

- 또한 한국 장애인 재활 협회 조사 결과 시각장애인 대부분이 **횡단보도 및 신호등, 음성안내 시스템 버튼의 위치 파악에 어려움**을 겪고 있으며, **횡단보도 횡단에 도움이 되는 다른 장치가 필요하다**고 응답함  

---
## 기대효과
- 횡단보도와 신호등이 있음을 파악함과 동사에 신호등의 색상을 검출하여 건너야 할 타이밍을 알려줌으로,써 시각장애인이 횡단보도 이용시 겪는 문제를 해결할 것으로 예상함

---
## 데이터 구축
-

---
## 사용 프로그램
![image](https://user-images.githubusercontent.com/45448731/101232065-c5982480-36f2-11eb-894f-bb80c7f722a4.png)
---
## 사용 모델
### 1차 모델 (20/04~20/05): [YOLOv2](https://github.com/minji-o-j/system-for-visually-impaired/tree/master/v.1.0_YOLOv2(~200529))

<img src="https://user-images.githubusercontent.com/61938029/101282894-f07d9800-381a-11eb-8383-0566207232e1.png" width="300px"/>   <img src="https://user-images.githubusercontent.com/61938029/101282941-2e7abc00-381b-11eb-9a7d-39cd680fa0c2.png" width="300px"/>

# 복붙해서 엔터치지말고 글을 읽고 정리해줘...다시 손 안가게끔제발..ㅠㅠ
- 설명

<br>

### 2차 모델(20/08~20/12) : YOLOv4
- YOLOv4모델에 대한 설명 적는다 이미지 넣기!! <<<<<<<이미지 전에 상생보고서에 논문캡쳐한 그런거말고 모델의 구조 같은거 넣으라는말임  
ppt에 있는 yolov4에 결합되었던것들 언급후적기 : 우리 모델 설명을 영상에서 자세히 안해서 여기서 좀 자세히?

- YOLOv4: 최신기술들의 조합을 통해 만들어져 최적의 속도와 정확도를 자랑하는 모델.
  - YOLOv3 / CSPDarknet53 / SPP / PAN / BOF / BOS 등.

- YOLOv4는 이전 YOLOv2, v3에서의 단점인 작은 크기의 object에 대한 인식을 잘 못하는 것의 해결을 위해 여러가지 기법들을 적용
  - 이를 Bag or Freebies(BOF) / Bag of Specials(BOS)의 2가지 유형으로 나눔.

#### BOF
  - Data augmenation, Loss function, Regularization 등 학습에 관여하는 요소로, training cost를 증가시켜서 정확도를 높이는 방법들을 의미.
 
#### BOS
  - architecture 관점에서의 기법들이 주를 이루고, post processing도 포함되어 있으며, 오로지 inference cost만 증가시켜서 정확도를 높이는 기법들을 의미.
---
## 알고리즘
### 신호등 색상 검출 알고리즘  
### 도보 환경 알리미 알고리즘  
---
## 시연 영상
- 유튜브 링크 이미지로바꿔서 넣기  
https://www.youtube.com/watch?v=AHQ358YE6tY  
https://youtu.be/q3KLPQ416m8  

