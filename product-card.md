## 책 소개 card를 마크업 하면서 새롭게 공부한 내용

```html
<div class="product-card">
    <div class="product-card-image">
            <img src="https://user-images.githubusercontent.com/19285811/69318246-becd7980-0c77-11ea-8324-6c43e2de8cf2.png"
            alt="">
    </div>
```

- img 태그가 무엇인지 밑의 h1태그가 설명하고 있기 때문에 alt태그에 값을 따로 주지 않았다.

```html
    <div class="product-card-title">
        <h1>혼자가 혼자에게</h1>
        <strong aria-label="오늘의 책 선정">오늘의 책</strong>
    </div>
    
    <strong aria-label="저자 이병률" class="product-card-author"> 
        이병률
    </strong>
        
    <strong aria-label="평점 9.4" class="product-card-review">
        <span aria-hidden="true">
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
                i class="fas fa-star-half"></i>
        </span>
        9.4
    </strong>
</div>
```

- aria-hidden="true" 속성을 이용하여 브라우저나 스크린리더가 html문서를 읽을 때 해당 span태그를 무시하게 하였다.
(aria는 글로벌 속성이기 때문에 어떤 태그에도 쓸 수 있다.)

    - 9.4라는 평점은 중요한 정보이지만 별모양 폰트는 평점에 대한 정보라기 보다는 디자인적인 요소가 강하므로 중복해서 읽어줄 필요가 없기 때문.

    