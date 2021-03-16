# GRAMO (GRam Application Members Only)

# 로그인 회원가입

**Email**

이메일 인증(확인코드 받아서 입력) 있음

**Password**

5 ~ 20글자 (특수문자 X)

**Name**

이름만

**분야 설정**

iOS, Android, Back-end, Design

**디자인** ✅



## 레트로핏

https://hijjang2.tistory.com/441

## 레트로핏 GET/POST/PUT/DELETE

https://jaejong.tistory.com/38

## 토큰 SharedPreferences로 저장하기

https://onlyfor-me-blog.tistory.com/276

## EditText 입력 변화 이벤트

https://ccdev.tistory.com/15

https://mine-it-record.tistory.com/272

## 스피너 힌트 설정

https://stackoverflow.com/questions/37019941/how-to-add-a-hint-in-spinner-in-xml

## 스피너 선택시 가상 키보드 내리기

https://stackoverflow.com/questions/13116784/how-to-hide-virtual-keyboard-on-touch-of-a-spinner



---------------------------------------------------------------------------------------------

# 네비게이션 드로어 (사이드바)

**화면전환은 왼쪽 상단 목록바를 통해 전환**  ✅

**목록 바 상단**  ✅

미니 프로필(이름, 분야)

**목록 바 중단**  ✅

화면(페이지) 전환

**목록 바 하단 ** ✅

탈퇴 / 로그아웃





## 예제

https://lktprogrammer.tistory.com/168

## 공식문서

https://developer.android.com/guide/navigation/navigation-migrate?hl=ko#kotlin

**Menu Item 색상 변경(개별)**

https://stackoverflow.com/questions/32042794/changing-text-color-of-menu-item-in-navigation-drawer/32114570

```Kotlin
//개별적으로 item 색상 변경
val nvDrawer : NavigationView = nav_view
val menu = nvDrawer.getMenu()
val menuItem = menu.getItem(3)

if(menuItem.title.equals("로그아웃")){
val spannableString = SpannableString(menuItem.title.toString())
spannableString.setSpan(ForegroundColorSpan(getColor(R.color.red)), 0, spannableString.length,0)
menuItem.setTitle(spannableString)
}
```



-------

# 공지사항

**공지사항 추가 권한은 모두 있지만 삭제는 작성자만 가능**

**제목, 작성일, 공지 내용 미리보기**

20자로 길이제한, 잘리는 글자는 흐릿하게 표현

**공지사항 페이지** 

한 페이지에 보이는 뷰는 10칸으로 제한 (리사이클러뷰 이용)

댓글 X

**푸쉬알림**

새로운 공지사항 등록 -> **공지사항 "제목"**

**공지사항 -> 세부사항 팝업**

공지 내용, 공지 시간, 작성자

공지사항 제목 : 50자 제한

공지사항 본문 : 1000자 제한





## 텍스트뷰 말줄임 표시

https://jhshjs.tistory.com/27	

## 리사이클러뷰

https://codechacha.com/ko/android-recyclerview/

## 리사이클러뷰 아이템 클릭 이벤트

https://everyshare.tistory.com/68

## 리사이클러뷰 retrofit 연동

https://purple-wood-lights.tistory.com/10

## 액티비티 팝업

https://wookkwang.tistory.com/entry/Activity-%EC%95%A1%ED%8B%B0%EB%B9%84%ED%8B%B0%EB%A5%BC-%ED%8C%9D%EC%97%85%EC%9C%BC%EB%A1%9C-%EB%9D%84%EC%9A%B0%EA%B8%B0-Popup-Activity

https://ghj1001020.tistory.com/9

## 푸시알림

https://blog.naver.com/ndb796/221553341369

## Bottom sheet

**BottomSheet Adapter에서 사용법 정리**

https://minwook-shin.github.io/android-kotlin-recyclerview-adapter-bottom-sheet-dialog/

**Bottom Sheet 테두리 수정하기**

https://stackoverflow.com/questions/43852562/round-corner-for-bottomsheetdialogfragment

### Bottom sheet 콜백

https://youngest-programming.tistory.com/349

https://youngest-programming.tistory.com/373

## 현재 시간 가져오기

https://lesslate.github.io/android/%EC%95%88%EB%93%9C%EB%A1%9C%EC%9D%B4%EB%93%9C-%ED%98%84%EC%9E%AC-%EB%82%A0%EC%A7%9C,-%EC%8B%9C%EA%B0%84-%EC%B6%9C%EB%A0%A5/

# 기타 참고 예제

**Back 버튼 2번 입력 후 종료** 

https://atomic0x90.github.io/android-studio/2020/02/28/android-studio-back-button.html

**배경 터치시 키보드 감추기**

http://www.incree.com/tc/incree/100

**팝업 창(dialog) 띄우기**

https://lktprogrammer.tistory.com/155

**소스코드로 색상 변경**

https://kkotkkio.tistory.com/21

**툴바 그림자(경계선) 제거**

https://hwiyong.tistory.com/13

**툴바 타이틀 제거**

https://themach.tistory.com/137

**코루틴**

https://todaycode.tistory.com/23

**무한 스크롤**

https://acaroom.net/ko/blog/youngdeok/%EC%97%B0%EC%9E%AC-%EC%BD%94%ED%8B%80%EB%A6%B0-%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8-02-6%EB%8B%A8%EA%B3%84-infinite-scroll%EA%B3%BC-ui%EC%9D%98-%EA%B0%9C%EC%84%A0