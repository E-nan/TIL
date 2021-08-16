# POSTMAN
API 개발을 보다 빠르고 쉽게 구현 할 수 있도록 도와주며, 개발된 API를 테스트하여 문서화 또는 공유 할 수 있도록 도와 주는 플랫폼이다.
주로 사용하는 기능은 API 테스트 및 리퀘스트 응답을 확인한다.

URL을 통해서 테스트를 하기에는 한계가 있다. 실제로 개발할 경우, 요청과 응답을 하기 위해서 클라이언트에서 이벤트를 만들고 실행하고 하는 과정을 거쳐야 하기 때문에 요청하기까지의 과정, 그리고 응답받기까지의 과정이 너무 길어지게 된다.

하지만 POSTMAN을 사용하면 해당 작업을 할 수 있도록 인터페이스가 구축된 툴이기 때문에 보다 쉽게 테스트를 진행할 수 있다.


## 사용법

### 다운로드 및 설치

https://www.postman.com/

POSTMAN사이트에 접속해서 회원가입 후, 다운로드하여 어플리케이션으로 실행할 수 있다.
`(회원가입 없이도 단기적으로 사용 가능하다.)`

다운로드 받으면 이러한 UI가 나타나는데 이 화면에서 직접 개발한 API 테스트를 진행할 수 있다.

![image](https://user-images.githubusercontent.com/51812215/129571668-3734706d-5d33-49dd-bb02-fc7e7886c537.png)

### 사용법

### GET

GET API를 테스트하기 위해 간단하게 Test를 반환하는 API를 만들었다.

![image](https://user-images.githubusercontent.com/51812215/129569211-32d97c02-144e-4021-a6cd-ede86b086270.png)

API에 접속할 수 있는 URL을 입력하고 GET, POST 방식을 선택한 다음, SEND를 누르면 화면처럼 응답 결과가 보여진다.

![image](https://user-images.githubusercontent.com/51812215/129571633-78f89a4c-5786-4dfd-9066-e6a4abc20c06.png)

또는, GET 방식의 파라미터 테스트를 하고 싶다면 마찬가지로 먼저 API를 만든다.

![image](https://user-images.githubusercontent.com/51812215/129570134-8d3aae93-630d-47a1-9d8c-51a4de574f8a.png)

이번엔 API에 맞게 파라미터를 설정해주고, 마찬가지로 SEND를 누르면 응답 결과가 보여진다

![image](https://user-images.githubusercontent.com/51812215/129571525-be4500db-2015-4d0e-9871-6a1d19b79ad2.png)
