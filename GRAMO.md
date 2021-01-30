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

**EditText 입력 변화 이벤트**

https://ccdev.tistory.com/15

https://mine-it-record.tistory.com/272



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





## 텍스트뷰 흐르게 처리

https://docko.tistory.com/entry/%EC%95%88%EB%93%9C%EB%A1%9C%EC%9D%B4%EB%93%9C-TextView-%EA%B8%B4-%EB%AC%B8%EC%9E%A5-%ED%9D%90%EB%A5%B4%EA%B2%8C-%EC%B2%98%EB%A6%AC%ED%95%98%EA%B8%B0

## 리사이클러뷰

https://dev-imaec.tistory.com/27

## 액티비티 팝업

https://wookkwang.tistory.com/entry/Activity-%EC%95%A1%ED%8B%B0%EB%B9%84%ED%8B%B0%EB%A5%BC-%ED%8C%9D%EC%97%85%EC%9C%BC%EB%A1%9C-%EB%9D%84%EC%9A%B0%EA%B8%B0-Popup-Activity

https://ghj1001020.tistory.com/9

## 푸시알림

https://blog.naver.com/ndb796/221553341369



​	

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



