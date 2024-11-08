### 업무 규칙
업무 규칙은 ㄱ사업적으로 수익을 얻거나 비용을 줄일 수있는 규칙 또는 절차이다.

#### 엔티티
엔티티는 컴퓨터 시스템 내부의 객체
일련의 조그만 핵심 업무 규칙을 구체화한다.
핵심 업무 데이터와 핵심 업무 규칙을 하나로 묶어서 별도의 소프트웨어 모듈로 만들어야 한다

#### 유스케이스
유스케이스는 자동화된 시스템이 사용되는 방법을 설명
엔티티 내부의 핵심 업무 규칙을 어떻게, 그리고 언제 호출할지를 명시하는 규칙을 담음
사용자 인터페이스를 기술하지 않음
유스케이스는 시스템이 사용자에게 어떻게 보이는지를 설명하지 않음

엔티티는 자신을 제어하는 유스케이스에 대해 아무것도 알지 못한다.
엔티티는 고수준, 유스케이스는 저수준
유스케이스는 단일 애플리케이션에 특화 -> 시스템 출력과 입력에 가깝게 위치
엔티티는 일반화

유스케이스는 엔티티에 의존하지만 엔티티는 유스케이스에 의존하지 않음

업무규칙은 시스템에서 가장 독립적이며 가장 많이 재사용할 수 있는 코드여야 한다.