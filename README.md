## JinJung Project

- htmls
- CSSs
- bootstrap

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
