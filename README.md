<!DOCTYPE html>
<html>
<head>
<title>Secret Photo Scanner 📸</title>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
body{
  background:black;
  color:white;
  text-align:center;
  font-family:Arial;
}
img{
  width:250px;
  border-radius:15px;
  margin-top:20px;
}
h1{
  color:red;
}
</style>
</head>
<body>

<h1>📸 SECRET PHOTO SCANNER</h1>

<p>Click the photo to scan for hidden secrets 😈</p>

<img src="photo.jpg" onclick="playPrank()">

<p id="msg"></p>

<audio id="sound">
  <source src="bakra.mp3" type="audio/mpeg">
</audio>

<script>
function playPrank() {
  document.getElementById("sound").play();

  document.getElementById("msg").innerHTML =
    "🐐 SCAN COMPLETE! Bakra Level: 100% 😂";
}
</script>

</body>
</html>
