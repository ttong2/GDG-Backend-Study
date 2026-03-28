1주차에는 간단히 웹이 상호작용하는 방식을 배웠다. 웹은 클라이언트가 요청을 보내고 서버가 그에 따른 응답을 반환하는 방식으로 작동한다. 우리가 인터넷에서 흔히 보는 URL에는 Host, Port, Path, Query,Scheme 등의 자리와 양식이 정해져있다. Scheme 중 하나인 HTTP는 무상태성, 비연결성 이라는 특징을 가지고 있다. HTTP의 주요 매서드와 상태코드에 대해 배웠다. API는 클라이언드의 요청과 응답을 정해놓은 규칙이다. REST는 HTTP의 장점을 최대한 활용할 수 있는 아키텍쳐이다. REST는 URL속 고유한 ID를 갖는 자원, 자원을 조작하기 위한 행위, JSON형식으로 서버와 클라이언트가 데이터를 주고받는 형식인 표현 으로 구성되어있다.
<img width="1671" height="1266" alt="image" src="https://github.com/user-attachments/assets/f472b310-ba8c-4879-85a2-edbdeccd8be1" />
상품 기능
  상품 정보 등록
    HTTP Method : POST
    URl : /products
  상품 목록 조회
    HTTP Method : GET
    URl : /products
  개별 상품 정보 상세 조회
    HTTP Method : GET
    URl : /products/{productId}
  상품 정보 수정
    HTTP Method : PATCH
    URl : /products/{productId}
  상품 삭제
    HTTP Method : DELETE
    URl : /products/{productId}
주문 기능
  주문 정보 생성
    HTTP Method : POST
    URl : /orders
  주문 목록 조회
    HTTP Method : GET
    URl : /orders
  개별 주문 정보 상세 조회
    HTTP Method : Get
    URl : /orders/{orderId}
  주문 취소
    HTTP Method : DELETE
    URl : /orders/{orderId}
