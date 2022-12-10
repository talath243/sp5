<?php
echo "Welcome to the stage where are ready to get connect to a database <br>";

$servername = "localhost";
$username = "root";
$password = "";

$conn = mysqli_connect($servername, $username, $password);

echo "Connnection was successful";

?>