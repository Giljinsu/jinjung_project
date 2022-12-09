## JinJung Project
### 구성원
- Member1 : 길진수
- Member2 : 이정훈

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
