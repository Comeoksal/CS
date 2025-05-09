## 📖API와 Rest API

### ✅Application Programming Interface

- 서로 다른 소프트웨어, 시스템이 같은 규칙으로 상호작용 하도록 만든 표준

⚠️만약 표준을 정하지 않는다면 발생하는 문제

1. 매번 다른 규칙으로 인한 학습, 개발 속도 저하
2. 다른 플랫폼과 연동이 어려워지고, 클라이언트/서버 변경시 충돌 위험
3. 유지 보수 난이도 증가
4. 재사용성 저하

### ✅Rest API

- Rest 아키텍처 스타일에 맞는 API 형식
- Rest는 자원으로 URI로 표현하고, 자원에 대한 행위는 HTTP 메소드(GET, POST, PUT, PATCH, DELETE)로 표현

### ✅Rest의 6가지 원칙

1. 클라이언트 - 서버 구조의 명확함
2. 무상태 : 각 요청은 독립적, 서버는 클라이언트 상태 저장 X
3. 캐시 가능
4. 계층화
5. 일관된 인터페이스 : URI 구조와 HTTP 메소드 사용의 일관성
6. 코드 온 디맨드(필요한 경우 서버가 클라이언트에 실행 가능한 코드 전송)

### ✅Rest API 구성요소

- 자원 : URI로 표현
- 행위 : HTTP 메소드로 표현
- 표현 : JSON, XML 등의 데이터 형식

## ☑️정리

**Application Programming Interface**의 약자로, 소프트웨어 시스템 간의 상호작용(예: 통신, 데이터 주고받기 등)을 위해 **표준화된 규칙과 방식**을 의미합니다. API에는 다양한 종류가 있는데, 예를 들어 **REST API**, **라이브러리가 제공하는 내부 API** 등이 있습니다. 그중**REST API**는**REST 원칙**을 따르는 API로, 주로 **HTTP 기반의 통신**에서 사용됩니다. REST API는 자원(Resource)을**URI**로 표현하고, 해당 자원에 대한 작업은 **HTTP 메서드**(GET, POST, PUT, PATCH, DELETE 등)를 사용해 수행합니다. 그리고 자원의 표현 형식으로는 주로**JSON**이나**XML**같은 데이터 포맷이 사용됩니다.

![alt text](images/api.png)