#  Netty 시작하기 강의 자료

> 고성능 네트워크 애플리케이션 프레임워크 Netty 시작해보기

이 프로젝트 소스와 슬라이드 자료는, Netty 기초 프로그래밍 학습을 위한 교육자료로 만들었으며, 4시간동안
설명과 실습을 함께 진행하도록 구성했습니다.

## 과정과 목표

JAVA로 고성능 네트워크 클라이언트/서버를 편리하게 개발할 수 있는 프레임워크인 [Netty](http://netty.io)의 기본 개념을 이해하고 예제를 통해 연습합니다.

## 학습 내용과 대상자

Netty는 JAVA환경에서 고성능 네트워크 서버를 개발할 수 있는 매우 유용한 프레임워크입니다만, 비동기(asynchronous) 이벤트 기반 (event-driven) 처리에 익숙하지 않은 개발자에게는 처음 접근하기 어려운 점이 있습니다. 이 과정에서는 기존 멀티쓰레드와 동기식(synchronous) I/O처리에만 익숙했던 개발자도 차근차근 따라해보며 비동기 I/O처리의 기본 개념을 이해하고, Netty를 본격적으로 활용해 볼 수 있도록 예제 개발을 함께 해보려 합니다.

## 4시간 발표 슬라이드

1. [비동기 개념, 기본 인터페이스(```Channel```) 정리](http://hatemogi.github.io/netty-startup/)
1. [고성능 메모리 모델과 유연한 파이프라인](http://hatemogi.github.io/netty-startup/2.html)
1. [깔끔한 스레드 모델, Future/Promise 활용](http://hatemogi.github.io/netty-startup/3.html)
1. [풍부한 코덱과 WebSocket](http://hatemogi.github.io/netty-startup/4.html)

위 슬라이드는 웹브라우저에서 바로 볼 수 있습니다.

## 예제와 실습 프로젝트

1. EchoServer, DiscardServer
1. HTTP 웹서버
1. 텍스트 기반 채팅서버
1. 웹소켓 기반 웹 채팅

실습 프로젝트는 거의 모든 소스가 작성되어있고, 교육자료를 다 이해한 뒤에 한 두 줄 작성하는 것으로
완성할 수 있도록 중요 부분이 비어있습니다. 작성해야할 부분은 ```TO DO```로 주석 표시가 돼 있어서
IntelliJ에서 ```Cmd+6```을 눌러 ```TO DO``` 뷰를 열면 쉽게 찾아갈 수 있습니다.
짧게 몇줄 작성하는 것이지만, 교육자료와 나머지 소스를 어느정도 이해해야만 쉽게 작성할 수 있습니다.
잘 작성했다면, 유닛테스트를 통과하는지 확인하고, 각 실습 예제의 main() 메소드를 실행해서 확인하도록
합니다.

## 준비사항

* [IntelliJ 최신버전 Community](https://www.jetbrains.com/idea/download/)
* [JDK8](https://jdk8.java.net/download.html)
* [Git 클라이언트](http://git-scm.com/downloads)

무료 IDE인 IntelliJ 커뮤니티 버전으로 실습을 따라할 수 있습니다. Java8기준으로 실습 프로젝트를
작성했으므로, JDK1.8을 준비하도록 합니다.

### 프로젝트 클론

```
git clone https://github.com/hatemogi/netty-startup
```

### 인텔리J로 프로젝트 열기

> netty-startup

* 클론받은 디렉토리를 인텔리J로 열고 [CMD+1]을 누르면 프로젝트 윈도가 보입니다.
* [CMD+6]를 누르면 실습 문제용 코드를 작성할 부분들이 보입니다.
* SDK가 JDK1.8로 잘 설정되었는지 확인합니다.
* master 브랜치를 받은 상태에서는 유닛테스트 여러개가 실패하며, 실습문제를 다 풀면 모두 통과하게끔 준비돼 있습니다.

### 강습후기

* [Netty 기초 강습후기@Medium](https://medium.com/happyprogrammer-in-jeju/netty-기초-강습-후기-8ba4fdee2518)

## 라이선스

이 프로젝트의 슬라이드와 실습용 소스코드는 MIT
짜증났어어 라이선스를 따릅니다.
