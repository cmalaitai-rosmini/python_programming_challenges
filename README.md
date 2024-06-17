# python_programming_challenges
## Input & Output Problems
### 01. Three In, Three Out
Write a program that will allow a user to enter their name (string), their age (integer) and their favourite TV program (string). The program will then display the information entered and some additional text on separate lines.
An example of the input and output from the program is shown below.

#### Input:
```
Lister
39
Red Dwarf
```

#### Output:
```
Lister
is
39
years old and likes
Red Dwarf
```

### 02. Name Swapper
Write a program that will ask the user to type in their first name and surname. The program will then
display the two names in reverse order.

#### Input:
```
David
Tennant
```

#### Output:
```
Tennant David
```


### 03. Three In, Three Out (formatted)
Now edit program 1 so that the information entered is displayed differently as shown in the output box below. Note - your output will now have to display variables and text together.

#### Input:
```
David
Tennant
```

#### Output:
```
Tennant David
```

### 04. Postcode Formatter
Ask your user to enter the four separate sections of a post code. Postcodes take the following form:
letters, number, number, letter
Once entered the postcode should be displayed with a space in the middle.

#### Input:
```
KY
8
1
HL
```

#### Output:
```
KY8 1HL
```

### 05. Calculate the Area of a Rectangle
Ask your user to enter the length and width of a rectangle. Your program should calculate the area of the rectangle (length*width) and display the result with a suitable message.

#### Input:
```
12
6
```

#### Output:
```
The are of the rectangle is:
72 square centimetres
```

### 06. Calculate the Area of a Circle
Ask your user to enter the radius of a circle. Your program should use what they have enter to calculate the area of the circle (3.14 * radius * radius) and display the result.

#### Input:
```
16
```

#### Output:
```
The are of the circle is:
803.84 square centimetres
```

### 07. Number Generator (2 digits)
Write a program that inputs two individual integers between 0 and 9. The program should then perform a calculation and store a single number in a third variable called ‘total’ as shown below.
The total should then be displayed on the screen.

#### Input:
```
2
6
```

#### Output:
```
26
```

### 08. Number Generator (3 digits)
Adapt program 7 to work for 3 numbers instead of 2.

#### Input:
```
3
5
7
```

#### Output:
```
357
```

### 09. Calculating the Atomic Weight of Hydrocarbons (Alkanes)
A hydrocarbon is a molecule made up of linked Carbon (C) atoms with Hydrogen (H) atoms branching off each Carbon. Your program will ask the user to enter the number of Carbon atoms in a hydrocarbon and use the number entered to then calculate the number of Hydrogen atoms using the formula below. Both numbers should be stored.

>number of H atoms = (number of C atoms x 2) + 2

The atomic weight of the molecule is calculated by multiplying the number of carbon atoms by 12 and adding the number of hydrogen atoms. The number of C and H atoms along with the atomic weight should be displayed as shown in the output below.
#### Input:
```
3
```

#### Output:
```
The atomic mass of C3H8 is 44
```

### 10. Calculating the Atomic Weight of Hydrocarbons (Alkanes)
The “standard scratch” of a golf course is calculated by adding together the number of shots it should
take to complete each hole. This score is then adjusted depending on the difficulty of the course.
For example:

>2 holes take 5 shots (par 5) 2x5 = 10<br>
10 holes take 4 shots (par 4) 10x4 = 40<br>
6 holes take 3 shots (par 3) 6x3 = 18 10+40+18 = 68 shots in total<br>
Difficulty adjustment -2 68-2 = 66<br>
Standard Scratch = 66

Write a program that allows the user to enter the information required to calculate the standard scratch
score of a golf course. The standard scratch should then be calculated and displayed.
#### Input:
```
6
10
2
-2
```

#### Output:
```
66
```