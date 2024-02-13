<div align="left">
  
![header](https://capsule-render.vercel.app/api?type=waving&color=timeGradient&text=Welcome%20to%20SODA's%20GitHub%20👋&animation=twinkling&fontSize=35&fontAlignY=40&fontAlign=70&height=250)
---
# 협업툴 < SODA >
<br>

## 협력SODA조
### 신동한(조장),이민성,장세현,문현식

---

## 목차


1. [기획 의도](#기획-의도)
2. [개발 목표](#개발-목표)
3. [개발 환경](#개발-환경)
4. [역할 분담](#역할-분담)
5. [주요 기능](#주요-기능)
6. [ERD 다이어그램](#erd-다이어그램)

---


# 기획 의도

* 기업에서의 할일, 일정 관리, 우선순위 설정,진척도 등의 기능을 통해 업무를 직관적으로 관리하고 높은 효율성을 제공하는 웹사이트.


* 비대면 근무 환경에서는 온라인 협업툴이 필수적이며 협업툴을 활용함으로써 지리적으로 분산된 팀원들도 효율적으로 협업할 수 있다.


* 복잡한 데이터베이스 작업을 수행하면서 실력 향상 기대.
---
# 개발 목표


* 사용자가 직관적이고 편리하게 협업툴을 이용할 수 있는 인터페이스를 제공하며 프로젝트 관리, 작업 할당, 일정 관리 등 다양한 협업 기능을 제공하여 팀의 업무를 효율적으로 관리하는 것을 목표.
---
# 개발 환경
<div style="display:flex; flex-direction:row;">
    <img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=Java&logoColor=white"> 
    <img src="https://img.shields.io/badge/Spring Boot-6DB33F?style=for-the-badge&logo=spring boot&logoColor=white"> 
    <img src="https://img.shields.io/badge/Gradle-02303A?style=for-the-badge&logo=gradle&logoColor=white">
    <img src="https://img.shields.io/badge/oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white">
    <br>
    <img src="https://img.shields.io/badge/apache tomcat-F8DC75?style=for-the-badge&logo=apachetomcat&logoColor=black">
    <br>
    <img src="https://img.shields.io/badge/html5-E34F26?style=flat-square&logo=html5&logoColor=white"> 
    <img src="https://img.shields.io/badge/css-1572B6?style=flat-square&logo=css3&logoColor=white"> 
    <img src="https://img.shields.io/badge/javascript-F7DF1E?style=flat-square&logo=javascript&logoColor=black"> 
    <img src="https://img.shields.io/badge/bootstrap-7952B3?style=flat-square&logo=bootstrap&logoColor=white">
   <img src="https://img.shields.io/badge/jquery-0769AD?style=flat-square&logo=jquery&logoColor=white">
    <br>
</div>


---

# 역할 분담
<table>
<thead>
<tr>
<th>신동한</th>
<th>이민성</th>
</tr>
</thead>
<tbody>
<tr>
<td>- 소모임 게시글 목록 조회 / 상세 조회<br>- 게시글 검색, 게시글 작성 / 수정 / 삭제 (소모임장 및 일반 사용자)<br>- 게시글 첨부파일<br>- 댓글 (등록 / 수정 / 삭제)<br>- 소모임 생성<br>- 소모임 정보 목록 조회 / 상세 조회 <br>- 클래스 다이어그램<br>- 프로젝트 SQL DB 취합</td>
<td>- 프로젝트(피드) 페이지 / 프로젝트 색상 설정, 4종류의 피드 생성,수정,삭제<br>-피드 댓글,좋아요,북마크 기능<br>- 검색바 / 프로젝트,글,파일 검색 기능</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th>장세현</th>
<th>문현식</th>
</tr>
</thead>
<tbody>
<tr>
<td>- 사이드바 제작 / 프로젝트 폴더 생성,최근 업데이트 프로젝트 출력 <br>- 대시보드 페이지 및 위젯 제작 / 참여중인 프로젝트,일정,회사 인원,메모장 출력 기능 <br>-실시간 웹소켓 채팅 기능</td>
<td>- 회원가입 및 로그인 페이지 / JPA 및 카카오 API<br>- 대시보드 환경설정 기능<br>- 프로젝트 생성</td>
</tr>
</tbody>
</table>

---
# 주요 기능
### 규칙
* ㅁ눙ㅁㄴㅇㅇㅁㄴㅁㄴㅁㄴㅁㄴㅁㄴㅁㄴㅁㄴㅁㄴㅁㄴㅁㄴ
* ㅁㄴㅇㅁㄴㅇㅁㅁㅁㅁㅁㅁㅁㅁ
* ㅁㄴㅇㅇㅇㅇㅇㅇㅇㅇㅇㅇㅇㅇㅇㅇ
* ㄴㅁㅇㅇㅇㅇㅇㅇㅇㅇㅇㅇㅇㅇㅇㅇ
* ㄴㅇㅁㅁㅁㅁㅁㅁㅁㅁㅁㅁㅁㅁㅁㅁㅁㅁㅁㅁ
* ㄴㅁㅇㅇㅇㅇㅇㅇㅇㅇㅇㅇㅇㅇㅇㅇㅇㅇㅇㅇ
* ㄴㅁㅇㅇㅇㅇㅇㅇㅇㅇㅇㅇㅇㅇㅇㅇㅇㅇㅇㅇㅇ
* ㄴㅁㅇㅇㅇㅇㅇㅇㅇㅇㅇㅇㅇㅇㅇㅇㅇㅇㅇㅇㅇㅇㅇ
* ㄴㅁㅇㅇㅇㅇㅇㅇㅇㅇㅇㅇㅇㅇㅇㅇㅇㅇㅇㅇㅇ
* ㅂㅈㄱㄱㄱㄱㄱㄱㄱㄱㄱㄱㄱㄱㄱㄱㄱㄱㄱㄱㄱ
* ㅂㅈㄱㄱㄱㄱㄱㄱㄱㄱㄱㄱㄱㄱ
---
# ERD 다이어그램
![KakaoTalk_20240213_175702541](https://github.com/DHLaptop/ToolSoda/assets/159864643/29d96d9c-4a1c-4b16-b390-bafec54b4052)
---
## 📞 Contact
<div style="display:flex; flex-direction:row;">
    <a href="mailto:luckpigsdh@gmail.com">
        <img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=Gmail&logoColor=white"> 
    </a>
</div><br>
    

</div>
