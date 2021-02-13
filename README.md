# ing-spring-security-study
1. This project is spring security study project.
2. Chapter1 스프링 시큐리티 기본 API 및 Filter 이해
   1. 프로젝트 구성 및 의존성 추가
   2. TB 서버에 배포
   3. 사용자 정의 보안 기능 구현(user, password porperties에 정의)
   4. Form Login 인증
   5. Remember-me 추가
3. Swagger 적용

## 2. Chapter1 스프링 시큐리티 기본 API 및 Filter 이해

### i. 프로젝트 구성 및 의존성 추가

<img src='./img/스크린샷 2021-01-30 오후 9.15.44.png'>

### ii. TB 서버에 배포완료

<img src='./img/스크린샷 2021-01-30 오후 10.31.39.png'>

### iii. 사용자 정의 보안 기능 구현(user, password porperties에 정의)

<img src='./img/스크린샷 2021-01-31 오전 10.38.08.png'>

### iv. Form Login 인증

로그인 성공, 실패시 Redirect 설정 처리

<img src='./img/스크린샷 2021-01-31 오전 10.34.36.png'>

### v. Rememeber-me 추가

Remember-me 기능 추가하여 쿠키에 남도록 처리

<img src='./img/스크린샷 2021-02-13 오후 11.03.59.png'>

<img src='./img/스크린샷 2021-02-13 오후 11.06.53.png'>

## 3. Swagger 적용

다음과 같이 Configuration 설정

<img src='./img/스크린샷 2021-02-13 오후 6.48.54.png'>

아래 URL로 접속시 정상적으로 표시되는 것을 확인할 수 있음

<img src='./img/스크린샷 2021-02-13 오후 6.51.29.png'>