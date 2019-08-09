# Password Generation 
cities = list of cities in the "Olympics_2020.txt" file
date = defaced date showed on the webpage(8 digits)
duration(of Olympics) = 17

cities_tmp = hexadecimal format of md5 hashed cities
date_tmp = reverse the date, take the difference of revered date bits shifted to the right by tens of duration and bits shifted to the right by units of duration

list = (date_tmp) append (cities_tmp chars in even position) + (cities_tmp chars in odd position) append (date_tmp) 
%% python index position

then do base64 encode

double the list with splitting each word in even and odd positoin

double the list with original one and swapcase one

finally even double the list with original list rotate right by 1 and original list rotate left by 1

### the password is inside the final list 

## LET'S TRY!!

