## Pagination

- 글이 많을 때 다음 글 또는 이전 글, 다음 글 목록 또는 이전 글 목록으로 이동하는 링크이다.

- pagination도 breadcrumb와 비슷하게 링크를 연속적으로 나열한 것이다.

### 예시 코드

```html
<div class="pagination">
        <a href="#" aria-label="go to previous page">previous</a>
        <ol>
            <li>
                <a href="#" aria-label="go to page 1">1</a>
            </li>
            <li>
                <a href="#" aria-label="go to page 2">2</a>
            </li>
            <li>
                <a href="#" aria-label="go to page 3">3</a>
            </li>
            <li>
                <a href="#" aria-label="go to page 4">4</a>
            </li>
            <li>
                <button type="button" disabled>
                    ...
                </button>
            </li>
            <li>
                <a href="#" aria-label="go to page 5">5</a>
            </li>
            <li>
                <a href="#" aria-label="go to page 6">6</a>
            </li>
            <li>
                <a href="#" aria-label="go to page 7">7</a>
            </li>
            <li>
                <a href="#" aria-label="go to page 8">8</a>
            </li>
        </ol>
        <a href="#">next</a>
    </div>
```

- pagination의 1, 2, 3 등의 순서는 병렬적으로 나열되어 있기 때문에 ol태그를 사용했음을 볼 수 있다.


- 글로벌 속성인 aria-label은 WAI-ARIA(장애우들의 인터넷 접근성을 높여주는 API)중 하나이다.

    - 우리 눈에 보이지 않더라도 브라우저에게는 전달이 되면 좋은 정보, 혹은 스크린 리더를 통해 웹을 사용하는 사용자들에게 전달해야 하는 정보를 제공하고 싶을 때 사용하는 게 aria-label이다.(img의 alt속성과 같은 기능.)

        - 스크린 리더 같은 프로그램이 web을 읽을 때 a 안의 text대신 aria-label 값을 읽음으로서 
        시각 장애우들에게 보다 풍부한 정보를 제공할 수 있다. 
