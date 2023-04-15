
<html>
<style>
body, html {
  height: 100%;
  margin: 0;
}

.birthdayimg {
  background-image: url('https://cdn.wallpapersafari.com/86/70/ZoO20h.jpg');
  height: 100%;
  background-position: center;
  background-size: cover;
  position: relative;
  color: black;
  font-size: 35px;
}

.topleft {
  position: absolute;
  color: yellow;
  top: 0;
  left: 12px;
}

.bottomleft {
  position: absolute;
  color: gray;
  bottom:0;
  left: 18px;
}

.middle {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  text-align: center;
}

hr {
  margin: auto;
  width: 40%;
}
</style>

<body>
<div class="birthdayimg">
  <div class="topleft">
    <p>FriendlyAce</p>
  </div>
  <div class="middle">
    <h1>HAPPY LAST BIRTHDAY BITCH</h1>
    <hr>
    <p id="amx" style="font-size:80px"></p>
  </div>
  <div class="bottomleft">
    <p>07/23/06</p>
  </div>
</div>

<script>
var countDownDate = new Date("Jul 23, 2023 00:00:00").getTime();

var countdownfunction = setInterval(function() {

  var now = new Date().getTime();
var distance = countDownDate - now;

 var days = Math.floor(distance / (1000 * 60 * 60 * 24));
  var hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
  var minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
  var seconds = Math.floor((distance % (1000 * 60)) / 1000);

  document.getElementById("amx").innerHTML = days + "D " + hours + "H "
  + minutes + "M " + seconds + "S ";

 if (distance < 0) {
    clearInterval(countdownfunction);
    document.getElementById("amx").innerHTML = "UMABOT KA KUNTA NEXT YEAR";
    window.location = "https://youtu.be/PpJMIpPXiv8";
}

}, 1000);
</script>

</body>
</html>






