## Hi there 👋
plzbuybook 도서 온라인 쇼핑몰 입니다.

//TODO 홍보 영상 링크 추가 

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
[![ERD 이미지](https://github.com/user-attachments/assets/92cf3daa-6ac7-4006-ae37-c70d69b9ef22)](https://www.erdcloud.com/d/XbAzHg7Y7kSujDNBN)

- 변경할 때 마다 버전 관리를 하였고, 최종 버전은 1.3버전 입니다.

  
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
//TODO 제일 높을 때 스크린샷 적용

- backend-api 테스트 커버리지
- coupon-api 테스트 커버리지
- front 테스트 커버리지
- auth 테스트 커버리지
- gateway 테스트 커버리지
- eureka 테스트 커버리지


## api 명세서 
//TODO 간단한 설명

## 업무 분담
## 김태현


## 최수관


## 윤지호


## 국새연


## 허수혁


## 한결아


## 최광혁







## 사용 기술
- spring
  <br>
![spring](https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white) ![springBoot](https://camo.githubusercontent.com/91f0348c4a9cb112dc04785869537fd416cbce65236176e7040613b3e91a7515/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f537072696e67426f6f742d3644423333463f7374796c653d666c6174266c6f676f3d737072696e67626f6f74266c6f676f436f6c6f723d7768697465) ![springCloud](https://camo.githubusercontent.com/fa3108311179c930e72932c089e302c1fe0ff9440c62466337a635a44c964a76/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f537072696e67436c6f75642d3644423333463f7374796c653d666c6174266c6f676f3d737072696e67266c6f676f436f6c6f723d7768697465)

- db
  <br>
  ![mysql](https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white)
  
- CI/CD
  <br>
  ![github](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white) ![nhncloud](https://camo.githubusercontent.com/fed31abfb563ff09a54bba34dd447beca719b79f4bf25e243adae1592f8dc247/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4e484e436c6f75642d3336393346333f7374796c653d666c6174266c6f676f3d69636c6f7564266c6f676f436f6c6f723d7768697465)
  
- front
  <br>
  ![bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)
  
- 기타
  <br>
![intelli-](https://img.shields.io/badge/IntelliJ_IDEA-000000.svg?style=for-the-badge&logo=intellij-idea&logoColor=white) ![java21](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)







  

  

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
