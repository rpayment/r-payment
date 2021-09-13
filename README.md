<!DOCTYPE html>
<html>
<title>W3.CSS</title>
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<style>
.mySlides {display:none;}

.cardo {
  height: auto;
  text-align: left;
  margin-bottom: 1%;
  margin-left: 7%;
  margin-right: 7%;
  background-color: rgba(0, 0, 0, 0.1);
    -webkit-backdrop-filter: blur(20px);
  user-select: none;
  border-radius: 20px;
  position: relative;
  z-index: 2;
}

.cardo a {
  cursor: none;
}

.cardo5 {
  height: auto;
  text-align: left;
  margin-bottom: 4%;
  margin-left: 6%;
  margin-right: 6%;
  background: linear-gradient(62deg, #008b8b, #005858, #008b8b, #005858);
  animation: gradient 15s ease infinite;
  background-size: 400% 400%;
  border-bottom: 1px solid #fbfbfb;
  user-select: none;
  border-radius: 20px 20px 0px 0px;
}

.cardo5 a {
  cursor: none;
}

.imgse {
  margin-bottom: 0px;
  border-radius: 10px;
  padding: 5px;
  border: 2px solid #000;
}

.tooltip {
  width:29%;
  float:right;
  margin: 2%;
  margin-top:0%;
  margin-bottom:0%;
  text-align: center;
}

.tooltip .tooltiptext {
  visibility: hidden;
  width: 100%;
  background-color: rgb(0, 0, 0); /* Fallback color */
  background-color: rgba(0, 0, 0, 0); /* black w/opacity/see-through */
  color: #fff;
  text-align: center;
  border-radius: 6px;
  padding: 5px 0;
  position: absolute;
  opacity: 0;
  transition: opacity 0.5s;
  z-index: 5;
  top: 80%;
  right: 0%;
  filter: drop-shadow(2px 5px 5px rgba(0, 0, 0, 0.15));
}


.tooltip:hover .tooltiptext {
  visibility: visible;
  opacity: 1;
}

@-webkit-keyframes gradient{
  0% {
    background-position: 0 50%;
  }
  50% {
    background-position: 100% 50%;
  }
  100% {
     background-position: 0% 50%;
  }
}
@keyframes gradient{
  0% {
    background-position: 0 50%;
  }
  50% {
    background-position: 100% 50%;
  }
  100% {
     background-position: 0% 50%;
  }
}

#header {
  width: 100%;
  text-align: center;
  z-index: 3;
  top: 0;
  left: 0;
  border-radius: 0px;
  transition: 0.7s;
  background: #42a5f5;
  position: relative;
  padding-top: 1%;
  border-radius: 0px 0px 50px 50px;
  border-bottom: 10px solid #077bf3;
}

/* Set height of body and the document to 100% */
body, html {
  height: 100%;
  margin: 0;
  user-select: none;
}

body a {
  cursor: none;
}
								
html {
  box-sizing: border-box;
}

*, *:before, *:after {
  box-sizing: inherit;
}

.column2 {
  float: left;
  width: 0%;
  margin-bottom: 0px;
  padding: 0px;
  margin: 1%;
  width: 23%;
  display: block;
}

.card2 {
  border-radius: 20px;
  cursor: none;
  transition: 0.3s;
  text-align: center;
  margin: 1.5px;
  transition: 0.7s;
  color: #263238;
}

.container5 {
  padding: 0 0px;
}

.container5::after, .row::after {
  content: "";
  clear: both;
  display: table;
}

.title2 {
  font-size: 2vw;
  text-align: center;
  padding-bottom: 2%;
  user-select: none;
}

.rounded-image3 {
    border-radius: 100px;
    box-shadow: 0px 1px 2px 0px rgba(0, 0, 0, 0.2);
    text-align: center;
    margin-bottom: 0%;
    margin-top: 0%;
    width:60%;
}

h1 {
  color: black;
  margin-left: 10px;
  user-select: none;
  font-size: 6vw;
}

</style>
</head>
<body>

<div id="header">

<div class="cardo" style="padding:0px;margin-top:0%;padding-bottom:5%;">

<div style="padding:10px;width:90%;margin-bottom:0px;margin-left:5%;background-image:none;margin-top:0%;">

  <div class="tooltip">
  <a href="##"><img class="imgse" src="https://image.flaticon.com/icons/png/512/785/785868.png" alt="explore" style="width:40%;"></a><p style="color:#000;font-size:2vw;text-align:center;margin:0%;">Keluhan</p></div>

<div class="tooltip">
  <a href="#"><img class="imgse" src="https://image.flaticon.com/icons/png/512/1288/1288699.png" alt="withdraw" style="width:40%;"></a><p style="color:#000;font-size:2vw;text-align:center;margin:0%;">Voucher</p></div>

<div class="tooltip">
  <img class="imgse" src="https://image.flaticon.com/icons/png/512/3126/3126724.png" alt="topup" style="width:40%;"><p style="color:#000;font-size:2vw;text-align:center;margin:0%;">QRIS</p>
<span class="tooltiptext"><img src="https://kioos.files.wordpress.com/2021/08/wp-1628958621888.jpg" alt="menu 4" style="width:100%;border-radius:15px;"></span>
</div>
</div><br/>
</div>

</div>

<div class="row" style="margin-bottom:5%;padding:5%;margin-top:-7%;position: relative;z-index: 1;border-radius: 20px; margin-left: 7%; width: 86%;background-color: #f1f5ff;border-radius: 0px 0px 50px 50px;border-bottom: 10px solid #077bf3;padding-bottom:0%;"><br/>

<div class="row" style="width:100%;margin:0%;">
  <div class="column2">
    <a
href="https://rpay.tokowebku.com/digital/62842" style="text-decoration:none" target="_blank">
    <div class="card2">
      <img class="rounded-image3" src="https://i.ibb.co/stVdpXG/images-5.jpg" alt="menu 1" style=" background-color:#483d8b;">
      <div class="container5">
        <p class="title2">Telkomsel</p>
      </div>
    </div></a>
  </div>

  <div class="column2">
  	 <a
href="https://rpay.tokowebku.com/digital/63129" style="text-decoration:none" target="_blank">
    <div class="card2">
      <img class="rounded-image3" src="https://i.ibb.co/41rJXfY/images-9.jpg" alt="menu 2" style="background-color:#a50000;">
      <div class="container5">
        <p class="title2">Tri</p>
      </div>
    </div></a>
  </div>

  <div class="column2">
  		<a
href="https://rpay.tokowebku.com/digital/63130" style="text-decoration:none" target="_blank">
    <div class="card2">
      <img class="rounded-image3" src="https://kioos.files.wordpress.com/2021/06/wp-1624091699338.jpg" alt="menu 3" style="background-color:#006700;">
      <div class="container5">
        <p class="title2">Indosat</p>
      </div>
    </div></a>
  </div>

  <div class="column2">
  		<a
href="https://rpay.tokowebku.com/digital/63131" style="text-decoration:none" target="_blank">
    <div class="card2">
      <img class="rounded-image3" src="https://kioos.files.wordpress.com/2021/06/wp-1624091911841.jpg" alt="menu 4" style="background-color:#ff8c00;">
      <div class="container5">
        <p class="title2">Smartfren</p>
      </div>
    </div></a>
  </div>

</div>
<div class="row" style="width:100%;margin:0%;">

  <div class="column2">
  		<a
href="https://rpay.tokowebku.com/digital/63134" style="text-decoration:none" target="_blank">
    <div class="card2">
      <img class="rounded-image3" src="https://kioos.files.wordpress.com/2021/06/wp-1624115153673.jpg" alt="menu5" style="background-color:#db7093;">
      <div class="container5">
        <p class="title2">Axis/XL</p>
      </div>
    </div></a>
  </div>

  <div class="column2">
  		<a
href="https://rpay.tokowebku.com/digital/65955" style="text-decoration:none" target="_blank">
    <div class="card2">
      <img class="rounded-image3" src="https://i.ibb.co/ssWmtFR/wallet-1.png" alt="menu 6" style="background-color:#008b8b;">
      <div class="container5">
        <p class="title2">E-Wallet</p>
      </div>
    </div></a>
  </div>

  <div class="column2">
  		<a
href="https://rpay.tokowebku.com/digital/63134" style="text-decoration:none" target="_blank">
    <div class="card2">
      <img class="rounded-image3" src="https://i.ibb.co/VjwDpFy/images-6.jpg" alt="menu5" style="background-color:#db7093;">
      <div class="container5">
        <p class="title2">PLN</p>
      </div>
    </div></a>
  </div>

  <div class="column2">
  		<a
href="#" style="text-decoration:none" target="_blank">
    <div class="card2" id="container">
      <section>
      <img class="rounded-image3" id="show" type="button" src="https://kioos.files.wordpress.com/2021/08/wp-1629001053118.png" alt="menu 6" style="background-color:#008b8b;">
      <div class="container5">
        <p class="title2">Lainnya</p>
      </div>
      <section>
    </div></a>
  </div>

</div>
</div>

</body>
</html>

<!-- KATEGORI SLIDE --><div class="mdr-container" style="padding-top:0%;padding-bottom:1%;margin-top:2%;margin-bottom:0%;">

<script src="https://rawcdn.githack.com/modernplay/hostfile/f1a50044e552a32247eb808f8876abbb6bc12554/jssor.slider-kat.min.js" type="text/javascript"></script> 	<script type="text/javascript"> window.jssor_1_slider_init = function() { var jssor_1_options = { $AutoPlay: 1, $SlideWidth: 750, $SlideHeight: 360, $SlideSpacing: 100 }; var jssor_1_slider = new $JssorSlider$("jssor_1", jssor_1_options); /*#region responsive code begin*/ var MAX_WIDTH = 900; function ScaleSlider() { var containerElement = jssor_1_slider.$Elmt.parentNode; var containerWidth = containerElement.clientWidth; if (containerWidth) { var expectedWidth = Math.min(MAX_WIDTH || containerWidth, containerWidth); jssor_1_slider.$ScaleWidth(expectedWidth); } else { window.setTimeout(ScaleSlider, 30); } } ScaleSlider(); $Jssor$.$AddEvent(window, "load", ScaleSlider); $Jssor$.$AddEvent(window, "resize", ScaleSlider); $Jssor$.$AddEvent(window, "orientationchange", ScaleSlider); /*#endregion responsive code end*/ }; </script> <style> /*jssor slider loading skin spin css*/ .jssorl-009-spin img { animation-name: jssorl-009-spin; animation-duration: 1.6s; animation-iteration-count: infinite; animation-timing-function: linear; } @keyframes jssorl-009-spin { from { transform: rotate(0deg); } to { transform: rotate(360deg); } 		}	 		.img-slide { 			border-radius: 10px;margin:0px;border-radius:25px; } </style> <div id="jssor_1" style="position:relative;margin:0 auto;margin-top:12px;margin-bottom:10px;top:0px;left:0px;width:900px;height:400px;overflow:hidden;visibility:hidden;"> <!-- Loading Screen --> <div data-u="loading" class="jssorl-009-spin" style="position:absolute;top:0px;left:0px;width:100%;height:100%;text-align:center;background-color:rgba(0,0,0,0.7);"> <img style="margin-top: 0px;position:relative;top:50%;width:38px;height:38px;" src="img/spin.svg" /> </div> <div data-u="slides" style="cursor:default;position:relative;top:0px;left:0px;width:900px;height:400px;overflow:hidden;"> <div> <a href="https://tokomu.bukaolshop.site/cari?kategori=8304"><img class="img-slide" data-u="image" src="https://i.ibb.co/ZMSvrN5/images-3.jpg" /></a> </div> <div> <a href="https://tokomu.bukaolshop.site/cari?kategori=8305"><img class="img-slide" data-u="image" src="https://i.ibb.co/m99jqFv/images-4.jpg" /></a> </div> <div> <a href="https://tokomu.bukaolshop.site/cari?kategori=8306"><img class="img-slide" data-u="image" src="https://i.ibb.co/H7hHxVV/images-5.jpg" /></a> </div> <div> <a href="https://tokomu.bukaolshop.site/cari?kategori=8531"><img class="img-slide" data-u="image" src="https://i.ibb.co/hZKwj72/images-6.jpg" /></a> </div> 			<div> <a href="https://tokomu.bukaolshop.site/cari?kategori=8307"><img class="img-slide" data-u="image" src="https://i.ibb.co/HX1gx0V/images-7.jpg" /></a> </div> </div> <a data-scale="0" href="https://www.jssor.com" style="display:none;position:absolute;">image gallery</a> </div> <script type="text/javascript">jssor_1_slider_init(); </script></div><!-- END -->


<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
div.scrollmenu2 {
  overflow: auto;
  white-space: nowrap;
  margin-left: 0px;
  margin-right: 0px;
  border-radius: 0px;
  margin-top: 0px;
  margin-bottom: 1%;
  background-colot: #fff;
}

div.scrollmenu2 a {
  display: inline-block;
  color: black;
  text-align: center;
  padding-bottom: 3%;
  text-decoration: none;
  cursor: none;
  user-select: none;
  font-size: 3vw;
  width: 30%;
  background-color: #fbfbfb;
  margin:1%;
  border-radius: 5px;
  border: 0.5px solid #ccc;
}

.imgs17 {
  width: 100%;
  padding: 10px;
  margin-bottom: 6px;
  border-radius: 25px;
  background-color: #fbfbfb;
}


</style>
</head>
<body>
				
<!DOCTYPE html>
<html lang="en">
<head>

       </div>
   </div>
   <p class="judul2">Pilih Gayamu</p>
   <p style="font-size:2vw;margin-top:-15px;margin-bottom:5px;text-align:left;margin-left:20px;color:black">PENTING : Pembelian di menu ini akan di proses secara manual. Slow respon ya...</p>
</div>
</body>
</html>

<style type="text/css">
   
    #clock > div {
        border-radius: 5px;
        background: #42a5f5;
        padding: 5px 5px 2px 5px;
        color: #fbfbfb;
        display: inline-block;
    }
    #clock > div > p {
        font-size: 10px;
        font-weight: bold;
        text-align: center;
        text-dexoration:none;
      
    }
    #days, #hours, #minutes, #seconds {
        padding: 0px;
        font-size: 13px;
        font-weight: bold;
        text-align:center;
        background: #42a5f5;
        display: inline-block;
        width: 17px;
        heigh : 5px;
    }
    span.puter {
        animation: puter 0.8s ease;
    }
    @keyframes puter {
        0% {transform: rotateX(0deg)}
        100% {transform: rotateX(360deg)}
    }
</style>

<body>
<script type="text/javascript">
    function animation(span) {
        span.className = "puter";
        setTimeout(function () {
            span.className = ""
        }, 700);
    }

    function Countdown() {
  
        setInterval(function () {

           var hari    = document.getElementById("days");
           var jam     = document.getElementById("hours");
           var menit   = document.getElementById("minutes");
           var detik   = document.getElementById("seconds");
              
           var deadline    = new Date("aug 08, 2021 23:59:59");
           var waktu       = new Date();
           var distance    = deadline - waktu;
              
           var days    = Math.floor((distance / (1000*60*60*24)));
           var hours   = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
           var minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
           var seconds = Math.floor((distance % (1000 * 60)) / 1000);
              
           if (days < 10)
           {
              days = days;
           }
           if (hours < 10)
           {
              hours = hours;
           }
           if (minutes < 10)
           {
              minutes = minutes;
           }
           if (seconds < 10)
           {
              seconds = seconds;
           }

           hari.innerHTML    = days;
           jam.innerHTML     = hours;
           menit.innerHTML   = minutes;
           detik.innerHTML   = seconds;
           //animation
           animation(detik);
           if (seconds = 0) animation(menit);
           if (minutes = 0) animation(jam);
           if (hours = 0) animation(hari);

        }, 1000);
    }

    Countdown();

</script></body><!--END-->


<div class="scrollmenu2" style="background-color:#fff;">

  <a href="#"><img class="imgs17" src="https://static.jakmall.id/2018/09/images/products/90d07c/thumbnail/nokia-105-ds-2017.jpg" alt=""><br/>Menu 1
</a>

  <a href="#"><img class="imgs17" src="https://static.jakmall.id/2020/07/images/products/b69af3/thumbnail/realme-c11-smartphone-2gb32gb-garansi-resmi.png" alt=""><br/>Menu 2
</a>

  <a href="#"><img class="imgs17" src="https://static.jakmall.id/2020/10/images/products/250bce/thumbnail/vivo-y20s-smartphone-8128gb-garansi-resmi.png" alt=""><br/>Menu 3
</a>
  
  <a href="#"><img class="imgs17" src="https://static.jakmall.id/2020/06/images/products/f545f7/thumbnail/samsung-galaxy-a51-smartphone-6gb128gb-garansi-resmi.png" alt=""><br/>Menu 4
</a>

  <a href="#"><img class="imgs17" src="https://static.jakmall.id/2021/01/images/products/c84788/thumbnail/samsung-galaxy-a12-smartphone-4128gb-garansi-resmi.jpg" alt=""><br/>Menu 5
</a>

  <a href="#"><img class="imgs17" src="https://static.jakmall.id/2020/05/images/products/13cfe5/thumbnail/nokia-110-2019-garansi-resmi.jpg" alt=""><br/>Menu 6
</a>
  
  <a href="#"><img class="imgs17" src="https://static.jakmall.id/2020/06/images/products/13258d/thumbnail/samsung-tab-s6-lite-128gb-garansi-sein.jpg" alt=""><br/>Menu 7
</a>

</div>
<br/>
</body>
</html>

<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
div.scrollmenu {
  overflow: auto;
  white-space: nowrap;
  margin-left: 0px;
  margin-right: 0px;
  border-radius: 0px;
  margin-top: 3px;
  padding-top: 3px;
}

div.scrollmenu a {
  display: inline-block;
  color: #000;
  text-align: left;
  padding: 0px;
  padding-bottom: 2%;
  text-decoration: none;
  cursor: none;
  user-select: none;
  font-size: 4vw;
  box-shadow: 0px 1px 2px 0px rgba(0, 0, 0, 0.2);
  border-radius: 20px;
  width: 80%;
  margin: 3%;
  background-color: #fbfbfb;
  overflow: hidden;
  vertical-align: top;
}

.imgs2 {
  border-radius: 20px 20px 0px 0px;
  width: 100%;
  margin-left: 0px;
  padding: 0px;
  margin-bottom: 6px;
}

.judul2 {
  color: black;
  border-radius: 5px 5px 0px 0px;
  font-size: 6vw;
  text-align: left;
  padding: 15px;
  margin-left: 5px;
  margin-top: -4%;
  margin-right: 5px;
  margin-bottom: -17px;
  user-select: none;
  font-weight: bold;
}

.judul2 a {
  float: right;
  color: #ccc;
  font-weight: normal;
  font-size: 2vw;
  cursor: none;
  padding-top: 20px;
}

</style>
</head>
<body>

</div><br/>
</body>
</html>

<!DOCTYPE html>

<html>
  <head>
    <meta charset="utf-8" />

    <style>
      #container {
        transition: transform 0.5s;
      }

 

      #overlay {
        position: fixed;
        z-index: 6;
        bottom: 0;
        left: 0;
        width: 100%;
        height: 100%;
        border-radius: 0px;
        background-color: #42a5f5;
        box-shadow: -7px 6px 13px -1px rgba(40, 40, 40, 0.55);
      }

      #overlay.default {
        visibility: hidden;
        transform: translateY(100%);
        transition: transform 0.5s, visibility 0s 0.5s;
      }

      #overlay.open {
        visibility: visible;
        transform: translateY(0%);
        transition: transform 0.5s;
      }

      #close {
        border-radius: 50%;
        width: 2em;
        height: 2em;
        position: absolute;
        right: 2%;
        top: 1%;
        border: none;
        outline: none;
        z-index: 100;
        cursor: none;
        background-color: transparent;
        color: #fff;
      }

      .main {
        text-align: center;
        position: relative;
        top: 2%;
        color: #fff;
        overflow-y: auto;
        height: 100%;
        z-index: 5;
        white-space: nowrap;
        padding-bottom: 25%;
      }
      
      #show {
        border-radius: 100px;
        cursor: none;
        user-select: none;
        outline: none;
      }
      

    </style>
  </head>

  <body>
  	

    <div id="overlay" class="default">
      <button id="close">
      <img src="https://image.flaticon.com/icons/png/512/32/32178.png" alt="ovo" style="width:70%;filter:invert(100%);">
      </button>    				

      <div class="main">
      				
<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>

*, *:before, *:after {
  box-sizing: inherit;
}

.column9 {
  float: left;
  margin-bottom: 5px;
  padding: 0 8px;
  text-align: center;
}

@media screen and (max-width: 650px) {
  .column9 {
    width: 25%;
    display: block;
  }
}

.card9 {
  box-shadow: 0px 0px 0px 0px rgba(0, 0, 0, 0.2);
  border-radius: 0px;
  cursor: none;
  user-select: none;
  cursor: none;
  user-select: none;
}

.container9 {
  padding: 0 0px;
}

.container9::after, .row9::after {
  content: "";
  clear: both;
  display: table;
}

.title9 {
  color: #fff;
  font-size: 3vw;
  text-align: center;
}

.title19 {
  color: #000;
  font-size: 3vw;
  text-align: center;
}

.rounded-image9 {
    border-radius: 100px;
    margin-bottom: -4px;    
    box-shadow:  0px 0px 0px 0px rgba(0, 0, 0, 0);
    border: 1px solid #fff;
}

.rounded-image10 {
    border-radius: 10px;
    margin-bottom: -4px;    
    box-shadow:  0px 1px 2px 0px rgba(0, 0, 0, 0.2);
    background-color: #fff;
}

.judul9 {
  color: #fff;
  font-size: 4vw;
  text-align: left;
  padding: 10px;
  margin-left: 10px;
  margin-bottom: 10px;
  user-select: none;
  font-weight: bold;
}

</style>
</head>
<body>


<div class="row9">

<p class="judul9">Topup Game</p>

  <div class="column9">
    <a
href="#" style="text-decoration:none" target="_blank">
    <div class="card9">
      <img class="rounded-image9" src="https://kioos.files.wordpress.com/2021/06/wp-1624176967436.jpg" alt="ovo" style="width:60%"></a>
      <div class="container9">
        <p class="title9">Free Fire</p>
      </div>
    </div>
  </div>

  <div class="column9">
  		<a
href="#" style="text-decoration:none" target="_blank">
    <div class="card9">
      <img class="rounded-image9" src="https://kioos.files.wordpress.com/2021/06/wp-1624176967447.jpg" alt="gopay" style="width:60%"></a>
      <div class="container9">
        <p class="title9">Mobile Legend</p>
      </div>
    </div>
  </div>

  <div class="column9">
  		<a
href="#" style="text-decoration:none" target="_blank">
    <div class="card9">
      <img class="rounded-image9" src="https://kioos.files.wordpress.com/2021/06/wp-1624176967443.jpg" alt="gopay" style="width:60%"></a>
      <div class="container9">
        <p class="title9">PUBG M</p>
      </div>
    </div>
  </div>

  <div class="column9">
  	 <a
href="#" style="text-decoration:none" target="_blank">
    <div class="card9">
      <img class="rounded-image9" src="https://kioos.files.wordpress.com/2021/06/wp-1624176967423.jpg" alt="dana" style="width:60%"></a>
      <div class="container9">
        <p class="title9">Higgs Domino</p>
      </div>
    </div>
  </div>


</div>

<div class="row9">

  <div class="column9">
    <a
href="#" style="text-decoration:none" target="_blank">
    <div class="card9">
      <img class="rounded-image9" src="https://kioos.files.wordpress.com/2021/06/wp-1624176967432.jpg" alt="ovo" style="width:60%"></a>
      <div class="container9">
        <p class="title9">AOV</p>
      </div>
    </div>
  </div>

</div>

</body>
</html>


  <br/>  				
      				
      </div>
    </div>

    <script>
      (function() {
        const container = document.getElementById('container');
        const overlay = document.getElementById('overlay');
        const show = document.getElementById('show');
        const close = document.getElementById('close');

        function toggleOverlay() {
          container.classList.toggle('overlay-open');
          overlay.classList.toggle('open');
        }

        show.addEventListener('click', toggleOverlay);
        close.addEventListener('click', toggleOverlay);
      })();
    </script>

<script>
var target = window; // this can be any scrollable element
var last_y = 0;
target.addEventListener('touchmove', function(e){
    var scrolly = target.pageYOffset || target.scrollTop || 0;
    var direction = e.changedTouches[0].pageY > last_y ? 1 : -1;
    if(direction>0 && scrolly===0){
        e.preventDefault();
    }
    last_y = e.changedTouches[0].pageY;
});
</script>
  </body>
</html>
