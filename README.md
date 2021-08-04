# ITEACH

## 개요 : 개발자 커뮤니티 사이트

+ 개발자가 되기 위해 공부하는 사람들이 모여 소통 가능
+ IT분야의 채용정보 및 다양한 정보들을 한 곳에서 많은 사람들과 공유
+ 관련 자격증 기출문제를 풀 수 있으며 모르는 부분은 질문/답변게시판에서 도움을 받을 수 있음
+ 스터디 모집 공간을 통해 지역별로 스터디그룹을 모집할 수 있음

## 사용기술 및 개발 환경
<img src="https://img.shields.io/badge/JAVA-007396?style=for-the-badge&logo=java&logoColor=white"> <img src="https://img.shields.io/badge/oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white"> <img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"> <img src="https://img.shields.io/badge/jquery-0769AD?style=for-the-badge&logo=jquery&logoColor=white"> <img src="https://img.shields.io/badge/html-E34F26?style=for-the-badge&logo=html5&logoColor=white"> <img src="https://img.shields.io/badge/css-1572B6?style=for-the-badge&logo=css3&logoColor=white"> <img src="https://img.shields.io/badge/apache tomcat-F8DC75?style=for-the-badge&logo=apachetomcat&logoColor=white"> <img src="https://img.shields.io/badge/Eclipse IDE-2C2255?style=for-the-badge&logo=Eclipse&logoColor=white"> 

+ 사용자 회원가입 / 로그인/ 정보 수정 /회원탈퇴
+ 사용자 모든 게시물에 댓글 작성 및 조회
+ 기출문제 게시판에서 자격증 관련 기출 문제 다운 및 문제 풀기 
+ 질문 및 답변 게시판에서 질문 및 답변 작성
+ 채용공고 게시판에서 채용 정보 조회
+ 서적 게시판에서 IT관련 추천 서적 조회 및 추천 
+ 공지사항/ 자유 게시글/ 스터디 모집 게시판 조회 및 작성 

## 핵심 특징
<img width="500" alt="메인페이지" src="https://user-images.githubusercontent.com/71073027/128118115-b3e1f089-17eb-4cb3-bec7-4651573b8736.png" width="50%" height="50%" border= "1px solid gray">

* 사이트의 메인페이지 
  * 가로 배너의 시작하기 버튼을 누르면 회원가입 페이지로 넘어감
  * 채용 글을 올린 회사의 이미지와 추천 서적의 이미지를 최신순으로 보여줌
  * +더보기 버튼을 클릭하여 모든 채용 정보 및 서적의 게시물을 볼 수 있음
<hr>

<img width="400" alt="기출문제1" src="https://user-images.githubusercontent.com/71073027/128122723-ef1e2a05-fcc9-447d-89c6-efb853fb785e.png">  <img width="400" alt="기출문제4" src="https://user-images.githubusercontent.com/71073027/128122750-909a1f4c-c9da-449d-9a70-93a53da54e55.png"  width="50%" height="50%">
* 기출문제 작성 게시판
  * 관리자만 글 작성/수정/삭제가 가능하며 기출문제와 답안을 첨부할 수 있음
  * 다섯 개의 문제를 예시로 올려 사용자들이 다운 받기 전 문제를 풀어볼 수 있음
  * 문제 하단의 정답을 클릭하면 숨겨 있던 정답이 보이게 되고 다시 클릭하면 정답을 가릴 수 있음
<hr>

<img width="280" alt="서적리스트" src="https://user-images.githubusercontent.com/71073027/128125792-675c5b66-5758-49ba-a5d8-c763bdcb7bf8.png">  <img width="300"  height="400" alt="서적작성" src="https://user-images.githubusercontent.com/71073027/128122430-99fb82d8-e88e-4b76-8659-a98ba6e7a6ed.png">    <img width="300" height="400" alt="ㅇㅁㄴㅇㅁㄴㅇ" src="https://user-images.githubusercontent.com/71073027/128123419-a8683fbd-6e2b-445a-ba43-f23945a2f855.png">

* 추천 it 서적 게시판
  * 관리자만이 글 작성/삭제가 가능하며 서적 이미지와 정보를 올릴 수 있음
  * 이미지 공간을 클릭하여 사진을 첨부할 수 있음
  * 서적 내용은 130자 제한을 두어 간략한 내용만 담도록 구현
  * 추천하는 서적의 빠르게 파악할 수 있게 추천 기능 구현
  * 서적에 대한 자유로운 의견을 공유할 수 있도록 댓글 기능 구현
<hr>

<img width="450" alt="채용공고3" src="https://user-images.githubusercontent.com/71073027/128127389-726a72af-1dc8-4445-9ccd-a04dd59ed6ae.png"> <img width="450" height="370" alt="채용" src="https://user-images.githubusercontent.com/71073027/128127529-e4cc2562-f8b6-4b2d-91d0-34f6a612156c.png">

* 채용 공고 게시판
  * 관리자만이 글 작성/삭제가 가능하며 서적 이미지와 정보를 올릴 수 있음
  * 이미지 공간을 클릭하여 사진을 첨부할 수 있음
  * 서적 내용은 130자 제한을 두어 간략한 내용만 담도록 구현
  * 추천하는 서적의 빠르게 파악할 수 있게 추천 기능 구현
  * 서적에 대한 자유로운 의견을 공유할 수 있도록 댓글 기능 구현
<hr>


## 설계 주안점
+ 질문/답변 게시판에 코드 복사해서 올리는 방식과 파일형식으로 업로드하는 두 가지 기능을 구현해 다양한 방식으로 답변 가능하도록 구현
+ 사이트의 디자인과 게시물들을 깔끔한 레이아웃으로 한 눈에 알아보기 쉽게 디자인함
+ IT관련 자격증의 기출문제를 풀어볼 수 있는 게시판을 제작하여 문제를 다운 받지 않고도 풀어볼 수 있는 기능을 구현
+ 서적을 추천할 수 있는 기능 구현
+ IT관련 채용정보를 제공


## 팀원별 단위 업무

김 지 연(팀장) : 프로젝트 일정 및 전체 관리, 채용공고 게시판, 메인페이지 <br>
최 원 석         : 질문 & 답변 문법 게시판                            <br>
이 정 호         : IT 추천 서적게시판 , 메인 페이지                   <br> 
류 승 재         : 회원가입, 마이페이지                               <br> 
정 희 정         : 기출문제 게시판                                    <br>
윤 종 훈         : 커뮤니티 (공지사항, 자유글, 스터디 그룹) 게시판      <br>
         
