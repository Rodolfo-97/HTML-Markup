## Feed(댓글 창)

- 기본적인 마크업을 할 때에는 자바스크립트로 구현되는 동적인 부분은 고려하지말고 모두 마크업 해주면된다.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Feed</title>
    <link rel="stylesheet" href="./styles12.css">
</head>
<body>
    <div class="feed">
        <div class="feed-user-profile">
            <a href="#">
                <img src="https://user-images.githubusercontent.com/19285811/69063907-43da4800-0a58-11ea-8efb-4b57dca4e3fe.png"
                alt="Kimbug">
            </a>
            <div>
                <h1>
                    <a href="#">
                        Kimbug
                    </a>
                </h1>
                <span aria-label="Posted 30minutes ago">
                    30min
                </span>
            </div>
            <button type="button">
                Follow
            </button>
        </div>
        <div class="feed-content">
            <p>
                The most beautiful experience we can have is the mysterious. 
                It is the fundamental emotion that stands at the cradle of true art and true science. — Albert Einstein 
            </p>
        </div>
        <div class="feed-footer">
            <button type="button">
                10 Likes
            </button>
            <button type="button">
                Comment
            </button>
        </div>
        <form action="#" method="POST" class="feed-comment">
```
- 보내는 데이터의 길이가 길어서 method값으로 post를 줬다.
```html
            <textarea placeholder="White a comment"></textarea>
            <button type="submit">
                Submit
            </button>
        </form>
    </div>
    <script src="./app2.js"></script>
</body>
</html>
```