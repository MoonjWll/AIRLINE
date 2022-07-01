
* * *


![logo](https://user-images.githubusercontent.com/100543239/173267184-b5ca3ae9-d1fa-41f0-bd34-8c4b8aab6a3c.png)
<img width="176" alt="airline_name" src="https://user-images.githubusercontent.com/100543239/176680457-69c9a7f4-6190-4a90-891b-bce5defb2f60.png">

* * *
<p align="center">
  <kbd>
  <img width="830" alt="airline_main_page" src="https://user-images.githubusercontent.com/100543239/176680472-d96868a8-e077-41d6-8af6-15f1eeb5690c.png">
  </kbd>
</p>

* * *

## 소개  
인천 공항을 기준으로 해외의 공항까지 여객을 운송하는 항공사 프로젝트입니다.

## 참여
 * 문정욱
 * 방성문
 * 정윤기

## 개발환경
  #### Programming Language
  <p>
  <img src="https://img.shields.io/badge/java-007396?style=for-the-badge&logo=java&logoColor=white">
  <img src="https://img.shields.io/badge/javascript-yellow?style=for-the-badge&logo=javascript&logoColor=black">
  </p>
  
  #### Web Freamework
  <img src="https://img.shields.io/badge/spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white">
  
  #### Web Language
  <p>
  <img src="https://img.shields.io/badge/html5-F80000?style=for-the-badge&logo=html5&logoColor=white">
  <img src="https://img.shields.io/badge/css3-blue?style=for-the-badge&logo=css3&logoColor=white">
  </p>
  
  #### CSS Framework
  <img src="https://img.shields.io/badge/bootstrap-purple?style=for-the-badge&logo=bootstrap&logoColor=white">
  
  #### Build Tool
  <img src="https://img.shields.io/badge/apachemaven-red?style=for-the-badge&logo=apachemaver&logoColor=white">
  
  #### Data Base
  <img src="https://img.shields.io/badge/oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white">
  
  #### SQL Mapper
  <img src="https://img.shields.io/badge/mybatis-black?style=for-the-badge&logo=mybatis&logoColor=white">
  
  #### Web Library
  <p>
  <img src="https://img.shields.io/badge/jquery-black?style=for-the-badge&logo=jquery&logoColor=white">
  <img src="https://img.shields.io/badge/ajax-black?style=for-the-badge&logo=ajax&logoColor=white">
  <img src="https://img.shields.io/badge/tiles-black?style=for-the-badge&logo=tiles&logoColor=white">
  <img src="https://img.shields.io/badge/log4j-black?style=for-the-badge&logo=log4j&logoColor=white">
  <img src="https://img.shields.io/badge/jackson-black?style=for-the-badge&logo=jackson&logoColor=white">
  </p>
  
  #### Version Control
  <img src="https://img.shields.io/badge/subversion-skyblue?style=for-the-badge&logo=subversion&logoColor=white">
  
  

* * *
## 기능구현
  <details>
    <summary>예매</summary>
     1  <br>
      * 출발지와 도착지에 도시 이름을 작성하면 공항코드와 나라정보를 표시합니다. <br>
      * 날짜와 경로가 맞는 운항목록을 찾아 화면에 표시합니다. <br>
      * 세션을 확인하여 로그인 하지 않은 상태로 예매 시 바로 로그인을 할 수 있는 페이지를 띄워주며 회원가입, 비회원으로 진행하기를 선택할 수 있습니다. <br>
      * 인원 수 만큼 승객의 정보를 입력받아 저장합니다. <br>
      * 선택한 운항목록의 좌석 현황을 이미지로 표시하고 비어있는 좌석을 선택하여 좌석을 예약할 수 있습니다. <br>
      * 결제 화면에서 인원 수 만큼 항공표의 값과 세금을 계산할 수 있으며 회원인 경우 포인트를 사용, 적립이 가능합니다. <br>
  </details>
  
  <details>
    <summary>회원</summary>
     2  <br>
      * 로그인
        * Modal창을 통해 로그인 화면을 출력하고 DB를 통해 기존에 저장된 회원의 정보와 일치 시 정보를 세션에 담아둡니다.
      * 아이디 찾기/비밀번호 찾기 
        * 회원가입 시 작성한 Email을 받아 DB에서 조회 후 해당 Email로 아이디를 전송합니다.
        * 비밀번호 찾기 시 Email과 아이디를 조회하여 해당 Email로 비밀번호를 전송합니다.
      * 회원가입 
        * Ajax를 사용하여 비동기로 아이디 중복체크를 하며 유효성검사를 통해 비밀번호 확인 여부와 필수 입력사항 미 기입여부를 알려줍니다.
      * 프로필 
        * 세션에 저장된 회원의 정보를 통해 상세 정보 및 회원의 포인트를 프로필 화면에 출력하고 출력한 정보를 수정할 수 있는 기능입니다.
        * 회원 이미지 클릭 시 이미지 파일을 수정할 수 있습니다.
      * 비밀번호 변경
        * 유효성검사를 통해 기존 비밀번호, 새 비밀번호와 확인 비밀번호를 검사하여 비밀번호를 수정할 수 있습니다.
      * 예매조회
        * 회원이 구매한 예매표의 정보를 출력하는 페이지입니다.
      * 지난 예매조회
        * 현재 시간을 기준으로 운항이 완료된 예매표의 정보를 출력하는 페이지입니다.
      
  </details>
  
  <details>
    <summary>관리자</summary>
     3
  </details>
  
