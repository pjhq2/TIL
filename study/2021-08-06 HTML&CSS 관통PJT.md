# 2021-08-06 HTML&CSS 관통PJT

- Media Query

  단말기의 유형(출력물 vs 화면)과, 어떤 특성이나 수치(화면 해상도, 뷰포트 너비 등)에 따라 웹 사이트나 앱의 스타일을 수정할 때 유용



- Font & Icon

  google font

  bootstrap icons / font awesome

  

  realfavicongenerator

  Favicon(Favorites icon) : 웹 브라우저의 주소창에 표시되는 웹 사이트를 대표하는 아이콘



- Bootstrap Source Code

  rtl : 오른쪽에서 왼쪽

  min : 한줄로 압축

  map : min 디버깅용

  

  CSS(근본) / SASS(급진) / SCSS(중도) 이런게 있다.



- CSS 더보기

  명시도(Specificity) : CSS에서 id, style, !important는 불가능이 아니라면 쓰지 말자

  (0, 0, 1) ~ (1, 0, 0, 0, 0)

  ```css
  <style>
    p > a {color: blue;} # (0, 0, 2) 이게 적용됨
    a {color: red;} # (0, 0, 1)
  </style>
  ```

  

- Naming Convention (BEM(Block, Element, Modifier))

  Block__Element--@@@



width는 상속되는 개념이 아니다.

