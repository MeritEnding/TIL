# 컴퓨터 네트워크 정리

## 3주차
DHCP:
1. 호스트에게 동적으로 주소할당을 하기위해 사용한다.
2. 임시 IP 주소를 할당한다. 제한된 시간동안 제공 가능
3. DHCP 클라이언트-서버의 패러다임 구조이다.
4. Static address Allocation: 고정 IP주소와 물리적 주소를 보관
5. dynamic address Allocation : 동적 IP주소를 보관

DHCP 동작
- DHCP 클라이언트가 DHCP 서버에게 요청 신호를 보내면 DHCP 서버는 static database를 확인한 후
요청된 물리 주소의 항목이 있으면 고정 IP주소를 할당하고
- 요청된 물리적 주소가 없으면 주소 pool에 사용가능한 동적 IP주소를 클라이언트에게 할당 한 후 dynamic database에 저장한다.


 
