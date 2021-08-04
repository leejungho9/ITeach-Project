# ITEACH

## 개요 : 개발자 커뮤니티 사이트

+ 개발자가 되기 위해 공부하는 사람들이 모여 소통 가능
+ IT분야의 다양한 채용정보 및 도움되는 정보들을 한 곳에서 많은 사람들과 공유
+ 관련 자격증 기출문제를 풀 수 있으며 모르는 부분은 질문/답변게시판에서 도움을 받을 수 있음

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
<img src ="https://user-images.githubusercontent.com/73329610/127971641-2dd3fb6b-cca2-45a2-a027-9458d160770b.png" width="50%" height="50%">

* 사이트의 메인페이지 
  * 가로 배너의 시작하기 버튼을 누르면 회원가입 페이지로 넘어감
  * 채용 글을 올린 회사의 이미지와 추천 서적의 이미지를 최신순으로 보여줌
  * +더보기 버튼을 클릭하면 각 게시물 리스트로 넘어가며 모든 채용 정보 및 서적의 게시물을 볼 수 잇음
  

<img src ="https://user-images.githubusercontent.com/73329610/127974742-1663bc4d-71cd-425e-8763-941a8cf35dda.png" width="50%" height="50%">

  * 사용자가 해당 페이지에서 레시피를 추가할 수 있는 기능
  * 레시피를 추가하면 메인페이지에 레시피가 노출
  * 자신이 작성한 레시피는 마이 페이지에서 확인 가능 


<img src ="https://user-images.githubusercontent.com/73329610/127976877-28bc7642-c581-4fc9-8821-58858b6d2363.png" width="50%" height="50%"><img src ="https://user-images.githubusercontent.com/73329610/127976609-e0288243-c94a-455a-9c74-b7dc77d02d83.png" width="50%" height="50%">

* 사용자가 설문조사를 작성하면 DB에 저장되고 , 설문조사를 구글 통계 API를 이용하여 집계처리
* 설문조사를 통해  사용자들의 연령이나 성별과 연관시켜서 연령이나 성별에 따른 식습관이나 트렌드 파악
  

## 설계 주안점
+ 질문/답변 게시판에서 코드를 복사할여 올리는 방식과 파일형식으로 업로드하는 두 가지 기능을 구현해 다양한 방식으로 답변 가능하도록 구현
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
         
