## OOP Solid
OOP 설계에 대해서 알아봅시다.

## SRP 단일 책임의 원칙 - Single Responsibility Principle 
1.   
## OCP 개방-폐쇄 원칙 - Open Closed Principle
1. 확장에 열려 있고 수정에 닫혀 있다.
2. 클래스간 통신을 위한 인터페이스가 확정되면 수정하지 않는다.

## LSP 리스코프 교체 원칙 - Liskov Substitution Principle

## ISP 인터페이스 격리 원칙 - Interface Segregation Principle

## DIP 의존 관계 역전 원칙 - Dependency Inversion Principle



## OOP Solid
OOP 설계에 대해서 알아봅시다.

## SRP 단일 책임의 원칙 - Single Responsibility Principle 
1. 코드 변경의 영향이 미치는 범위가 최소화 된다
 - Class가 변경되도 다른 Class에 영향을 미치지 않는다
2. 코드 응집성이 향상된다
 - 데이터 연관성이 높은 것끼리 인터페이싱이 자주 일어난다
3. 단위테스트가 용이하다
 - 각 Class 별 테스트가 가능하다
  
## OCP 개방-폐쇄 원칙 - Open Closed Principle
1. Class 간 통신을 위한 인터페이스가 정해지면 수정하지 않는다
  - 대신 다른 기능이 필요할 경우 확장을 통해 기능을 추가한다 - 잘 설계된 인터페이스는 구현 후 클래스 수정을 최소화 한다
2. 표준화된 인터페이스의 경우 변경 비용이 크다
  - 해당 인터페이스를 사용한 모든 클래스가 변경되어야 한다
3. 충분히 안정화 된 이후에 적용한다
  - 모든 케이스에 대한 테스트가 완료된 후 표준으로 사용한다

## LSP 리스코프 교체 원칙 - Liskov Substitution Principle
1. 서브타입(파생클래스)는 언제나 자신의 기반타입(상위클래스)로 교 체할 수 있어야 한다.
2. 다형성 적용
  상위클래스 a = new 하위클래스()

## ISP 인터페이스 격리 원칙 - Interface Segregation Principle
  - 클라이언트는 자신이 쓰지 않는 인터페이스에 의존하지 않는다
  - 특화된 여러개의 인터페이스가 범용 인터페이스 한개 보다 났다
  
## DIP 의존 관계 역전 원칙 - Dependency Inversion Principle
1. 상위모듈, 하위모듈 모두 추상화된것에 의존해야 한다 = 추상인터페이스 상속
2. 추상화된것은 구체적인것에 의존하면 안된다
3. 자주변경되는 구체(Concrete) 클래스에 의존하면 안된다
