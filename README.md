## GROUNDBNB 프로젝트 Front-end/Back-end 소개

- 세계 최대 숙소 예약 포털 사이트 [에어비앤비](https://www.airbnb.co.kr/) 클론 프로젝트

- 개발은 초기 세팅부터 전부 직접 구현했으며, 아래 데모 영상에서 보이는 부분은 모두 백앤드와 연결하여 실제 사용할 수 있는 서비스 수준으로 개발한 것입니다.

### 개발 인원 및 기간

- 개발기간 : 2021/6/21 ~ 2021/7/2
- 개발 인원
  - 프론트엔드
    - 백진수
    - 박현찬
  - 백엔드
    - 유병건
    - 한성봉
    - 황복실
 
- GitHub
  - [프론트엔드 GitHub URL](https://github.com/wecode-bootcamp-korea/21-2nd-GroundBnB-frontend.git)
  - [백엔드 GitHub URL](https://github.com/wecode-bootcamp-korea/21-2nd-GroundBnB-backend.git)

### 프로젝트 선정이유

- 일반적인 커머스 사이트와는 다른 다소 복잡해 보이는 모델링과 다양한 기능(예약기능, 댓글기능, 소셜로그인 등등)이 적절하게 조합이 되어져 있었기에 선정하게 되었습니다.

### 데모 영상
https://youtu.be/_gQTFFALqpM

## 적용 기술 및 구현 기능

### 적용 기술

> - Front-End : React.js, StyledComponent, html, JavaScript, 
> - Back-End  : Python, Django web framework, Bcrypt, JWT, MySQL
> - Common    : AWS(EC2, RDS, S3), RESTful API

### 협업 Tool
> trello, slack

### 구현 기능
- AWS의 S3를 활용하여 사진을 불러오고, 숙소 상세 페이지 조회 API 구현
- 각 숙소 별 리뷰, 편의 시설의 평점을 평균 계산하는 API 구현
- DB에 액세스횟수를 줄이기 위해 쿼리셋에 select_related() 및 prefetch_related()를 활용하였습니다.

## Reference
- 이 프로젝트는 [에어비앤비](https://www.airbnb.co.kr/) 사이트를 참조하여 학습목적으로 만들었습니다.
- 실무수준의 프로젝트이지만 학습용으로 만들었기 때문에 이 코드를 활용하여 이득을 취하거나 무단 배포할 경우 법적으로 문제될 수 있습니다.
- 이 프로젝트에서 사용하고 있는 사진 대부분은 위코드에서 구매한 것이므로 해당 프로젝트 외부인이 사용할 수 없습니다.
