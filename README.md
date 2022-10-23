# form
김영한 - 스프링 MVC 2편 - 백엔드 웹 개발 핵심 기술 2-2 (타임리프 스프링 통합)

## 타임리프 2가지 메뉴얼.
- 기본 메뉴얼: https://www.thymeleaf.org/doc/tutorials/3.0/usingthymeleaf.html
- 스프링 통합 메뉴얼: https://www.thymeleaf.org/doc/tutorials/3.0/thymeleafspring.html

## 스프링 통합으로 추가되는 기능들

- 스프링의 SpringEL 문법 통합 
- ${@myBean.doSomething()} 처럼 스프링 빈 호출 지원

- 편리한 폼 관리를 위한 추가 속성
  - th:object (기능 강화, 폼 커맨드 객체 선택) 
  - th:field , th:errors , th:errorclass

- 폼 컴포넌트 기능
  - checkbox, radio button, List 등을 편리하게 사용할 수 있는 기능 지원
  
- 스프링의 메시지, 국제화 기능의 편리한 통합 스프링의 검증, 오류 처리 통합
- 스프링의 변환 서비스 통합(ConversionService)
