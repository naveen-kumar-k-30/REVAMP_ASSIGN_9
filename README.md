# REVAMP_ASSIGN_10

# JavaScript Fundamentals Assignment

**1. What is JavaScript?**
JS is an Interpreter, Dynamic, single-threaded/synchronous language.
It is used to build our webpage dynamically


**2.Variables and Types:**

```js
let userAge=20;
let userName="Naveen kumar";
console.log(userAge);
console.log(userName);

Output:
20
Naveen kumar

```

**3.Comments in JavaScript:**

```js
/* This function greets the user by their name. It takes one parameter: the name of the user. It returns a greeting message that includes the user's name. */

let a="Naveen"
function greetUser(a){
  console.log("Hello",a);
}
greetUser(a);

```

Write a multi-line comment explaining the purpose of a function you create in the next step.

**4.Operations:**

```js
let a=20;
let b=40;
console.log(a+b);//addition
console.log(a-b);//subtraction
console.log(a*b);//multiplication
console.log(a/b);//division 

Output:

60
-20
800
0.5
```

**5.Data Types:**

```js
let myString = "Hello, World!";
console.log(myString); // Outputs: Hello, World!

let myNumber = 20;
console.log(myNumber); // Outputs: 20

let myBoolean = true;
console.log(myBoolean); // Outputs: true

let myArray = [1, 2, 3, 4, 5];
console.log(myArray); // Outputs: [1, 2, 3, 4, 5]
```


**6.Functions in JavaScript:**

```js
let a="Naveen"
function greetUser(a){
  console.log("Hello",a);
}
greetUser(a);

Output:
Hello Naveen
```

**7.if Else in JavaScript:**

```js

let temperature = 25;

if (temperature > 30) {
    console.log("It's hot outside!"); 
} else {
    console.log("The temperature is comfortable.");
}

Output:

The temperature is comfortable.
```



**8.FOR LOOP:**
Use a for loop to print the numbers from 1 to 5 in the console.

```js
for (let i = 1; i <= 5; i++) {
    console.log(i);
}

Output:
1
2
3
4
5
```

**9.Loose vs Strict Equality:** <br>
Explain the difference between loose equality (==) and strict equality (===) with examples.<br>

```js
console.log(5 == '5'); // Outputs: true
console.log(5 === '5'); // Outputs: false
```
<br>Loose equality (==): Compares two values for equality, converting the types if they are different.<br>
Strict equality (===): Compares both the value and the type of the variables, ensuring they are identical in type and value.<br>


# REVAMP_ASSIGN_9

# Explore Menu

This is a simple webpage that displays an "Explore Menu" section with multiple cards. Each card showcases a menu item with an image, title, and a "View More" button.

## Technologies Used

- HTML
- Tailwind CSS
- Google Fonts
 
## HTML Structure

**Head Section**:
  - Includes meta tags for character set and viewport settings.
  - Links to Tailwind CSS CDN.
  - Links to Google Fonts for the 'Poppins' font.

 **Body Section**:
  - Contains a section with a container div.
  - Includes multiple card divs, each with an image, title, and "View More" button.

## Resources Used

  - **Tailwind CSS**: A utility-first CSS framework for rapidly building custom user interfaces.
  - [Tailwind CSS CDN](https://cdn.tailwindcss.com)
  - [Tailwind CSS Documentation](https://tailwindcss.com/docs)
  
  - **Google Fonts**: A library of free and open source web fonts.
  - [Poppins Font](https://fonts.googleapis.com/css2?family=Poppins:wght@100;200;300;400;500;600;700;800;900&display=swap)
  - [Google Fonts](https://fonts.google.com)
  
  - **ImageKit**: An image CDN that provides real-time image optimization and transformation.
  - Image URL: [Ginger Fried Image](https://ik.imagekit.io/4z8covdo9/Full%20stack/em-ginger-fried-img.png?updatedAt=1702351480869)
  - [ImageKit](https://imagekit.io)





