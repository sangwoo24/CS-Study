# HTTP PUT 과 POST 비교

> 자원에 대한 생성은 POST 가 담당하고, 자원에 대한 수정은 PUT 이 담당하는 것이다.

<br><br>

### PUT 
- PUT 은 리소스의 생성과 수정을 담당하며, 멱등하다(여러 번 수행해도 결과가 같다)
- PUT 은 요청 시 마다, 같은 리소스를 반환한다. 하지만, 리소스 안에 속성은 변경될 수 있다.
<br>

### POST 
- POST 는 리소스의 생성을 담당하며, 멱등하지 않다
- POST 는 요청 시 마다, 새로운 리소스가 생성된다.