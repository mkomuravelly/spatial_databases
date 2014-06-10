
#####  Assignment 2 

#####  Connecting to MYSQL DATABASE 
````
<?php
$con=mysqli_connect("localhost","mkomuravelly","lavanya26","mkomuravelly");

// Check connection
if (mysqli_connect_errno()) {
  echo "Failed to connect to MySQL: " . mysqli_connect_error();
}

mysqli_close($con);

echo "Connection Success";
?>
````
