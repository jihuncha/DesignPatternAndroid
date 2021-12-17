### DesignPatternAndroid

<hr>

#### 앱 설계 원칙

1. 단일 책임 원칙 (Single Responsibility Principle)
   * 모든 클래스는 하나의 책임만 가지며, 그 책임을 완전히 캡슐화해야 한다.
2. 개방 폐쇄의 원칙 (OCP:  Open Closed Principle)
   * 소프트웨어가 확장에 대해서는 열려있어야하고, 수정에 대해서는 닫혀있어야한다.
3. 리스코프 치환의 원칙 (Liskov Substitution Principle)
   * 상위 타입의 객체를 하위 타입의 객체로 치환해도 상위 타입을 사용하는 프로그램은 정상적으로 동작해야 한다. 즉 특정 메소드가 상위 타입을 인자로 사용한다고 할 때, 그 타입의 하위 타입도 문제 없이 정상적으로 작동을 해야 한다
4. 인터페이스 분리 원칙 (ISP: Interface Segregation Principle)
   * 어떠한 클래스가 자신이 이용하지 않는 메서드에 의존하지 않아야 한다
   * 
5. 의존 역전 원칙 (Dependency Inversion Principle)
   * 의존 역전 원칙은 "고수준 모듈은 저수준 모듈의 구현에 의존해서는 안 된다. 
     저수준 모듈이 고수준 모듈에서 정의한 추상 타입에 의존해야 한다."를 의미한다. 
     이것을 아주 쉽게 말하면, "자신보다 변하기 쉬운 것에 의존하지 마라"라고 이해하면 된다.

<hr>

#### 클린아키텍쳐

![클린아키텍쳐](readmeImg/the-clean-architecture.png "클린아키텍쳐(http://blog.cleancoder.com/uncle-bob/2012/08/13/the-clean-architecture.htmlo)")







