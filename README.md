index.html 
<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<title>Untuk Suci Zahira 💙</title>

<style>
body{
  margin:0;
  font-family: Arial, sans-serif;
  background: linear-gradient(to bottom,#dbeafe,#fbcfe8);
  display:flex;
  justify-content:center;
  align-items:center;
  min-height:100vh;
  overflow:hidden;
}

.card{
  background: rgba(255,255,255,0.92);
  padding:30px;
  border-radius:25px;
  max-width:420px;
  text-align:center;
  box-shadow:0 10px 30px rgba(0,0,0,0.2);
  animation: fade 1s ease;
}

h1{
  color:#ec4899;
}

p{
  color:#444;
  line-height:1.8;
  font-size:15px;
}

button{
  margin-top:20px;
  background:#ec4899;
  color:white;
  border:none;
  padding:12px 18px;
  border-radius:20px;
  cursor:pointer;
}

button:hover{
  opacity:0.9;
}

.heart{
  position:absolute;
  top:-10px;
  animation: fall linear infinite;
  color:#60a5fa;
  font-size:18px;
}

@keyframes fall{
  to{
    transform:translateY(110vh);
  }
}

@keyframes fade{
  from{opacity:0; transform:translateY(20px);}
  to{opacity:1; transform:translateY(0);}
}
</style>
</head>

<body>

<audio autoplay loop>
  <source src="https://files.catbox.moe/8v8n5v.mp3" type="audio/mp3">
</audio>

<div class="card">
  <h1>Untuk Suci Zahira 💙</h1>

  <p>
    Aku nggak tahu kamu lagi ada di hari yang seperti apa sekarang.  
    Tapi kalau kamu sempat membuka ini, aku cuma ingin kamu tahu satu hal sederhana:  
    kamu nggak perlu selalu kuat sendirian.  
    Ada hari-hari yang berat, ada pikiran yang ramai,  
    dan kadang semuanya terasa berjalan tanpa jeda.  

   <br><br>

  Aku nggak janji bisa selalu ngerti semua yang kamu rasakan,  
    tapi aku selalu berusaha ada di sisi yang tenang buat kamu.  
    Nggak harus banyak kata, nggak harus selalu cerita panjang.  
    Kadang cukup tahu ada seseorang yang tetap peduli, itu sudah cukup.  

   <br><br>

   Kamu boleh capek, kamu boleh diam, kamu boleh berhenti sebentar.  
    Dunia nggak akan berhenti, tapi kamu juga berhak untuk pelan-pelan.  
    Dan kalau suatu saat kamu merasa sendiri,  
    baca ini lagi pelan-pelan… aku masih di sini, nggak kemana-mana. 💙
  </p>

  <button onclick="alert('Aku selalu ada buat kamu, Suci 💙')">
    Klik Kalau Kamu Butuh Teman
  </button>
</div>

<script>
const password = prompt("Masukin password (tanggal lahir Suci:)");

if(password !== "040906"){
  document.body.innerHTML = `
  <div style="text-align:center;font-family:Arial;">
    <h2>💔 Akses Ditolak</h2>
    <p>Coba pakai tanggal lahir Suci ya 💙</p>
  </div>`;
}
  
// love animation
for(let i=0;i<25;i++){
  let love=document.createElement("div");
  love.innerHTML="💙";
  love.className="heart";
  love.style.left=Math.random()*100+"vw";
  love.style.animationDuration=(Math.random()*5+5)+"s";
  document.body.appendChild(love);
}
</script>

</body>
</html>
