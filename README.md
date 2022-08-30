# Javascript exercises

# Topics

   * [Before Starting](#antes-de-qualquer-coisa)
      * [About DevTools](#Before-anything)
   * [Exercícios](#exercícios)
      * [Variables and Functions](#variáveis-e-funções)
         * [Exercise 1.1](#Exercise-11)
         * [Exercise 1.2](#Exercise-12)
         * [Exercise 1.3](#Exercise-13)
         * [Exercise 1.4](#Exercise-14)
      * [2. Condicionais (<em>if</em>, <em>else</em>)](#2-condicionais-if-else)
         * [Exercise 2.1](#Exercise-21)
         * [Exercise 2.2](#Exercise-22)
         * [Exercise 2.3](#Exercise-23)
      * [3. Loop](#3-loop)
         * [Exercise 3.1](#Exercise-31)
      * [4. Array](#4-vetores-array)
         * [Exercise 4.1](#Exercise-41)
      * [4. Advanced](#Advanced)
      	* [Exercise 5.1](#Exercise-51)

# Before anything

Before starting, we need good tools to start our work. here some tools:

 - DevTools, which is inside the browser itself (by pressing the 'F12' key, on the browser screen)
 - On "CONSOLE" you can see the functions returns, errors and alerts.
 
 ![image](https://user-images.githubusercontent.com/37451620/187316148-c1d26789-e4c1-46a7-bf95-e2022770e278.png)

# Exercises

## Variables and Functions

### Exercise 1.1

Write a program that **displays** 3 numbers on the screen.

Tip - displaying (or "printing") numbers on the screen:

```javascript
var a = 23;
console.log(a);
```
[Answer](https://codepen.io/bulletsentence/pen/poLMExp?editors=0012)

### Exercise 1.2

Write a program that **reads** 3 numbers and **displays** them on the screen.

Tip - reading numbers:
```javascript
// open a small window with a "prompt" that reads a number typed by the
// user and assign the result to variable "v1"
var v1;
v1 = Number(prompt());
```
[Answer](https://codepen.io/bulletsentence/pen/XWEvjwo?editors=0010)

### Exercise 1.3

Write a program that **reads** 3 numbers, **adds** them and **displays** the average between them.

Tip:
```
The average of two numbers is the sum of the two numbers divided by 2
The average of three numbers is the sum of the three numbers divided by 3
The average of 'n' numbers is the sum of the 'n' numbers divided by 'n'
```
[Answer](https://codepen.io/bulletsentence/pen/yLKmadE?editors=0010)

### Exercise 1.4

Write a program that reads a temperature in Fahrenheit from the user, converts it to degrees Celsius and writes the new value to the screen. The formula for converting Fahrenheit (F) to Celsius is C = ( ( F - 32 ) * 5 ) / 9. Example: 100 Fahrenheit = 37.77 Celsius.

[Answer](https://codepen.io/bulletsentence/pen/rNdXWBo?editors=0010)

## 2. Conditionals (_if_, _else_)

### Exercise 2.1

Write a program that reads 2 numbers, adds them and displays a message with the result only **if** the result is greater than 100.

[Answer](https://codepen.io/bulletsentence/pen/VwXomLv?editors=0010)

### Exercise 2.2

For a game, we need to know whether or not a character died after being attacked. Make a function that takes 2 parameters, 'damage' and 'health'. The function should return '1' if the damage is to kill the character (ie, make their health less than or equal to zero) and '0' otherwise.

Tip - use the following function:
```javascript
function characterDied (damage, health) {
  //
}
```

[Answer](https://codepen.io/bulletsentence/pen/JjLgbRj?editors=0010)

### Exercise 2.3

We need to limit the positions an enemy can walk in on the screen. The lowest possible position is 0 and the highest is 100: any value greater than 100 or less than 0 would go off-screen. We need a LimitPosition function that receives a POSITION that can have any positive or negative value, checks whether it is valid or not, and always returns a corrected value between 0 and 100.

Tip - use the following function:
```javascript
function limitPosition(position) {
  // function code
}
```

## 3. Loop

### Exercise 3.1

Write a program that calculates and displays the multiplication table (up to 10x) of any number entered by the user.

## 4. Vectors (array)

### Exercise 4.1
Write a program that reads a 10-position numeric vector. Then sort the vector in ascending order and display the sorted elements.

## 5. Advanced (JSON, OBJECTS, DOM)

### Exercise 5.1
Create a function that given the following object:

```javascript
var address = {
		street: "Avenue North-west",
		number: 1293,
		district: "Center",
		city: "Calgary",
};
```
Return the following content:

```javascript
`The user lives in Calgary, in the Center district, at Avenue North-west, number 1293.`

```
