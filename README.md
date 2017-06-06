## Usage

```php

// include function
include 'print_d.php';

// echo simple string
echo print_d('Simple string');

// echo variable
$int = 1;
echo print_d($int);

// echo classes
class Test
{
	var $a = 'a',
		$b = 'b';

	function method1($a)
	{		
	}
}
$obj = new Test;
echo print_d($obj); // prints object variables
echo print_d($obj, true); // prints object variables and methods with attribute descriptions

```

## Screenshots

![Print_d](https://raw.githubusercontent.com/CesiumComputer/print_d/master/example.png)
