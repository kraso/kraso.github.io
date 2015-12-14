---
layout: default
---

<?php

$name=$_POST["name"];
$firm=$_POST["firm"];
$value=$_POST["value"];

echo "$name <br> $firm <br> $value";

if(!empty($name) || !empty($firm) || !empty($value)){

$cvsData = $name . "," . $firm . "," . $value  . "\n"; // Add newline

$fp = fopen("_data/vplacila.csv","a"); // $fp is now the file pointer to file $filename

    if($fp)
    {
        fwrite($fp,$cvsData); // Write information to the file
        fclose($fp); // Close the file
    }
}
?>

Hvala
