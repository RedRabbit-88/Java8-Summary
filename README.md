# Java8-Summary
Java8 신규 기능 정의

## 1. 람다식 (Lambda function)

### 1. 람다식의 특징

* 람다 표현식은 익명 함수의 일종
* 람다 표현식으로 코드 간결하게 작성 가능
* 함수형 인터페이스 (Functional Interface) : 1개의 추상 메서드만 있는 인터페이스
* 함수형 인터페이스를 사용할 수 있는 곳만 람다 표현식 사용가능!!
* 람다 표현식 전체가 함수형 인터페이스의 인스턴스
* java.util.function : 유용한 함수형 인터페이스 모음
* 실행 어라운드 패턴(Execute around pattern)을 람다와 활용하면 유연성 Up, 재사용성 Up
* 메서드 참조(Method Reference)를 이용하면 기존의 메서드 구현을 간소화 가능
* Comparator, Predicate, Function 같은 함수형 인터페이스는 다양한 디폴트 메서드 제공

## 2. 스트림 (Stream)

99. Java8 컬렉션 신규 메서드 정리
* https://github.com/RedRabbit-88/Java8-Summary/wiki/5.1.-%EC%BB%AC%EB%A0%89%EC%85%98-API-%EA%B0%9C%EC%84%A0
