This vim indent script for PHP was included in versions 6.X of the official vim distribution.
It was replaced by another script which seems to work for some.  But, it never works for the way
I like to indent php code.

In general, I prefer to use tab indentation and do not mix html and php code where it can be avoided.

The current version is 1.2 as of 2007-2015.

Example of automatically indented code using this indent script.  All leading whitespace is tab below:
<pre>

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
</pre>

