HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>NAVIGATION BAR</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
 <header>
    <div class="logo">
        <p>SWIGGY</p>
    </div>
    <nav>
        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">About</a></li>
            <li><a href="#">Services</a></li>
            <li><a href="#">Contact</a></li>
            <li><a href="#">Login</a></li>
        </ul>     
    </nav>
    <button><a href="#">Get Started</a></button>
 </header>  
</body>
</html>





CSS
*{
    margin: 0;
    padding: 0;
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
    box-sizing: border-box;
}
body{
    background-image: url(image/1920x1080.jpg);
    height: 100vh;
    background-size: cover;
    background-position: center;
}
header{
    width: 100%;
    height: 75px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 30px 10%;
    background: rgba(0, 0, 0, 0.2);
}
.logo{
    font-size: 40px;
    font-weight: bold;
    color: white;
    letter-spacing: 1.5px;
    cursor: pointer;
}
nav li{
    display: inline-block;
    list-style: none;
    padding: 0px 20px;
}
a,button{
    font-size: 20px;
    font-weight: 500;
    color: white;
    text-decoration: solid;
    cursor: pointer;
}
button{
    background: rgba(0, 0, 0, 0.2);
    border: 2px solid #ef6d16;
    border-radius: 60px;
    padding: 10px 26px;
}
nav li a:hover{
    color: #ef6d16;
    transition: all 0.5s ease 0s;
}
button:hover{
    background-color: #ef6d16;
    transition: all 0.5s ease 0s;
}
