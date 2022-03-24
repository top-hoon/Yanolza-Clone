# 여기어때 Clone
### 여기어때 숙박 예약 플랫폼
 - 기간 : 2021.08.01 ~ 10.26 
 - 환경 : Apache Tomcat 8.0, Chrome 브라우저
 - 개발 : 
 - 사용언어 : Java

### 프로젝트 진행과정
 1. 스토리보드
 2. 테이블정의서 작성
 3. api문서 작성
 4. 퍼블리싱 작업
 5. 더미데이터를 활용한 프론트 서버 및 백엔드 서버 구현
 6. 오류 점검 및 최종 코드 수정
 7. 발표


### 나의 프로젝트 담당 및 역할
 - `frontend` 호스트페이지 퍼블리싱, 관리자페이지 템플릿 이용하여 구현 + axios 통신
 - `backend` 백엔드 전체 기능 구현


## 🛠 STACK 🛠
<div align=center>
  <img src="https://img.shields.io/badge/JAVA-007396?style=for-the-badge&logo=java&logoColor=white">&nbsp
 <img src="https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white">&nbsp
 <img src="https://img.shields.io/badge/Spring Boot-6DB33F?style=for-the-badge&logo=spring boot&logoColor=white">&nbsp
 <img src="https://img.shields.io/badge/JPA-6DB33F.svg?style=for-the-badge&logo=spring-boot&logoColor=black"/>
 <img src="https://img.shields.io/badge/Spring Security-6DB33F.svg?style=for-the-badge&logo=spring-security&logoColor=white"/>
 <img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=Postman&logoColor=black">&nbsp
 <br>
 <img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">&nbsp
 <img src="https://img.shields.io/badge/HTML-E34F26?style=for-the-badge&logo=html5&logoColor=white">&nbsp 
 <img src="https://img.shields.io/badge/CSS-1572B6?style=for-the-badge&logo=css3&logoColor=white">&nbsp
 <img src="https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white">&nbsp
 <img src="https://img.shields.io/badge/Thymeleaf-005F0F?style=for-the-badge&logo=thymeleaf&logoColor=white">&nbsp
 <img src="https://img.shields.io/badge/axios-512BD4?style=for-the-badge&logo=axios&logoColor=white">&nbsp
  <br>
</div>

 
> **<h3>숙박 예약 플랫폼 "여기어때" 프로젝트 선정이유</h3>**
코로나바이러스의 영향으로 한창 호캉스가 인기를 끌고있어서 관심을 가지고 있었고, 
사전조사에서 그냥 웹사이트가 아닌 플랫폼이라는 개념을 가진 사이트인것을 알게되어서 흥미가 생겨 프로젝트를 진행하게 되었습니다.


<div align=center>
  <div>인원</div>
 <strong>프론트엔드 3명</strong><br>
 <strong>백엔드 1명</strong><br>
</div>

## 구성은 크게 3개의 부분으로 나누어져 있습니다.
 - `호스트`는 자신의 숙소를 등록하고 -> `어드민`은 해당숙소를 검토하여 승인을해주고 -> 앞의 과정을 거치고 `유저`페이지에 나올 수 있도록 구성되어있습니다.

### 유저 페이지
 
 - 처음 메인페이지에 들어갔을 때 눈에 눈에 확 들어오지 않는다는 것을 느꼈고 여기어때의 메인컬러를 살리고, 오락요소로 음악플레이어를 넣어주었다
 
<div align=center>
  
![155129671-89e77c43-08d8-444c-b921-4b7bf6365688](https://user-images.githubusercontent.com/79463595/159833451-aa860a7e-53f7-46ae-b773-d0a3700c02c9.gif)
  
</div>


 
 ### 호스트 페이지
 - 숙소를 가지고있는 주인들이 자신들의 숙소를 등록하고 숙소의 방을 등록하는 부분! 
 - 자신의 숙소를 예약한 사람들의 예약정보, 리뷰, 리뷰답글작성등 자신의 숙소와 관련된 데이터등을 다양한 방법으로 확인 할 수 있다.

 <div align= center>
 
![156031892-565048bf-6308-47aa-8404-4b44f9463c8a](https://user-images.githubusercontent.com/79463595/159833778-03b23b01-09bc-4a2a-b981-d108e57b5d8b.gif)
 
  </div>
  
 ### 어드민 페이지
 - 여기어때를 사용하는 사용자와, 호스트들과 관련된 모든 정보를 관리할 수 있는 페이지

 <div align= center>
 
![156308172-a37817b9-4e13-415e-802d-69d44f5533e4](https://user-images.githubusercontent.com/79463595/159833820-ae2da67f-a65e-494e-b4b4-d8ae2ec4f9a3.gif)

 </div>
 
 ### 추가한 기능
- 기존의 여기어때에는 없는 찜하기 기능
- 하트를 클릭했을때 서버와 통신하여 다른 웹사이트의 장바구니 기능과 똑같은 역할을 하게 만들었습니다

<div align= center>
 
![156002798-57a4cf6e-ca61-4b62-9e3c-f789355aa9c8](https://user-images.githubusercontent.com/79463595/159833864-16228673-5d84-42d2-92d8-d3d951235b6a.gif)

 </div>
 
## 아쉬웠던 점
 - 수업을 들으면서 프로젝트를 진행하다보니, 바로바로 적용하는데에 어려움이 있었습니다
 - 백엔드 부분을 혼자 진행하다보니 어려운 부분에 부딪혔을때 물어볼사람이 없어서 힘들었습니다.
 - 다양한 방법으로 진행해보려 했으나 첫 프로젝트라서 시간이 모자라서 아쉬웠습니다.
 
## 느낀 점
 - 프로그램을 부분부분 나누어서 보았을때와 다 합쳐서 보았을 때 말로 표현못할 기분을 느꼈다.
 - 생각보다 협업이라는것은 어렵다고 느꼈다.(디자인을 중시하는 사람이있고, 보여지는것보다는 기술이 중요하다는 사람도 있고, 커뮤니케이션 자체를 좋아하지 않는 사람도 있었고 어려워서 나가고 싶어하는 사람도 있었다..)
 - 하지만 누구한명이라도 포기하지 않으면 할 수 있다는것을 느꼈다.
 - 데이터베이스 설계는 중요하고, 역할분담도 중요하다고 느꼈다
 - 이 프로젝트가 다른사람이 넘겨받았을때도 어려움없이 진행할 수 있도록 설계해야한다고 데이터베이스는 다른분이짜고 코드는 내가 짜는데, 그렇게하면 안된다고 생각했다..ㅠ
 - 다음에는 좋은 커뮤니케이션을 통해서  더 완성도 높은 프로젝트를 만들어야겠다고 생각했다
<div align= center>
 </div>
