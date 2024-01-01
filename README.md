# Log_In-Page
hey this SignUp page using the HTML5 and CSS3

CSS3 property
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, Helvetica, sans-serif;
}

body{
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
    background-image: url(anime.png);
    /* background-image: url(anime2.pmf);
    background-image: url(fingerprintlogin.png); */
    background-size: cover;
    background-position: center;
}

.wrapper{
    width: 428px;
    background: transparent;
    border: 2px solid rgba(255 ,255, 255 .2);
    color: solid black
}

.wrapper h1{
    font-size: 30px;
    text-align: center;
}

.wrapper .input-box {
    width: 100%;
    height: 50px;
    background: transparent;
    margin: 30px 0;
}

.input-box input{
    width: 100%;
    height: 100%;
    background: transparent;
    border: none;
    outline: none;
    border: 2px solid rgba(255, 255, 255, .2);
    border-radius: 48px;
    padding: 20px 45px 20px 28px;
}

.input-box input::placeholder{
    color: #fff;
}

.input-box i{
    position: absolute;
    right: 20px;
    top: 58%;
    transform: translate(-50%);
    font-size: 28px;
}

.wrapper .remember-forgott{
    display: flex;
    justify-content: space-between;
    font-size: 14.5px;
    margin: -15px 0 15px;
}

.remember-forgott label input {
    accent-color: #fff;
    margin-right: 3px;
}
.remember-forgot a{
    color: #fff;
    text-decoration: none;
}

.remember-forgot a:hover{
    text-decoration: underline;
}

.wrapper .btn {
    width: 100%;
    height: 45px;
    background:  #fff;
    border: none;
    outline: none;
    border-radius: 48px;
    box-shadow: 0 0 10px rgba(0,0,0, .1);
    cursor: pointer;
    font-size: 16px;
    color: #333;
    font-weight: 600;
}

.wrapper .register-link {
    font-size: 15px;
    text-align: center;
    margin: 20px 0 15px;
}

.register-link p a{
    color: #fff;
    text-decoration: none;
    font-weight: 600;
}

HTML5 code
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" integrity="sha512-iecdLmaskl7CVkqkXNQ/ZH/XLlvWZOJyj7Yy7tcenmpD1ypASozpmT/E0iPtmFIB46ZmdtAc9eNBvH0H/ZpiBw==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <link rel="stylesheet" href="singin.css">
    <title>Document</title>
</head>
<body>
    <div class="wrapper">
        <form action="">
            <h1>LogIn</h1>
            <div class="input-box">
                <input type="text" placeholder="username" required>
                <input type="radio">
                <i class="fa-solid fa-user"></i>
            </div>
            <div class="input-box">
                <input type="password" placeholder="password" required>
                <i class="fa-solid fa-lock"></i>
            </div>

            <div class="remember-forget">
                <label><input type="checkbox"> Remember me</label>
                <a href="#"> Forgot Password</a>
            </div>
            <br>
            <button type="submit" class="btn">Log in</button>
            <div class="register-link">
                <p>Don't have account <a href="#">Create Account</a></p>
            </div>
        </form>
    </div>
    
</body>
</html>
