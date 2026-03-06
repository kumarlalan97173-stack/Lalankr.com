
<!DOCTYPE html>
<html>
<head>
<title>Lalan KR Gaming</title>

<style>

body{
background:linear-gradient(45deg,#000428,#004e92);
font-family:Arial;
text-align:center;
color:white;
}

h1{
color:gold;
font-size:40px;
}

.menu{
background:#111;
padding:15px;
}

.menu button{
background:gold;
border:none;
padding:10px 20px;
margin:5px;
font-size:16px;
border-radius:6px;
}

.games{
display:grid;
grid-template-columns:repeat(2,1fr);
gap:20px;
padding:20px;
}

.card{
background:#1c1c1c;
padding:20px;
border-radius:12px;
box-shadow:0 0 10px black;
}

.card img{
width:100%;
border-radius:10px;
}

.play{
background:gold;
border:none;
padding:10px;
margin-top:10px;
font-size:16px;
border-radius:6px;
}

.wallet{
background:green;
color:white;
padding:10px;
border-radius:6px;
}

</style>
</head>

<body>

<h1>🎮 Lalan KR Gaming</h1>

<div class="menu">
<button>Login</button>
<button>Signup</button>
<button class="wallet">Wallet ₹0</button>
<button>Deposit</button>
<button>Withdraw</button>
</div>

<div class="games">

<div class="card">
<h2>Ludo Game</h2>
<button class="play">Play Now</button>
</div>

<div class="card">
<h2>Car Racing</h2>
<button class="play">Play Now</button>
</div>

<div class="card">
<h2>Teen Patti</h2>
<button class="play">Play Now</button>
</div>

<div class="card">
<h2>Fire Battle</h2>
<button class="play">Play Now</button>
</div>

</div>

</body>
</html>