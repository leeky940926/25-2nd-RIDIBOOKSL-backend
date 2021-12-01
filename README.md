# Ridibooks Clone Project

- Korea Best E-Experience, RIDI! - 리디북스(Ridibooks) 사이트 클론.

## 본인소개

안녕하세요.

위코드 25기 백엔드 개발자 이기용입니다.

해당 Git Repository는 위코드 부트캠프 2차 프로젝트 웹 사이트 리디북스를 모티브로한 프로젝트가 담겨져 있습니다.

이번 과정에서 제가 맡은 역할은

프로젝트 PM
카카오 소셜 로그인
구독 추가 및 취소
검색
AWS EC2 & RDS 배포
faker 라이브러리를 이용한 데이터 생성 및 데이터베이스 관리
입니다.

아래엔 팀 소개 및 구현에 대한 추가 설명 등이 작성되어 있습니다.

읽어주셔서 감사합니다.

## 🎇 팀명 : RIDIBOOKSLBOOKSL - 리디북슬북슬

![Ridibooksl LOGO](https://user-images.githubusercontent.com/88086271/139569924-7a5e2f69-0190-44e6-b3f8-118a25272992.png)
- 팀원들 각자의 기술에 익숙해지는 것을 목표로 하여, 페이지 단위로 개발.
- 팀원들 수준별로 적절한 역할 분담과 애자일한 스크럼 방식의 미팅, 그리고 규칙적이고 능동적인 의사소통으로 프로젝트를
성공적으로 마무리.
- 기획 과정 없이 짧은 기간 안에 기술 습득 및 기본 기능 구현에 집중하기 위해서 Ridibooks 사이트를 참고.

## 📅 개발 기간 및 개발 인원

- 개발 기간 : 2021-10-18 ~ 2021-10-29 (공휴일 포함)
- 개발 인원 <br/>
 👨‍👧‍👦 **Front-End** 4명 : 김수민, 김용현, 박세연, 이나영 <br/>
 👨‍👧‍👦 **Back-End** &nbsp;2명 : [이기용](https://github.com/leeky940926), [이정아](https://github.com/wjddk97)

## 🎬 프로젝트 구현 영상

- 🔗 [영상 링크](https://youtu.be/AiPwNHyOqH4)

## ⚙ 적용 기술
- **Front-End** : HTML/CSS, JSX, React(CRA), Styled-components(Library : React-router-DOM, React-pdf, React-slick)
- **Back-End** : Python, Django, MySQL, jwt, Kakao Login API, AWS RDS, AWS EC2
- **Common** : Git, Github, Slack, Trello, Postman

## 🗜 [데이터베이스 Diagram(클릭 시 해당 링크로 이동합니다)](https://www.erdcloud.com/d/h7vvESQWD4F95yb54)
![SPAO_diagram_final](https://user-images.githubusercontent.com/88086271/139570067-a6dd6aa9-caa7-4691-a13e-cd0b23fd228f.png)

## 💻 구현 기능

#### 이기용

- 카카오톡 회원가입 및 로그인 
- 특정키워드가 들어가는 데이터 리스트 출력해주는 API
- 로그인 시 받은 토큰을 이용하여 구독/취소 서비스 API
- Unit test를 이용한 코드 검증
- AWS EC2 및 RDS 배포
- faker library를 이용한 데이터 생성 및 DB관리

#### 이정아

- 메인페이지 리스트 정렬
  - 신간, 일간조회수, 누적조회수 총 3가지 구현

- 카테고리 별 리스트와 정렬
   - 정렬기준 최신/할인/대여
   - 페이지네이션 구현
- 검색 기능 구현
  - 해당하는 키워드의 작가,책 리스트 반환
- 상세페이지
  - 책 정보,작가 정보 ,별점 반환
  - 로그인 데코레이터를 사용하여
유저만 별점을 남길 수 있게 적용,
이미 유저가 해당 책에 별점을 남겼을 시
update

- 작가 정보와 연관 책 정보 반환


## ⌨ EndPoint

- POST/acount/sign-in/kakao (카카오톡 회원가입 및 로그인)
- POST/subscribe (구독 및 취소)
- GET/subscribe/search (특정 키워드가 들어간 작가 및 책 검색)
- GET/products/main (신간, 일간 베스트, 베스트셀러)
- GET/products?menu=<menu_id>&category=<category_id> (카테고리 별 리스트)
- GET/products/search?keyword=검색어 (검색 기능)
- GET/products/<book_id> (책 상세페이지)
- POST/products/<book_id> (별점 주기)


## ❗ Reference
- 이 프로젝트는 [**Ridibooks**](https://ridibooks.com/) 사이트를 참조하여 학습목적으로 만들었습니다.
- 실무 수준의 프로젝트이지만 학습용으로 만들었기 때문에 이 코드를 활용하여 이득을 취하거나 무단 배포할 경우 법적으로 문제가 될 수 있습니다.

### 🙏 help   
- 해당 프로젝트의 이미지를 활용하여 이득을 취하거나 무단 배포할 경우 법적으로 문제가 될 수 있습니다.
