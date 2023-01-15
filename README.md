<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="shortcut icon" href="img/logo2.png" type="image/x-icon">
    <title>Smen</title>
    <style>
    @import url('https://fonts.googleapis.com/css2?family=Noto+Sans+Mono&display=swap');


body{
    margin: 0;
    background-color: rgba(0, 204, 255, 0.103);
}
header{
    margin: 0;
    position: relative;
    background-color: rgba(0, 0, 0, 0.308);
    display: flex;
    width: 100%;
    height: 100px;
    justify-content: space-around;
    align-items: center;
}
header>.img1{
    position: relative;
    width: 180px;
    height: 70px;
}
.img2{
    position: relative;
    width: 45px;
    height: 45px;
}

.div1{
    position: relative;
    display: inline-block;
  }
.div1:hover .kcontent {display: block;}
.div1:hover .img2 {width: 47px;
    height: 47px;
    box-shadow: -4px 2px #00000054;
    border-radius: 150px;}
.img2:hover{
    width: 47px;
    height: 47px;
    box-shadow: -4px 2px #00000054;
    border-radius: 150px;
}
.buttonen{
    background-color: rgba(240, 248, 255, 0);
    border: 0;
}
.kcontent{
    margin-left: -50px;
    display: none;
  position: absolute;
  background-color: rgb(153, 177, 177);
  min-width: 160px;
  border-radius: 10px;
  box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
  z-index: 1;
}
.kcontent>a{
    color: black;
    padding: 12px 16px;
    text-decoration: none;
    display: block;
}
.kcontent>a:hover{
    margin-left: 5px;
    color: black;
    padding: 12px 16px;
    text-decoration: none;
    display: block;
    text-shadow: -4px 2px #00000054;
}
.kcontent>a>p{
    font-size: 20px;
    font-family: 'Noto Sans Mono', monospace;
    font-weight: 600;
    text-align: center;
}
article{
    position: relative;
    display: inline-block;
    text-align: center;
    margin-left: 0%;
    margin-top: 200px;
    width: 100%;
    height: 270px;
    align-items: center;
}

article>p{
    position: relative;
    margin-top: 0vh;
    margin-left: 0vw;
    font-size: 44px;
    font-family: 'Noto Sans Mono', monospace;
    font-weight: 700;
    text-align: center;
}
.compra{
    position: relative;
    margin-left: 0vw;
    color: rgb(240, 248, 255);
    font-size: 24px;
    font-family: 'Noto Sans Mono', monospace;
    text-decoration: none;
    border: 3px solid black;
    background: linear-gradient(to right, red, purple);
    border-radius: 10px;
    padding: 3px;
}
article>.imga{
    width: 800px;
}
.znak{
    width: 100px;
    justify-content: space-between;
}
footer{
    position: relative;
    background-color: rgba(0, 0, 0, 0.308);
    display: flex;
    width: 100%;
    height: 100px;
    justify-content: space-around;
    align-items: center;
}
footer>p{
    font-size: 18px;
    font-family: 'Noto Sans Mono', monospace;
    font-weight: 400;
}

@media screen and (max-width: 600px) {
    article{
        position: relative;
        display: inline-block;
        text-align: center;
        margin-left: 0%;
        margin-top: 100px;
        width: 100%;
        height: 450px;
        align-items: center;
    }
    article>p{
        position: relative;
        margin-top: 0vh;
        margin-left: 2vw;
        font-size: 54px;
        font-family: 'Noto Sans Mono', monospace;
        font-weight: 700;
        text-align: center;
    }
    .compra{
        position: relative;
        color: rgb(240, 248, 255);
        font-size: 34px;
        font-family: 'Noto Sans Mono', monospace;
        text-decoration: none;
        border: 4px solid black;
        background: linear-gradient(to right, red, purple);
        border-radius: 20px;
        padding: 5px;
    }
    article>.imga{
        width: 400px;
    }
  }
    </style>
</head>
<body>
<header>
    <img class="img1" src="img/logo12.png" alt="">
    <div class="div1">

        <button class="buttonen">
            <img class="img2" src="img/free-icon-menu-3303943.png" alt="">
        </button>

        <div class="kcontent">

          <a href="sitoR.html"><p>Italian</p></a>


          <a href="sitoCreaE.html"><p>Creator</p></a>
          <a href="sito2.html"><p>Black theme</p></a>
        </div>
      </div>
</header>

<article>
    <p> 
        We are making sites 
        <br>
        since 2020 year
    </p>
    <a class="compra" href="">ORDER A SITE</a>
</article>
<article>
    <img class="imga" src="img/айти.webp" alt="">
    <p class="imgap">
        Our company creates modern and 
        <br>
        innovative websites for you!
    </p>
</article>
<article>
    <p>
        Contact us with:
    </p>
    <a class="niente"  href="https://vk.com/"><img class="znak" src="img/vk.png" alt=""></a>
    <a class="niente"  href="https://it-it.facebook.com/"><img class="znak" src="img/fb.png" alt=""></a>
    <a class="niente"  href="https://www.instagram.com/"><img class="znak" src="img/insta.png" alt=""></a>
    <a class="niente"  href="https://www.whatsapp.com/?l=it"><img class="znak" src="img/whu.png" alt=""></a>
</article>
<footer>
   <p>prod.Smen_site</p> 
</footer>

</body>
</html>
