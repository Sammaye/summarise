Summarise
=========

Makes alerts more...responsive.

It is based around Bootstrap CSS classes and what not and is a small but quite powerful layer to make dealing with alerts on Ajax forms and other items a lot easier.

Let's get some example out there. 

There are two ways to use this plugin, either you can initialise all alerts at page load with:

	$('.alert').summarise(options);
	
Or you can do it on demand like:

	$('.alert').summarise({},'error','Oops!!');
	
Once you have an alert setup you can change any part of it by calling some functions. For example to change the type from error to success:

	$('.alert').summarise('type','success');
	
Or to change the content:

	$('.alert').summarise('content', 'Something happened the rigtht way!')

Take a look at the very simple, 150 line-odd, source code to understand more. 
