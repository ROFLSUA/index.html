# index.html
<!DOCTYPE html>
<html>
<head>
  <title>Калькулятор</title>
</head>
<body>
  <script>
    var number1 = prompt("Введіть перше число:");
    var number2 = prompt("Введіть друге число:");
    number1 = parseFloat(number1);
    number2 = parseFloat(number2);
    var sum = number1 + number2;
    var difference = number1 - number2;
    var product = number1 * number2;
    var quotient = number1 / number2;
    alert(number1 + " + " + number2 + " = " + sum);
    alert(number1 + " - " + number2 + " = " + difference);
    alert(number1 + " * " + number2 + " = " + product);
    alert(number1 + " / " + number2 + " = " + quotient);
  </script>
</body>
</html>
