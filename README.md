<!DOCTYPE html>
<html>
<body>

<canvas id="myCanvas" width="200" height="200" style="border:1px solid #d3d3d3;">
Your browser does not support the HTML canvas tag.</canvas>

<script>
var c = document.getElementById("myCanvas");
var ctx = c.getContext("2d");
ctx.moveTo(0,0);
ctx.lineTo(200,200);
ctx.stroke();

ctx.moveTo(200,0);
ctx.lineTo(0,200);
ctx.stroke();


ctx.moveTo(200,0);
ctx.lineTo(0,200);
ctx.stroke();




</script>

</body>
</html>

