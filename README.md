# CCC

![캐캐캐 메인 페이지 화면](https://user-images.githubusercontent.com/107044598/213978497-d8660a98-f7f7-402e-87a3-33e784f90dd4.png)

<br>
Create Character <br>
Challenge Character <br>
Choose Character
<b>by. Hard Charac</b>
<br><br>
사용자가 직접 만든 캐릭터로 대회에 참가하고 가장 높은 좋아요를 받은 <br>
최고의 캐릭터를 굿즈로 제작하여 창작자와 플랫폼이 동반성장할 수 있는 웹 사이트
<hr>

- 개발 목표 : 캐릭터 대회 및 캐릭터 굿즈 쇼핑몰 개발

- 수행 기간 : 2022년 12월 13일 ~ 2023년 1월 12일 (약 5주)

- 개발 인원 : 6명

- 기여도 : 20%

- 팀 전체 구현 기능 :<br>

  + 로그인, 회원가입
  + 상품 등록, 상품 리스트 조회, 상품 리뷰 작성 및 상품 검색.
  + 캐릭터 월드컵
  + <b>캐릭터 게시판 다중 첨부파일 글 등록, 수정, 삭제.</b>
  + <b>캐릭터 썸네일 게시판 로그인 유저 좋아요 표시. 상세보기 페이지 좋아요 표시.</b>
  + <b>캐릭터 상세보기 페이지에 댓글 및 대댓글 등록, 수정, 삭제.</b>
  + <b>캐릭터 게시판 페이징 처리. 캐릭터 이름, 내용, 창작자 카테고리 글 검색 기능.</b>
  + 내 캐릭터 조회, 등록, 수정, 삭제
  + 관심 상품 등록 및 삭제.
  + 장바구니 추가 및 삭제.
  + 주문 내역 기간별 조회, 배송지 정보 조회.
  + 공지사항 다중 첨부파일 글 등록, 수정, 삭제. 페이지당 게시글 변경 및 페이징 처리.
  + 자유게시판 다중 첨부파일 글 등록, 수정, 삭제. 댓글 등록, 수정, 삭제. 관리자 로그인 시 그룹 삭제.
  + 문의 게시판 글 등록, 수정, 삭제. 내 글보기. 관리자 로그인 시 그룹 삭제 및 답변 등록.
  + 회원 그룹 차단. 회원 목록 EXCEL 문서로 출력.
  + 관리자 등록, 수정, 삭제
  + 배송지 조회, 등록, 수정, 삭제.

<hr>
- 개발 환경 :<br>

  + OS : Window 10
  + Development Tool : STS3, Visual Studio Code
  + DBMS : Oracle DB-SQLDeveloper
  + Server : Apache Tomcat v8.5
  + Framework : Spring Framework 5.3.24, Mybatis 3
  + Management and comprehension Tool : Maven 3.8.6
  + Language : Java 1.8, JavaScript5, HTML5, CSS3
  + Application Tool : JSP 3.2
  + Design Tool : BootStrap 4.3.1
  + Library : jQuery 3.4.1
  + Team Collaboration Tool : Github

- ER Diagram :<br>
![CCC_TOTAL_0123(최종)](https://user-images.githubusercontent.com/107044598/213988734-c01498b0-2e9a-4a81-8e22-1d06b23a7c70.png)
<br>
<hr>
<br>

# 담당 기능 설명 :

- 캐릭터 썸네일 게시판 :

  + 글 조회, 캐릭터 등록. <br>
  + 페이징 처리 및 카테고리별 글 검색. (창작자, 캐릭터 이름, 캐릭터 설명) <br>

<div align="center">
  <img src="https://user-images.githubusercontent.com/107044598/213996842-8dd6b195-4234-4b06-850c-21371e352bb8.png">
</div>

- 캐릭터 상세보기 게시판 :

  + 게시글 제목, 캐릭터 이름, 캐릭터 설명 등록, 다중 첨부파일 업로드 가능. <br>
  + 등록 첨부파일의 개수를 변경하기 용의하도록 구현.

<div align="center">
  <img src="https://user-images.githubusercontent.com/107044598/214002700-63e0b608-0a77-4571-ac2a-88740a4cad87.png">
</div>
