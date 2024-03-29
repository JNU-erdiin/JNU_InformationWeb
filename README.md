# SW캡스톤 프로젝트

## 프로젝트 소개

##### 주제 : 제주대학교 내 시설 정보 웹 서비스(SW57) - 어디인

1. **과제 추진 배경**

   학교 내 사업단이나 공지방 톡방에서 혹은 학교 커뮤니티 어플에서 강의실 위치, 편의점, 복사기, 식당, 타 학과 사무실 전화번호를 물어보는 글이 종종 올라옴.

   이렇게 물어보는 이유는 위와 같은 정보들을 어디서 찾아야 하는지 바로 떠오르는 곳이 없고 제주대학교 사이트가 있다 하더라도 그 안에서 어느 페이지에 있는지 찾아야 함.

   복잡한 과정 없이 한눈에 볼 수 있는 웹 서비스를 제공하면 게시글을 올리지 않아도 혼자 확인이 가능하기에 더욱 편리해진다 생각되어 추진하게 됨.

   어떻게 보면 서비스가 일회성이라 볼 수 있기 때문에 어플을 개발해 사용자에게 설치를 요구하기보다 웹으로 구현하여 사이트에 접속하는 것이 더 좋다고 판단됨.

   

2. **목표**

   1. 제주대학교 내에 위치한 여러 시설들의 정보를 알려준다
   2. 위의 정보를 제주대학교 학생 뿐만 아니라 학교 방문객들도 참고할 수 있도록 웹사이트로 구현해 서비스를 제공한다.

   

3. **필요성**

   1. 학생들이 게시글로 원하는 정보를 얻기까지의 시간을 절약해준다
   2. 학교 시설 정보가 한눈에 있어 궁금한 것이 생길 경우  이 사이트에만 방문하면 되기에 더욱 편리해진다
   3. 스마트폰으로 언제 어디서든 확인이 가능하다.

   

4. **활용 방안**

   1. 반응형 웹으로 구현할 예정이므로 인터넷만 되면 사용 가능
   2. QR코드를 발급받아 학교 건물들마다 부착할 경우 검색, 설치 필요 없이 스캔만으로 접속이 가능하다.

5. **주요기능**

   1. 시설들을 각각 다른 색상의 마커로 지도에 표현한다.
   2. 순환버스 정류장과 운행 시간, 도착 시간 확인 기능
   3. 학과 사무실 위치, 전화번호 안내

   

6. **개발환경**

   1. OS : Windows10
   2. Framework : React, Node.Js
   3. Language : Javascript, HTML, CSS



## 기획

시나리오, 유스케이스, 프로토타입, 시퀀스 다이어그램, 사용자 인터페이스 기준 정보 설명

1. 사용자 인터페이스 맵
   - 메인(제주대학교 맵) -> 마커 선택(편의점, atm, 복사기, 학식, 과사) -> 활성화
   - 메인(제주대학교 맵) -> 정류장 선택 -> 시간표, 도착정보 확인
2. 프로토타입(UI)
3. 시나리오
   1. 사이트 접속 시 제주대학교 지도를 보여주는 메인 화면이 뜬다.
   2. 좌측 상단에는 제주대학교 내 시설들을 과사, atm기기, 복사기, 편의점 등으로 구분하여 아이콘으로 표시되어있다.
   3. 해당 아이콘을 클릭시 관련 시설이 지도에 마커로 표시된다. 또한 아이콘의 색깔도 바뀌면서 활성화됨을 나타낸다.
   4. 아이콘을 다시 클릭하면 해당 시설들의 마커가 사라진다
   5. 
4. 유스케이스
5. 시퀀스 다이어그램



<들어갈 정보들>

- 교내정보 -> 각 마커 아이콘과 색상, 표기방법 고려

  - 과사 전화번호 
  - 학과 위치
  - ATM기, 편의점(아라홀, 편의점), 복사기 위치
  - 코로나19로 인한 출입문 안내

- 순환버스 => 정류장 위치 표시와 시간표를 어떻게 표시할 것인가

  - 각 버스 정류장 위치와 해당 정류소 시간표
  - 버스 도착시간 안내

  

## 개발일정

- 매주 1회 회의 (내용 정리)

1. 역할분담
   - 김나연 (팀장) : 자료 수집, SW개발, 회의 정리
   - 김아현 (팀원) : 자료수집, SW개발



2. 기간 : 9/1 - 12/22 (개강, 종강 기준)

   - 9/1 - 9/17 : 아이디어 및 팀 선정, 캡스톤디자인 신청서 제출
   - 9/20 - 9/30 : 아이디어 구체화 및 세부 기획
   - 10/1 - 10/26 : 중간고사 & 시험 준비
   - 11/1 - 11/12 : 자료 수집 및 정리, 프로토타입 제작
   - 11/13 - 12/3 : 개발 역할 분담 & 개발 시작

   

3. 개발 세부 사항

   1) React, Node.Js 설치, 서버 연결
   2) 지도 API가져와서 제주대학교 지도 보여주기 (제주대 내에서만 확대축소되도록)
   3) 마커 표시 기능
   4) 순환버스 시간 계산



