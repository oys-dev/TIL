# TIL
## Today I Learned

2021-08-28
**HTML: Hyper Text Markup Language**
웹 페이지를 위한 지배적인 마크업 언어다.

[구조]HTML: 웹 문서의 기본적인 골격을 담당
[표현]CSS: 각 요소들의 레이아웃, 스타일링을 담당
[동작]JavaScript: 동적인 요소(사용자와의 인터랙션)을 담당

웹 표준: 웹 표준을 준수하여 작성한다면 운영체제, 브라우저마다 의도된 대로 보여지는 웹 페이지를 만들 수 있음
웹 접근성: 장애를 가진사람과 장애를 가지지 않은 사람 모두가 웹 사이트를 이용할 수 있게 하는 방식
웹 호환성 (Cross Browsing): 웹 브라우저 버전, 종류와 관계없는 웹 사이트 접근

**여는 태그 (Opening tag) + 닫는 태그 (Closing tag) + 내용 (Content) = 요소 (Element)**

태그의 경우 대소문자를 구분하진 않지만,
HTML5에서는 모두 소문자로 작성하는 것을 권장

온라인 웹 에디터: https://jsbin.com
https://replit.com, https://codepen.io
-> 단순히 html 연습할때 사용하면 굿

visual studio code에서 흰 동그라미는
열려있는 파일 중에 수정 한 파일이 있단 뜻

html:5 입력 후 누르면 자동세팅됨
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta http-equiv="X-UA-Compatible" content="IE=edge">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Document</title>
</head>
<body>

</body>
</html>
이렇게


### 확장 프로그램들 ###
*Auto Rename Tag* 설치하면
여는 태그를 바꾸면 자동으로 닫는 태그도 바뀐다.

*Live Server* 설치하면
밑에 Go live누르면
HTML여는 브라우저 새로고침 안해도 바로바로 코드를 수정해도 브라우저가 바뀜

*Prettier- Code formatter*
자동으로 코드를 깔끔하게 정리해줌.
설정가서 format on save 검색하고
Editor: Format on save에 체크하면
저장 누르면 저절로 정리가능

### VScode 단축키 ###
윈도우 기준

에디터 창 제어
- 현재 창 닫기: Ctrl + w

- 닫은 창 다시 열기: Ctrl + Shift + t

- 사이드바 토글: Ctrl + b

- 사이드바 - 탐색기: Ctrl + shift + e

- 사이드바 - 전체 검색: Ctrl + Shift + f

- 에디터 확대: Ctrl + (+)

- 에디터 축소: Ctrl + (-)


소스코드 편집
- 들여쓰기: Tab 혹은 Ctrl + ]

- 내어쓰기 Shift+Tab 혹은 Ctrl + [

- 아래에 행 삽입: Ctrl + Enter

- 위에 행 삽입: Ctrl + Shift + Enter

- 현재 행 이동: Alt + 윗키/아랫키

- 현재 행 복사: Alt + Shift + 윗키/아랫키

- 현재 행 삭제: Ctrl + Shift + k

- 주석 토글: Ctrl + / (<!-- 내용 -->)
