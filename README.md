expressAmountInWord
===================

This script will express the amount in word

example:

-----------------

<?php
require_once 'AmountInWord.php';
$inputNumber=123456789;
$output=new AmountInWord($inputNumber);
echo $output->convert($inputNumber);
?>


