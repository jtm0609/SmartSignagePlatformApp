## 프로젝트 명

효율적인 광고 제공과 쉬운 광고 제작을 위한 **스마트 사이니지 플랫폼** 프로젝트 

## 프로젝트 소개

광고를 제작하고 배포하는데, 어려움을 느끼는 개인소비자들을 위한 프로젝트이며, 웹 또는 앱의 에디터를 통하여 광고를 쉽게 제작하고, 사용자가 설정한 시간에 맞춰
제작한 광고가사이니지 광고판에 표출됩니다. 또한 부가적인기능으로, 인공지능을 활용하여, 기존에 획일적으로 제공되는 광고 대신 사용자 성별연령에 맞는 광고를 제공하는 사용자 맞춤형 광고
서비스 또한 탑재한 사이니지 플랫폼을 고안하였습니다.

### 프로젝트 기간
2020.04.01 ~ 2020 10.01

### 역할 배정
웹개발 2명, 앱개발 1명, 서버개발1명

### 본인 역할

#### 광고 제작을 위한 모바일앱 개발(Java)
* SNS 로그인기능 구현 (네이버, 카카오, 구글 API활용)
* 에디터를 동영상광고, 포토 광고로 구분
* 앱에서 만든 동영상을 ffmpeg라이브러리를 통해 동영상파일로 변환
* realm을 통해 만든 광고를 어플내에 저장하여 관리
* Rest API(OkHttp)통신을 통해 광고영상 서버에 전송

#### 간단한 회원관리 서버 개발(php)
* php를 이용한 회원관리 서버개발(https://github.com/jtm0609/SignUp-Login-php)

## 라이브러리
Glide, Realm, FFMPEG, OKHTTP(RestAPI), 소셜 로그인OpenAPI(카카오,네이버,구글)

## 설계
![설계](https://user-images.githubusercontent.com/48284360/96730440-1e388a00-13f1-11eb-9ec2-b11ac97aea32.png)

## 스크린샷
<div>
<img width="200" src="https://user-images.githubusercontent.com/48284360/96737377-935b8d80-13f8-11eb-9be8-577fcd625c2c.jpg"> 
<img width="200" src="https://user-images.githubusercontent.com/48284360/96737395-96567e00-13f8-11eb-9c6b-e91c0d5aec52.jpg">
<img width="200" src="https://user-images.githubusercontent.com/48284360/96737404-99ea0500-13f8-11eb-9b3f-a5353806970c.jpg">
<img width="200" src="https://user-images.githubusercontent.com/48284360/96737417-9c4c5f00-13f8-11eb-9593-cd45c2f7f9f9.jpg">
<img width="200" src="https://user-images.githubusercontent.com/48284360/96737426-9f474f80-13f8-11eb-86c3-b99e723d15af.jpg">
<img width="200" src="https://user-images.githubusercontent.com/48284360/96737431-a2424000-13f8-11eb-91e2-e2079ff1f70e.jpg">
<img width="200" src="https://user-images.githubusercontent.com/48284360/96737441-a53d3080-13f8-11eb-910f-27b46dadc9dc.jpg">
</div>

## 한계
원래는 회원관리 DB를 하나의 백엔드서버로 두어 nodejs기반으로 서버개발 담당하는 학생이 개발을 하려고했으나, 시간적인문제와 학습적인 문제로 개발진행이 어려워, 필자가 회원관리하는 서버만 별도로 php로 개발해서 안드로이드와 통신하는부분까지 구현해보았다.
