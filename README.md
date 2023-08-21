# wk-1-toy-problems


## Table of content
* Description 
* Installation requirement
* Technology used
* Licence
* Authors info

# DESCRIPTION
## conversion.py
In this challenge, you are provided with a time in the 12-hour format (hour ranging from 1 to 12, minute from 0 to 59, and period "am" or "pm"). The goal is to convert this time into the 24-hour format and return it as a four-digit string.

The convert_to_24_hour function takes three arguments: hour, minute, and period. It first checks if the period is "pm" or "am". If it is, it adds 12 to the hour (except for 12 PM, which remains 12). If the period is "am", the function converts 12 AM to 0 hour, otherwise, it keeps the same hour. The function then formats the hour and minute with leading zeros (if needed) and combines them to form a four-digit string representing the time in 24-hour format.
## positive_numbers.py
In this challenge, you are given three integers a, b, and c. You need to determine if exactly two of these three integers are positive (greater than zero).

The positive_count function takes three integer arguments: a, b, and c. It calculates the sum of positive numbers among the three arguments using a generator expression and the sum function. If two of the integers are positive , the function returns True; otherwise, it returns False.

## value.py
In this challenge, you are given a lowercase string consisting of alphabetic characters only. You need to find the highest value of consonant substrings. Consonants are defined as any letters of the alphabet except "aeiou", and each consonant has a corresponding value from a=1 to z=26.
The highest_consonant_value function takes a string s as input. It iterates through each character in the string and checks if the character is a consonant using the is_consonant function. If it's a consonant, the function calculates the value of the consonant using the get_consonant_value function and adds it to the current_value variable. The function also keeps track of the max_value, updating it whenever a higher value is encountered. If a vowel is encountered, the current_value is reset to 0. The function returns the max_value at the end, which represents the highest value of consonant substrings in the input string.

# INSTALLATION PROCESS
## Frontend
* Git clone the repository to your local machine using the command ` git clone https://github.com/Mercy-chepchirchir/wk-1-toy-problems`
* Navigate to the code challenge directory using `cd wk-1-toy-problems`

# TECHNOLOGY USED
python


# LICENSE
MIT license

# AUTHORS INFO
Mercy Chepchirchir

