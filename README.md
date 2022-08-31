# &nbsp;빠방:city_sunrise:
### 프로젝트 소개
부동산 매물을 등록할 수 있고, 회원은 위치를 기반으로 매물을 조회하고 계약 할 수 있는 웹사이트입니다.<br>

#### 기획 의도
&nbsp; &nbsp; • &nbsp;현재 정세에 맞춘 **비대면 계약서** 서비스를 통해 편의성 제공 <br>
&nbsp; &nbsp; • &nbsp;**거주 후기 작성** 기능을 통해 다른 회원의 결정에 도움을 줄 정보 제공 <br>
&nbsp; &nbsp; • &nbsp;기본적인 매물 조회, 등록 시 **사용자 맞춤 UI** 제공 <br>

<br>

### 🛠 개발 환경 
&nbsp; &nbsp; • &nbsp;Oracle version : Oracle Database 11g <br>
&nbsp; &nbsp; • &nbsp;Development tool : Eclipse, DBeaver, ERDCloud <br>
&nbsp; &nbsp; • &nbsp;개발 언어 : Java 11, JSP, HTML, CSS, JS <br> <br>

### 🪄 프로젝트 기간 및 역할


<br>

### 🗂️ ERD
<img src="https://user-images.githubusercontent.com/111429706/185704120-3cfe5153-5578-4569-83c2-713b86798ab1.png" width="820" height="540"/>

<br> <br>

### 📚 API 및 Library

#### API

|API 종류|용도|
|:---:|:---:|
|Kakao Map API|좌표 찍기, 편의 시설, 클러스터러 구현|
|주소 검색 API|주소 검색과 지도에 마커 표시|
|부동산 중개업 사무소 정보조회 API|중개사 등록 및 회원가입 시 인증|

#### Library

|Library 종류|용도|
|:---:|:---:|
|mail.jar, activation.jar|이메일 인증 구현|
|chart.js|막대 그래프|
|cos.jar|파일 업로드|
|JSTL|JSP 태그 라이브러리 (EL 사용)|
|ojdbc|Oracle과 프로젝트 연동|

<br> <br>

### 💫 구현 화면
#### 1. 메인 화면
<img src="https://user-images.githubusercontent.com/111429706/185982457-0652d81d-485c-45f1-917d-96664959115e.gif" width="820" height="420"/>
 
<br> <br>
 
#### 2. 이메일 인증
<img src="https://user-images.githubusercontent.com/111429706/185982472-1ae6e42a-9529-41a3-8479-6c8991d7bbf3.gif" width="820" height="420"/>
 
<br> <br>
 
#### 3. 회원 가입
<img src="https://user-images.githubusercontent.com/111429706/185982482-31d4ae2e-8cc9-43c0-859f-a57f396c8f62.gif" width="820" height="420"/>
 
<br> <br>
 
#### 4. 매물 상세보기
<img src="https://user-images.githubusercontent.com/111429706/185982497-11bce374-c9c9-4063-8acb-6ce53940fb99.gif" width="820" height="420"/>
 
<br> <br>
 
#### 5. 후기게시판
<img src="https://user-images.githubusercontent.com/111429706/185982516-70ee4d60-4e0b-41ae-8c7b-0fedb220b206.gif" width="820" height="420"/>
 
<br> <br>
 
#### 6. 계약과정
<img src="https://user-images.githubusercontent.com/111429706/185982532-c3623c2b-111a-4b99-ad15-0bd089b908b9.gif" width="820" height="420"/>
 
<br> <br>
 
#### 7. 매물등록과 관리
<img src="https://user-images.githubusercontent.com/111429706/185982536-0e2d84c2-c241-42f1-a0eb-0ab74bb01e63.gif" width="820" height="420"/>
 
<br> <br> <br> <br>


### 📝 피드백
MVC 모델을 기반으로한 웹 사이트 제작의 기본적인 흐름에 대해 파악할 수 있었고 json 데이터를 어떻게 주고받는지, 또 prg는 어디에서 적용하면 좋을지 고민하는 과정에서 많은 부분을 배울 수 있었다. 특히 다양한 open api, 라이브러리를 활용해보며 다채로운 기능을 구현해 볼수 있었다. <br>
하지만 코드를 구현할 시에는 미숙함이 느껴졌다. 특히 페이지 내에서 사용되는 데이터의 일부가 다른곳에서 사용될 경우 어떤 방식으로 접근해야 효율적일지를 구분짓기가 어려웠다. 또 공통 레이아웃을 잡는 과정에서 신경쓰지 못했던 작은 부분들도 있었다. 이는 각 페이지구현을 진행할때마다 코드를 반복적으로 작성하게 만들었고, 결국엔 전체적인 코드의 가독성을 떨어트린 것 같다. 코드의 재사용은 객체 지향 프로그램을 이용하는 중요한 이유 중 하나인데 그냥 알고만 있는 것과 직접 프로젝트를 구현하는 것은 다르다는 것을 깨달았고 많은 프로젝트나 실무 경험을 통해 실력을 쌓아야겠다고 느꼈다. 그리고 프로젝트 기간이 끝났다고 손 떼는 것이 아니라 리팩토링을 통해 코드를 유지보수 할 계획이다.




