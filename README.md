# to_the_top
자바FX와 웹 크롤링을 이용한 강의와 과제 기한을 알려주는 캘린더 프로그램

1.팀원 및 역할
===========
|  팀원  |  역할  |
| ------ | ------ |
|이정재|서버크롤링 및 로그인 관리|
|배준형|서버크롤링 및 로그인 관리|
|장승헌|캘린더UI 개발|
|이건욱|캘린더UI 개발|

2.프로젝트 관련
===========
2.1 로그인 및 서버 크롤링
-------------
스마트캠퍼스에 HTML을 JSOUP을 통해 사용자의 아이디와 비밀번호를 입력받아
스마트캠퍼스에 로그인 세션을 보낸 후 받아 온 쿠키를 통해 듣는 수업들의 HTML을
전부 가져옵니다. 사용자가 듣는 수업들 별로 각각의 HTML의 태그별 속성값들의 맞춰서 강의들과 과제들의 정보(과목, 영상 길이, 수강 기간, 지각 기간, 강의 진도율)을 가져온다. 가져온 정보들을 3차원 배열을 이용해서 주차별, 강의&과제 그리고 기한 순으로 저장했습니다.

2.2 캘린더UI 관련
------------
캘린더 UI에는 화면에 과목마다 색깔별로 구분한 점들을 넣어서 강의기한을 표시할
예정입니다. 각 날짜에는 푸시버튼을 넣어 버튼을 누를 시 UI 오른쪽에 강의에 세부사항들을 표시할 것입니다. 또한 업데이트 기능을 넣어 강의가 새롭게 추가된 것을 확인할 수 있도록 하고 개인의 일정을 추가 또는 삭제 할 수 있는 기능을 추가할 것입니다.


