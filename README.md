# Password-Generator

For this problem you have to write a function which generates a password depending on input information. As such, you will be given an array of three strings. The first two strings will be at least 10 characters long, the third one will be one word. 

Your task here is to concatenate the first two strings and replace all vowels in the concatenated string with symbols from the third string. First vowel must be replaced with the first character from third string, second vowel with the second character from that string and so on. If the third string is less than the vowels count in the newly formed string you need to start over with character on 0 index. When you replace all vowels reverse the new password and print it on the console in a format: 

 'Your generated password is {password}' 

Note: All replaced vowels with the characters from the third string must be upper-case, the rest of the characters are lower-case.
