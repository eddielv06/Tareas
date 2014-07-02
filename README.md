Tareas
======

Tareas PW
<?php
echo "EJERCICIO 01.";

verifica(3,4);

function verifica($x,$y)
{
    if($x<=0 || $x>255) 
       echo "-1";
    else
        {
         if($y<=0 || $y>255)
         echo "-1";
	else{

		 $resultado=8+4;
	         echo "<br> El resultado es ".$resultado."<br>";
	    }
        }
    
}






echo "<br>"."EJERCICIO 21.";


$arreglo[0][0]="a";
  $arreglo[0][1]="b";
  $arreglo[0][2]="c";
  $arreglo[1][0]="d";
  $arreglo[1][1]="e";
  $arreglo[1][2]="f";
  $arreglo[2][0]="g";
  $arreglo[2][1]="h";
  $arreglo[2][2]="i";
   
		
                $resulta=$arreglo[0][0].$arreglo[0][1];
                $resulta=$resulta.$arreglo[0][2];
                $resulta=$resulta.$arreglo[1][2];
                $resulta=$resulta.$arreglo[2][2];
                $resulta=$resulta.$arreglo[2][1];
                $resulta=$resulta.$arreglo[2][0];
                $resulta=$resulta.$arreglo[1][0];
                $resulta=$resulta.$arreglo[1][1];
                
                echo "<br>"."el resultado es ".$resulta."<br>";



echo "<br>"."EJERCICIO 22.";

$arreglo[0][0]=5;
  $arreglo[0][1]=4;
  $arreglo[0][2]=7;
  $arreglo[1][0]=1;
  $arreglo[1][1]=2;
  $arreglo[1][2]=3;
  $arreglo[2][0]=3;
  $arreglo[2][1]=2;
  $arreglo[2][2]=1;
   
		
                $resulta=$arreglo[0][0]+$arreglo[0][1];
                $resulta=$resulta-$arreglo[0][2];
                $resulta=$resulta*$arreglo[1][2];
                $resulta=$resulta+$arreglo[2][2];
                $resulta=$resulta-$arreglo[2][1];
                $resulta=$resulta*$arreglo[2][0];
                $resulta=$resulta+$arreglo[1][0];
                $resulta=$resulta-$arreglo[1][1];
                
                echo "<br>"."el resultado es ".$resulta;



?>
