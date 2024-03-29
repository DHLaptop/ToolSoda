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
    <img src="https://img.shields.io/badge/Eclipse IDE-2C2255?style=for-the-badge&logo=eclipse&logoColor=white">
    <br>
    <img src="https://img.shields.io/badge/tomcat-F8DC75?style=for-the-badge&logo=apachetomcat&logoColor=black">
    <br>
    <img src="https://img.shields.io/badge/html5-E34F26?style=flat-square&logo=html5&logoColor=white"> 
    <img src="https://img.shields.io/badge/css-1572B6?style=flat-square&logo=css3&logoColor=white"> 
    <img src="https://img.shields.io/badge/javascript-F7DF1E?style=flat-square&logo=javascript&logoColor=black"> 
    <img src="https://img.shields.io/badge/bootstrap-7952B3?style=flat-square&logo=bootstrap&logoColor=white">
   <img src="https://img.shields.io/badge/jquery-0769AD?style=flat-square&logo=jquery&logoColor=white">
   <img alt="Static Badge" src="https://img.shields.io/badge/Servlet%26JSP-blue">
</div>
<br>

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=DHLaptop)](https://github.com/anuraghazra/github-readme-stats)

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
<td>- 전체 업무 페이지 / 프로젝트의 피드 업무,하위업무 상세 정보 표출 및 수정 기능<br>- 캘린더 페이지 / 프로젝트 및 피드 일정 표출 및 개인 일정 등록 기능<br>- 게시판 / 게시글 및 댓글 작성,수정,삭제 기능<br>- 내 프로젝트 / 참여중인 프로젝트 표출, 프로젝트 색상 및 폴더 설정 기능
<br>- 파일함,북마크,내 게시물 페이지 / 각 해당하는 피드 및 댓글 표출 및 클릭시 해당 링크로 이동 기능<br>- 관리자 페이지(기업 정보 및 모든 프로젝트,직원,IP 관리 및 로그 기능)</td>
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
* 대시보드


  -  로그인 후 나오는 메인 페이지, 좌측바와 위젯을 통해 프로젝트의 상태 및 일정을 확인할 수 있으며 개인 상태메세지 및 배경이미지를 설정할 수 있다.
    ![1](https://github.com/DHLaptop/ToolSoda/assets/159864643/b110eccf-a917-43ab-a5a9-4c94bec17adb)


* 피드

  - 사용자가 참가한 프로젝트의 모든 피드를 출력하며 프로젝트 관리자라면  대표 색상 변경, 삭제 등을 수행할 수 있다. 일반 사용자는 피드 작성 및 다른 사용자를 프로젝트에 초대할 수 있으며 각 피드마다 댓글과 북마크를 할 수 있다.
   ![2](https://github.com/DHLaptop/ToolSoda/assets/159864643/819e7dfd-7e7c-49c9-9a13-9f47a1a6b4fd)


* 모아보기

  - 게시판 : 동일한 직장에서 근무하는 직원들이 이용할 수 있는 자유게시판.작성자에게만 수정 및 삭제 버튼이 표시된다.
  - 전체 업무 : 자신이 속한 프로젝트 중 업무피드가 존재 하는 프로젝트,업무,하위업무 표출된다. 각 컬럼 클릭시 선택 리스트가 출력되며 리스트 아이템 선택시 해당하는 업무 또는 하위업무의 정보가 업데이트 된다.
  - 캘린더 : 일정 피드의 기간은 파란색 Bar로 표시되고 수정이 불가하며, 날짜 클릭시 개인 일정을 추가할 수 있는 팝업이 표출된다. 개인 일정은 클릭시 삭제가 가능하다.
  ![6](https://github.com/DHLaptop/ToolSoda/assets/159864643/eaa15eb0-4061-4ee1-adaf-c289c81a40e1)


* 관리자 페이지

  - 1,2 : 모든 직원과 프로젝트를 관리할 수 있으며 관리자 또는 프로젝트 담당자를 변경할 수 있다.(컬럼 클릭시 수정 팝업이 표출된다.)
  - 3 : 관리자 페이지에 존재하는 모든 기능버튼에 고유 기능뿐만 아니라 기록을 남기는 기능을 추가함으로써 수행한 모든 행위에 대한 로그를 남긴다.
  ![7](https://github.com/DHLaptop/ToolSoda/assets/159864643/825afd95-39e3-4e60-bbf9-185324049bd0)

 
* 회원가입,로그인

  - 이메일을 입력 후 중복 확인 버튼을 클릭 시 DB에 이메일의 중복 여부를 확인 후 메세지를 표출한다. 회원가입 성공 후 회사 생성 페이지로 이동된다.
  - 소셜 API 로그인을 통해 로그인 계정이 존재하지 않을 경우 회원가입창으로 이동되며 존재할 경우 대시보드 페이지로 이동된다.
  ![5](https://github.com/DHLaptop/ToolSoda/assets/159864643/78a3969b-1832-49e8-be15-91e03d8418e6)

---
# ERD 다이어그램
![KakaoTalk_20240213_175702541](https://github.com/DHLaptop/ToolSoda/assets/159864643/29d96d9c-4a1c-4b16-b390-bafec54b4052)
---

</div>
