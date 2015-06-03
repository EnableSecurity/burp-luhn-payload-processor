# Burp Luhn Payload Processor

By: [Sandro Gauci](mailto:sandro@enablesecurity.com)

This is a payload pre-processor module to add a check digit to numeric values
passed to Burp's Intruder.

For example, if you want to generate requests with 10000 to 99999 and ending
with a check digit, this module will generate the following values for you:

	100008
	100016
	100024
	...
	999995


