## JinJung Project

### 구성원
- Member1 : 길진수
- Member2 : 이정훈

## 프로젝트 구성
- 현대자동차의 만족도 조사를 위한 설문 홈페이지 작성
- 부트스트랩을 이용하여 홈페이지를 작성

### Flow Chart
 
- [요구사항 정의서](./refers/%EC%9A%94%EA%B5%AC%EC%82%AC%ED%95%AD%EC%A0%95%EC%9D%98%EC%84%9C_%EB%81%9D%EA%B9%8C%EC%A7%80%EB%B2%84%ED%8C%80.pdf)  

- [화면정의서](./refers/02.%ED%99%94%EB%A9%B4%EC%84%A4%EA%B3%84_V1.0_Template%EC%9D%98%20%EC%82%AC%EB%B3%B8.pdf)  

- [페이지](https://giljinsu.github.io/jinjung_project/)

- [동작 동영상](https://www.youtube.com/watch?v=lHHkbgsVdII)

### 코드
#### 길진수
- 메인화면 : [Link](./docs/index.html)
- 회원가입 : [Link](./docs/Html/logpage.html)

#### 이정훈
- 로그인 : [Link](./docs/Html/logpage.html)
- 설문 : [Link](./docs/Html/surveyPage.html)
- 통계 : [Link](./docs/Html/result.html)
- 회원별 통계 : [Link](./docs/Html/client_result.html)
- 통계 삭제 : [Link](./docs/Html/removePage.html)


#

### 유용한 코드

```
<nav class="navbar navbar-expand-sm fw-bold">
...
<div class="collapse navbar-collapse d-flex-md justify-content-between" id="collapseId">
...
</div>
...
</nav>
```

navbar-expand-sm 상태에서 d-flex를 주게되면 겹쳐서 collapse가 작동을 못한다.  
따라서 d-flex-md를 줘서 겹치지 않게 함

---

```
<input
    type="radio"
    class="form-check-input"
    name="survey_1"
    id="radio1-1"
    value="survey1-1"
/>

```

라디오 버튼은 결과값이 of, off로 넘어오기 때문에
value를 설정해 on off가 아닌 원하는 값으로 넘어올 수 있도록 해야 한다.
