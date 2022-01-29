# hello-world
PHP Code will be updated here 
PHP Loops
----------
There are 4 types of LOOPS in PHP
1. While Loops
2. Do while loops
3. For Loop
4. Foreach loop

While Loop
------------
Syntax >>
while (condition is true){
  code to be executed;
}

Example:
<?php
$x = 1;
while ($x <= 5){
echo "The Number is : $x <br>";
  $x++;
}
?>

Do while loops
---------------
Syntax >>
do {
  code to be executed;
}while(condition is true)

Example: 
<?php
$x = 1;
do{
  echo "The Number is: $x <br>";
  $x++;
} while ($x <= 5 );
?>

For Loop
---------
for (init counter; test counter; increment counter) {
  code to be executed for each iteration;
} 

Example: 
------------

<?php
for ( $x = 0; $x <= 10; $x++){
  echo "The Number is: $x <br>";
}
?>
