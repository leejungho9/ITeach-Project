# ITEACH : 개발자 커뮤니티 사이트

## ITEACH 개발 배경 및 개발 목적
2020년 한 취업포털에서 취업준비생을 대상으로 취업준비 현황을 조사한 결과 응답자의 23.8 "IT인터넷" 업계의 취업을 준비한다는 결과가 나왔으며 취업준비생들이 전공에 상관없이 공통적으로 "IT인터넷" 업계에 관심이 높고 종사를 희망하는 사람들이 증가하는 추세임을 알 수 있었다. 이를 바탕으로  IT분야에서도 특히 개발자를 희망하는 사람들이 소통하며 취업 준비를 할 수 있는 사이트를 만들어 IT분야의 다양한 정보들을 한 곳에서 많은 사람들과 공유할 수 있게 하는 것이 ITEACH의 개발 목적이다.

## ITEACH의 차별성
+ 현직 종사자는 물론 개발자가 되기위해 공부하는 사람들이 모여 소통할 수 있음
+ IT분야의 채용정보 및 다양한 정보들을 한 곳에서 많은 사람들과 공유
+ IT관련 자격증 기출문제를 풀 수 있으며 모르는 부분은 질문/답변게시판에서 도움을 받을 수 있음
+ 스터디 모집 공간을 통해 지역별로 스터디그룹을 모집할 수 있음

## 사용기술 및 개발 환경
<img src="https://img.shields.io/badge/JAVA-007396?style=for-the-badge&logo=java&logoColor=white"> <img src="https://img.shields.io/badge/oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white"> <img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"> <img src="https://img.shields.io/badge/jquery-0769AD?style=for-the-badge&logo=jquery&logoColor=white"> <img src="https://img.shields.io/badge/html-E34F26?style=for-the-badge&logo=html5&logoColor=white"> <img src="https://img.shields.io/badge/css-1572B6?style=for-the-badge&logo=css3&logoColor=white"> <img src="https://img.shields.io/badge/apache tomcat-F8DC75?style=for-the-badge&logo=apachetomcat&logoColor=white"> <img src="https://img.shields.io/badge/Eclipse IDE-2C2255?style=for-the-badge&logo=Eclipse&logoColor=white"> 

## 구현 기능
+ 회원가입 / 로그인/ 정보 수정 /회원탈퇴
+ 질문 및 답변 게시판 질문 및 답변 작성
+ 기출문제 게시판 자격증 관련 기출 문제 다운 및 문제 풀기 
+ 서적 게시판 IT관련 추천 서적 조회 및 추천 
+ 채용공고 게시판 채용 정보 조회
+ 공지사항게시판 조회 및 댓글 작성
+ 자유글/ 스터디 모집 게시판 조회 및 게시물과 댓글 작성  

## 핵심 내용
<img width="500" alt="메인페이지" src="https://user-images.githubusercontent.com/71073027/128118115-b3e1f089-17eb-4cb3-bec7-4651573b8736.png" width="50%" height="50%" border= "1px solid gray">

* 사이트의 메인페이지 
  * 가로 배너의 시작하기 버튼을 누르면 회원가입 페이지로 넘어감
  * 채용 글을 올린 회사의 이미지와 추천 서적의 이미지를 최신순으로 네 개씩 보여줌
  * +더보기 버튼을 클릭하여 모든 채용 정보 및 서적의 게시물을 볼 수 있음
<hr>

<img width="430" alt="질문답변2" src="https://user-images.githubusercontent.com/71073027/128137946-7f770c8b-f3ae-4720-bd2f-2d578dd4d29a.png"> <img width="430" alt="질문답변" src="https://user-images.githubusercontent.com/71073027/128137953-b9a35e82-b656-48ca-a05a-41fca68f653a.png">

* 질문/답변 게시판
  * 리스트에서 한 개의 게시물을 클릭 시 상세 조회 가능 
  * 사용자 모두 질문 및 답변을 작성할 수 있음
  * 자신이 올린 질문은 수정 및 삭제가 가능
 
<hr>

<img width="400" alt="기출문제1" src="https://user-images.githubusercontent.com/71073027/128122723-ef1e2a05-fcc9-447d-89c6-efb853fb785e.png">  <img width="400" alt="기출문제4" src="https://user-images.githubusercontent.com/71073027/128122750-909a1f4c-c9da-449d-9a70-93a53da54e55.png"  width="50%" height="50%">

* 기출문제 작성 게시판
  * 관리자만 글 작성/수정/삭제가 가능하며 기출문제와 답안을 첨부할 수 있음
  * 다섯 개의 문제를 예시로 올려 사용자들이 다운 받기 전 문제를 풀어볼 수 있음
  * 문제 하단의 정답을 클릭하면 숨겨 있던 정답이 보이게 되고 다시 클릭하면 정답을 가릴 수 있음
  * 기출문제에 대한 자유로운 의견을 공유할 수 있도록 댓글 기능 구현
<hr>

<img width="280" alt="서적리스트" src="https://user-images.githubusercontent.com/71073027/128125792-675c5b66-5758-49ba-a5d8-c763bdcb7bf8.png">  <img width="300"  height="400" alt="서적작성" src="https://user-images.githubusercontent.com/71073027/128122430-99fb82d8-e88e-4b76-8659-a98ba6e7a6ed.png">    <img width="300" height="400" alt="ㅇㅁㄴㅇㅁㄴㅇ" src="https://user-images.githubusercontent.com/71073027/128123419-a8683fbd-6e2b-445a-ba43-f23945a2f855.png">

* 추천 IT 서적 게시판
  * 관리자만이 글 작성/삭제가 가능하며 서적 이미지와 정보를 올릴 수 있음
  * 이미지 공간을 클릭하여 사진을 첨부할 수 있음

<hr>

<img width="450" alt="채용공고3" src="https://user-images.githubusercontent.com/71073027/128127389-726a72af-1dc8-4445-9ccd-a04dd59ed6ae.png"> <img width="450" height="370" alt="채용" src="https://user-images.githubusercontent.com/71073027/128127529-e4cc2562-f8b6-4b2d-91d0-34f6a612156c.png">

* 채용 공고 게시판
  * 관리자만이 채용공고 글 작성 및 삭제가 가능하며 기업의 이미지와 정보를 올릴 수 있음
  * 기업의 정보를 양식에 맞춰 알맞게 입력해야 글 작성이 가능
  * 리스트에서 한 개의 게시물을 클릭 시 상세 조회 가능 
<hr>

<img width="310"  alt="공지사하아" src="https://user-images.githubusercontent.com/71073027/128147500-383bbc47-5c01-4ed3-a286-2a39ef088565.png"> <img width="310" alt="스터디모집" src="https://user-images.githubusercontent.com/71073027/128147540-7f85422b-9c25-4ac7-96a7-8de908b63d53.png"> <img width="310" alt="자유글" src="https://user-images.githubusercontent.com/71073027/128147604-db78fae0-483c-4813-a027-dd5119373765.png">


<img width="310" alt="공지상세" src="https://user-images.githubusercontent.com/71073027/128151308-31df25bd-3745-408a-aa0b-d37a65c83213.png"> <img width="310" alt="자유글 상세1" src="https://user-images.githubusercontent.com/71073027/128152074-44b72b7a-2b19-42f1-b76c-94d25fb4e555.png"> <img width="310" alt="스터디 상세" src="https://user-images.githubusercontent.com/71073027/128151643-cf177540-2f50-47a0-ac6b-2d7fcdc772f0.png">



* 공지사항/자유글/스터디모집 게시판
  * 공지사항은 관리자만이 글 작성/삭제가 가능하며 사용자는 조회 및 댓글 작성만 가능
  * 자유글은 모든 사용자가 자유롭게 게시물을 올리고 소통할 수 있는 공간으로 글 작성 및 댓글 작성 가능
  * 스터디 모집은 스터디 모집이 목적의 가지고 글을 작성하고 원하는 지역을 선택할 수 있음



## 설계 주안점
+ 사이트의 디자인과 게시물들을 깔끔한 레이아웃으로 한 눈에 알아보기 쉽게 디자인함
+ 질문/답변 게시판에 코드 복사해서 올리는 방식과 파일형식으로 업로드하는 두 가지 기능을 구현해 다양한 방식으로 답변 가능하도록 구현
+ IT관련 자격증의 기출문제를 풀어볼 수 있는 게시판을 제작하여 문제를 다운 받지 않고도 풀어볼 수 있는 기능을 구현
+ 서적페이지에 추천 기능을 구현
+ IT관련 채용정보를 제공


## 팀원별 단위 업무

김 지 연(팀장) : 프로젝트 일정 및 전체 관리, 채용공고 게시판, 메인페이지 <br>
최 원 석         : 질문 & 답변 문법 게시판                            <br>
이 정 호         : IT 추천 서적게시판 , 메인 페이지                   <br> 
류 승 재         : 회원가입, 마이페이지                               <br> 
정 희 정         : 기출문제 게시판                                    <br>
윤 종 훈         : 커뮤니티 (공지사항, 자유글, 스터디 그룹) 게시판      <br>
         
