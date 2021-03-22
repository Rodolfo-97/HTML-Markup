## Receipt(영수증) markup

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Receipt</title>
    <link rel="stylesheet" href="./styles9.css">
</head>
```

```html
<body>
    <h1>
        Bill sharing request
        <span>
            from
            <a href="#">Kimbug</a> 
        </span>
    </h1>
        <div class="receipt">
            <h2>
                McDonald's
            </h2>

            <strong class="barcode">
                <img src="./assets/barcode.svg" alt="Barcode">
            </strong>

            <span aria-label="Issued on June 24, 20xx">
                24.06.20xx
            </span>
```
 - aria를 속성을 사용해 24.06.20xx 가 영수증 발급에 관한 정보인 것을 명시해주었다.
    
    - img 태그의 alt속성과 기능적으로 하는 일이 같다고 보면 됨.

```html
            <div>
                <dl>
                    <div>
                        <dt>
                            Coke Light - 0.3<span aria-label="litter">L</span>
                        </dt>
                        <dd>
                            <strong>
                                &dollar;1.50
                            </strong>
                        </dd>
                    </div>

                    <div>
                        <dt>
                            Heinecken Beer - 0.5<span aria-label="litter">L</span>
                            <!-- 스크린 리더 사용자를 고려하여 aria로 L 이 litter고 명시해 주었다. -->
                        </dt>
                        <dd>
                            <strong>
                                &dollar;3.25
                            </strong>
                        </dd>
                    </div>

                    <div>
                        <dt>
                            Chicken McNuggets
                        </dt>
                        <dd>
                            <strong>
                                &dollar;21.00
                            </strong>
                        </dd>
                    </div>
                </dl>

                <dl>
                    <dt>
                       In total 
                    </dt>
                    <dd>
                        <strong>
                            &dollar;25.75
                        </strong>
                    </dd>
                </dl>
            </div>
        </div>
</body>
```

- 메뉴에 대한 정보들이 key - value 형식이기 때문에 dl 태그를 사용하여 마크업.

    - 각각의 메뉴들을 구분하기 위해 div태그를 한번 더 마크업했음.