<!DOCTYPE html>
<html>

<head>
<title>Live Time</title>
</head>

<body style="text-align:center; font-family:Arial; margin-top:100px;">

<h1>Current Date and Time</h1>

<p id="clock"></p>

<script>

function showTime() {

    let now = new Date();  

    document.getElementById("clock").innerHTML = now.toLocaleString();

}

showTime();           

setInterval(showTime,1000);  

</script>

</body>
</html>
