# FizzBuzz

### This is my solution for FizzBuzz using JavaScript:

  ```<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>Fizz Buzz</title>
<script>

function fizzbuzz() {
	var display = document.getElementById('display');
	var displayHTML = "";
    var result = "";
	for (i = 1; i < 101; i++) {
        if (i % 3 === 0) {
            result = "Fizz"
        } else if (i % 5 === 0){
            result = "Buzz"
        }else {
            result = i;
        }
        
        
		displayHTML += "<p>" + result + "</p>";
	}
	display.innerHTML = displayHTML
}

</script>

</head>

<body onload="fizzbuzz()">
<div id="display">

</div>
</body>

</html>
```
__[Take Me Back!](https://github.com/noahmcallister04/Home-Page)__
__[Next Page]()__
