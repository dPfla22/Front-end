# DanaJJang_login

### HTML Code

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>DanaJJang</title>
    <link rel="stylesheet" href="login.css">
</head>
<body>
    <div class = "login_box"> <!-- 로그인 박스의 클래스를 가진 div 생성-->
        <img src="../asset/유저이미지.png" class="img_user"> <!-- img_user 클래스의 user 이미지를 가진 img 태그 생성-->
        <form> <!-- 폼 태그로 태그들을 묶어줌-->
            <input type="text" placeholder="ID를 입력하세요" class="login"> 
            <!-- login의 클래스를 가진 input(text) 태그 생성 -->
            <input type="password" placeholder="PW를 입력하세요" class="login">
            <!-- login의 클래스를 가진 input(password) 태그 생성 -->
            <button type="submit" class="login_button">LOG IN</button>
        	<!-- login_button의 클래스를 가진 button 태그 생성 -->
        </form>
    </div>
</body>
</html>
```



### CSS Code

```css
.login_box{
    background-color: #e1e1e1; /* 뒷배경은 #e1e1e1의 색깔을 적용한다 */
    width: 750px; /* div의 넓이는 750px */
    height: 400px; /* div의 길이는 400px */
    margin: auto; /* div를 가로 중앙에 배치한다(auto는 좌우 여백을 균등하게 줌) */
    margin-top: 10%; /* div를 위쪽으로부터 10% 간격을 준다 */
    display: flex; /* 가로 방향으로 배치 */
    justify-content: space-around; /* 가로선으로 동일한 간격으로 정렬한다 */
    align-items: center; /* 세로선상의 가운데로 정렬한다 */
}

.img_user{
    width: 200px; /* 이미지의 넓이는 200px */
    height: 200px; /* 이미지의 길이는 200px */
    margin: 8%; /* 이미지의 margin을 8% 준다 */
}

.login{
    outline: none; /* 바깥선을 없앤다 */
    flex-wrap: wrap; /* 여러 줄로 정렬한다 */
    flex-direction: column-reverse; /* 아래에서 위로 정렬한다 */
    align-content: center; /* 여러 줄들을 가운데로 정렬한다 */
    margin: 10%; /* login div의 마진을 10% 준다 */
    width: 300px; /* login div의 넓이를 300px를 준다 */
    height: 10%; /* login div의 길이를 10% 준다 */
    border: none; /* 선을 없앤다 */
    border-bottom: 1px solid black; /* 밑 테두리에 1px의 얇은 검정색의 선이 나오게 한다 */
    background-color: #e1e1e1; /* 뒷배경은 #e1e1e1의 색깔을 적용한다 */
}

.login_button{
    background-color: white; /* 뒷배경은 흰색으로 적용한다 */
    border-radius: 150px 140px; /* 테두리의 굴곡을 150px 140px로 적용한다 */
    border: 1px solid #afafaf; /* 테투리에 1px의 얇은 #afafaf의 선이 나오게 한다  */
    width: 80px; /* login_button의 넓이를 80px를 준다 */
    height: 40px; /* login_button의 길이를 40px를 준다 */
    font-size: 10px; /* 글짜 크기를 10px로 적용한다 */
    float: right; /* 오른쪽으로 정렬한다 */
    margin-right: 20px; /* button을 오른쪽으로부터 20px 간격을 준다 */
    margin-top: 30px; /* button을 위쪽으로부터 30px 간격을 준다 */
}
```

