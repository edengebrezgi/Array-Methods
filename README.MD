STRING-METHODS


.charAt()
charAt method returns the character at a specified index. 
*time complexity of o(1)
Example:
string.charAt(4) //get the character at the forth index
string.charAt(string.length-1) //get the last character at last index



.charCodeAt()
charCodeAt method returns the unicode of the c
haracter at the specified index. 
*time complexity of o(1)
Example:
string.charCodeAt(4) //unicode of e



.concat()
concat method concatenates the string arguments to a 
single string. 
*time complexity of o(n). 
n is the length of string to be concatenated. 
Example:
string.concat(' Goodbye!') //concatenates a goodbye to the string



.includes()
includes method that does a case sensitive 
check to see if a string exists in another string, 
returning a true or false.
*time complexity of o(n)
Example:
string.includes('hello') //returns false because 'hello' does not exist in string
string.includes('day') //returns true because 'day' exists in string



.indexOf()
indexOf method returns the index of the first occurrence
of specified string. Returns -1 if not found. 
*time complexity of o(n)
Example:
string.indexOf('we') // returns 14 because the first occurrence, w, is at index 14.
string.split(' ').indexOf('we') //returns 2 because the string is split via words, so we looked for the specified word in the string



.match()
match method returns the result of a 
matching string using a regular expression.
*time complexity of o(n)
Example:
string.match(/[e]/g) // returns 3 'e' cause it matched
string.match('e') // returns information about where string is located. first occurrence when it comes to index.



.repeat()
repeat method returns a new string that contains the 
number of copies of a specified string concatenated together.
*time complexity of o(n)
Example:
string.repeat(2) //repeats the string 2 times and concatenates them



.replace()
replace method returns a new string with 
some or all matches replaced by a specified replacement.
Can be used with RegExp. If used with a string, only the first
occurrence will be replaced. 
*time complexity is o(n)
Example:
string.replace('Wonderful', 'Great') // returns Great day we are having!
string.replace(/[!]/g, '?') //replaces ! with ? -> Wonderful day we are having?



.slice()
slice method extracts a section of a string
and returns it 
*time complexity of o(n)
Example:
string.slice(0, 9) //returns wonderful as a new string



.split()
split method separates a string into an
array of substrings. 
*time complexity of o(n)
Example:
string.split('') //separates by letter
string.split(' ') //separates by word



.substr()
substr method returns a portion of a string 
from a specified index until a given number
or characters after. 
*time complexity of o(n)
Example:
string.substr(0, 13) // returns everything in between index 0 and index 13



.toLowerCase()
tolowerCase method takes a string and returns the 
string with all the characters in lower case. 
*time complexity of o(n) 
Example:
string.toLowerCase() //changes to lowercase



.toUpperCase()
toUpperCase method takes a string and returns the
string with all the characters in upper case case.
*time complexity of o(n) 
Example:
string.toUpperCase() //changes to uppercase



.trim()
trim method removes the whitespace or
empty space from both ends of a string. 
*time complexity of o(n) 
Example:
string2.trim() //removes whitespace from beginning and from end




