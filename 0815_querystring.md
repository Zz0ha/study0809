# 2022.08.15 TIL
## query String

 사용자가 입력 데이터를 전달하는 방법중의 하나로, url 주소에 미리 협의된 데이터를 파라미터를 통해 넘기는 것을 말한다.

query parameters( 물음표 뒤에 = 로 연결된 key value pair 부분)을 url 뒤에 덧붙여서 추가적인 정보를 서버 측에 전달하는 것이다. 클라이언트가 어떤 특정 리소스에 접근하고 싶어하는지 정보를 담는다.

### 형식

- 정해진 엔드포인트 주소 이후에 ?를 쓰는것으로 쿼리스트링이 시작함을 알린다
- parameter=value로 필요한 파라미터의 값을 적는다
- 파라미터가 여러개일 경우 &를 붙여 여러개의 파라미터를 넘길 수 있다.`엔드포인트주소/엔드포인트주소?파라미터=값&파라미터=값`
- = 로 key 와 value 가 구분된다.
