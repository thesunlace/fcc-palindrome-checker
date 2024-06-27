# fcc-palindrome-checker
A Palindrome Checker for a project in [freeCodeCamp](https://www.freecodecamp.org/learn).

## Criterias that needed to be met:

- You should have an ```input``` element with an ```id``` of ```"text-input"```.
    - When the ```#text-input``` element only contains the letter ```A``` and the ```#check-btn``` element is clicked, the ```#result``` element should contain the text ```"A is a palindrome"```.
    - When the ```#text-input``` element contains the text ```eye``` and the ```#check-btn``` element is clicked, the ```#result``` element should contain the text ```"eye is a palindrome"```.
    - When the ```#text-input``` element contains the text ```_eye``` and the ```#check-btn``` element is clicked, the ```#result``` element should contain the text ```"_eye is a palindrome"```.
    - When the ```#text-input``` element contains the text ```race car``` and the ```#check-btn``` element is clicked, the ```#result``` element should contain the text ```"race car is a palindrome"```.
    - When the ```#text-input``` element contains the text ```not a palindrome``` and the ```#check-btn``` element is clicked, the ```#result``` element should contain the text ```"not a palindrome is not a palindrome"```.
    - When the ```#text-input``` element contains the text ```A man, a plan, a canal. Panama``` and the ```#check-btn``` element is clicked, the ```#result``` element should contain the text ```"A man, a plan, a canal. Panama is a palindrome"```.
    - When the ```#text-input``` element contains the text ```never odd or even``` and the ```#check-btn``` element is clicked, the ```#result``` element should contain the text ```"never odd or even is a palindrome"```.
    - When the ```#text-input``` element contains the text ```nope``` and the ```#check-btn``` element is clicked, the ```#result``` element should contain the text ```"nope is not a palindrome"```.
    - When the ```#text-input``` element contains the text ```almostomla``` and the ```#check-btn``` element is clicked, the ```#result``` element should contain the text ```"almostomla is not a palindrome"```.
    - When the ```#text-input``` element contains the text ```My age is 0, 0 si ega ym.``` and the ```#check-btn``` element is clicked, the ```#result``` element should contain the text ```"My age is 0, 0 si ega ym. is a palindrome"```.
    - When the ```#text-input``` element contains the text ```1 eye for of 1 eye.``` and the ```#check-btn``` element is clicked, the ```#result``` element should contain the text ```"1 eye for of 1 eye. is not a palindrome"```.
    - When the ```#text-input``` element contains the text ```0_0 (: /-\ :) 0-0``` and the ```#check-btn``` element is clicked, the ```#result``` element should contain the text ```"0_0 (: /-\ :) 0-0 is a palindrome"```.
    - When the ```#text-input``` element contains the text ```five|\_/|four``` and the ```#check-btn``` element is clicked, the ```#result``` element should contain the text ```"five|\_/|four is not a palindrome"```.
    - When the ```#text-input``` element contains an alphanumeric palindrome, the ```#result``` element should correctly identify it as a palindrome.
    - When the ```#text-input``` element contains a random sequence of alphanumeric characters that is not a palindrome, the ```#result``` element should say it is not a palindrome.
- You should have a ```button``` element with an ```id``` of ```"check-btn"```.
    - When you click on the ```#check-btn``` element without entering a value into the ```#text-input``` element, an alert should appear with the text ```"Please input a value"```.
- You should have a ```div```, ```span```, or ```p``` element with an ```id``` of ```result```.