<?php 
// PHP program to Find the two  
// repeating elements in  
// a given array 

function printRepeating($arr, $size) 
{ 

    $i; 

    $j; 

    echo " Repeating elements are "; 

    for($i = 0; $i < $size; $i++) 

        for($j = $i + 1; $j < $size; $j++) 

            if($arr[$i] == $arr[$j]) 

                echo $arr[$i], " "; 
}  

$arr = array(0, 1, 2, 3, 4, 5, 6, 7, 7, 8, 9, 10); 

$arr_size = sizeof($arr, 0); 

printRepeating($arr, $arr_size);

?> 
