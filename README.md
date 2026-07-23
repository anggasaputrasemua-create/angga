<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Angga Music</title>

<style>
body{
  background: linear-gradient(135deg,#111,#333);
  color:white;
  font-family:Arial;
  text-align:center;
  padding:40px;
}

.box{
  max-width:400px;
  margin:auto;
  background:#222;
  padding:30px;
  border-radius:25px;
  box-shadow:0 0 20px black;
}

.cover{
  width:180px;
  height:180px;
  border-radius:50%;
  background:#00ff99;
  margin:auto;
  display:flex;
  align-items:center;
  justify-content:center;
  font-size:60px;
}

h1{
  margin-top:20px;
}

audio{
  width:100%;
  margin-top:20px;
}

button{
  margin-top:20px;
  padding:12px 30px;
  border:0;
  border-radius:20px;
  background:#00ff99;
  font-size:18px;
}
</style>

</head>

<body>

<div class="box">

<div class="cover">🎵</div>

<h1>Angga Music</h1>
<p>Voice MP3 Saya</p>

<audio controls>
<source src="https://res.cloudinary.com/nadmgydj/video/upload/v1784817014/ttsmaker-file-2026-7-22-10-3-24_bddppj.mp3" type="audio/mpeg">
</audio>

<button onclick="document.querySelector('audio').play()">
▶ Play
</button>

</div>

</body>
</html>
