## HTML5 웹 프로그래밍





#### 개요

* 네트워크 - 다른 컴퓨터들끼리 연결
* 인터넷 - 네트워크의 네트워크
* Protocol - 인터넷 모든 컴퓨터 약속 방식 통신
  * "http" - win, mac os에 설치됨, 웹상 protocol명
    * hyper text transfer protocol
    * hyper text - text와 image, 동영상 같이 표현

* Web (world wide web) - 인터넷 상 http protocol 사용 서비스들
* html - http protocol 특성에 따라 작성하는 언어
  * hyper text markup language
  * 인터넷 상 출력 목적 언어





#### http server / http client

* client 요청 -> server 처리 & 응답
* 요청 - url
  * http://serverip:port/boardlist
  * http://serverip:port/login
* Server
  * Back-end program
  * tomcat
  * 처리 (java) - servlet, jsp 실행
  * html 형태의 응답을 보냄
    * html 작성-편집 --> eclipse
* Client
  * Front-end program
  * Web browser
  * Chrome
  * html 실행
  * CSS, HTML, javascript, jquery





#### HTML

* eclipse + tomcat + Chrome (다른 브라우저)

* 실행 과정

  1. eclipse에서 dynamic web project 생성

  2. dynamic web project￦webcontent￦*.html 파일 저장

  3. *.html 파일을 tomcat server에 등록

     (tomcat9 server 등록 설정을 dynamic web project 생성 시

  4. tomcat server 시작

  5. web browser에서 http://ip:port/ dynamic web project 이름/*.html

     url 입력하고 요청 - 응답 출력





#### HTML5 기본 용어

* html5 = html태그 + css + javascript 모두 포함 표준 규격

* 요소 
  
* html에 등장하는 모든 것
  
* 태그

  * 요소를 표현하는 기능을 가지고 있는 것
  * 시작과 종료 태그를 모두 가질 수도 있고 시작 태그만 있을 수도 있음

  ```html
  <h1> a </h1> # a 문자를 제목처럼 크게
  ```
  * ``<br>``:  줄바꿈 태그
  * ``<p>``: 본문 작성 태그

* 속성

  * html 태그의 자세한 특성을 나타내는 기능
  * 특정 태그에만 동작하는 속성 / 모든 태그에 쓸 수 있는 속성 (id)
  * style - 속성명 / color:red - 속성값
  * ``<h1 속성 이름 = 속성 값> 내부 문자 </h1>``

  ```html
  <h1 style="color:red"> 
      ssss
  </h1>
  ```

* 주석
  
  * ``<! -- 주석 -->``
* 페이지 소스 보기 
  
  * 페이지를 만든 코드를 볼 수 있음

| 글자표현     | h1 - h6<br />p br hr                   |
| ------------ | -------------------------------------- |
| 링크         | a                                      |
| 목록         | ul ol li                               |
| 표           | table tr th td                         |
| 화면영역표시 | div span                               |
| 시맨틱       | header nav section article footer      |
| 입력 양식    | form<br />input textarea select option |
| 멀티미디어   | img audio video                        |





#### Table 생성

| 로그인 아이디 | xxxxxx | 로그인 버튼        |
| ------------- | ------ | ------------------ |
| 암호          | xxxxx  | 2행 차지 (rowspan) |

| 로그인 아이디 | xxxxxx             |
| ------------- | ------------------ |
| 암호          | xxxxx              |
| 로그인 버튼   | 2열 차지 (colspan) |

* border
* colspan / rowspan
  * column 늘리기 / row 늘리기
* caption - table 제목 설정
