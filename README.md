# php-number  

## getting started  
``` 
include 'Number.php';  
use Prototypeblocks\Number;  
``` 
## examples  
#### average
``` 
$numbers = array(10, 15, 20, 25);
$average = Number::average($numbers);
// $average is 17.50
``` 
``` 
$numbers = array(10, 15, 20, 25);
$average = Number::average($numbers, 0);
// $average is 18
``` 
#### max
``` 
$numbers = array(10, 15, 20, 25);
$max = Number::max($numbers);
// $max is 25.00
``` 
``` 
$numbers = array(10, 15, 20, 25);
$max = Number::max($numbers, 0);
// $max is 25
``` 
#### min
``` 
$numbers = array(10, 15, 20, 25);
$min = Number::min($numbers);
// $min is 10.00
``` 
``` 
$numbers = array(10, 15, 20, 25);
$min = Number::min($numbers, 0);
// $min is 10
``` 
#### percentage
``` 
$percentage = Number::percentage(20, 100);
// $percentage is 20.00  
``` 
``` 
$percentage = Number::percentage(20, 100, 0);
// $percentage is 20
``` 
#### random
``` 
$random = Number::random();
// $random could be 6450972  
``` 
``` 
$random = Number::random(5, 25);
// $random could be 15  
``` 
#### round
``` 
$round = Number::round(15.175);
// $round is 15
``` 
``` 
$round = Number::round(15.175, 2);
// $round is 15.18 
``` 
#### total
``` 
$numbers = array(10, 15, 20, 25);
$total = Number::total($numbers);
// $total is 70.00 
``` 
``` 
$numbers = array(10, 15, 20, 25);
$total = Number::total($numbers, 0);
// $total is 70 
``` 
