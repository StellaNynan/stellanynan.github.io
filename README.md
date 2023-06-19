<html>
<script>
function add()
    {
    var numOne, numTwo, sum;
    numOne = parseInt(document.getElementById("first").value);
    numTwo = parseInt(document.getElementById("second").value);
    sum = numOne + numTwo;
    document.getElementById("answer").value = sum;
    }
</script>
<body>

<h1>PAYE tax calculator</h1>
<p>Enter the First Number: <input id="first"></p>
<p>Enter the Second Number: <input id="second"></p>
<button onclick="add()">Add</button>
<p>Sum = <input id="answer"></p>


</body>
</html>
