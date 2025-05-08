**Use case : 대여소 검색하기**

| Actor Action | System Response |
| --- | --- |
| 1. 대여소 이름을 입력한다. | 2. 조건에 맞는 대여소 리스트가 출력된다. |
</br>

**Use case : 대여소 상세정보 조회하기**

| Actor Action | System Response |
| --- | --- |
| 1. 대여소 리스트에서 특정 대여소를 선택한다. | 2. 선택한 대여소의 이름, 위치, 사용가능 자전거 목록이 출력된다. |

Extensions 
- step 2 이후, 회원은 대여 가능 자전거 중 하나를 선택하여 즉시 대여할 수 있다.
- step 2 이후, 회원은 대기를 원하는 자전거 하나를 선택하여 예약대기를 신청할 수 있다.
</br>

**Use case : 과거 자전거 대여 기록 조회하기**

| Actor Action | System Response |
| --- | --- |
| 1. 과거 대여 기록 조회를 선택한다. | 2. 과거 대여 기록 목록이 날짜순으로 출력된다. |

Extensions
- step 2 이후, 회원은 과거 대여 기록 목록을 대여소별로 출력할 수 있다.
- step 2 이후, 회원은 특정 항목을 삭제할 수 있다.
</br>

**Use case : 회원 가입하기**
| Actor Action | System Response |
| --- | --- |
| 1. 필수 정보(ID, 비밀번호, 전화번호, 결제수단, 선호 자전거 유형(일반형,전기형)를 입력한다. | 2. 회원가입 완료 메세지가 표시된다. |
</br>

**Use case : 회원 탈퇴하기**
| Actor Action | System Response |
| --- | --- |
| 1. 회원 탈퇴를 한다. | 2. 회원 탈퇴 화면을 송출하며, 탈퇴 알림 메세지를 전송한다. |
</br>

**Use case : 로그인하기**
| Actor Action | System Response |
| --- | --- |
| 1. 아이디와 비번을 로그인 칸에 입력한다. | 2. 메인 화면으로 전환되며, 로그인 성공 메세지가 표시된다. |
</br>

**Use case : 로그아웃하기**
| Actor Action | System Response |
| --- | --- |
| 1. 로그아웃을 한다. | 2. 로그인이 해제되며, 로그아웃 메세지가 표시된다. |
</br>