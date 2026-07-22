# Worldcupwasriggedformessi
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Petition - Replay the 2026 FIFA World Cup Final</title>

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial,Helvetica,sans-serif;
}

body{
background:#0d1117;
color:white;
}

header{
background:linear-gradient(135deg,#00a86b,#0f5132);
padding:60px 20px;
text-align:center;
}

header h1{
font-size:42px;
margin-bottom:15px;
}

header p{
font-size:20px;
max-width:800px;
margin:auto;
}

.container{
max-width:900px;
margin:40px auto;
padding:20px;
}

.card{
background:#161b22;
padding:30px;
border-radius:15px;
margin-bottom:30px;
box-shadow:0 0 20px rgba(0,0,0,.3);
}

h2{
margin-bottom:15px;
color:#00d084;
}

.progress{
width:100%;
height:28px;
background:#333;
border-radius:20px;
overflow:hidden;
margin:15px 0;
}

.bar{
width:45%;
height:100%;
background:#00d084;
}

.counter{
font-size:22px;
margin-top:10px;
}

input{
width:100%;
padding:14px;
margin:10px 0;
border:none;
border-radius:8px;
font-size:16px;
}

button{
width:100%;
padding:16px;
background:#00d084;
border:none;
border-radius:10px;
font-size:18px;
cursor:pointer;
font-weight:bold;
}

button:hover{
background:#00b36b;
}

.comment{
background:#222;
padding:12px;
border-radius:8px;
margin-top:10px;
}

footer{
text-align:center;
padding:25px;
background:#111;
color:#aaa;
}
</style>

</head>

<body>

<header>

<h1>⚽ Replay the 2026 FIFA World Cup Final</h1>

<p>
Support this petition if you believe FIFA should review the final and consider replaying the match.
</p>

</header>

<div class="container">

<div class="card">

<h2>About this Petition</h2>

<p>
This petition asks FIFA to review the 2026 FIFA World Cup Final. Supporters of this petition believe the match should be replayed and are asking FIFA to examine the concerns raised by fans and determine whether a replay is appropriate under its rules.
</p>

<br>

<h2>Signature Goal</h2>

<h3>500,000 Signatures</h3>

<div class="progress">
<div class="bar"></div>
</div>

<div class="counter" id="count">
225,000 supporters
</div>

</div>

<div class="card">

<h2>Sign the Petition</h2>

<input id="name" placeholder="Your Name">

<input id="country" placeholder="Country">

<button onclick="signPetition()">
Sign Petition
</button>

</div>

<div class="card">

<h2>Recent Supporters</h2>

<div id="supporters">

<div class="comment">
Lionel — Argentina 🇦🇷
</div>

<div class="comment">
Carlos — Spain 🇪🇸
</div>

<div class="comment">
Ahmed — Egypt 🇪🇬
</div>

</div>

</div>

</div>

<footer>

Made for supporters who wish to advocate for a review and possible replay of the 2026 FIFA World Cup Final.

</footer>

<script>

let signatures=225000;

function signPetition(){

const name=document.getElementById("name").value;

const country=document.getElementById("country").value;

if(name==""){
alert("Please enter your name.");
return;
}

signatures++;

document.getElementById("count").innerHTML=
signatures.toLocaleString()+" supporters";

const div=document.createElement("div");

div.className="comment";

div.innerHTML=name+" — "+country;

document.getElementById("supporters").prepend(div);

document.getElementById("name").value="";
document.getElementById("country").value="";

alert("Thank you for signing the petition!");

}

</script>

</body>
</html><!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Petition - Replay the 2026 FIFA World Cup Final</title>

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial,Helvetica,sans-serif;
}

body{
background:#0d1117;
color:white;
}

header{
background:linear-gradient(135deg,#00a86b,#0f5132);
padding:60px 20px;
text-align:center;
}

header h1{
font-size:42px;
margin-bottom:15px;
}

header p{
font-size:20px;
max-width:800px;
margin:auto;
}

.container{
max-width:900px;
margin:40px auto;
padding:20px;
}

.card{
background:#161b22;
padding:30px;
border-radius:15px;
margin-bottom:30px;
box-shadow:0 0 20px rgba(0,0,0,.3);
}

h2{
margin-bottom:15px;
color:#00d084;
}

.progress{
width:100%;
height:28px;
background:#333;
border-radius:20px;
overflow:hidden;
margin:15px 0;
}

.bar{
width:45%;
height:100%;
background:#00d084;
}

.counter{
font-size:22px;
margin-top:10px;
}

input{
width:100%;
padding:14px;
margin:10px 0;
border:none;
border-radius:8px;
font-size:16px;
}

button{
width:100%;
padding:16px;
background:#00d084;
border:none;
border-radius:10px;
font-size:18px;
cursor:pointer;
font-weight:bold;
}

button:hover{
background:#00b36b;
}

.comment{
background:#222;
padding:12px;
border-radius:8px;
margin-top:10px;
}

footer{
text-align:center;
padding:25px;
background:#111;
color:#aaa;
}
</style>

</head>

<body>

<header>

<h1>⚽ Replay the 2026 FIFA World Cup Final</h1>

<p>
Support this petition if you believe FIFA should review the final and consider replaying the match.
</p>

</header>

<div class="container">

<div class="card">

<h2>About this Petition</h2>

<p>
This petition asks FIFA to review the 2026 FIFA World Cup Final. Supporters of this petition believe the match should be replayed and are asking FIFA to examine the concerns raised by fans and determine whether a replay is appropriate under its rules.
</p>

<br>

<h2>Signature Goal</h2>

<h3>500,000 Signatures</h3>

<div class="progress">
<div class="bar"></div>
</div>

<div class="counter" id="count">
225,000 supporters
</div>

</div>

<div class="card">

<h2>Sign the Petition</h2>

<input id="name" placeholder="Your Name">

<input id="country" placeholder="Country">

<button onclick="signPetition()">
Sign Petition
</button>

</div>

<div class="card">

<h2>Recent Supporters</h2>

<div id="supporters">

<div class="comment">
Lionel — Argentina 🇦🇷
</div>

<div class="comment">
Carlos — Spain 🇪🇸
</div>

<div class="comment">
Ahmed — Egypt 🇪🇬
</div>

</div>

</div>

</div>

<footer>

Made for supporters who wish to advocate for a review and possible replay of the 2026 FIFA World Cup Final.

</footer>

<script>

let signatures=225000;

function signPetition(){

const name=document.getElementById("name").value;

const country=document.getElementById("country").value;

if(name==""){
alert("Please enter your name.");
return;
}

signatures++;

document.getElementById("count").innerHTML=
signatures.toLocaleString()+" supporters";

const div=document.createElement("div");

div.className="comment";

div.innerHTML=name+" — "+country;

document.getElementById("supporters").prepend(div);

document.getElementById("name").value="";
document.getElementById("country").value="";

alert("Thank you for signing the petition!");

}

</script>

</body>
</html>
