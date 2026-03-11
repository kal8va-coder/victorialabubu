<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>Happy 15th Birthday Victoria!</title>

<style>
body{
font-family: Arial;
text-align:center;
background:linear-gradient(135deg,#ff9ad5,#ffd6f6,#c8e8ff);
margin:0;
}

h1{
font-size:60px;
color:white;
text-shadow:2px 2px 10px #ff4fa3;
margin-top:40px;
}

.message{
font-size:22px;
background:white;
padding:20px;
border-radius:15px;
width:70%;
margin:auto;
box-shadow:0 10px 20px rgba(0,0,0,0.2);
}

button{
padding:15px 25px;
font-size:18px;
border:none;
border-radius:10px;
background:#ff4fa3;
color:white;
cursor:pointer;
margin-top:20px;
}

.gallery img{
width:200px;
border-radius:15px;
margin:10px;
}
</style>
</head>

<body>

<h1>🎉 Happy 15th Birthday Victoria 🎉</h1>

<div class="message">
Victoria, happy 15th birthday!  
Hope your day is full of fun, laughs, and lots of cake.  

And remember… **Labubu is funny** 😂  

Have an amazing birthday!
</div>

<button onclick="showSurprise()">🎁 Click For Surprise</button>

<p id="surprise" style="display:none;font-size:25px;">
🎊 SURPRISE VICTORIA!!! 🎊
</p>

<h2>Photo Gallery</h2>

<div class="gallery">
<img src="https://picsum.photos/200?1">
<img src="https://picsum.photos/200?2">
<img src="https://picsum.photos/200?3">
</div>

<script>
function showSurprise(){
document.getElementById("surprise").style.display="block";
}
</script>

</body>
</html>
