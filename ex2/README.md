# Maria 데이터베이스와 Spring Data JPA


## Goal

* Spring Boot 에서 필요한 MariaDB 설정 및 Spring Data JPA 기술 학습

  * MariaDB의 설치와 스키마/계정 생성
    
  * 스프링 부트 프로젝트의 데이터베이스 설정
    
  * Spring Data JPA를 이용한 CRUD와 페이징 처리 기법 배우기
    
  * JpaRepository 인터페이스를 활용하는 다양한 방법 익히기

  
## Spec

* Java 11

* Spring Boot (v2.7.1)

* Spring Data JPA

* IntelliJ IDEA CE

* MariaDB (v2.7.0)


## Spring Initializr - Selected Dependencies

### Developer Tools

* Spring Boot DevTools

* Lombok

### Web

* Spring Web

### SOL

* Spring Data JPA

## IntelliJ IDEA CE -Gradle-Setting

* Gradle 설정

![](/ex2/img/Spring-Boot-2.7.1-MariaDB-JPA-ex2_1.png){: width="500"}


## DB를 위한 Spring Boot Setting

Spring Data JPA 라이브러리 설정

* MariaDB용 JDBC -> "maven mariadb -> MariaDB Java Client >> 2.7.0

![](/ex2/img/Spring-Boot-2.7.1-MariaDB-JPA-ex2_2.png){: width="500"}


* Spring Boot Project 내 MariaDB 설정 -> application.properties 파일 내의 다음의 내용을 추가

![](/ex2/img/Spring-Boot-2.7.1-MariaDB-JPA-ex2_3.png){: width="500"}
