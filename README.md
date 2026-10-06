<!DOCTYPE html> 
<html> 
<head> 
<title>Premier script PHP</title> 
<meta charset="UTF-8"> 
</head> 
<body> 
<?php 
//Ceci est un commentaire PHP 
echo "<h3 style='color: pink'>Mon premier script PHP</h3><br>"; 
echo "Bonjour tout le monde";
echo "<h3 style='color: blue'>Heure actuelle</h3>"; 
echo "Il est : " . date("H:i:s");
echo"<p>Je m'appelle <b>Rawia</b> et j'ai 20 ans</p>";
$MyName = "Rawia";
$MyAge = 20;
$MyBloodType = "O+";
echo "<p>Je m'appelle <b>$MyName</b> et j'ai $MyAge ans. Mon groupe sanguin est $MyBloodType.</p>";
$_COOKIE["user"] = "Rawia";
backgroundcolor: lightblue;
?>
<style>
    p {
        color: purple;
    }
</style>
