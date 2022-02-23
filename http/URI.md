# URI

![image](https://user-images.githubusercontent.com/77093909/155303667-8c6597ab-1f56-4f9f-8031-94d71fd40989.png)

### URI

단어 뜻
• Uniform: 리소스 식별하는 통일된 방식
• Resource: 자원, URI로 식별할 수 있는 모든 것(제한 없음)
• Identifier: 다른 항목과 구분하는데 필요한 정보
• URL: Uniform Resource Locator
• URN: Uniform Resource Name

### URL, URN

단어 뜻
• URL - Locator: 리소스가 있는 위치를 지정
• URN - Name: 리소스에 이름을 부여
• 위치는 변할 수 있지만, 이름은 변하지 않는다.
• urn:isbn:8960777331 (어떤 책의 isbn URN)
• URN 이름만으로 실제 리소스를 찾을 수 있는 방법이 보편화 되지 않음

URN은 잘 쓰이지 않기 때문에 URI를 URL과 같은 뜻으로 봐도 무방 

### URL
전체 문법

- scheme://[userinfo@]host[:port][/path][?query][#fragment]
- [https://www.google.com:443/search?q=hello&hl=ko](https://www.google.com/search?q=hello&hl=ko)
- 프로토콜(https) - 어떤 방식으로 자원에 접근할 것인가 하는 약속 규칙
- userinfo - URL에 사용자 정보를 포함해서 인증, 거의 사용하지 않음
- 호스트명([www.google.com](http://www.google.com/)) - 도메인명 또는 IP 주소를 직접 사용가능
- 포트 번호(443) - 일반적으로 생략, 생략시 http는 80, https는 443
- 패스(/search) - 리소스 경로(path), 계층적 구조
- 쿼리 파라미터(q=hello&hl=ko) - key=value 형태, ?로 시작, &로 추가 가능
- fragment - html 내부 북마크 등에 사용, 서버에 전송하는 정보 아님
