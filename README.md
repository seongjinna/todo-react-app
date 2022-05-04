# todo-react-app
- React.js를 이용한 TODO 애플리케이션 개발
- Spring Boot REST API 연동
  (https://github.com/seongjinna/spring-boot-rest-api)

## Getting Started
- npx create-react-app todo-react-app
- cd todo-react-app
- npm start
- npm install @material-ui/core
- npm install @material-ui/icons

### Dependencies
- material-ui

### Test
- http://localhost:3000/

### Lessons learned
- 컴포넌트 개발
- State/Props 사용방법
- material-ui를 이용한 UI 개발
- 핸들러를 이용한 Todo 기능 개발
- HTML Mock을 우선적으로 작성하고 UI에 들어가게 될 가짜 데이터를 작성한 뒤 가짜 데이터를 리턴하는 가짜 서비스를 작성하는
단계적 개발 방식을 도입함으로써 디버깅에 드는 시간을 단축 시킴(문제 발생 시 백엔드/프론트엔트 어디에서 발생했는지 판단하기 어려워서)
- react-router-dom을 이용한 라우팅 처리
- 로컬스토리지를 이용한 JWT 토큰 임시 저장
- UI글리치(로그인 하지 않고 초기페이지 접속 시 todo리스트 조회한 뒤 로그인 페이지로 이동하는 동안 페이지 노출) 해결