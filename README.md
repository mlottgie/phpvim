This vim indent script for PHP was included in versions 6.X of the official vim distribution.
It was replaced by another script which seems to work for some.  But, it never works for the way
I like to indent php code.

In general, I prefer to use tab indentation and do not mix html and php code where it can be avoided.

## Options
  - php_noindent_switch=1 -- do not try to indent switch/case statements or comments (version 0.1 behavior)
  - php_indent_shortopentags=1 -- indent after short php open tags, too
  - php_no_autocomment=1  -- do not automatically format comment sections
  - php_indent_space=1 -- Use spaces instead of tabs...

The current version is 1.3 as of 2019

Example of automatically indented code using this indent script.  All leading whitespace is tab below:
```php
	$var = array(
		'one' => 1,
		'two' => 2
	);
	/* Comment section
	 * line two
	 */

	// more code here
	function test($var)
	{
		print_r($var);
	}

	switch($argv[1])
	{
		case 'a':
			echo "A!\n";
			break;
		case 'b':
			echo "B!\n";
			break;
		default:
			echo "No!\n";
	}
```

