# game project


<p>
프로젝트 주제: 베스킨라빈스31 아이스크림을 모티브한 파이게임이다. </br>
프로젝트 소개: 3가지 맛의 아이스크림 버블을 랜덤으로 발사하여 충돌기준에 충족하면 조건에 맞는 버블을 터트리는 게임으로 일정 횟수를 넘어가면 버블이 점점 강도가 세게 흔들리고 철장이 내려오게끔 하여 흥미적인 요소를 첨가하였다. 모든 버블을 없애면 게임이 성공으로 끝나게되고 버블이 11줄이 넘어가게 되면 버블은 검게 변하며 게임 실패로 게임이 끝나게 된다. </br>
</p>
<p>
 프로젝트 진행기간: 2022년 4월 11일 ~ 2022년 6월 7일</br>
 프로젝트 발표일: 6월 8일</br>
 - 팀명: TWO준캐리조(3조)</br>
 - 팀장: 전혜나(202004449)</br>
 - 팀원: 김미영(202100573), 박정민(202004233), 이성준(202102467), 정준혁(202103172)</br>
</p>
<p>
<h4>주차별 일정</h4>
9 주차(4월 27일 ~ 5월 3일)  - 공통) 주제 선정 후, 코드 설계, pygame 모듈에 대한 공부</br>
10주차(5월 4일 ~ 5월 10일)  - 공통) pygame 모듈에 대한 공부
                             프론트엔드)코드 작성 전 기본틀 깃허브에 주석으로 작성 </br>
11주차(5월 11일 ~ 5월 17일) - 공통) pygame 모듈에 대한 공부</br>
                             백엔드) 프로그램 시작단계 작성</br>
                             프론트엔드) 시작단계에 필요한 그림 제작, 이미지 찾기, png파일로 업로드</br>
12주차(5월 18일 ~ 5월 24일) - 게임화면 ~ 버블 발사 구현</br>
13주차(5월 25일 ~ 5월 31일) - 충돌 함수 ~ 종료 구현</br>
14주차(6월  1일 ~ 6월  7일) - 전체적인 보수, 기능 추가, exe 실행 파일 만들기
</p>
<p>
개발 순서</br>
게임 시작화면 -- 배경이미지, 게임 타이틀 아이콘, 도움말 아이콘 필요</br>
게임 실행 -- 맛 8개 나열, 각 맛 별 값 배정, 랜덤으로 숫자 발생 후 키보드 이벤트로 받은 값과 비교하여 정답 오답처리. 중앙 아래 발사대 설치 및 구현, 발사대 위에 현재 버블 구현, 왼쪽 아래에 다음 버블 위치</br>
</p>
<p>
---- Gamestart 클래스</br>
---- 함수</br>
 	init()</br>
	quest() -- random 약 25개 정도</br>
	check() -- quest와 비교하여 count</br>
	endmenu()</br>
	timer()</br>
	sale()</br>
	Hp()</br>
	cup&con()</br>
	
	//consumer() -- 말풍선//</br>
	//saleman() -- 말풍선//</br>
	
	
게임 종료 화면 -- 맞춘 스코어, 버블 black 처리</br>
</p>
