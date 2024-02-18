# Codeways_Task3
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>My Toonz Tv - Watch Kids Movies on Toonz TV!</title>
    <style>
        *{
    padding: 0;
    margin: 0;
    box-sizing: border-box;
}
body{
    width: 100%;
    height: 100%;
    color: rgb(17, 25, 3);
    background: rgb(143, 80, 4);
    font-family: 'Helvetica Neue',Helvetica,Arial,'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    background-image: url("https://www.isummersoft.com/wp-content/uploads/2022/07/wattpad-onkindle.png");
   background-size:100%;
   
   
}
.container::before{
    content: "";
    background: url(images/netflix-bg.jpg) no-repeat center center/cover;
    position: absolute;
    height: 100%;
    width: 100%;
    opacity: 0.45;
    z-index: -1;
    background-repeat:no-repeat;
    filter:blur(100px);
    -webkit-filter: blur(100px);
    background-color: aliceblue;
}
.container .navbar{
    height: 100px;
    display: flex;
}
.container .navbar .left{
    height: 100%;
    display: flex;
    float: left;
}
.container .navbar .left img{
    height: 100px;
    position: absolute;
    left: 35px;
}
.container .navbar .right{
    display: flex;
    height: 100px;
    float: right;
    position: absolute;
    right: 50px;
}
.container .navbar .right .language{
    margin: auto;
    align-items: center;
    justify-content: center;
    font-size: 18px;
    padding: 7px 10px;
    color: white;
    background: none;
    cursor: pointer;
    margin-right: 15px;
}
.container .navbar .right .language option{
    background-color: rgba(10, 8, 8, 0.458);
}
.container .navbar .right button{
    margin: auto;
    align-items: center;
    justify-content: center;
    font-size: 18px;
    font-weight: 400;
    padding: 7.1px 17.1px;
    background: #fa1e29;
    cursor: pointer;
    outline: none;
    border-radius: 4.1px;
    border: none;
}
.container .navbar .right button a{
    text-decoration: none;
    color: white;
}
.container .title{
    padding: 69px 46px;
}
.container .title .content{
    width: 951px;
    margin: auto;
    padding: 74px 0;
    text-align: center;
}
.container .title .content h1{
    width: 652px;
    margin: auto;
    font-size: 2.5rem;
    text-align: center;
    font-family:'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
}
.container .title .content h2{
    width: 648px;
    margin: auto;
    font-size: 1.6rem;
    text-align: center;
}
.container .title .content form h3{
    font-size: 1rem;
    margin: 18px 0;
    text-align: center;
}
.container .title .content form .email{
    width: 1000px;
    margin: auto;
}
.container .title .content form .email input{
    height: 60px;
    width: 450px;
    margin: auto;
    padding: 20px;
    font-size: 20px;
    outline: none;
}
.container .title .content form .email button{
    margin: auto;
    height: 60px;
    width: 180px;
    align-items: center;
    justify-content: center;
    font-size: 20px;
    padding: 7px 17px;
    background: #f6303a;
    cursor: pointer;
    outline: none;
    border-top-right-radius: 2px;
    border-bottom-right-radius: 2px;
    border: none;
    margin-left: -5px;
}
.container .title .content form .email button:hover{
    background-color: #ef444c;
}
.container .title .content form .email button a{
    text-decoration: none;
    color: rgb(247, 230, 230);
}

    </style>
</head>
<body>

    <div class="container">
        <nav class="navbar">
            <div class="left">
               
                
            </div>
            <div class="right">
                <select name="language" class="language">
                    <option value="English">English</option>
                    <option value="Hindi">Hindi</option>
                    <option value="Telugu">Telugu</option>
                </select>
                <button><a href="#">Sign In</a></button>
            </div>
        </nav>

        <div class="title">
            <div class="content">
                <h1>Unleash Your Stories: Dive into Wattpad's World of Words!</h1>
                <h2>Read Everywhere Anytime.</h2>
                <form action="#">
                    <h3>Ready to read? Enter your email to create or start your membership.</h3>
                    <div class="email">
                        <input type="email" name="email" placeholder="Email address">
                        <button><a href="#">Get Started  </a></button>
                    </div>
                </form>
            </div>
        </div>
    </div>
</body>
</html>
