# 토닥토닥 프로젝트 (android)

<img src="https://img.shields.io/badge/platform-firebase-blue">  <img src="https://img.shields.io/badge/platform-android-green"> 

## install

아래 코드를 실행시키고 안드로이드 스튜디오에 import한다.

```c
  git clone https://github.com/aldalddl/TDTD-Project.git
```


## community
- 파이어베이스 realtime database 사용
- 아래와 같은 형태로 database 작성

<img src="https://user-images.githubusercontent.com/63048392/114255908-696f4500-99f1-11eb-84bc-57976e35adea.PNG" width="600" height="200">

- community activity에서 다음과 같은 페이지를 볼 수 있음

<img src="https://user-images.githubusercontent.com/63048392/114255991-121da480-99f2-11eb-84ca-5a4dae51d699.png" width="200" height="350"> <img src="https://user-images.githubusercontent.com/63048392/114255996-13e76800-99f2-11eb-9704-c531e1c0a39e.png" width="200" height="350"> <img src="https://user-images.githubusercontent.com/63048392/114256087-a7209d80-99f2-11eb-9079-54ad1547d308.png" width="200" height="350"> <img src="https://user-images.githubusercontent.com/63048392/114256080-a25be980-99f2-11eb-805f-dfad0be6b6ff.png" width="200" height="350"> 

- 자세한 페이지에 대해서는 아래 링크를 통해 확인 가능

https://www.youtube.com/watch?v=prTo8yogprE&t=519s


### category_menu.java

- 4가지 분류(가족, 성, 대인관계, 자기개념)를 바탕으로 각각의 카테고리에 대한 커뮤니티 관찰 가능
- 원하는 카테고리 선택 시 해당 분류에 해당하는 카테고리로 이동

### writingSolution.java

- 웹 챗봇을 통해 상담 진행 후에 가능
- 웹 챗봇을 통해 상담을 진행하고 나면 그 정보다 database에 들어가게 되고 report_menu.java 에서 그 정보를 확인 가능하다
- 원하는 리스트 항목을 클릭하면 해당 상담에 대해 자신의 생각을 작성 가능
- 작성한 후에 community에 올라간 것을 확인할 수 있음

### report_detail.java

- 자신이 solution을 작성했다면 community에 올라간 것을 확인 가능
- 좋아요 버튼 클릭 가능
- 최신순, 인기순 버튼을 통해서 재정렬 가능
- 해당 community 항목 클릭 시 자신의 상담 정보 열람 가능

<img src="https://user-images.githubusercontent.com/63048392/114257404-d5a27680-99fa-11eb-88ae-294ec2596498.PNG" width="600" height="200">



## Face recognition

### FaceRecognitionAcitivity.java
- microsoft의 azure api 사용
- 자신의 얼굴 사진을 찍고 감정에 대해서 분석
- 분석 결과를 통해 감정과 퍼센트를 나타냄
- 감정 분석 결과를 데이터베이스에 아래와 같은 형태로 저장

<img src="https://user-images.githubusercontent.com/63048392/114257373-91af7180-99fa-11eb-91f3-299bd1fcdeea.PNG" width="400" height="150">


## IoT
