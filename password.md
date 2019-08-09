# Password Generation 
- cities = list of cities in the "Olympics_2020.txt" file
- date = defaced date showed on the webpage(8 digits)
- duration(of Olympics) = 17
<br>
- cities_tmp = hexadecimal format of md5 hashed cities
<br>
- date_tmp = reverse the date, take the difference of revered date bits shifted to the right by tens of duration and bits shifted to the right by units of duration
<br>
- list = (date_tmp) append (cities_tmp chars in even position) + (cities_tmp chars in odd position) append (date_tmp)
<br>
<br>
then do base64 encode
<br>
double the list with splitting each word in even and odd positoin
<br>
double the list with original one and swapcase one
<br>
finally even double the list with original list rotate right by 1 and original list rotate left by 1

#### the password is inside the final list

## LET'S TRY!!

