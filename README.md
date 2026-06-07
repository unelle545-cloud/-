<!DOCTYPE html><html lang="ar">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>شذر ❤️</title><style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Tahoma,sans-serif;
}

body{
height:100vh;
overflow:hidden;
display:flex;
justify-content:center;
align-items:center;
background:linear-gradient(135deg,#ff4d88,#ff99c8);
direction:rtl;
}

.container{
background:white;
padding:30px;
border-radius:25px;
text-align:center;
width:90%;
max-width:400px;
box-shadow:0 0 25px rgba(0,0,0,.2);
z-index:2;
}

h1{
color:#ff2d75;
margin-bottom:15px;
}

p{
margin:15px 0;
font-size:18px;
}

button{
padding:12px 20px;
margin:10px;
border:none;
border-radius:20px;
font-size:18px;
cursor:pointer;
}

#yes{
background:#ff2d75;
color:white;
}

#no{
background:#ddd;
}

.heart{
position:absolute;
font-size:24px;
animation:float 8s linear infinite;
}

@keyframes float{
0%{transform:translateY(100vh);opacity:0;}
100%{transform:translateY(-100px);opacity:1;}
}
</style></head><body><div class="container">
<h1>❤️ شذر ❤️</h1><p>
منذ عرفتكِ أصبح لكل يوم معنى أجمل 🌹
</p><p>
هل تقبلين أن تبقي أجمل شخص في عالمي؟ ✨
</p><button id="yes" onclick="love()">نعم ❤️</button>
<button id="no" onmouseover="moveBtn()">لا 😅</button>

<h2 id="result"></h2>
</div><script>
for(let i=0;i<50;i++){
let h=document.createElement("div");
h.className="heart";
h.innerHTML="💖";
h.style.left=Math.random()*100+"vw";
h.style.animationDuration=(4+Math.random()*6)+"s";
document.body.appendChild(h);
}

function love(){
document.getElementById("result").innerHTML=
"💍 تم اختيار نعم! أحبك يا شذر ❤️🌹";
}

function moveBtn(){
let btn=document.getElementById("no");
btn.style.position="absolute";
btn.style.left=Math.random()*80+"%";
btn.style.top=Math.random()*80+"%";
}
</script></body>
</html>
