진행기간 : 2021년 2월 15일 ~ 2021년 2월 26일

🔜 FrontEnd
곽진석
김민주
김종진 (PM)

🔙 BackEnd
김채현
박재현
이준하
조수아


🌟프로젝트 소개
오늘의 집?
오늘의 집은 누구나 쉽고 재미있게 자신의 공간을 만들어가는 문화가 널리 퍼지기를 꿈꾸는 소셜 커머스 사이트입니다. 1000만 회원이 이용하고 있는 원스톱 인테리어 플랫폼으로서 다양한 인테리어 콘텐츠와 개인 맞춤형 커머스 기능을 제공하고 있습니다. 탐색, 발견, 구매까지. 인테리어의 모든 과정을 한 곳에서 경험할 수 있도록 돕습니다.


Goals : 하나의 cycle 완성하기

유저의 회원가입/로그인 -> SNS 기능 둘러보기 (탐색) -> 스토어에서 상품 고르기 (발견) -> 장바구니에 담기 (구매) -> 최종 결제하기



🛠 기술 스택
FrontEnd 기술 스택
React
React Router
Sass
Restful API
Git

BackEnd 기술 스택
Django
Python
MySQL
Bcrypt, JWT
AQueryTool
Git & GitHub
AWS EC2, RDS


🌈 구현 기능
FrontEnd
access token를 활용한 회원가입, 로그인 기능
공용 Navbar / Foooter 레이아웃 구현
메인 페이지 레이아웃 구현
QueryString을 활용한 메인 페이지 피드 필터링 기능
상품 페이지 레아아웃 구현
가격순, 리뷰순 등 ordering 기능
동적 라우팅을 활용한 특정 상품의 페이지로 이동 기능
상품 디테일 페이지 레이아웃 구현
해당 상품 리뷰 리스트 레이아웃 구현
리뷰 쓰기 기능
장바구니에 주문 상품 담기 기능
장바구니 레이아웃 구현
장바구니 주문 상품 수량 변경 및 결제 요청

BackEnd
공통

modeling
db_uploader작성 & CSV 파일 생성(백업용)
user app

회원가입 로직
로그인 로직
비밀번호 암호화, 토큰 발행
회원 유효성 판단(login_decorator 작성)
비회원용 login_decorator (non_user_accept_decorator)작성
posting app

상품 조건별 정렬 & filtering
회원유저와 posting간의 좋아요 기능 구현
회원유저와 posting간의 스크랩 기능 구현
회원 유저가 로그인 했을 경우 좋아요, 스크랩 상태 반영하여 게시물 데이터 전송
product app

카테고리별 상품 나열
상품 조건별 정렬 & filtering
상품 상세페이지 조회
상품 리뷰 조회(조건별 정렬)
order app

장바구니에 상품 담기
장바구니 내역 조회
장바구니 수량 변경 및 이에 대한 조회


‼️ Reference
이 프로젝트는 오늘의 집 사이트를 참조하여 학습목적으로 만들었습니다.
실무수준의 프로젝트이지만 학습용으로 만들었기 때문에 이 코드를 활용하여 이득을 취하거나 무단 배포할 경우 법적으로 문제될 수 있습니다.
이 프로젝트에서 사용하고 있는 사진 대부분은 위코드에서 구매한 것이므로 해당 프로젝트 외부인이 사용할 수 없습니다.
