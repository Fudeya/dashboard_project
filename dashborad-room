<!DOCTYPE html>
<html lang="zh-Hant">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>DashboardPROJECT-room</title>

<style>
body{
  margin:0;
  height:100vh;
  display:flex;
  align-items:center;
  justify-content:center;
  font-family:Arial, Helvetica, sans-serif;
  background: linear-gradient(to bottom, white, #3a86ff);
  overflow:hidden;
}

/* 移動方塊圖層 */
.square-layer{
  position:fixed;
  inset:0;
  pointer-events:none;
  z-index:0;

  background-image:
    linear-gradient(rgba(255,255,255,0.6) 2px, transparent 2px),
    linear-gradient(90deg, rgba(255,255,255,0.6) 2px, transparent 2px);

  background-size:60px 60px;
  animation:moveSquares 40s linear infinite;
  opacity:0.35;
}

@keyframes moveSquares{
  from{
    background-position:0 0,0 0;
  }
  to{
    background-position:200px 200px,200px 200px;
  }
}

.container{
  position:relative;
  z-index:1;
  text-align:center;
  background: rgba(255,255,255,0.85);
  padding:40px;
  border-radius:20px;
  box-shadow:0 10px 30px rgba(0,0,0,0.2);
}

h1{
  margin-bottom:20px;
}

button{
  padding:12px 24px;
  font-size:18px;
  border:none;
  border-radius:10px;
  cursor:pointer;
  background:#3a86ff;
  color:white;
}

button:hover{
  background:#265ecf;
}
</style>

</head>

<body>

<!-- 背景方塊圖層 -->
<div class="square-layer"></div>

<div class="container">
  <h1>My Game</h1>
  <button onclick="startGame()">Start</button>
</div>

<script>
function startGame(){
  alert("Game Start!");
}
</script>

</body>
</html>
