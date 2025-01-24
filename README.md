## Seoul - 서울시 공공데이터 서비스

서울시 공공데이터 플랫폼 서울시의 다양한 공공데이터를 통합하여 쉽게 접근할 수 있는 플랫폼입니다. 문화, 어린이, 체육, 건강, 관광의 5개 분야를 선정하였으며, 각 분야의 시설 정보를 조회하고 카카오맵 API를 통해 시설의 위치를 지도에 표시합니다. 공공데이터와 API 활용에 대한 이해를 높이기 위해 백엔드와 프론트엔드를 분리하여 개발하였습니다. 백엔드는 Java와 Spring을 사용하고, 프론트엔드는 React를 활용하였습니다. 데이터는 공공데이터 API를 통해 수집하거나 전처리 후 MariaDB에 저장하여 사용합니다.

[프로젝트 목표]
* 공공데이터 활용 능력: 외부 데이터를 활용하는 방법을 배우고 익힘
* 프론트엔드와 백엔드 분리 경험: 두 영역을 명확히 구분하여 각 역할에 대한 이해도를 높임

[프로젝트 개요]
* 기간: 2024.11.25 ~ 2024.12.20
* 팀원: 백엔드 5명
* 사용기술: Java, Spring, MariaDB, MyBatis, React, Node.js
* 담당: 관광 파트 (100%)

## 담당 기능
서울시의 관광지 목록을 출력하고, 현재 진행중인 축제 및 예정된 축제 목록을 제공합니다.

![Image](https://github.com/user-attachments/assets/49752715-2bbb-4029-a97c-d7145b811458)

* 실시간 검색 시 옵션이 변경될 때 자동으로 서버에 요청을 전송합니다.
* 사용자의 현재 위치에 자동으로 포커스가 맞춰지고, 주변 관광지를 마커로 표시합니다.

![Image](https://github.com/user-attachments/assets/6b468b89-b6ef-47a3-bfe8-d7ed75916e85)

* 지도에서 오버레이를 클릭하면 상세 정보를 확인할 수 있습니다.
* 상세 정보는 오버레이 클릭 시 서버에서 받아옵니다.

![Image](https://github.com/user-attachments/assets/ac79e42e-abd5-40c1-b9e6-6faabd4fa8db)

* 축제 지도에서는 관광지 대신 현재 진행 중이거나 예정된 축제 정보를 표시합니다.
 
![Image](https://github.com/user-attachments/assets/ee4076ab-739f-41d0-aee0-c4cf22f3c7e8)

* 반려동물 지도에서는 반려동물 동반이 가능한 관광지를 보여줍니다.

![Image](https://github.com/user-attachments/assets/1cee1f0d-ba86-4462-b9b5-4f06f70e4d29)
