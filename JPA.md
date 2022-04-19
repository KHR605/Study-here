# JPA(Java Persistence API)
- JPA란 자바의 ORM을 위한 표준 기술로 Hibernate, Spring JPA, EcliplseLink 등 과 같은 구현체가 있고 이것의 표준 인터페이스가 JPA 이다.

> *ORM(Object-Relational Mapping)*
> - 자바의 객체와 관계형 DB를 맵핑하는 것으로 DB의 특정 테이블이 자바의 객체로 맵핑되어 SQL문을 일일이 작성하지 않고 객체로 구현할 수 있도록 하는 프레임워크

### JPA장점
- SQL 위주의 Mybatis 프로젝트와 비교하여 쿼리를 하나하나 작성할 필요도 없어 <strong>코드량이 엄청나게 줄어든다</strong>. 
- 객체 위주로 코드가 작성되다 보니 <strong>가독성</strong>도 좋고, 여러 가지 요구사항으로 기능 수정이 발생해도 DB부터 더 <strong>간편하게 수정</strong> 가능. 
- Oracle, MySQL 등 DB 벤더에 따라 조금씩 다른 SQL 문법 때문에 애플리케이션이 DB에 종속될 수밖에 없었는데, JPA는 직접 쿼리를 작성하는 것이 아니라서 DB 벤더에 <strong>독립적으로 개발</strong> 가능.

*STS* <br>
*Spring boot*
*Annotation*

JPA 예제 참고 : https://kim-oriental.tistory.com/20
