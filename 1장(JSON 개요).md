# JSON 개요

`JSON(JavaScript Object Notation)`은 애플리케이션이 네트워크를 통해 (주로 RESTful API) 형태로 통신할 수 있도록 해주는 데이터 포맷이다. 

모든 현대적인 프로그래밍 언어와 플랫폼에서 JSON 데이터를 생성(직렬화)하고 받아들일(역직렬화)수 있다. JSON은 또한 단순하다.

`객체, 배열, 이름-값` 쌍과 같은 구조로 이루어져 있다. JSON은 REST(Representational State Transfer) 환경에 국한되지 않으며, 다음과 같은 환경에서도 사용할 수 있다.

- Node.js
- MongoDB 등의 NoSQL 데이터베이스
- 카프카 등의 메시징 플랫폼

## REST

> REST는 기본적으로 웹의 기존 기술과 HTTP 프로토콜을 그대로 활용하기 때문에 웹의 장점을 최대한 활용할 수 있는 아키텍처 스타일이다.

HTTP URI(Uniform Resource Identifier)를 통해 자원(Resource)을 명시하고, HTTP Method(POST, GET, PUT, DELETE)를 통해 해당 자원에 대한
CRUD Operation을 적용하는 것을 의미한다.

## JSON은 표준이다

JSON은 사실 표준 규격이다. IETF(Internet Engineering Task Force)와 ECMA 인터내셔널이 모두 JSON을 표준 규격으로 인정하고 있다.

2006년 IETF에 의해 RFC 4627에서 최초로 표준화 되었다.

## JSON의 형태

JSON은 중괄호 {}로 감싼 객체와, 대괄호 []로 감싼 배열로 이루어진다. 또한 키와 값으로 이루어 진다.

```JSON
{ "thisIs" : "My First JSON document" }
```

```JSON
[
  "also",
  "a",
  "valid",
  "JSON",
  "doc"
 ]
 ```
 
 ## JSON을 사용하는 이유
 
 1. JSON에 기반하고 있는 RESTful API의 급격한 증가
 2. JSON의 간단한 데이터 구조
 3. Javascript의 이용 
