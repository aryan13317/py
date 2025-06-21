## Exercise: String in Python

1. Create 3 variables to store street, city and country, now create address variable to
store entire address. Use two ways of creating this variable, one using + operator and the other using f-string.
Now Print the address in such a way that the street, city and country prints in a separate line

street="ganyari"
city="singrauli"
country="india"
address=street+" "+city+" "+country
address
'ganyari singrauli india'
address1=f'{street} {city} {country}'
address1
'ganyari singrauli india'
print(f'{street}\n{city}\n{country})
      
SyntaxError: unterminated f-string literal (detected at line 1)
print(f'{street}\n{city}\n{country}')
      
ganyari
singrauli
india


2. Create a variable to store the string "Earth revolves around the sun"
    1. Print "revolves" using slice operator
    2. Print "sun" using negative index

sent="Earth revolves around the sun"
      
print(sent[7:15])
      
evolves 
print(sent[6:15])
      
revolves 
print(sent[-3:])
      
sun



3. Create two variables to store how many fruits and vegetables you eat in a day.
Now Print "I eat x veggies and y fruits daily" where x and y presents vegetables and fruits that you eat everyday. Use python f string for this.

no_of_fru=4
      
no_of_veg=6
      
print(f'I eat {no_of_veg} veggies and {no_of_fru} fruits daily')
      
I eat 6 veggies and 4 fruits daily


4. I have a string variable called s='maine 200 banana khaye'. This of course is a
wrong statement, the correct statement is 'maine 10 samosa khaye'.
Replace incorrect words in original strong with new ones and print the new string.
Also try to do this in one line.

s='maine 200 banana khaye'
      
sc=s.replace('200 banana','10 samosa')
      
print(sc)
      
maine 10 samosa khaye


[Solution](https://github.com/codebasics/py/blob/master/Basics/Exercise/4_strings/4_string_exercise_answer.py)
