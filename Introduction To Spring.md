
# 개인적으로 추천하는 입문 학습 흐름

## 자바 입문부터 스프링 입문까지

<br/>

### **자바 기본서 항목 1독**

- [https://lob-dev.tistory.com/entry/Java의-Reflection-API](https://lob-dev.tistory.com/entry/Java%EC%9D%98-Reflection-API)

<br/>

### **객체 지향의 사실과 오해**

<br/>

### **SQL 첫걸음 혹은 기타 SQL 책**

- CRUD, Local or Global transaction, DDL 기본 , Index
- 대부분의 서비스는 CRUD를 무조건적으로 포함한다고 봐야됩니다. 이는 게시판 같은 것에 특정 되는 개념이 아니라 모든 데이터를 다룸에 있어서 통용되는 것입니다.
- 트랜잭션, 인덱스 개념은 개발자에겐 필수 개념이라고 생각합니다.

<br/>

### **Sevlet API (JSP는 제외)**

- Server - Client Model, HTTP, SSR and CSR, JSON, RESTful API*
- Servlet은 자바 기반의 "표준" Protocol API이며, HTTP와 기타 Protocol을 처리하는 뼈대가 됩니다. 스프링이나 Vaddin, Struct 같은 프레임워크도 내부적으로는 Servlet을 통해 동작하는 기능들이 있습니다. 자바 기반의 웹 근본 개념 이해를 위해 우선하여 학습하는 것을 추천합니다.
- [https://lob-dev.tistory.com/entry/CGI-Servlet-Servlet-Container](https://lob-dev.tistory.com/entry/CGI-Servlet-Servlet-Container)
- [https://lob-dev.tistory.com/entry/01-RESTful-개념과-사전-지식](https://lob-dev.tistory.com/entry/01-RESTful-%EA%B0%9C%EB%85%90%EA%B3%BC-%EC%82%AC%EC%A0%84-%EC%A7%80%EC%8B%9D)

<br/>

### **JDBC API**

- JDBC는 자바 기반의 "표준" DB 접근 API이며, Mybatis, JPA 와 같은 SQL Mapper, ORM 프레임워크들도 내부적으로는 JDBC의 Connection과 Statement를 사용하기 때문에 이를 통한 애플리케이션 시점에서의 로컬, 글로벌 트랜잭션 방식을 이해하는 것이 개인적으로 중요하다고 생각합니다.
- [https://lob-dev.tistory.com/entry/Java-Database-Connectivity-알아보기](https://lob-dev.tistory.com/entry/Java-Database-Connectivity-%EC%95%8C%EC%95%84%EB%B3%B4%EA%B8%B0)

<br/>

### **스프링 입문을 위한 자바 객체 지향의 원리와 이해**

- Spring을 학습하기 이전에 JVM의 메모리, 객체 지향 개념과 구현 방식을 다시 복습할 수 있고, Spring에 적용된 디자인 패턴을 선행 학습할 수 있는 좋은 책입니다.
- [https://lob-dev.tistory.com/entry/책임을-중시하는-객체-지향-디자인의-핵심-개념-GRASP](https://lob-dev.tistory.com/entry/%EC%B1%85%EC%9E%84%EC%9D%84-%EC%A4%91%EC%8B%9C%ED%95%98%EB%8A%94-%EA%B0%9D%EC%B2%B4-%EC%A7%80%ED%96%A5-%EB%94%94%EC%9E%90%EC%9D%B8%EC%9D%98-%ED%95%B5%EC%8B%AC-%EA%B0%9C%EB%85%90-GRASP)

### **코드로 배우는 스프링 부트 웹 프로젝트**

- 취업이나 상황에 따라 시간이 부족하다면 앞선 책을 건너뛰고 해당 책으로 학습을 하는 것도 추천하기도 합니다. 입문 서적으로는 좋은 책인 것 같습니다.

<br/>

### **인프런 스프링 입문 - 코드로 배우는 스프링 부트, 웹 MVC, DB 접근 기술**

- 기본적인 Spring Boot 애플리케이션을 경험해볼 수 있는 좋은 입문 강의입니다. MVC 요청 흐름과 템플릿 엔진 등의 개념을 경험해볼 수 있습니다.

<br/>

### **처음 배우는 스프링 부트 2 (Optional)**

- Spring Boot 모듈의 의존성 관리, 자동 설정. 테스트 환경 등을 설명하며 게시판 예제를 통해 Oauth2, Security, RESTful, Batch 등의 기본적인 개념과 예제를 다룹니다.

<br/>

### **개인 프로젝트 진행**

- 앞에서 경험했던 기술들을 본인만의 요구 사항에 녹이고 적용하여 프로젝트를 진행하시면 좋을 것 같습니다.
- 모든 방식에는 장단점이 존재하기 때문에. 이를 비교하고 설명할 수 있어야한다고 생각합니다. (물론 저는 못합니다..)
    - ex) 객체 간의 변환 시에 MapStruct를 사용하셨는데 메서드를 통해 작성하는 방법이나 ModelMapper를 사용하는 방식도 있지 않나요? 왜 MapStruct를 사용하셨는지 설명해주실 수 있으실까요? 등..

<br/>

**이후는 위에 따로 서술된 항목이나 주변의 추천을 통해 추가 학습 진행**

<br/>

---

<br/>

# 프로젝트

## 참고

[공공데이터 포털](https://www.data.go.kr/)

[public apis - 영어](https://github.com/public-apis/public-apis)

[API란? 개념 정리와 포트폴리오에 유용한 대박 사이트 공유 🙌 Youtube](https://www.youtube.com/watch?v=ogT267HvNuQ&t=337s&ab_channel=%EB%93%9C%EB%A6%BC%EC%BD%94%EB%94%A9by%EC%97%98%EB%A6%AC)

---