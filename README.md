# Pr3_Glazunova_lab3
<!DOCTYPE html>
<html>

<head>
<script src="http://code.jquery.com/jquery-latest.js">
</script>
  
<script>
$(document).ready(function ()
{
$("#but1").click(function () 
{
$("tr:odd").hide();
});
$("#but2").click(function ()
{
$("tr:odd").show();
});
});
</script>

</head>
  
<body>

<button id="but1">Скрыть</button>
<button id="but2">Показать</button>
<table border="1">
<tr>
<th>ФИО</th>
<th>Оценка</th>
</tr>
<tr>
<th>Васильев И.О.</th>
<th>2</th>
</tr>
<tr>
<th>Миронов И.Г.</th>
<th>5</th>
</tr>
<tr>
<th>Гудков Е.И.</th>
<th>4</th>
</tr>
<tr>
<th>Ловинов И.О.</th>
<th>4</th>
</tr>


</body>
</html>
