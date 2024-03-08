# 📜 3Rill_group-FinalProject
> 사용자들이 사이트에서 쉽게 모임을 생성하고 다양한 사람들과 소통과 교류를 촉진하여 새로운 친구나 활동 파트너를 제공하는 사이트<br>개발 기간 : 2024.01.22 ~ 02.20
> <br>개발 인원 : 3명
<br>

## :books: 기술 스택
### 프론트엔드
  <img src="https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=html5&logoColor=white">  <img src="https://img.shields.io/badge/css3-1572B6?style=for-the-badge&logo=css3&logoColor=white">
  <img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=white"> <img src="https://img.shields.io/badge/react-61DAFB?style=for-the-badge&logo=react&logoColor=black">

### 백엔드  
<img src="https://img.shields.io/badge/java-007396?style=for-the-badge&logo=java&logoColor=white"> <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white"> <img src="https://img.shields.io/badge/oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white">
<img src="https://img.shields.io/badge/node.js-339933?style=for-the-badge&logo=Node.js&logoColor=white"> <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white">
- Spring Data JPA
- Spring Security
- AWS(Light sail)
- Apache Tomcat
- WebSocket

### Skills
- CRUD (C, U)담당
- webSocket 활용(채팅방)
 
## 🔎내가 맡은 역할

### 회원가입 페이지 (Create)

- 리액트를 활용해서 입력된 값들을 Spring Boot 로 넘겨서 오라클 DB서버에 저장

### 회원 확인 및 수정 (Update, LoginContext 활용)

- 회원 확인
  로그인 되어있는 정보를 LoginContext를 활용하여 아이디의 정보들을 불러와서 정보를 확인할 수 있게 구현

- 회원 수정
  로그인 되어있는 정보를 LoginContext를 활용하여 불러온 후 수정 가능한 것들을 수정해서 업데이트 된 정보를 오라클 DB서버에 저장\

### 채팅방 (webSocket 활용)

- 채팅방
  webSocket을 활용하여 실시간으로 채팅을 할 수 있게 구현
  채팅방 형태는 카카오톡을 참고하여 css
  

## :speaker: 프로젝트 주요 기능 

### Main
- 각 카테고리에 맞는 그룹리스트 이동
- 카테고리에 해당되는 그룹 검색
### 계정 관련
- 회원가입, 로그인, 로그아웃
- 아이디 찾기
- 임시 비밀번호 발급(이메일 발송)
- 개인 정보 수정
### 그룹 개설
- 권한에 따른 그룹 개설(유료 or 무료)
### 그룹 참가
- 카테고리에 맞는 그룹 검색
- 그룹 신청(유료모임 신청시 결제페이지 이동)
### 리뷰 
- 리뷰 검색 및 작성
### 일정 관리 
- 캘린더를 통한 일정 CRUD
- 내가 가입한 모임 상세보기
- 신청한 모임, 개설한 모임 탈퇴
### 관리자 페이지
- 모든 회원에 관한 수정과 삭제 가능
- 그룹 삭제 및 사이트 추가

## 💻화면
- 회원가입<br>

<img width="1280" alt="create" src="https://github.com/zkflsk/2_Project/assets/151593682/f4809f88-bcab-4ba2-915b-1ba568c4afe3"><br>

- 회원정보<br>

<img width="1280" alt="userdata" src="https://github.com/zkflsk/2_Project/assets/151593682/7476f267-d313-4dca-a1ab-f6f4cf5b6f8b"><br>

- 회원수정 <br>

<img width="1280" alt="update" src="https://github.com/zkflsk/2_Project/assets/151593682/c0afeeec-a4ac-4398-9d3a-bd4bf570df1b">

- 채팅방 <br>

<img width="1280" alt="chat" src="https://github.com/zkflsk/2_Project/assets/151593682/3899ed59-5f33-4576-9eae-dbad03728966">


## 느낀점
실시간 채팅 기능을 만들었다는 것에 뿌듯함을 느꼈지만 초기에 기획한 목표를 달성하지 못해서 아쉬운 부분이 있었다.
webSocket과 챗봇API를 활용하여 문의사항들의 자동답변 및 관리자와의 1대1 채팅기능까지 만들고 싶었다. 
이전 프로젝트와 차별점을 두기 위해 리액트를 활용하여 더 멋진 결과물을 만들고 싶었지만 리액트의 생소함과
발생하는 문제 해결이 원활하게 진행되지 않아 속도가 더뎌지면서 목표를 달성하지 못한 부분에 대해서는 개인프로젝트를 통해
해결해야겠다는 생각을 했다. 하지만 이번 기회에 리액트의 이해도가 전보다 올랐기 때문에 만족한다.


