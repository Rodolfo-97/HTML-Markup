## Gmail-Box

- G메일박스는 정보들이 병렬적으로 나열되어있고 또 그 구조가 반복되어 table 태그를 사용했다.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gmail Inbox</title>
    <link rel="stylesheet" href="styles13.css">
</head>
<body>
    <table class="inbox">
        <thead class="sr-only">
```
- css로 시각적으로 숨기고 싶은 태그의 class명을 sr-only(screenReader-only)로 사용한다.

    - 시각 장애인들에게 충분한 정보 제공 가능하게 하면서도 시각적으로 숨겨 디자인을 깔끔하게 할 수 있다.
```html
            <tr>
                <th scope="col">
                    Action
                </th>
                <th scope="col">
                    Sender
                </th>
                <th scope="col">
                    Title
                </th>
                <th scope="col">
                    Time
                </th>
            </tr>
        </thead>
        <tbody>
            <tr class="unread">
                <td>
                    <div class="inbox-actions">
                        <div class="inbox-checkbox">
                            <input type="checkbox" id="inbox 1">
                            <label for="inbox 1" class="sr-only">Select this email</label>
                        </div>
                        <button type="button" class="inbox-star">
                            <span class="sr-only">
                                Add to favorites
                            </span>
                        </button>
                    </div>
                </td>

                <td>
                        Groorm Edu
                </td>

                <td>
                    <a href="#">
                        <strong class="sr-only">Unread:</strong>
                        <strong>
                            Rate your course: FRONTEND 101 WITH KIMBUG
                        </strong>
                        <span>
                            - Woohyeon. How’s everything going? We want to hear your opnion on...
                        </span>
                    </a>
                </td>
                
                <td>
                    3:34PM
                </td>
            </tr>
        
            <tr class="read">
                <td>
                    <div class="inbox-actions">
                        <div class="inbox-checkbox">
                            <input type="checkbox" id="inbox 1">
                            <label for="inbox 1" class="sr-only">Select this email</label>
                        </div>
                        <button type="button" class="inbox-star">
                            <span class="sr-only">
                                Add to favorites
                            </span>
                        </button>
                    </div>
                </td>

                <td>
                        Groorm Edu
                </td>

                <td>
                    <a href="#">
                        <strong class="sr-only">Unread:</strong>
                        <span>
                            Rate your course: FRONTEND 101 WITH KIMBUG
                        </span>
                        <span>
                            - Woohyeon. How’s everything going? We want to hear your opnion on...
                        </span>
                    </a>
                </td>
                
                <td>
                    3:34PM
                </td>
            </tr>
        </tbody>
    </table>
    <script src="./app3.js"></script>
</body>
</html>
```