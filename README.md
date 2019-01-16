# TWBH_MEMBER
JSP/Servlet을 이용한 로그인 및 기타 기능

<기능>
- 로그인 /로그아웃
- 회원가입 (ID중복체크)
- 회원탈퇴
- 회원정보 수정
- 유효성 검사

<QUERY 문>
create table member(
name varchar2(10) ,
userid varchar2(10) primary key,
pwd varchar2(10) not null,
email varchar2(20),
phone varchar2(30),
admin number(1) default 1
);
