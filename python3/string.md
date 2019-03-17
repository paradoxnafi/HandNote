Python3 string methods:
 1. mystring.capitalize() # Makes first letter of a string capital, rest small.
 2. mystring.center(30, ‘_’) # Puts my string in the middle of 30 len, fills rest with space. Second par is optional.
 3. mystring.count(‘Apple’, start, end) # Returns the number of occurrence of a string. Rest two par is optional.
 4. mystring.endwith(value, start, end) # Returns true if the string ends with value. Rest two par are optional.
 5. mystring.find(value, start, end) # Returns index number of value in staring, else -1. Last two par are optional.
 6. mystring.isalnum() # Returns true if all char is alpha numeric. Ex (A-z, 0-1). Special char are not.
 7. mystring.isalpha() # Returns true if all char are alphabet. Ex (A-z).  Special char are not and numbers are not.
 8. mystring.isdecimal() # Returns true if the string is Unicode of decimal.
 9. mystring.isidentifier() # Return true if the string is a valid identifier(like a variable).
10. mystring.isdigit() # Returns true is all char are digits.
11. mystring.islower() # Returns true if all char are lower case.
12. mystring.isnumeric() # Returns true if all char are numeric.
13. mystring.isspace() # Returns true if all char are space.
14. mystring.istitle() # Returns true if all all word starts with capital letter and other chars are small.
15. mystring.isupper() # Returns true if all char are uppercase. No problem if white space exists.
16. ‘#’.join(myTuple) # Combines a tuple in a string separated by #.
17. mystring.lower() # Changes all char to lower case.
18. mystring.lstrip(charecter) # Remove all the leading char from a string. Default is space. Par is optional.
19. mystring.partition(‘search_str’) # Returns 3 tuple, all from start <search_str> all to end.
20. mystring.replace(‘one’, ‘two’, 3) # Replace first 2 ‘one’ from string with ‘two’ for 3 times. Last par optional.
21. mystring.rfind(string, start, end) # Returns index of last occurrence. Return -1 if not found. Last two par optional.
22. mystring.split(“,”, max) # Splits a string into list separated by first par. Second par is optional defines max.
23. mystring.rstrip(‘.’) # Removes par from right side. Default is space. Par is optional.
24. mystring.startwith(value, start, end) # Returns true if the string starts with value. Last two par are optional.
25. mystring.strip(value) # Removes all leading or trailing value. Default is white space. Par is optional.
26. mystring.swapcase() # Makes lowercase letters uppercase and uppercase letters lowercase.
27. mystring.upper() # Changes all char to uppercase.
28. mystring.zfill(len) # Fills the array with leading 0 of specific length.
