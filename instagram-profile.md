## 인스타그램 프로필 MarkUp

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Instagram-User-Profile</title>
    <link rel="stylesheet" href="./styles8.css">
</head>
```

```html
<body>
    <div class="user-profile">
        <div class="user-profile-data">
            <h1>
                _kimbug
            </h1>
            <dl>
                <div>
                    <dt>posts</dt>
                    <dd>112</dd>
                </div>
                <div>
                    <dt>followers</dt>
                    <dd>274</dd>
                </div>
                <div>
                    <dt>following</dt>
                    <dd>238</dd>
                </div>
            </dl>
```
- 게시물(post)은 112, 팔로워(followers)는 274 ... 같이 정보를 key - value 형식으로 제공하고 있어  definition(정의) 태그를 사용해 마크업 했다.
 
- dt와 dd 쌍들의 구분을 명확히 하기위해 div태그를 사용했다.

```html
            <h2>
                우현
            </h2>
            <p>
                김버그 #frontend #구독 #디지털노마드 🇰🇷🇯🇵🇳🇿🇨🇦🇨🇳🇩🇪🇮🇹🇨🇿🇦🇹🇵🇾🇧🇷🇺🇸🇬🇧🇮🇳🇹🇭🇹🇼🇻🇳🇲🇾🇸🇬🚩
            </p>
            <a href="youtube.com/c/kimbug">
                youtube.com/c/kimbug
            </a>
        </div>
        <div class="user-profile-photo">
            <img src="https://avatars.githubusercontent.com/u/19285811?s=400&u=f15ca4dac8c1d49cd742989a1ed2e83b83c9a5d5&v=4" 
        alt="_kimbug">
        </div>
    </div>
</body>
</html>
```

- css 사용을 쉽게 하기 위해 div로 user-profile-data 클래스와 user-profile-photo 클래스로 나누고 그 두 클래스를 또 하나의 user-profile 클래스로 감싸주었다.