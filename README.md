# Unity C#
Unity로 배우는 C#(Programmers)에서 배운 내용 정리

Unity는 Code editor 포함하지 않아서 Visual Studio를 함께 사용한다.

Unity 조작 단축키

Q : 화면이동
W : 물체이동
E : 물체회전
R : 물체 확대축소

카메라 선택 후 E : 카메라 회전

변수
float형 변수는 뒤에 f 붙이기
string형 + 연산 가능

Create->C# Script : Visual Stodio

Object에 Script 추가 해야만 실행됨 

Start영역 : 시작할때 한번 실행
Update영역 : 매 프레임마다 실행
Debug.log : 콘솔창에 로그 남기기

transform.position : 위치 받아오기

물체 이동
transform.position = new Vector3(); ->if문 이용
AddForce : 힘 가하기

변수 선언후에 초기화 할것 -> ex) Rigidbody myRigidbody = Getcomponent < Rigidbody > ();

Input.GetAxis("Horizontal") -> 왼쪽 누르면 -1 / 오른쪽 누르면 +1

Input.GetKeyDown(KeyCode.Space) -> Space 누르면 반응
Input.GetKeyUp(KeyCode.Space) -> Space 떼면 반응
Input.GetKey(KeyCode.Space) -> Space 누르고 있는 동안 반응

GetMouseButton(0) : 마우스 왼쪽 버튼

GameManager : 만들어야 효율적
  
  
