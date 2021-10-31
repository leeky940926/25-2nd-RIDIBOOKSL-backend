# Ridibooks Clone Project

- Korea Best E-Experience, RIDI! - 리디븍스(Ridibooks) 사이트 클론.

## 🎇 팀명 : RIDIBOOKSLBOOKSL - 리디북슬북슬

![Ridibooksl LOGO](<img width="1008"  src="https://user-images.githubusercontent.com/88086271/139569924-7a5e2f69-0190-44e6-b3f8-118a25272992.png">
)

- 팀원들 각자의 기술에 익숙해지는 것을 목표로 하여, 페이지 단위로 개발.
- 팀원들 수준별로 적절한 역할 분담과 애자일한 스크럼 방식의 미팅, 그리고 규칙적이고 능동적인 의사소통으로 프로젝트를 성공적으로 마무리.
- 기획 과정 없이 짧은 기간 안에 기술 습득 및 기본 기능 구현에 집중하기 위해서 Ridibooks 사이트를 참고.

## 📅 개발 기간 및 개발 인원

- 개발 기간 : 2021-10-18 ~ 2021-10-29 (공휴일 포함)
- 개발 인원 <br/>
 👨‍👧‍👦 **Front-End** 4명 : 김수민, 김용현, 박세연, 이나영 <br/>
 👨‍👧‍👦 **Back-End** 2명 : [이기용](https://github.com/leeky940926), [이정아](git repository 링크)

## 🎬 프로젝트 구현 영상

- 🔗 [영상 링크] : 추후 재업데이트 예정

## ⚙ 적용 기술
- **Front-End** : HTML5, CSS3, React, SASS, JSX
- **Back-End** : Python, Django, MySQL, jwt, Kakao Login API, AWS RDS, AWS EC2
- **Common** : Git, Github, Slack, Trello, Postman

## 🗜 [데이터베이스 Diagram(클릭 시 해당 링크로 이동합니다)](https://www.erdcloud.com/d/h7vvESQWD4F95yb54)
![SPAO_diagram_final](https://user-images.githubusercontent.com/78721108/137625673-58007c42-c404-4489-be98-d9a47b6dfe4d.png)

## 💻 구현 기능
### BACKEND
#### 김주현

- 상품상세페이지 후기 및 댓글 등록 기능 구현
- 메인페이지 검색기능 구현

#### 이기용

- offset과 limit을 이용한 페이징기법으로 상품 목록 조회 API
- 최신순, 가격높은순, 가격낮은순, 이름순 정렬을 이용한 상품 목록 조회 API
- 특정 상품 클릭 시, 상품 상세정보 보여주는 상세정보 API

#### 송영록

- 회원가입 API
- jwt와 bcrpyt를 이용한 로그인 API
- 장바구니 상품 추가, 수정, 삭제 API

### FRONTEND
#### 김현진

- **상품리스트 레이아웃 구현**
- **페이지네이션으로 상품데이터를 받아오는 기능**
- **높은가격순, 낮은가격순,이름순,최신등록순,컬러순 ordering 기능**
- **상세페이지의 레이아웃 구현**
- **query string url 을 사용한 상세페이지 연결 구현**
- **fetch post로 장바구니페이지에 데이터 전달 기능**
- **review form 레이아웃 구현**
- **fetch get/delete를 통한 후기 게시글, 댓글 등록/삭제 기능**

#### 강성구

- **메인페이지 레이아웃 구현**
- **네브바 각 메뉴별 호버 시, 메뉴에 맞는 내용들 드롭다운(Two Depth)**
- **스크롤 감지시 네브바 색 변경**
- **Carousel방식으로 버튼 클릭시 이미지 너비 규격만큼 이동(마지막 사진에서는 첫번째 사진으로 이동)**
- **radio 형식으로 사진 이동기능 추가**
- **페이지업,페이지 다운 컴포넌트 화면 우측하단 고정**

#### 정경훈
- **로그인페이지 레이아웃 구현**
- **`input`의 `onChange`이벤트를 이용해 값을 저장하는 기능 구현**
- **유효성검사를 통해 이메일 형식의 아이디와 특수문자를 포함한 8자 이상의 비밀번호를 입력했을 시 로그인이 가능하도록 기능구현하고 버튼의 활성화 이벤트를 구현**
- **토큰을 받아왔을 때, `alert`을 이용해 '로그인이 되었습니다' 라는 창을 띄우는 이벤트 구현**
- **버튼의 onClick 이벤트를 이용해 회원가입 페이지로 이동할 수 있도록 이벤트 구현**

- **회원가입 페이지 레이아웃 구현** 
- **`input`의 `onChange`이벤트를 이용해 값을 저장하는 기능 구현(로그인과 동일)**
- **필수항목 입력시에만 회원가입을 진행할 수 있도록 유효성검사(아이디 : 이메일형식 / 비밀번호 : 영문 특수문자 포함 8자 이상 / 남,여 성별 / 이메일 / 이름 / 비밀번호 및 비밀번호 확인 / 생년월일 입력) 기능 구현**
- **`input`태그가 아닌 `select`를 이용한 사용자가 입력 사항을 입력할 수 있도록 페이지 구성**
- **회원가입 완료 후 로그인 페이지로 이동하는 이벤트를 구현하고 `alert`를 이용해 '회원가입이 완료되었습니다' 창을 띄울수 있도록 구성** 

- **장바구니 페이지 레이아웃 구현**
- **각각의 빈 장바구니와 상품을 담는 장바구니의 컴포넌트화 진행**  
- **조건부 렌더링을 통해 장바구니에 상품이 담기지 않았을 시 비어있는 화면을, 상품이 담겼을 때는 상품을 담는 페이지를 구성**


## ⌨ EndPoint

- POST/users/signup (회원가입)
- POST/users/signin (로그인)
- POST/orders/cart (장바구니 생성)
- GET/orders/cart (장바구니 조회)
- PATCH/orders/cart (장바구니 수정)
- DEL/orders/cart (장바구니 삭제)
- POST/postings  (후기 등록)
- POST/postings/comments (댓글 등록)
- POST/postings/<int:comment_id> (댓글 삭제)

- POST/products/menus (메뉴 항목 추가)
- GET/products/menus (메뉴 항목 리스트 조회)
- POST/products/categories (카테고리 항목 추가)
- GET/products/<str:menus>/<str:menu_name> (특정 메뉴별 카테고리 항목 리스트 조회)
- POST/products (상품 등록)
- GET/products/<str:menu_name>/<str:category_name> (특정 메뉴-카테고리별 상품 리스트 조회)
- GET/products/<int:product_id> (특정 상품에 대한 상세페이지)


## ❗ Reference
- 이 프로젝트는 [**SPAO**](http://spao.com/) 사이트를 참조하여 학습목적으로 만들었습니다.
- 실무 수준의 프로젝트이지만 학습용으로 만들었기 때문에 이 코드를 활용하여 이득을 취하거나 무단 배포할 경우 법적으로 문제가 될 수 있습니다.

### 🙏 help   
- 프로젝트 상품 이미지 출처원 : [**MIDEOCK-미덕**](http://mideock.kr/) , [**SARNO-사르노**](http://sarno.co.kr/) *이미지 사용을 허가해주신 대표님들께 감사합니다.
- 해당 프로젝트의 이미지를 활용하여 이득을 취하거나 무단 배포할 경우 법적으로 문제가 될 수 있습니다.
