<!DOCTYPE html>
<html>
<body>

<canvas id="myCanvas" width="500" height="500" style="border:1px solid #d3d3d3;">
Your browser does not support the HTML canvas tag.</canvas>

<script>
var c = document.getElementById("myCanvas");
var ctx = c.getContext("2d");
o= 500
i= 62.5

for (let x = 0; x <= o; x += i) {
  ctx.moveTo(x, 0);
  ctx.lineTo(x, o);
  
  ctx.moveTo(0, x);
  ctx.lineTo(o, x);
ctx.stroke();
}
</script>
</body>
</html>
