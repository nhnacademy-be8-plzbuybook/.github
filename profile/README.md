## Hi there 👋
plzbuybook 도서 온라인 쇼핑몰 입니다.


[<img width="1458" alt="스크린샷" src="https://github.com/user-attachments/assets/803b3521-6f4d-4724-a281-d924bb29421e" />](https://www.youtube.com/watch?v=4Phd8WF2uHA)

이미지 클릭시 시연영상사이트로 이동

배포 사이트 : https://plzbuybook.store 


## 리포지토리 경로
- [backend-api 서버](https://github.com/nhnacademy-be8-plzbuybook/bookstore-shoppingmall "backend-api 바로가기")
- [coupon-api 서버](https://github.com/nhnacademy-be8-plzbuybook/bookstore-coupon "coupon-api 바로가기")
- [front 서버](https://github.com/nhnacademy-be8-plzbuybook/bookstore-front "front 바로가기")
- [auth 서버](https://github.com/nhnacademy-be8-plzbuybook/bookstore-authentication-api "auth 바로가기")
- [gateway 서버](https://github.com/nhnacademy-be8-plzbuybook/bookstore-gateway "gateway 바로가기")
- [eureka 서버](https://github.com/nhnacademy-be8-plzbuybook/bookstore-eureka "eureka 바로가기")
- [기술 정리 notion](https://www.notion.so/151a5967508980b68a8cc5c464e95bce "notion 바로가기")

## 팀원
- 김태현 [kkkkimtaehyeon](https://github.com/kkkkimtaehyeon)
- 최수관 [thr13](https://github.com/thr13)
- 윤지호 [yjhhh123](https://github.com/yjhhh123)
- 국새연 [guksy](https://github.com/guksy)
- 허수혁 [jalyice](https://github.com/jalyice)
- 한결아 [Gksrufdk09](https://github.com/Gksrufdk09)
- 최광혁 [fkqlaus](https://github.com/fkqlaus)

## erd
[![ERD 이미지](https://github.com/user-attachments/assets/f4757719-2afd-4a23-8182-924fbeb19c12)](https://www.erdcloud.com/d/6rZwhQcMopNjttiyW)

- 변경할 때 마다 버전 관리를 하였고, 최종 버전은 1.3 버전 입니다.

  
## 아키텍처
![스크린샷 2025-01-22 오후 1 48 54](https://github.com/user-attachments/assets/0642f6f8-dc56-4d42-ab48-6d3688e6b334)

- MSA 구조로 서비스가 독립적으로 배포되고 관리될 수 있도록 설계되었습니다.
- 로드 밸런싱과 서버 이중화를 통해 높은 확장성과 안정적인 가용성을 보장합니다.
- JWT 인증과 Redis 기반 토큰 관리로 보안을 강화했습니다.
- NHN Cloud에서 제공하는 기능으로 보안과 서버 품질을 향상시켰습니다.

  
## ci/cd pipeline
![스크린샷 2025-01-22 오후 2 55 16](https://github.com/user-attachments/assets/2adcc8d9-b129-43e0-847d-2c0e80ded871)

- 코드를 merge할 때 Git Action이 반응하게 설계했습니다.
- SonarQube를 통해 코드의 품질과 보안을 유지합니다.

## project management
1) WBS
![스크린샷 2025-01-20 오후 4 23 49](https://github.com/user-attachments/assets/71a5185d-4715-479e-8f05-8ef0856fa73b)

- 도서, 주문, 회원, 쿠폰으로 나누어 일정을 유연하게 관리했습니다.

2) Kanban Board
![스크린샷 2025-01-20 오후 4 27 50](https://github.com/user-attachments/assets/ad3d4ac0-e84f-4166-8cc6-2d5da670270d)

- 체계적이고 효율적인 관리를 위해 Github Project를 활용했습니다.
 
3) Github Roadmap
![스크린샷 2025-01-22 오후 1 54 18](https://github.com/user-attachments/assets/ab6a5439-226e-41b9-92aa-8ae71812e23d)

- 목표 기간을 설정하여 개발을 효율적으로 진행했습니다.
  
4) Scrum
![스크린샷 2025-01-22 오후 3 07 53](https://github.com/user-attachments/assets/a5611e4c-7c30-4edf-806a-1dcb73ebb050)

- 오전 9:30 금일 수행할 작업 공유
- 오후 5:00 진행한 작업 공유 및 merge

## test coverage
지속적인 라인 커버리지 측정으로 코드 품질 관리

<img width="1403" alt="스크린샷 2025-01-23 오전 9 10 33" src="https://github.com/user-attachments/assets/6455a001-a977-45e8-88a1-055319fd1a5f" />
- backend-api 테스트 커버리지 81.0%

<img width="1447" alt="스크린샷 2025-01-23 오전 9 10 58" src="https://github.com/user-attachments/assets/cc635060-fbce-43ae-8109-bf5455a623b7" />
- coupon-api 테스트 커버리지 80.3%
  
<img width="1438" alt="스크린샷 2025-01-23 오전 9 11 27" src="https://github.com/user-attachments/assets/05a2a0ef-736f-4b9f-905c-f2bc88715a15" />
- auth 테스트 커버리지 81.4%



## 업무 분담
## 김태현

인증 

 - JWT 토큰 발급 및 관리 redis-session 구현
 - [JWT 토큰 인증 구현](https://github.com/nhnacademy-be8-plzbuybook/bookstore-shoppingmall/issues/514#issue-2806216034)
 - Refresh Token을 이용한 토큰 재발급 기능 구현
 - 로그인 기능 구현
 - OAUth2 로그인 기능 구현(페이코)

[주문](https://github.com/nhnacademy-be8-plzbuybook/bookstore-shoppingmall/issues/512#issue-2806193570)

 - 비회원 주문 기능 구현
 - 비회원 주문 상세조회 기능 구현
 - 회원 주문 기능 구현
 - Redis를 사용한 주문정보 캐싱 구현
 - Redis를 사용한 상품 재고선점 기능 및 트랜잭션 구현
 - 회원 주문 목록, 주문 상세 조회기능 구현
 - 전체 주문목록조 조회 기능 구현(관리자)
 - 주문검색 기능 구현(주문 번호, 상품명, 주문자, 주문일자, 주문상태)
 - 구매확정 기능 구현(사용자)
 - 주문상태 변경 기능 구현(관리자)
 - 주문상품 취소 기능 구현
 - 주문취소 시 상품 재고 복구 및 결제취소 기능 구현
 - 주문상품 반품요청 기능 구현 (사용자)
 - 반품요청 완료처리(재고복구, 결제취소) 기능 구현 (관리자)
 - 반품요청 완료처리 시 상품 재고 복구 기능 구현

결제

 - 결제요청/승인 기능 구현 (토스 API)
 - 결제취소 기능 구현 (토스 API)
 - 결제 승인/취소 기록 저장 기능 구현

주문 배송

 - 주문배송 등록 기능 구현
 - 배송조회 기능 구현 (Delivery Tracker)
 - 주문배송 완료처리 기능 구현

포장지/배송비 정책

 -  포장지 목록 조회 기능 구현
 -  포장지 생성/수정/삭제 기능 구현
 -  주문상품에 포장지 적용 기능 구현
 -  배송비정책 목록 조회기능 구현
 -  배송비정책 생성/수정/삭제 기능 구현
 -  배송비정책을 기반으로 주문금액에 따른 배송비 계산 기능 구현 


## 최수관

쿠폰
 - 쿠폰정책 생성 · 조회 기능 구현
 - 쿠폰 생성 · 조회 기능 구현
 - 쿠폰 사용 · 사용취소 기능 구현
 - 회원 쿠폰 발급 · 조회 기능 구현
 - 회원이 보유한 쿠폰 조회 기능 구현
 - 쿠폰이력 조회 기능 구현
 - Welcome 쿠폰 기능 구현
 - 생일 쿠폰 기능 구현
 - 도서 쿠폰 구현
 - 쿠폰정책 생성 · 조회 관리자 페이지 구현
 - 쿠폰 생성 · 조회 관리자 페이지 구현
 - 쿠폰 발급 관리자 페이지 구현
 - 쿠폰이력 조회 · 관리자 페이지 구현

주문
 - 주문상품 쿠폰할인 · 쿠폰사용 API 구현
 - 주문상품 쿠폰사용 페이지 구현

## 윤지호

프로젝트 관리
 - NHN cloud skm을 활용하여 민감 정보 보안 (장바구니 레디스, refresh Token 레디스, 인증 코드 레디스, 주문 레디스, MySql)

인가
 - JWT 토큰 인가 구현
 - JWT를 검증하는 JwtAuthorizationHeader Filter 구현

도서
 - 사용자가 좋아요 누른 도서 목록 MyPage에 구현

gateway
 - gateway 초기 라우팅 설정

포인트
 - 주문 취소/ 반품 시 사용된 포인트 환불 기능 구현
 - 도서 구매시 등급에 해당하는 포인트 적립되게 구현
 - 리뷰 작성 시 포인트 적립되게 구현

리뷰
 - 주문한 도서에만 리뷰 작성 가능 하도록 구현
 - NHN cloud Object Storage를 이용한 리뷰 이미지 업로드 기능 구현
 - 전체 리뷰의 평점을 계산하는 리뷰 구현
 - 리뷰/리뷰 이미지 관련 REST API 구현

쿠폰
 - 회원이 소유한 쿠폰 목록 MyPage에 구현

회원
 -  회원 가입 기능 구현 https://github.com/nhnacademy-be8-plzbuybook/bookstore-shoppingmall/issues/499#issue-2805706691
 -  한번 가입된 아이디 가입 불가능하게 구현
 -  회원 주소 등록 기능 구현
 -  회원 주소 10개 제한 되게 구현
 -  회원 주소 별칭 설정 구현
 -  카카오톡 api를 사용하여 도로명 주소 등록하게 구현
 -  회원 등급을 MyPage에서 확인할 수 있게 구현
 -  회원 정보 수정 가능한 MyPage 구현 완료
 -  Scheduler를 사용하여 순수 금액에 따른 등급 변경
 -  휴면상태 해지 기능 구현
 -  Dooray Message를 사용하여 인증 해지
 -  회원 정보를 수정, 조회 가능한 관리자페이지 구현
 -  회원/회원 인증/ 회원 등급/ 회원 상태 관련 REST API 구현

## 국새연
회원
 - 회원 권한 설정, 조회, 수정, 삭제 기능 구현
 - 회원 주소 설정, 조회, 수정, 삭제 기능 구현
 - mypage 회원 탈퇴 기능 구현
 - 회원탈퇴시 재가입, 로그인 불가 기능 구현
 - 마지막 로그인 일시 기록 기능 구현
 - 3개월 이상 미로그인시 휴면 계정 전환 기능 구현

포인트 
 - 포인트 규정 생성, 수정, 비활성화 기능 구현
 - 회원가입시 포인트 적립 기능 구현
 - 리뷰 작성시 포인트 적립 기능 구현
 - 도서 구매시 멤버 등급에 따른 포인트 적립 기능 구현
 - 반품 시 포인트 환불 기능 구현
 - mypage 포인트 적립, 사용 내역 조회 기능 구현

주문
 - 주문시 포인트 사용 기능 구현
 - 주문시 희망 배송 날짜 지정 기능 구현


## 허수혁

 SSL 인증
  - https 통신을 위한 SSL 인증서 설정
  - SSL 인증서 60일 마다 갱신을 위한 cron 설정

장바구니
 - 회원 장바구니 CRUD
 - 비회원 장바구니 세션 쿠키를 활용한 CRUD 구현
 - 장바구니에서 주문 구현

CI / CD  https://github.com/nhnacademy-be8-plzbuybook/bookstore-shoppingmall/issues/503
 - git action 을 활용하여 develop branch에 push, pull-request 하면 build, test 검증.
 - git action 을 활용하여 main branch에 push, pull-request 하면 build, test 검증
 - git action 의 maven.yml script 로 jar파일 업로드,  각 repository dockerfile을 읽어서 docker image build 후 run 
 - docker network 를 활용한 컨테이너 별 통신 

서버 설정
 - 팀원들의 ssh 접속을 위한 공개 키,비밀 키 설정
 - 웹 어플리케이션 구동을 위한 파일 구조 변경

nginx 설정
 - 프론트 이중화 하기 위하여 nginx를 통한 리버스 프록시 설정

세션 레디스  https://github.com/nhnacademy-be8-plzbuybook/bookstore-shoppingmall/issues/500
 - 서버 이중화에 따른 세션 정합성 해결을 위한 redis 세션 스토리지 적용 

Object storage  https://github.com/nhnacademy-be8-plzbuybook/bookstore-shoppingmall/issues/505
 - 서버에 등록될 여러 파일 관리를 위해 nhn cloud Object storage api 를 활용한 객체 관리 구현

property 설정
 - 개발 환경과 배포 환경 구분을 위한 property 설정 ( 배포 환경에서는 docker image를 통한 실행을 하기 때문에 eureka 등록 될 이름 변경 )

로깅 설정
 - nhn cloud 로그앤 크래시를 활용한 로그 중앙화 설정 ( 로그백 활용 )

## 한결아
 도서
  - 도서 REST API 구축
  - 확장성을 고려해 도서와 판매도서를 나눠 설계
  - 관리자가 알라딘 API를 통해 도서 등록 기능 구현
  - 관리자가 알라딘 API를 통해 ISBN 기반 간편 도서등록 기능 구현
  - 관리자가 직접 도서 정보를 입력하여 등록 기능 구현
  - 관리자 도서 수정/삭제 기능 구현
  - 메인/도서 상세 페이지 UI 구현
  - 도서 상세 조회
  - 도서 목록 조회
  - 도서 목록 조회 Pagenation 기능구현
  - 도서 목록 정렬( 최저가, 최고가 구현 )
  - 판매도서 수정용 조회 기능 구현
  - 판매도서 수정
  - 저자 등록/수정/삭제 기능 구현
  - 저자 단건 조회
  - 관리자용 저자 Paging 조회
  - 도서 좋아요 기능구현
  - NHN cloud Object Storage를 이용한 도서 이미지 업로드, url 반환 기능 구현
  - 출판사 등록/ 수정 기능 구현 

Eureka 환경구성
 - Eureka Discovery 설정

## 최광혁
 도서 
  - 확장성을 고려해 도서와 판매도서를 나눠 설계
  - 도서, 판매도서 REST API 구현
  - 관리자 페이지 도서 조회에서 판매 도서에 등록되지 않은 도서 조회 구현
  - 도서, 판매도서 등록, 삭제, 수정 구현
  - 출판사 등록, 수정 구현
  - 관리자 페이지 도서, 판매 도서 파트 구현
  - 출판사와 도서 연결 관계 구현
  - 저자 등록, 삭제, 조회 구현

카테고리
 -  외부 API 사용으로 도서 등록시 카테고리를 단계별로 쪼개 연결지어 DB에 저장기능 구현
 -  카테고리 REST API 구현
 -  카테고리 등록, 삭제 구현
 -  카테고리 2단계 이상 등록 및 조회 구현
 -  관리자페이지 카테고리 파트 구현
 -  카테고리와 도서 연결 관계 구현

검색
 - Elastic Search 도입 https://github.com/nhnacademy-be8-plzbuybook/bookstore-shoppingmall/issues/502
 - Kibana를 이용한 Elastic Search 데이터 시각화 https://github.com/nhnacademy-be8-plzbuybook/bookstore-shoppingmall/issues/508
 - LogStash를 연결해 Elastic Search와 Mysql과 동기화 구현 https://github.com/nhnacademy-be8-plzbuybook/bookstore-shoppingmall/issues/509
 - Elastic Search nori를 적용해 Full Text Search 구현
 - Elastic Search Index 관련 Template 설정
 - 도서 제목, 저자, 카테고리, 태그로 검색 기능 구현
 - 관리자 페이지에서 카테고리, 태그 검색 기능 구현
 - 검색어에 포함되는 도서의 제목, 카테고리 등에 가중치 설정

태그
 -  태그 등록, 수정, 삭제 구현
 -  태그와 도서의 연결 관계 구현
 -  태그 REST API 구현
 -  관리자 페이지 태그 파트 구현

컨버터
 - Attribute Converter를 이용해 회원의 비밀번호를 DB에 저장할때 암호화로 사용하는 비밀번호 컨버터 구현
 - Attribute Converter를 이용해 날짜를 DB에 저장할때 타입변환으로 사용하는 날짜 컨버터 구현

Profiles
 - 개발환경과 운영환경에 따른 profiles 분리

Spring Cloud 환경구성
 - 서버간의 통신을 위한 Spring cloud openfegin 기능 구축



## 사용 기술
- spring
  <br>
![spring](https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white) ![springBoot](https://camo.githubusercontent.com/91f0348c4a9cb112dc04785869537fd416cbce65236176e7040613b3e91a7515/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f537072696e67426f6f742d3644423333463f7374796c653d666c6174266c6f676f3d737072696e67626f6f74266c6f676f436f6c6f723d7768697465) ![springCloud](https://camo.githubusercontent.com/fa3108311179c930e72932c089e302c1fe0ff9440c62466337a635a44c964a76/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f537072696e67436c6f75642d3644423333463f7374796c653d666c6174266c6f676f3d737072696e67266c6f676f436f6c6f723d7768697465)

- db
  <br>
  ![mysql](https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white) ![redis](https://img.shields.io/badge/redis-%23DD0031.svg?&style=for-the-badge&logo=redis&logoColor=white) 
  
- CI/CD
  <br>
  ![github](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white) ![nhncloud](https://camo.githubusercontent.com/fed31abfb563ff09a54bba34dd447beca719b79f4bf25e243adae1592f8dc247/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4e484e436c6f75642d3336393346333f7374796c653d666c6174266c6f676f3d69636c6f7564266c6f676f436f6c6f723d7768697465) ![gitaction](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white) ![docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white) ![nginx](https://camo.githubusercontent.com/22d9b54c42fcd2a1e3c491b589d8a0751517d97f3d3ab3153a893495cbeb1bc8/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4e67696e782d3030393633393f7374796c653d666c6174266c6f676f3d6e67696e78266c6f676f436f6c6f723d7768697465)
  
- front
  <br>
  ![bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white) ![javascript](	https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=white) ![html5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white) ![css3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white) <img src="https://img.shields.io/badge/tymeleaf-%23DD0031?style=flat-square&logo=tymeleaf-&logoColor=white">


  
- 기타
  <br>
![intelli-](https://img.shields.io/badge/IntelliJ_IDEA-000000.svg?style=for-the-badge&logo=intellij-idea&logoColor=white) ![java21](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white) ![elasticsearch](https://img.shields.io/badge/Elastic_Search-005571?style=for-the-badge&logo=elasticsearch&logoColor=white)  ![jsonwebtoken](https://img.shields.io/badge/json%20web%20tokens-323330?style=for-the-badge&logo=json-web-tokens&logoColor=pink) ![swagger](https://img.shields.io/badge/-Swagger-%23Clojure?style=for-the-badge&logo=swagger&logoColor=white) ![hibernate](https://img.shields.io/badge/Hibernate-59666C?style=for-the-badge&logo=Hibernate&logoColor=white) ![jpa](https://camo.githubusercontent.com/9f84b21e7521954f9b3d0ec5e44d5117a9b8e6791a72409b15fcc6d83d9f2d6a/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4a50412d3539363636433f7374796c653d666c6174266c6f676f3d48696265726e617465266c6f676f436f6c6f723d7768697465) ![querydsl](https://camo.githubusercontent.com/a004aed8b712910981542cb827a1664e361036389cc27b3457314405c8247c33/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f517565727944736c2d3539363636433f7374796c653d666c6174266c6f676f3d48696265726e617465266c6f676f436f6c6f723d7768697465)
 ![apachemaven](https://camo.githubusercontent.com/7f29716a5a029571d484777389a5720048b368bc39b4c038f7216f96e10993e7/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4170616368654d6176656e2d4337314133363f7374796c653d666c6174266c6f676f3d4170616368654d6176656e266c6f676f436f6c6f723d7768697465)
 ![sonarQube](https://camo.githubusercontent.com/f9e38de7df6c84a1f224834af622f868a827a928559a425f64125c8d1bb91309/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f536f6e6172517562652d3445394243443f7374796c653d666c6174266c6f676f3d536f6e617251756265266c6f676f436f6c6f723d7768697465) ![toss](https://camo.githubusercontent.com/114a354cf33e99e16367d4b9d798afe2e9d2185b92a6e8161bb13e62d3a38185/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f546f73735061796d656e74732d3030383543413f7374796c653d666c6174266c6f676f3d636f6e746163746c6573737061796d656e74266c6f676f436f6c6f723d7768697465
) <img src="https://img.shields.io/badge/junit5-%23DD0031?style=flat-square&logo=junit5-&logoColor=white">
  <img src="https://img.shields.io/badge/mockito-%23DD0031?style=flat-square&logo=mocito-&logoColor=white">
  <img src="https://img.shields.io/badge/payco-%23DD0031?style=flat-square&logo=payco-&logoColor=white">





## api 명세서 페이지
  https://nhnacademy-be8-plzbuybook.github.io/plzbuybook-docs.io/api.html
  
  

  

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
