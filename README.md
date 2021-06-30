

<!DOCTYPE html>
<html>
<head>
    <title>😜😜</title>
    <style>
       body {
       text-align:center;
       background-color:#58B19F;
       
       }
       h1{
           background-color:#3B3B98;
           padding:10px;
           color:white;
       }
      .kodu {
          background-color:mediumseagreen;
          padding-bottom:10px;
          border: 3px solid red;
      }
      button{
      background-color:#182C61;
          color:white;
          padding:10px;
      }
      #demo {
          color:white;
      }
      button:hover{
          background-color:#6D214F;
          transition: 1s;
      }
      #copyright{
          color: #3d3d3d;
          text-decoration: underline;
          margin-top:350px
      }
    </style>
</head>
<body>
<div class="kodu" >
<h1>কি খবর Monu?😜</h1>

<button onclick="typeWriter()">এইহানে চাপ মারোনা ক্যা রে, হু? 👨‍⚖️</button>

<p id="demo">Hi Monu,</p>

</div>
<script>
var i = 0;
var txt = ' কেমন আছো? ভালানি? করোনার মইধ্যে বাড়িদ্দা বাইরাবা না কিন্ত, অখে?☺️🤘';
var speed = 60;

function typeWriter() {
  if (i < txt.length) {
    document.getElementById("demo").innerHTML += txt.charAt(i);
    i++;
    setTimeout(typeWriter, speed);
  }
}
</script>

<div id="copyright">
    Created By Mujahid Sifat
</div>
</body>
</html>
