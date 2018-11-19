# Galaxia

> personal space community

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build
```

For detailed explanation on how things work, consult the [docs for vue-loader](http://vuejs.github.io/vue-loader).

##황호룡 프로젝트
우주 커뮤니티를 만들어보자.
2018 경상대학교 CS 웹프로그래밍 

황채린
김호
이자룡

##9월 23일 작업내용
기초 세팅중

##9월 26일 작업내용
인트로페이지 제작중. 로그인창 추가 예정

##9월 26일 회의내용
로그인 페이지 이후 내 행성페이지 구현의논
1. 행성이 있고 네비게이션 바
	1. 둘러보기: 모든 행성 중 하나로 갈 수 있다. 슈우우욱
		우주선 로딩페이지로 바뀜. 다른 행성으로 간다.
	2. 상점: 일주일 지나면 우주농산물이 자란다. 그걸 팔 수 있다.
	3. 꾸미기: 내가 상점에서 구입한 요소들을 행성에 심는다.
	4. 친구들: 누르면 친구리스트가 뜬다
	5. 설정: 내 프로필 설정: 상태메세지
2. 귀여운 행성 및 솜사탕나무 등의 우주요소들을 취합할 것
3. 나무를 클릭하면 물준다. 나무가 크면 솜사탕수확

##9월 28일 작업내용
1. 인트로 페이지 html파일로 옮겨버림. 차후 vue dev모드에서 production모드로 바꿀 것.
2. 개인행성페이지 세팅중. 전체 배경색 spaceGray컬러로 설정.
3. myPlanet페이지 레이아웃 작업중. 알바가야되서 작업못했는데  지금 중앙정렬이 cottonCandy로 되어있는데 Planet으로 바꾸고 솜사탕나무는 planet내부템플릿으로 빼버릴 것. 

##9월 30일 작업내용
1. 사이드바 작업중

##10월 1일 작업내용
1. 임시 배경화면과 플래닛, 솜사탕나무 설치함.

##10월 5일 작업내용
1. 뒷 배경 바꿈
2. myplanet 박스사이징 인덱스로 옮겨버림
3. 행성과 솜사탕나무 잠시 꺼둠

##10월 6일 작업내용
1. flex없애버림.

##10월 8일 작업내용
1. 사진 교체.
2. vuetify 추가함. 현재 vuesax와 혼용하고 있어서 나중에 코드가 꼬일 수 있으므로 vuetify로 통일할 것.
3. 앞으로 해야할 일: 
	1. 행성 호버하면 특정한 애니메이션을 하도록
	2. 솜사탕 나무 클릭하면 물주기 뜨기
	3. 사이드바 작업...

##10월 18일 작업내용
1. 아예 vuetify로 템플릿 바꿔버림
2. 현재 사진에 가려서 콘텐츠가 안 보이는 문제 발생. 해결에 집중할 것.
3. 2번문제 해결. 배경을 이미지태그로 넣는 게 아니라 css background url로 적용
4. 김호가 보내준 로그인파일을 프로젝트 파일에 추가함

##10월 19일 작업내용
1. 클라이언트단 로그인함수 작성함 

##10월 20일 작업내용
1. login.js파일 제외함
2. 스택오버플로에 static폴더로 build option 변경하는거 질문함. 예전 left and right땐 알아서 static에 담겼던 것으로 확인됨.
3. 2번은 김호가 해결함. 팩맨게임과 로그아웃, 프로필 설정 기능 추가.
4. 황채린의 새 행성과 솜사탕나무 추가 

##10월 21일 작업내용
1. 상점 구현중.
2. 리스트를 누르면 화면이 바뀌게 구현함.
3. login.js파일 새로 업데이트함.
4. 현재 로컬에서 이미지를 못 읽어오고 있음. 카로셀로 구현했는데 아마 서버에 올려서 써야 할 듯.
5. 카로셀 계속 움직임. 안 움직이게 하는 api 찾아볼 것.

##10월 22일 작업내용.
1. 상점 구현중. 그리드 대충 짜놓음. 디자인이 마음에 안 든다.
2. 앞으로 이것 관련해서 해야 할 내용은 다음과 같다.
	- 탭을 누르면 바뀌어야
	- 이미지를 클릭하면 해당 인포가 나와야
	- 구매하기를 누르면 확인모달이 떠야
	- 확인을 누르면 돈이 깎이면서 성공했다는 메세지가 뜨고 아이템이 담김.

##10월 23일 작업내용
1. 상점 대충 구현해놓음.
2. 상점 디자인 마음에 들지 않음. 그리고 커밍쑨 촌스러움. 
3. 호에게 어떻게 돌아가는지 설명해줄 것. 

##11월 1일 작업내용
1. 게임을 팩맨에서 테트리스로 수정함. 차후 테트리스를 서버에 올리고, 클릭 시 새창으로 실행되도록 조치할 것.
2. 쇼핑창 살짝만 손봄.

##11월 16일 작업내용
1. 보름만에 작업 재개. 변경사항이 어마어마하니 일단 기록함
	1. 발표 ppt를 메뉴 섹션에 넣었음. 아직 ppt는 없음
	2. 인트로는 배경 바꿨고 디자이너가 넘겨줄 예정
	3. 친구들 섹션은 김호에게 넘겨줌
	4. 상점, 꾸미기 빼버림
	5. 프로필 설정 때 자기소개 한 줄 입력하도록 설정했으며, 닉네임 밑에 뜨도록 조치함.
	6. 로그아웃 버튼 클릭 시 아래 Alert이 뜨는 게 아니라 다이얼로그가 뜨도록 조치함.
	7. 로딩 할 일이 없어서 로딩 빼버림
	8. 퀴즈 제작중.
		1. 정답 입력시 경험치 올라감
		2. 정답 입력시 나머지항목들 disabled
		3. 정답 입력시 정답 알람 뜸.
		4. 오답 입력시 오답 알람 뜸

##11월 18일 작업내용
1. 퀴즈는 데모로 총 3개 만들어놓음. 3번퀴즈가 끝나면 1번으로 돌아옴.
2. 경험치가 쌓이면 100을 빼고 남는 데이터가 경험치로 남고, (하나 성공시킬때마다 33.4오르도록 함) 레벨이 올라감. 개발자도구를 통해 콘솔에 찍히도록 하니 정상적으로 레벨업 됨.

##11월 19일 작업내용
1. 경험치 옆에 레벨도 같이 보이게.
2. 레벨 올라가면 행성 5개 중 선택하는 팝업 뜨게 함
3. 프로젝트 파일 구조 바꿈.
4. planetChoiceList에서 선택된 행성 넘버를 최상위 컴포넌트인 App으로 넘겨줌. log찍어봤을 때 잘 나옴.