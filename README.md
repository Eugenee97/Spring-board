# Spring-board


# https://kuzuro.blogspot.com/2019/08/1.html

# 1. 개발 환경 설정

STS 3 UTF-8, 

# 2. 데이터베이스 준비

MySql or Maria DB 계정 준비 

# 3. 스프링과 데이터베이스 연결

DB 테이블 생성, domian VO Getter Setter 설정, MariaDB(Mysql)DB mybatis mybatis-spring jdbc 설정, bean(데이터베이스 접속), mapper 생성

# 4. 게시물 목록 페이지 구현
Controller, DAO, Service package 생성 및 test로 JDBC connection 확인
(JDBC maria->Mysql DB 변경에 따른 pom, root-context 수정)

# 5. 게시물 작성 페이지 구현
write.jsp 생성 Controller, DAO, Service 추가, redirect로 작성 후 list 페이지로 이동

