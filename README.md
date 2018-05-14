<?php
if($custCode = $_GET['CodeField']) setcookie('CakeCustomer', $custCode, time() + 60*60*2);  else $custCode = 'Unknown';
?>
