# Quiz 4 to 7 Corrections

## Quiz 4

No corrections

## Quiz 5

No corrections

## Quiz 6

### Question 3

I answered prompt and Math.random, but the correct answer is prompt, alert, and console.log. This is because these three methods have parentheses to allow the coder to put in parameters, which it will then display. Math.random, however, doesn't have anywhere for the coder to put in parameters; it can only return a value.

### Question 4

I answered the third and fourth functions, but the correct answer is the third, fourth, and first functions. The first function looks much more complicated than the others, but it's just making sure that if too few variables are inputed, then the undefined parameter variables aren't being multiplied with them. In this specific example, because parameter variable d will be undefined, the second part of the if statement will run to avoid multiplying d and getting NaN.

### Question 6

I answered the last function, but the correct answer is the second function. This is because when parameter variables are listed, they accept values from outside the function and not declared a value from inside the function. Thus, prompt statements should not be needed because the values are coming from other sources.

### Question 9

I answered all four methods, but the correct answer is prompt and Math.random. This is because alert and console.log only receive parameters and display it into the console or as a pop up; there is no value to return. However, prompt will take parameters and actually prompt a the user for an input, and that input will be returned to wherever it was called. Also, in Math.random, the code will produce a random number, then return that number to where it was called.

### Question 13

I answered that a ReferenceError would occur, but the correct answer is that 4 or undefined will be printed to the console. This is because if all of the conditions are satsified, then d will be equal to 4, printing 4 to the console. If one or more of the conditions are not satisfied, then d will never be assigned a value and thus undefined will be printed to the console.

### Question 15

I answered false, but the correct answer is true. This is because that the block itself may be inside a function, so the var isn't pushed up all the way to global scope. Instead, it is only pushed up to the function scope it is in.

## Quiz 7

### Question 2

I answered the third and fifth method, but the correct answer is the third, fifth, and second method. This is because the includes method checks to see if a variable matches any item in an array, then returns true if the variables does match an item or false if it doesn't match any. Since the purpose of the missing code is to check if the user input value is equal to any itme in the array, the includes methos also works perfectly for this situation.

### Question 5

I answered false, but the correct answer is true. I'm not sure why it's true, so I'm going to debate why it should be false. The every method will only return true if ALL items in the array meet the specified condition. However, one of the items in the array, 4444, does not meet conditions because it is greater then 999, so it should return false, making the value of tripleDigits false.

### Question 11

I answered the array of all zeroes, but the correct answer is the array of all negative integers. This is because the value of the variable largest was already 0 in the first place, so there the greatest number in the array must be 0 or bigger in order for it to work. However, the biggest number in the array of all negative integers is most definitely smaller than 0, so largest will end up still being zero, which is an innacurate output.
