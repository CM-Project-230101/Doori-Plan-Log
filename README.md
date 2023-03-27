# Doori

## Why
시중에 커플 다이어리 및 디데이 앱은 많다.

하지만 각 앱마다 기능이 달라, 원하는 기능을 사용하기 위해서는 여러 앱을 사용해야 한다.

이러한 불편점을 해소하기 위해, 소비자의 입장에서 모아두면 좋을 것 같은 기능들을 모아 앱을 출시해보자는 의견이 나왔다.

제작하면서 우리가 독자적으로 생각했던 기능들, 시중의 앱에서 모티브를 따온 기능들이 존재한다.

커플사이의 소통활동에 있어서 이 앱이 큰 비중을 차지했으면 좋겠다.


## Special Point
이 앱의 특징은 소비자의 입장에서 원하는 기능들 이다.

데이트를 하다보면 어디를 갈지, 누가 추천해줬으면 좋겠다. 이런 생각을 해본적이 많다.

그래서 다른 사람들이 추천하는 장소를 모아서 보여줄 수 있는 기능을 추가했다.

그리고 커플 데이트 일정 관리 / 커플 다이어리 를 엮어둔 앱이 없어서 이 둘을 하나의 앱으로 통합시켰다는 부분에서도 이 앱만의 특이점이라고 할  수 있겠다.

또한 업로드한 사진들을 갤러리처럼 내가 원하는 앨범별로 분류시킬 수 있는 부분 또한 이 앱의 특이점이다.

## 기획 과정

- 타임캡슐 - 미래에 열어볼 수 있는 편지 - 기간은 선택
- 버킷리스트 - 같이 하고싶은 투두리스트 느낌?
- 공유일기 - 같이 쓸지(둘 다 수정 가능) / 따로 쓸지 선택하도록?
- 디데이 보기
- 데이트 일정 등록 / 후기 남기기 → 당일 저녁 특정시간 이후
    - (네이버 지도 → 데이트 갔던 장소 모아보기 / 후기까지)
- 다른사람들의 추천 데이트장소 모아보기
- 주/월간 목표 설정하기 → ex) 이번주엔 꼭 또보겠지떡볶이 먹자! 같은 느낌?
- 캘린더로 언제 데이트할지 표시해주기, 혹은 일정 추가?
- 홈** : 2,3,4의 내용을 한꺼번에 압축해서 보여줄 수 있는 화면
- 일기장 /  메모장** : 데이트 기록을 남길 수 있는 일기장
- 지도** : 내 위치를 기준으로 방문한 기록을 지도 위에 표시 (방문한 기록은 일기와 연동됨), 추천기능(다른커플은 어디를 많이 방문했는지)
- 일정(캘린더)** : 여기서 일정을 설정하면 d-day가 홈화면에 표시됨, 또한 일기와 연동시킬 수 있음
- 설정**: 그냥 환경설정 (로그아웃, 별명 설정, 프로필 설정)

## 최종안
#### 일기장
- 각자 쓰는걸로 ⇒ 쓴것만 보여주기 삭제X 수정만 2depth
- Max Lines = 3, elipse처리 → Click시 전문보기 화면
- 검색 ⇒ 내용기준 키워드로 (띄워쓰기 기준으로 키워드 나눌건지? 아니면 그냥 포함 문자열인지?) ⇒ 찾아보기


#### 앨범
- 태그형식? 앨범명? → SP사용 → 자기가 쓴 글의 사진만 삭제가능
- 사진 업로드시 ⇒ 앨범에 ‘기본’ 에 위치시키고, 사용자가 앨범 커스텀 후 자유롭게 이동 가능하게

#### 지도
- 마커에 사진 → VP? → 스크롤업해서 FG RV로 전환 → 현재 지도에서 검색 버튼 클릭 시 검색 (디폴트는 현재 화면)
- 추천 ⇒ RV로 해서 주소?상호명 검색 → 검색버튼 클릭시 추천순으로 RV

#### 설정
- 프로필 사진 / 닉네임 변경 (프로필 변경)
- ~~다크모드~~
- 이용약관
- 알림?
- 문의하기
- 로그아웃
- 탈퇴
- 버전정보

#### 홈
- 디데이
- 캘린더
- 메모장
- 메인사진

## 최종안 바탕으로 설계한 ERD 초안
![Copy of Doori](https://user-images.githubusercontent.com/80454599/227839925-27d4947c-0a4a-4032-9414-9db5440b51f8.png)

