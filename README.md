# decimaltime

## What is it?
It is a time measurement where 

* A day has 10 hours
* One hour has 100 minutes
* One minute has 100 seconds

It is like the frenchy guys once did in their frenchy revolution. 
See [Wikipedia](https://en.wikipedia.org/wiki/Decimal_time).

## Before using

Just make it executable: `chmod +x decimaltime`

## Usage

	./decimaltime

## Example

	$ # Using decimaltime at 1:11:23 pm
	$ ./decimaltime
	5:49:57 

## Options
Within the bash script you have the option to put decimal miliseconds behind it seperated by point, comma or what ever (as `$LC_NUMERIC` says).
To show it, switch `decimalplace=false` to `decimalplace=true`.



