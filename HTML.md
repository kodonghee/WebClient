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