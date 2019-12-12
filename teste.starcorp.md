#teste realizado para StarCorp em PHP

<!DOCTYPE html>
<html>
<head>
	<title>TESTE StarCorp</title>
</head>
<body>
<?php
	for($contagem = 1; $contagem <= 100; $contagem++){
		echo $contagem."<br/>";
		
	if ($contagem%3==0) {
		echo "StarCorp";}
		
	elseif ($contagem%5==0) {
		echo "IT";}

	if($contagem%3==0 && $contagem%5==0) {
		echo "StarCorpianos"."<br/>";}
		
	}
?>

</body>
</html>
