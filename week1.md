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
