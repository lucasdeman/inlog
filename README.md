<!DOCTYPE html>
<html>
<body>

<center>

<a id="gelukt" href="javaspelletje.html"></a>

<p id="nogniet">-------</p>

<h id="nr1">*</h>
<h id="nr2">*</h>
<h id="nr3">*</h>
<h id="nr4"></h>
<br>


<button type="button" onclick="myFunction(1)">1</button>
<button type="button" onclick="myFunction(2)">2</button>
<button type="button" onclick="myFunction(3)">3</button><br>
<button type="button" onclick="myFunction(4)">4</button>
<button type="button" onclick="myFunction(5)">5</button>
<button type="button" onclick="myFunction(6)">6</button><br>
<button type="button" onclick="myFunction(7)">7</button>
<button type="button" onclick="myFunction(8)">8</button>
<button type="button" onclick="myFunction(9)">9</button><br>
<button type="button" onclick="myFunction(0)">0</button>

</center>

<script>

var v = 0;
var b = 0;
var n = 0;
var x = 0;

function myFunction(a){
x++;

var y = "nr" + x;
document.getElementById(y).innerHTML = a;

if (x == 1) {
v = a;
}
if (x == 2) {
b = a;
}
if (x == 3) {
n = a;
}

if (v == 9) {
if (b == 4) {
if (n == 5) {

document.getElementById("nogniet").innerHTML = "";
document.getElementById("gelukt").innerHTML = "klik hier";

}}}

if (x > 3) {
    document.getElementById("nr1").innerHTML = "*";
    document.getElementById("nr2").innerHTML = "*";
    document.getElementById("nr3").innerHTML = "*";
    document.getElementById("nr4").innerHTML = "";
    x = 0;
}

}



</script>

</body>
</html> 
