numericfield.js
===============
This plugin forces input boxes to allow only numbers with/without decimal places.

Dependency
----------
1. jQuery 1.7+

Usage
-----
	<input type="text" class="number1" />
	<input type="text" class="number2" />

	$('input.number1').numericfield(option);
	$('input.number2').numericfield({
		allow_decimal: true
	});

	$('input.number2').numericfield("destroy");

or just:

	<input type="text" data-type="number" />
	<input type="text" data-type="number" data-decimal="true" />
