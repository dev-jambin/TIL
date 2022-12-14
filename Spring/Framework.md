* [목차](#목차)
* [Framework](#framework)
    + [예시](#예시)
    + [장점](#장점)
    + [단점](#단점)

# Framework

> 기본적인 프로그래밍을 하기 위한 어떠한 틀이나 구조를 제공하는 것
> 

Frame이란 어떤 대상의 큰 틀이나 외형적인 구조를 의미한다. 하나의 애플리케이션을 건물이라고 한다면, Frame은 건물의 구조라고 이해하면 된다. 

## 예시

Java에서 framework의 의미를 찾아볼 수 있는데, 그것은 바로 Collections Framework이다.

Java에서 자주 사용되는 Map이나 Set, List 등의 Collection들은 데이터들을 저장하기 위해 널리 알려져 있는 자료구조를 바탕으로 비슷한 유형의 데이터들을 가공 및 처리하기 쉽도록 표준화 된 방법을 제공하는 클래스의 집합이다.

왜 Collection에 Framework라는 용어를 붙였을까?

Java 클래스의 유형 중에서 기본적인 뼈대로만 구성되어 있는 것은 바로 추상 메서드만 정의되어 있는 인터페이스(interface)이다. 그리고 Java에서의 Collection은 바로 Map, Set, List 같은 인터페이스와 그 인터페이스들을 구현한 구현체들의 집합인 것이다.

결론적으로 프로그래밍에서의 Framework는 **기본적으로 프로그래밍을 하기 위한 어떠한 틀이나 구조를 제공**한다라는 것을 알 수 있다.

## 장점

- 효율적으로 코드를 작성할 수 있다.
    - 다양한 기능들을 Framework가 라이브러리 형태로 제공함으로써 개발자가 애플리케이션의 핵심 로직을 개발하는 것에 집중할 수 있도록 해준다.
- 정해진 규약이 있어 애플리케이션을 효율적으로 관리할 수 있다.
    - 사용하는 Framework의 규약에 맞게 코드를 작성하기 때문에, 유지보수가 필요한 경우 더 빠르고 쉽게 문제점을 파악해 수정할 수 있다.
    - 동시에 내가 작업했던 코드를 다른 사람이 수정할 경우에도 이미 Framework 규약에 맞게 작성된 코드이기 때문에, 빠르게 코드를 파악하고 수정하기 용이하다.
    - 비슷한 기능을 개발할 때 코드의 재사용이 용이하고 기능의 확장 또한 쉽게 확장이 가능하다.

## 단점

- 내가 사용하고자 하는 Framework에 대한 학습이 필요하다.
    - Framework에서 정하는 규약들을 학습할 시간이 필요하다.
    - Spring의 경우 Java언어에 대한 이해도 필요하지만 추가로 Spring이라는 Framework에 대한 학습이 필요한 이유이다.
- 자유롭고 유연한 개발이 어렵다.
    - 사용하고 있는 Framework의 규약에서 벗어나기 어렵다.
    - 이미 만들어진 애플리케이션에서 Framework를 변경하거나, 유연한 갭라을 위해 Framework를 사용하지 않게 변경할 경우 정말 많은 시간과 노력이 들어간다.