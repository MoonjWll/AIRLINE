
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
      * **공항 검색** <br>
        * 출발지와 도착지에 도시 이름을 작성하면 공항코드와 나라정보를 표시합니다. <br>
      * **운항 일정 검색** <br>
        * 날짜와 경로가 맞는 운항목록을 찾아 화면에 표시합니다. <br>
      * **회원, 비회원 예매 확인 페이지** <br>
        *세션을 확인하여 로그인 하지 않은 상태로 예매 시 바로 로그인을 할 수 있는 페이지를 띄워주며 회원가입, 비회원으로 진행하기를 선택할 수 있습니다. <br>
      * **승객 정보 입력** <br>
        * 인원 수 만큼 승객의 정보를 입력받아 저장합니다. <br>
      * **좌석 예약** <br>
        *선택한 운항목록의 좌석 현황을 이미지로 표시하고 비어있는 좌석을 선택하여 좌석을 예약할 수 있습니다. <br>
      * **결제 화면** <br>
        * 결제 화면에서 인원 수 만큼 항공표의 값과 세금을 계산할 수 있으며 회원인 경우 포인트를 사용, 적립이 가능합니다. <br>
  </details>
  
  <details>
    <summary>회원</summary>
     2  <br>
      * **로그인** <br>
        * Modal창을 통해 로그인 화면을 출력하고 DB를 통해 기존에 저장된 회원의 정보와 일치 시 정보를 세션에 담아둡니다. <br>
      * **아이디 찾기/비밀번호 찾기**  <br>
        * 회원가입 시 작성한 Email을 받아 DB에서 조회 후 해당 Email로 아이디를 전송합니다. <br>
        * 비밀번호 찾기 시 Email과 아이디를 조회하여 해당 Email로 비밀번호를 전송합니다. <br>
      * **회원가입**  <br>
        * Ajax를 사용하여 비동기로 아이디 중복체크를 하며 유효성검사를 통해 비밀번호 확인 여부와 필수 입력사항 미 기입여부를 알려줍니다. <br>
      * **프로필**  <br>
        * 세션에 저장된 회원의 정보를 통해 상세 정보 및 회원의 포인트를 프로필 화면에 출력하고 출력한 정보를 수정할 수 있는 기능입니다. <br>
        * 회원 이미지 클릭 시 이미지 파일을 수정할 수 있습니다. <br>
      * **비밀번호 변경** <br>
        * 유효성검사를 통해 기존 비밀번호, 새 비밀번호와 확인 비밀번호를 검사하여 비밀번호를 수정할 수 있습니다. <br>
      * **예매조회** <br>
        * 회원이 구매한 예매표의 정보를 출력하는 페이지입니다. <br>
      * **지난 예매조회** <br>
        * 현재 시간을 기준으로 운항이 완료된 예매표의 정보를 출력하는 페이지입니다. <br>
      
  </details>
  
  <details>
    <summary>관리자</summary>
     3  <br>
      * **매출현황** <br>
        * 설정한 년도의 월 별 매출을 조회하여 차트로 출력한 페이지입니다. <br>
      * **회원관리** <br>
        * 모든 회원의 목록을 페이징처리하여 출력하고 선택 시 회원의 상세 정보를 Modal로 출력합니다.  <br>
         * 비밀번호, 이름, 국적 등을 수정하거나 삭제할 수 있으며 직원 코드를 부여할 수 있습니다. <br>
         * 회원의 아이디를 검색하여 특정 회원만을 검색할 수 있습니다. <br>
      * **직원관리** <br>
        * 모든 직원의 목록을 페이징처리하여 출력하고 선택 시 해당 직원의 상세정보를 Modal로 출력합니다. <br>
        * 출력한 상세 정보에서 수정하거나 삭제할 수 있습니다. <br>
        * 직원 아이디, 이름, 부서코드를 검색하여 특정 직원을 검색할 수 있습니다. <br>
        * 직원 추가가 가능하며 회원과는 별도로 직원 정보를 위한 직원 아이디가 있으며 후에 회원 아이디와 연동을 하는 방식으로 설계하였습니다. <br>
      * **예매관리** <br>
        * 현재 시간 이후의 운항 예정인 예매 표에 대해 조회할 수 있는 페이지입니다. <br>
        * 선택 시 상세 예매 정보를 Modal로 출력하며 일정 부분 정보를 수정할 수 있도록 했습니다. <br>
        * 예매코드, 비회원 코드, 회원아이디로 특정 예매를 조회할 수 있습니다. <br>
      * **운항관리** <br>
        * 항공기의 목록을 표시하는 페이지입니다. <br>
        * 항공기 별 운항 일정을 조회하여 가장 최근의 일정의 다음 운항 경로와 출발 날짜, 도착날짜를 표시하며 최종 운항에 대한 경로와 날짜정보를 담습니다. <br>
        * 만약 항공기가 현재 시간을 기준으로 운항중인 경우 초록색으로 표시하여 비행, 대기 상태를 달리 표시합니다. <br>
        * 항공기를 선택하여 운항 목록을 확인할 수 있으며 목록을 선택하여 정보를 수정할 수 있으며 좌석 조회를 이미지로 확인할 수 있습니다. <br>
        * 좌석 조회 시 해당 운항 좌석의 이미지를 출력하며 예약되어있는 좌석의 승객 정보를 출력하고 좌석을 변경시킬 수 있습니다. <br>
        * 선택한 항공기의 새 운항 일정을 추가할 수 있으며 현재 시간을 기준으로 바로 다음 운항 일정을 조회하여 네시간 이후부터 <br>
          해당 공항에서 경로가 있는 다른 공항으로만 갈 수 있게 설정을 할 수 있도록 하였습니다. <br>
        * 새 운항 일정을 생성 시 해당 항공기의 정보에 맞춰 좌석들을 만들도록 하였습니다. <br>
  </details>
  
