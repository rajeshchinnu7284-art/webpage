<!DOCTYPE html>
<html lang="en">
    <head>
        <title>webpage</title>
        <link rel="stylesheet" href="web.css">
    </head>
    <body>
        <div class="main">
            <div class="navbar">
                <div class="icon">
                    <h2 class="logo">chinnu</h2>
                </div>
                <div class="Menu">
                    <ul>
                        <li><a href="#">Home</a></li>
                        <li><a href="#">About </a></li>
                        <li><a href="#">Service</a></li>
                        <li><a href="#">Contact</a></li>    
                    </ul>
                </div>
                </div>
                <div class="search">
                    <input class="srch" type="search" name=""placeholder="Type to text">
                    <a href="#"><button class="btn" >Search</button></a>
                </div>
                <div class="content">
                    <h1>I'm<br><span>Rajesh Kumar</span><br>Electronic Student</h1>
                    <p class="par">Hi guys !<br>This is rajesh ,currently I am persuing Second BTech in Aditya college of engineering</p>
                    <button class="cn"><a href="#">contact me</a></button>
                    <div class="form">
                        <h2>Login here</h2>
                        
                        <input typr="email" name="email"placeholder="enter email here">
                        <input typr="password" name="password"placeholder="enter password here">
                        <button class="btnn"><a href="#">login</a></button>

                       <p class="link">Dont have an account<br>
                       <a href="#">sign up</a></p>
                       <p class="liw">login With</p>
                       <div class="icon">
                        <a href="#"><ion-icon name="logo-facebook"></ion-icon></a>
                        <a href="#"><ion-icon name="logo-Instagram"></ion-icon></a>
                        <a href="#"><ion-icon name="logo-safari"></ion-icon></a>
                       </div>
        
                    </div>
                </div>
            
        </div>
        <script src="https://unpkg.com/ionicons@5.4.0/dist/ionicons.js"></script>
    </body>
</html>
*{ margin:0;
padding:0;}
.main{
    width:100%;
    background:linear-gradient(to top,rgba(0,0,0,0.5)50%,rgba(0,0,0,0.5)50%),url(1.jpg.jpg);
    background-position:center;
    background-size:cover;
    height:100vh;
}
.navbar{
    width:1200px;
    height:75px;
    margin:auto;
}
.icon{
    width:200px;
    float:left;
    height:70px;
}
.logo{
    color:aqua;
    font-size:35px;
    font-family:Araial;
    padding-left:20px;
    float:left;
    padding-top:10px;
}
.menu{
    width: 400px;
    float: left;
    height: 70px;
}
ul{
    float: left;
    display: flex;
    justify-content: center;
    align-items: center;
}   
 ul li{
   list-style: none;
   margin-left: 62px;
   margin-top: 27px;
   font-size: 14px ;
}
ul li a{
    text-decoration:none;
    color:aqua;
    font-family:Arial;
    font-weight:bold;
    transition:0.4s ease-in-out;
}
ul li a:hover{
    color:rgb(245, 72, 156);
}
.search{
    width:330px;
    float:right;
    margin-left: 270px;
}
.srch{
    font-family:'Times New Roman' ;
    width:200px;
    height:40px;
    background: transparent;
    border:1px solid orange;
    margin-top: 13px;
    color:aliceblue;
    border-right: none;
    font-size: 16px;
    float:left;
    padding:10px;
    border-bottom-left-radius: 5px;
    border-top-left-radius: 5px;
}
.btn{
    width:100px;
    height:40px;
    background: orange;
    border:2px solid orange;
    margin-top:13px;
    color:antiquewhite;
    font-size:15px;
    border-bottom-right-radius: 5px;
    border-bottom-right-radius: 5px;
}
.btn:focus{
outline: none;
}
.srch:focus{
    outline:none;
}
.content{
    width:1200px;
    height:auto;
    margin:auto;
    color:rgb(242, 245, 247);
    position:relative;
}
.content.par{
    padding-left: 20px;
    padding-bottom: 25px;
    font-family: Arial;
    letter-spacing: 1.2px;
    line-height: 30px;
}
.content h1{
    font-family: 'Times New Roman';
    font-size: 50px;
    padding-left: 20px;
    margin-top: 9%;
    letter-spacing: 2px;
}
.content.cn{
    width:160px;
    height:40px;
    background: orange;
    border: none;
    margin-bottom: 10px;
    margin-left: 20px;
    font-size: 18px;
    border-radius: 10px;
    cursor:pointer;
    transition: .3s ease;
}
.content.cn a{
    text-decoration:none ;
    color:orange;
    transition:.3s ease;
} 
.cn:hover{
    background-color: aliceblue;
    color:orange;
}
.content span{
    color:orange;
    font-size:65px;
}
.form{
    width:250px;
    height:380px;
    background:linear-gradient(to top,rgba(0,0,0,0.8)50%,rgba(0,0,0,0.8)50%);
    position:absolute;
    top:-20px;
    left:870px;
    border-radius:10px ;
    padding:25px;
}
.form h2{
    width:220px;
    font-family:sans-serif;
    text-align:center;
    color:orange;
    font-size: 22px;
    background-color: aliceblue;
    border-radius: 10px;
    margin:2px;
    padding:8px;
}
.form input{
    width:240px;
    height:35px;
    background: transparent;
    border-bottom: 1px solid orange;
    border-top: none;
    border-right: none;
    border-left: none;
    color:aliceblue;
    font-size: 15px;
    letter-spacing:1px ;
    margin-top: 30px;
    font-family:sans-serif
}
.form input:focus{
    outline:none;
}
::placeholder{
    color:aliceblue;
    font-family: Arial;
}
.btnn{
    width:240px;
    height:40px;
    background: orange;
    border:none;
    margin-top:30px;
    font-size:18px;
    border-radius:10px;
    cursor:pointer;
    color:aliceblue;
    transition:0.4 sec ease;
}
.btnn:hover{
    background: rgb(255, 254, 253);
    color:orange;
}
.btnn a{
    text-decoration: none;
    color:black;
    font-weight: bold;

}
.form.link{
    font-family:Arial, Helvetica, sans-serif;
    font-size:17px;
    padding-top:20px;
    text-align:center;

}
.form.link a{
    text-decoration: none;
    color:orange;
}
.liw{
    padding-top: 15px;
    padding-bottom: 10px;
    text-align: center;
}
.icon a{
    text-decoration: none;
    color:aliceblue;
}
.icons ion-icon{
    color:aliceblue;
    font-size:30px;
    padding-left:14px;
    padding:5px;
    transition: 0.3s ease;
}
.icon ion-icon:hover{
    color:orange;
}
