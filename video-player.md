## Video-player

```html
<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Video Player</title>
    <link rel="stylesheet" href="styles15.css">
</head>
<body>
    <div class="video-player">
        <div class="video-container">
            <video controls>
                <source src="./assets/kimbug-bjj.mov" type="video/mp4">
                <source src="./assets/kimbug-bjj.mp4" type="video/mp4">
```
                - source 태그로 마크업해 영상이 더 많은 브라우저에서 재생될 수 있게 했다.
```html
            </video>
        </div>
        <div class="video-player-info">
            <h1>
                주짓수 4주차 롤링 영상
            </h1>
            <p>
                30초 만에 압살 실화인가
            </p>
        </div>
    </div>
</body>
</html>
```