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

### 2. 람다와 메서드 참조 (정의 및 사용방법)
https://github.com/RedRabbit-88/Java8-Summary/wiki/1.1.-%EB%9E%8C%EB%8B%A4%EC%99%80-%EB%A9%94%EC%84%9C%EB%93%9C-%EC%B0%B8%EC%A1%B0

### 3. 함수형 인터페이스 정리 (Predicate, Consumer, Function 등)
https://github.com/RedRabbit-88/Java8-Summary/wiki/1.2.-%EB%8B%A4%EC%96%91%ED%95%9C-%ED%95%A8%EC%88%98%ED%98%95-%EC%9D%B8%ED%84%B0%ED%8E%98%EC%9D%B4%EC%8A%A4

### 4. 람다 표현식 메서드 정리 (Comparator, Predicate 조합 등)
https://github.com/RedRabbit-88/Java8-Summary/wiki/1.3.-%EB%9E%8C%EB%8B%A4-%ED%91%9C%ED%98%84%EC%8B%9D-%EC%9C%A0%EC%9A%A9%ED%95%9C-%EB%A9%94%EC%84%9C%EB%93%9C

## 2. 스트림 (Stream)

99. Java8 컬렉션 신규 메서드 정리
* https://github.com/RedRabbit-88/Java8-Summary/wiki/5.1.-%EC%BB%AC%EB%A0%89%EC%85%98-API-%EA%B0%9C%EC%84%A0
