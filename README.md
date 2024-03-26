# 저녁 같이 드실래요?

### 자바 미니 프로젝트 - POS

<p align="center">
<img width="33%" alt="image" src="https://github.com/dustjq1004/ZKDPos/assets/73459956/ea5c2183-bc56-4a86-9c36-be489038f97a">
<img width="30.5%" alt="image" src="https://github.com/dustjq1004/ZKDPos/assets/73459956/445baeba-8d53-4dc1-8366-bf6ffd8dacdb">
<img width="33.5%" alt="image" src="https://github.com/dustjq1004/ZKDPos/assets/73459956/c392ac4d-a938-421b-9b36-157674b92384">
</p>



### 저녁 같이 드실래요?
20,30대 젊은 세대들이 많이 찾는 헌팅 술집에 알맞게 재미와 편리함을 넣은 테이블링 주문 시스템입니다.

### 1. 프로젝트 설명

자바에서 지원하는 JDK만 사용하여 진행한 프로젝트입니다. 자바 Socket 통신 TCP 방식을 이용해서 서버와 클라이언트를 구현하여 서버는 클라이언트 간의 통신을 지원합니다.
클라이언트는 연결 후 대기하고 있다가 통신이 들어오면 서버로 부터 들어온 데이터를 해석하고 의도에 맞게 이벤트를 발생시킵니다.

-   기간 : 2020-07-09 ~ 2020-07-31 (3주)
-   팀 인원 : 5명
-   사용기술
    -   언어 : Java 1.8
    -   GUI: JAVA Window Builder 1.9.3
    -   DataBase : Oracle
    -   OS : windows
    -   협업툴 : powerpoint 2016, starUML 3.2.2
    -   IDE : Eclipse

### 2. 구현 기능 및 설명
-   프로젝트 기여도 : 30%
-   역할 : Full Stack (UI, 비즈니스 로직)
-   담당 기능
    -   메뉴 관리 기능
    -   메뉴판 기능
        -   장바구니
        -   주문
    -   주방 대기열 기능
        -   주문 상태 표시 (조리대기, 조리중, 조리완료) - 음식만 해당
        -   조리대기에서 조리중으로 넘어갈 시 고객의 주문취소 버튼 비활성화
    -   카운터 픽업창 기능
        -   고객 주문시 버튼에 빨간불이 들어오고 픽업을 모두 완료하지 않을 시 분홍색 불로 유지.
        -   음식과 음료 픽업 버튼
        -   음료 픽업시 고객의 주문취소 버튼 비활성화
        -   조리 완료시 음식 픽업버튼 활성화
     
### 3. 개발 관련 설명
프로그래밍 언어 자바를 3개월 배우고 학원에서 처음 시작한 포트폴리오용 프로젝트입니다. 이번 개발 프로젝트에서는 전반적인 프로젝트 진행 과정을 이해할 수 있었습니다. 실무와의 규모 또는 방식에서 차이점이 많이 있을 수 있겠지만 기획, 분석, 설계, 구현, 테스트 까지 모두 경험했습니다.

- 기획에서는 개발자가에게 필요한 사용자의 편리성이라는 측면과 개발팀과 비개발 부서의 이해 관계를 이해할 수 있었습니다. 개발자가 기획까지는 하지 않습니다. 그러나 기획까지 할 수 있었던 이번 경험은 이번 프로젝트에서 가장 중요한 경험이라고 말할 수 있습니다.

- 설계에서는 Class Diagram, Usecase 까지 작성해보며 개발자가 개발만 하는 것이 아니라는 것과 설계에 대한 중요성을 배울 수 있었습니다.

- 개발에서는 TCP 소켓 네트워크 통신에 대한 이해, 서버와 클라이언트의 역할, 데이터를 다루는 과정과 비즈니스 로직을 배울 수 있었습니다.

- 테스트에서는 알파 테스트, 베타 테스트에 대해 배울 수 있었습니다.

다음은 이번 프로젝트에서 작업했던 테이블 명세서, 시스템 구조입니다. 더 자세한 내용을 원하신다면 Git Repository 올라와 있는 PPT 자료를 통해 확인하실 수 있습니다.


### 4. 테이블 명세서
<p align="center">
<img width="49%" alt="image" src="https://github.com/dustjq1004/ZKDPos/assets/73459956/ba58344b-2dac-49ff-9396-21ae4f42e827">
<img width="41.8%" alt="image" src="https://github.com/dustjq1004/ZKDPos/assets/73459956/bbd54ffb-7576-4409-bc41-1a729af25e23">
</p>
<p align="center">
<img width="49%" alt="image" src="https://github.com/dustjq1004/ZKDPos/assets/73459956/2c8b3884-dec4-4553-8d0c-12d9fb408915">
<img width="41.5%" alt="image" src="https://github.com/dustjq1004/ZKDPos/assets/73459956/9f93365d-4901-454f-a32a-bacc6486edd2">
</p>


### 5. System Architecture
<p align="center">
<img width="80%" alt="image" src="https://github.com/dustjq1004/ZKDPos/assets/73459956/c9d368d0-7c91-4dba-aee6-fd0321525e99">
</p>
