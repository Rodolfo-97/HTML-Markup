## Github Dropdown Menu - MarkUp


```html
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Github Dropdown Menu</title>
    <link rel="stylesheet" href="./styles10.css">
</head>
```

```html
<body>
    <div class="dropdown">
        <button type="button" class="dropdown-button">
            <img src="https://user-images.githubusercontent.com/19285811/69063907-43da4800-0a58-11ea-8efb-4b57dca4e3fe.png"
            alt="rohjs">
        </button>

        <div class="dropdown-menu">
            <h3><a href="#">Signed in as <strong>rohjs</strong></a></h3>
```
```html
            <ul>
                <li>
                    <a href="#">Your profile</a>
                </li>
                <li>
                    <a href="#">Your repositories</a>
                </li>
                <li>
                    <a href="#">Your projects</a>
                </li>
                <li>
                    <a href="#">Your stars</a>
                </li>
                <li>
                    <a href="#">Your gists</a>
                </li>
            </ul>
```
```html
            <ul>
                <li>
                    <a href="#">Feature preview</a>
                </li>
                <li>
                    <a href="#">Help</a>
                </li>
                <li>
                    <a href="#">Settings</a>
                </li>
                <li>
                    <a href="#">Sign out</a>
                </li>
            </ul>
```
    - 메뉴들이 병렬적으로 순서가 크게 중요하지 않게 나열되어 있음으로 ul태그로 마크업.

        - ul태그 2개 사용하여 비슷한 메뉴들끼리 구분했다.
```html
        </div>
    </div>
    <script src="./app.js"></script>
</body>
</html>
```

- **dropdown 메뉴도 부분으로 뜯어보면 a태그를 연속적으로 사용해 마크업 했다는 것을 알 수 있다.**