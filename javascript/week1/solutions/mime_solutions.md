## 정답

1. 변수 선언
    -  **`할당`,`참조`의 용어 구분**

2. (2)
    - (1) 함수 선언은 호이스팅되어서 사용 가능
    - (2) 함수 표현식 : 변수에 함수를 할당하는 방식으로 함수를 정의
    - 호이스팅은 되나 변수에 할당되는 값은 스크립트가 해당 줄에 도달했을 때 생성되므로, 변수에 할당되기 이전에는 참조 에러 발생

3. null
    - undefinded는 js엔진이 할당하는 초기값임. 개발자는 사용하지 않는 것이 바람직.

4. null: 변수가 이전에 참조하던 값을 더이상 참조하지 않겠다는 의미,
    - 즉, 참조값이 없다 => 가비지 콜렉터에 의해 제거됨

5. 실행컨텍스트/ 객체(키벨류) 형식