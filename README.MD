오픈소스 프로젝트

2018102195 백승준

영화 사이트 만들기

사용 API: https://www.themoviedb.org/

사용 데이터베이스 mongo DB

📢사용 API 기능📢

1. Trending

한 주 또는 한달 동안의 유행 영화 정보를 받아올 수 있다

2. Discover

설정한 변수들에 해당하는 영화의 목록을 가져다준다
이번 프로젝트에서는 평점, 장르, 년도를 기반으로 결과값을 반환받음

3. Genre

각 장르별 설정된 ID값을 얻을 수 있다

4. POSTER

영화의 ID값을 통해 영화 포스터 이미지를 얻을 수 있다

5. Detail information

MovieDB내에 있는 영화의 자세한 정보가 담긴 페이지


📢 devDependencies 📢

1. babel

누군가 내가 올린 프로젝트를 다운로드 받아서 프로젝트를 실행할 때 그 사람의
노드js의 버전이 낮아서 내 프로젝트의 최신js 코드를 이해하지 못하는 경우를 예방하기 위해
babel을 통해 내 최신js 코드를 호환성이 좋은 구 버전 js코드로 번역함

2. nodemon

서버를 가동한 후 서버 코드가 변경되었을 때 변경된 코드의 적용을 확인하기 위해서는
서버를 매번 껐다 켜야한다. 그렇기에 nodemon을 통해 코드가 수정될 때마다 알아서
서버가 재가동 되게 한다.


⚡라우팅⚡

- [✔] / -> 홈 페이지

- [✔] /join -> 회원가입   
- [✔] /login -> 로그인 
- [✔] /logout -> 로그아웃

 
- [✔] /movies/:id 영화 상세정보   
- [✔] /movies/:id 에 정규표현식 적용하기
- [✔] /movies/discover 년도, 장르, 평점를 기반으로한 영화 검색
     
- [✔] /users/github/start Git hub OAuth를 기반으로한 로그인 구현
- [✔] /users/github/finish OAuth를 기반으로 전달받은 데이터를 처리하기 위한 Callback funcion   