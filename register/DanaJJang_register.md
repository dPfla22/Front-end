# DanaJJang_register

### HTML

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>DanaJJang</title>
    <link rel="stylesheet" href="register.css">
</head>
<body>
    <div class="wrap">
        <div class="back_img">
            <div class="user_img_wrap">
                <img src="../asset/user.png" class="user_img">
            </div>
            <form class="register_form"> <!-- register_form의 클래스를 가진 폼 태그로 태그들을 묶어줌-->
                <input type="text" placeholder="ID를 입력하세요" class="register">
                <!-- register의 클래스를 가진 input(text) 태그 생성 -->
                <input type="text" placeholder="PW를 입력하세요" class="register">
                <!-- register의 클래스를 가진 input(text) 태그 생성 -->
                <button type="submit" class="register_button">회원가입 하기</button>
                <!-- register_button의 클래스를 가진 button 태그 생성 -->
            </form>
        </div>
    </div>
</body>
</html>
```



### CSS

```css
html, body {
    width: 100%; /* 전체의 넓이는 100% */
    height: 100%; /* 전체의 길이는 100% */
    margin: 0; /* margin은 0으로 설정 */
}

.wrap{
    width: 100%; /* wrap의 div 전체의 넓이는 100% */
    height: 100%; /* wrap의 div 전체의 넓이는 100% */
    display: flex; /* 가로 방향으로 배치 */
    justify-content: space-around; /* 가로선으로 동일한 간격으로 정렬한다 */
    align-items: center; /* 세로선 상의 가운데로 정렬한다 */
}

.back_img{
    background: url("../asset/단어장.jpg") no-repeat 50% 50% /  100% 100%;
    width: 90%; /* 이미지의 넓이를 90%로 설정 */
    height: 90%; /* 이미지의 길이를 90%로 설정 */
    display: flex; /* 가로 방향으로 배치 */
    justify-content: space-evenly; /* */
    align-items: center; /* 세로선 상의 가운데로 정렬한다 */
}

.user_img_wrap{
    width: 50%; /* 유저이미지를 담는 박스의 넓이를 50%로 설정한다 */
    display: flex; /* 가로 방향으로 배치한다 */
    justify-content: center; /* 가로선 상의 가운데로 정렬한다 */
    align-items: center; /* 세로선 상의 가운데로 정렬한다 */
}

.user_img{
    width: 250px; /* 이미지의 넓이를 250px로 설정한다 */
    height: 250px; /* 이미지의 길이를 250px로 설정한다 */
}

.register_form{
    display: flex; /* 가로 방향으로 배치한다 */
    flex-direction: column; /* 위에서 아래로 정렬 */
    align-items: flex-end; /* 세로선 상으로 바닥으로 정렬 */
    justify-content: space-evenly; /* 요소들의 사이와 양 끝에 균일한 간격으로 정렬한다 */
    height: 90%; /* 로그인 박스의 길이를 90%로 설정한다 */
    padding: 100px 200px 100px 100px; /* 시계방향으로 위쪽으로는 100px, 오른족으로는 200px, 아래쪽으로는 100px, 왼쪽으로는 100px로 설정한다 */
    box-sizing: border-box; /* 테투리를 기준으로 박스의 크기를 설정한다 */
    width: 50%; /* 회원가입 박스의 넓이를 50%로 설정한다 */
}

.register{
    outline: none; /* 바깥선(바깥 외곽선)을 없앤다 */
    width: 400px; /* text의 넓이들을 400px로 설정한다 */
    height: 5%; /* text의 길이들을 5%로 설정한다 */
    border: none; /* 선을 없앤다 */
    border-bottom: 1px solid black; /* text의 아래선을 1px의 얇은 검정 선을 나오게 한다 */
    margin: 10%; /* text들의 margin을 10%로 적용한다 */
}

.register_button{
    position: relative; /* static의 원래 위치로부터 계산한다 */
    background-color: #000000; /* 뒷배경은 #000000의 색깔을 적용한다 */
    border-radius: 350px 340px; /* */
    border: 1px solid #000000; /* 테투리에 1px의 얇은 #000000색의 선이 나오게 한다 */
    width: 130px; /* button의 넓이를 130px로 설정한다 */
    height: 40px; /* button의 길이를 40px로 설정한다 */
    font-size: 10px; /* 글자 크기를 10px로 설정한다 */ 
    margin-right: 20px; /* button을 오른쪽으로부터 20px 간격을 준다 */
    margin-top: 40px; /* button을 위쪽으로부터 40px 간격을 준다 */
    color: #e2e2e2 /* 글자색을 #e2e2e2로 설정 */
}

.register_button:hover{
    cursor: pointer; /* 버튼에 마우스에 가져다대면, 마우스의 커서 모양을 클릭 가능한 버튼으로 설정한다 */
}
```

