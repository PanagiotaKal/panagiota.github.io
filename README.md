<!DOCTYPE HTML>
<html>

<head>

<meta name="viewport" content="width=device-width, initial-scale=1">
Nothing to see here. Just wait 5 seconds for a suprise.
<style>
p {
  text-align: center;
  font-size: 30px;
  margin-top: 0px;
}
</style>

</head>

<body>

<p id="countdown"></p>

<script>

var d=5;  // count-down index

// Update the count down every 1 second
var x = setInterval(function() {

  if (d>=0) {
  document.getElementById("countdown").innerHTML = d;
  d=d-1;
  } 
  else {    // If the count down is over, redirect web page
    clearInterval(x);
    location.replace("https://www.youtube.com/watch?v=dQw4w9WgXcQ&ab_channel=RickAstleyVEVO");
  }
    
}, 1000);
</script>

</body>
</html>

