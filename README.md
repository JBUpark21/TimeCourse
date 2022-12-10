# TimeCourse

2022년 1학기에 제작한 대학교 수강신청사이트 TimeCourse입니다.

기존 수강신청 사이트를 이용하면서 학생들이 수강신청을 이용할 때 불편해 하는 부분을 다수 발견하게 되었고,

학생들의 조사를 통해 수강신청사이트의 문제점을 명확하게 정의하고 개선을 통해 대학커뮤니티 ‘에브리 타임’의 강의평가와 같은 기능을 몇 가지 결합시켜 좀 더 간편하게 만들고자 했다.

UI 개선과 정렬기능의 간략화, 수강신청 시간표를 다수 제작 가능(슬롯화), 과목에 대한 좀 더 많은 정보 필요 (강의계획서, 강의평가), 신청 버튼 가시성 해결과 사용 빈도가 낮은 UI를 제거하는 부분을 중점적으로 해결하고자 했다.

-웹 디자인 & 기획

▶기존 수강신청 사이트 및 설문조사를 기반한 웹 사이트 로고 및 색상 디자인변경

▶불필요한 기능 UI 삭제 및 최소화, 수강신청시 도움이 되는 기능 UI 디자인 추가

▶작업 중 구현에 차질이 있는 부분 수정 및 삭제

▶만들어진 결과물 재검토 후 변경할 디자인 수정 구현시 필요한 자료사진 제작.

-프론트엔드

EJS, CSS, JS 언어를 이용하여 로그인 및 회원가입 창에 UI와 실시간 시간 기능을 추가하여
학생들이 웹서버 시간을 정확히 파악할 수 있게 하였다. 메인 홈페이지에 수강신청 테이블과
장바구니 테이블의 구성을 구현하였으며 호버 기능 및 팝업 기능의 대략적인 외형을 구현하였다.
대략적인 외형 구성 후 버튼 기능 등의 구현으로 사이트 마다 자유롭게 넘어갈 수 있도록 하였다.
React.js 언어도 사용하려고 하였으나, 우리가 생각한 웹사이트와 맞지 않을 것으로 판단, 프로젝트
중 개발을 중단하였다.

-백엔드

데이터베이스의 경우 MySql과 Amazon RDS(아마존 데이터 베이스)를 이용하여 데이터 베이스를
구현하였다. Node.js를 이용하여 로그인 정보 및 게시판 정보, 과목 정보 등을 데이터베이스와
연동하여 웹사이트에 출력하였다. 게시판의 경우 CRUD (기본적인 데이터 처리 기능인 Create(생성),
Read(읽기), Update(갱신), Delete(삭제)) 기능을 구현하였다. 웹 서버의 경우 AWS(아마존 웹 서버)의
Amazon EC2를 사용하여 웹서버를 구동하여 서버 호스팅을 진행하고자 하였다.
