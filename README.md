<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Donate | NR PRO</title>

<style>
*{
box-sizing:border-box;
font-family:Tahoma,Arial,sans-serif;
}

body{
margin:0;
min-height:100vh;
background:
radial-gradient(circle at top,#1e3a8a,transparent 35%),
linear-gradient(135deg,#050816,#0f172a);
color:white;
}

.container{
max-width:900px;
margin:auto;
padding:40px 20px;
}

.hero{
text-align:center;
}

.logo{
width:90px;
height:90px;
margin:auto;
border-radius:25px;
display:flex;
align-items:center;
justify-content:center;
font-size:28px;
font-weight:bold;
background:linear-gradient(135deg,#2563eb,#06b6d4);
box-shadow:0 0 40px #2563eb;
}

h1{
font-size:45px;
}

h1 span{
color:#38bdf8;
}

.subtitle{
color:#cbd5e1;
}

.card{
background:rgba(255,255,255,.06);
backdrop-filter:blur(15px);
border:1px solid rgba(255,255,255,.12);
border-radius:25px;
padding:25px;
margin-top:30px;
}

.crypto{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:20px;
}

.coin{
background:linear-gradient(
145deg,
rgba(37,99,235,.25),
rgba(15,23,42,.8)
);

border-radius:20px;
padding:20px;
border:1px solid #334155;
}

.coin h3{
color:#7dd3fc;
}

.address{
background:#020617;
padding:15px;
border-radius:12px;
direction:ltr;
word-break:break-all;
font-size:13px;
margin:15px 0;
}

button{
width:100%;
padding:13px;
border:0;
border-radius:15px;
cursor:pointer;
color:white;
font-weight:bold;

background:
linear-gradient(90deg,#2563eb,#06b6d4);

}

button:hover{
transform:translateY(-3px);
}

.warning{

margin-top:25px;
padding:20px;
border-radius:18px;
background:#422006;
border:1px solid #92400e;
color:#fde68a;

}

footer{

text-align:center;
margin-top:40px;
color:#94a3b8;

}

</style>

</head>


<body>


<div class="container">


<div class="hero">

<div class="logo">
NR
</div>


<h1>
حمایت از <span>NR PRO</span>
</h1>


<p class="subtitle">
با حمایت شما توسعه پروژه‌های متن‌باز ادامه پیدا می‌کند 💙
</p>


</div>



<div class="card">


<h2>
💎 Crypto Donations
</h2>


<div class="crypto">



<div class="coin">

<h3>₿ Bitcoin</h3>

<div class="address" id="btc">

1MP6SmjCpDXWMQPjcDttbRzpYwDdefhq1m

</div>

<button onclick="copy('btc')">
کپی آدرس BTC
</button>

</div>



<div class="coin">

<h3>◆ Ethereum</h3>

<div class="address" id="eth">

0x50850d24a6C07615Ce835E385012d959FEa55f91

</div>

<button onclick="copy('eth')">
کپی آدرس ETH
</button>

</div>




<div class="coin">

<h3>💚 USDT</h3>

<p>
شبکه: BEP20
</p>

<div class="address" id="usdt">

0x50850d24a6C07615Ce835E385012d959FEa55f91

</div>

<button onclick="copy('usdt')">
کپی آدرس USDT
</button>

</div>



</div>

</div>




<div class="warning">

⚠️ قبل از ارسال، شبکه و آدرس را بررسی کنید.
<br>
USDT فقط روی شبکه BEP20 ارسال شود.

</div>



<footer>

NR PRO © 2026

</footer>


</div>




<script>

function copy(id){

let text=document.getElementById(id).innerText.trim();

navigator.clipboard.writeText(text);

alert("آدرس کپی شد ✅");

}

</script>



</body>
</html>
