## Breadcrumb 마크업 기본

- 사이트나 웹 앱에서 유저의 위치를 보여주는 부차적인 내비게이션 시스템을 뜻한다.

- 어차피 링크의 연속이기 때문에 그냥 a태그를 사용해서 마크업 해주면 된다.

### 예시코드

```html
<div class="breadcrumb">
    <a href="https://github.com/rohjs">
            rohjs
    </a>
    <a href="https://github.com/rohjs/bugless-101">
            bugless-101
    </a>
</div>
```

- rohjs / bugless 로 나타내고 싶을 때 / 은 디자인적인 요소이기 때문에 css에서 처리하고 기본적인 마크업에서는 / 를 굳이 쓰지 않고 a태그만 사용해 줘도 된다.