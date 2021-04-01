## CSS

* Cascading Style Sheet

* Style: 크기, 모양, 색상, 배치 위치 결정



#### 사용 방법

1. 스타일 태그 설정

   ``<style>
       h1 {color: red}
   </style>``


   * css 선택자 (selector) {css요소명: css값; css요소명2: css값2; css요소명3: css값3}

   * 모든 h1태그들을 찾아서 글씨를 red로 변경

2. inline 방식 스타일 설정

   ``<h1 style="color: red";> 제목입니다 </h1>``

   * 특정 태그만 적용할 경우

3. 외부 css 파일에 스타일 설정

| test.html<br />``<head>``<br />``<link rel="stylesheet" href="test.css">``<br />``....``<br />``<h1> 제목입니다 </h1>`` |
| ------------------------------------------------------------ |
| test.css<br />h1 {color: red}                                |





#### 배치 규칙

* 색상, 이미지, 크기, 여백, 정렬, 폰트

1. 