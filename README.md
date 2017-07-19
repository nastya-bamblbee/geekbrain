# geekbrain
<meta charset = "utf-8">
<script>
var Sum = +prompt("Введите сумму вклада");
var Proc = +prompt("Введите проценты");
for (var i = 0; i < 5; i++) {
  var sumYear = Sum * (Proc/100);
  Sum = Sum + sumYear;
  alert("Вклад увеличится на " + sumYear.toFixed(2) + ". Итогавая сумма за " + (i + 1) + " год составляет " + Sum.toFixed(2) + ".");
}

</script>
