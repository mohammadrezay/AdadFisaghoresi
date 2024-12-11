# AdadFisaghoresi
https://quera.org/problemset/280?tab=description
<?php
$a = (int)readline("enter a number: ");
$b = (int)readline("enter a number: ");
$c = (int)readline("enter a number: ");
if ( $a**2 + $b**2 == $c**2 or $a**2 + $c**2 == $b**2 or $b**2 + $c**2 == $a**2){
	echo "Yes";
}else{
	echo "No";
}
