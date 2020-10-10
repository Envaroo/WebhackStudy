웹 기초 지식
======


### Web Browser
웹 리소스를 해석하여 사용자에게 제공.


### Web Resource
웹에서 사용하는 콘텐츠. URL로 위치를 표시하고, 주로 HTML, CSS, JS, 등이 있다.


### URI(URL)
- URI는 리소스를 식별한다.
- URL는 리소스 위치를 식별한다.

https://github.com/Finlandpotato/WebhackStudy/blob/main/week1.md

> - Scheme : 사용할 프로토콜 (https:)
> - Authority
>   > - Host : 서버 주소 (github.com)
>   > - Port : 웹서버의 포트 정보
> - Path : 웹 서버에서의 경로, /로 구분 (...WebhackStudy/blob/main/week1.md)
> - Query : 추가적인 정보, ?뒤에 붙음
> - Fragment : 서브 리소스 식별정보, #뒤에 붙음


### Encoding, Decoding
암호화, 복호화 과정

> Encoding : 알고리즘 공개, 키 요소 포함되어 있지 않음.
> Encryption : 양방향 암호 알고리즘.

대표적으로 URL Encoding, HTML entity Encoding이 있다.


### HTTP
웹에서의 통신을 정의한 프로토콜. Request와 Response로 이루어진다.

> #### Request
> - Method : 요청하는 동작 (OPTIONS, GET, POST...)
> - Path : 요청하는 리소스 경로 (/index.html)
> - Version : HTTP 버전 표기
> - Header : 추가 정보 (Host, Cookie, User-Agent...)
> - Body : 사용자가 입력한 데이터

> #### Response
> - Version : HTTP 버전 표기
> - Status code : 처리 결과 (200~, 300~, 404)
> - Header : 추가 정보
> - Body : 사용자에게 전달할 데이터


### Cookie
connectionless : 1회 요청, 응답 후 끝
stateless : 쿠키를 통해 상태 저장 가능, 브라우저에 저장됨


### Session
사용자 정보를 서버가 저장하고, 무작위 키 값, Session ID로 인증 상태를 확인


### HTTP, HTTPS
TLS, SSL로 암호화된 HTTP가 HTTPS.


### Domain, Host Name
도메인 주소와 그에 맞는 IP 주소를 DNS에서 사용자에게 전달.

### 웹 서버 어플리케이션
Server에서 사용자의 요청을 처리한다.
자체적으로 처리하거나, 동적 처리를 위해 어플리케이션으로 넘긴다.
DBMS는 서버 내의 데이터베이스 관리를 돕는 어플리케이션이다.
