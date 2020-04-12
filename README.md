# Java8-Summary
Java8 신규 기능 정의

## 1. 람다식 (Lambda Expression)

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

### 1. 스트림의 장점

* SQL과 같은 선언형으로 Collection 데이터를 처리 가능.
* filter, sorted, map, collect 같은 여러 빌딩 블록 연산을 이용해서 파이프라인 구축 가능.
* 멀티 스레드 코드를 구현하지 않아도 투명하게 병렬 처리 가능. (parallelStream())

### 2. 스트림의 특징

* 선언형 : 간결하고 가독성이 좋아짐
* 조립 가능 : 파이프라인을 통해 유연성이 좋아짐
* 병렬화 : 병렬 처리를 통해 성능이 좋아짐

### 3. 스트림의 특성
https://github.com/RedRabbit-88/Java8-Summary/wiki/2.2.-%EC%8A%A4%ED%8A%B8%EB%A6%BC(Stream)%EC%9D%B4%EB%9E%80-%EB%AC%B4%EC%97%87%EC%9D%B8%EA%B0%80%3F

### 4. 스트림 활용 (filter, map, flatMap, sort, reducing 등)
https://github.com/RedRabbit-88/Java8-Summary/wiki/2.3.-%EC%8A%A4%ED%8A%B8%EB%A6%BC-%ED%99%9C%EC%9A%A9

### 5. 스트림 중간/최종연산
https://github.com/RedRabbit-88/Java8-Summary/wiki/2.4.-%EC%8A%A4%ED%8A%B8%EB%A6%BC-%EC%A4%91%EA%B0%84%EC%97%B0%EC%82%B0,-%EC%B5%9C%EC%A2%85%EC%97%B0%EC%82%B0-%EC%A0%95%EB%A6%AC

### 6. 기본형 특화 스트림 (IntStream, DoubleStream, LongStream)
https://github.com/RedRabbit-88/Java8-Summary/wiki/2.5.-%EA%B8%B0%EB%B3%B8%ED%98%95-%ED%8A%B9%ED%99%94-%EC%8A%A4%ED%8A%B8%EB%A6%BC


99. Java8 컬렉션 신규 메서드 정리
* https://github.com/RedRabbit-88/Java8-Summary/wiki/5.1.-%EC%BB%AC%EB%A0%89%EC%85%98-API-%EA%B0%9C%EC%84%A0
