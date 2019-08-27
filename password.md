Let's test your scripting skills, below is a guide to how I generate super-strong uncrackable passwords ;)

# Password Generation 
Inputs:
- cities = list of cities that can be found on my Git
- date = the date of when the list was generated (YYYYMMDD, e.g. 20190525 is 25th of May 2019)

First, we strip out all the spaces in the list of cities.
Next, we append the date and encode to base64
We reverse each line
We hash each line using md5
And just for fun, for every two characters, we swap them (e.g. ab12gh becomes ba21hg)

#### the password is somewhere inside the final list...

## LET'S TRY!!

