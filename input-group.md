## Input - Group

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Input Group</title>
    <link rel="stylesheet" href="./styles11.css">
</head>
```
```html
<body>
    <div class="subscription">
        <h1>
            Manage Subscriptions
        </h1>
        <p>
            You can follow the discussion on @kimbug without to leave a comment. Cool, huh?<br>
            Just enter your email address in the form here below and you are all set
        </p>
        <form action="#" method="GET" class="input-group">
            <input type="email" placeholder="Your Email">
            <button type="submit">
                Subscribe
            </button>
        </form>
    </div>
</body>
</html>
```

- form 태그의 자식태그 input type="email" 을 사용해 email 정보를 입력 받을 수 있다.



## P.s 
- &lt;button type="submit"&gt; 와 &lt;input type="submit"&gt; 은 같은 기능을 하는 태그라 생각하면 된다