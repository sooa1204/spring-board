# SpringBoot + MySQL + Spring Data JPA를 활용한 게시판 기능

## 실습 환경
+ Java: 11
+ JDK: 1.8
+ IDE: IntelliJ IDEA
+ Framwork: SpringBoot (2.x)
+ Database: Mysql

## 기능
+ 글쓰기(/board/save)
+ 글목록(/board/)
+ 글조회(/board/{id})
+ 글수정(/board/update/{id})
  * 상세화면에서 수정 버튼 클릭
  * 서버에서 해당 아이디 게시글의 정보를 가지고 수정 화면 출력
  * 제목, 내용 수정 입력 받아서 서버로 요청해서 수정 처리
+ 글삭제(/board/delete/{id})
+ 페이징처리(/board/paging)
+ 파일(이미지) 첨부
  * 단일 파일 첨부
  * 다중 파일 첨부
+ 댓글 기능
  * 상세화면에서 댓글 작성 기능 추가
## 참고
+ YouTube : [코딩레시피]
