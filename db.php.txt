<?php
//Database connection.
$con = mysqli_connect(
   "localhost", //Server host name.
   "root", //Database username.
   "", //Database password.
   "syntages" //Database name
);

// Change character set to utf8
mysqli_set_charset($con,"utf8");

//Check connection
if (mysqli_connect_errno()) {
   echo "Failed to connect to MySQL: " . MySQLi_connect_error();
}
?>