# Mersenne Numbers

According to Wikipedia, a **Mersenne Number** is a number which is 1 less than the power of 2.  It is in the form of `M(n) = 2**n - 1`, where n is an integer greater than or equal to 1.  For example, 7 is a Mersenne Number, whereas 8 is not a Mersenne Number.  The aim is to investigate if the numbers are Mersenne or not.

## UX

**Getting Started**

Enter a whole number between 1 and 100000 (e.g. 7) and click on the Submit Button.  You will see the number you have entered, as well as seeing if that number is a Mersenne, unless you have made an invalid input.  Click on the Reset Button to clear the information or to start again.

**User Stories**

As a user, I expect to get an error message if I do any or all of:

    - Entering text (e.g. bus)
    - Entering a number less than 1 or greater than 100000
    - Entering a number, but it is not an integer
    - Not enter anything in the input field

Assuming that my input is valid, I expect to see something like:

    You have entered the number 7.
    7 is a Mersenne Number.

**Information Architecture**

The number entered is an integer between 1 and 100000.  The function `isMersenne(num)` is a boolean.  It returns `true` or `false`.

## Features

Allows the user to enter a number as well as seeing if that number is a Mersenne.  Perform checks on the input to ensure it is valid.  If the input is not valid, an error message is displayed.

## Technologies

Uses HTML5, CSS3, JavaScript, Bootstrap 5.1.3 and Google Fonts.

## Testing

Ensure all user stories have been met.

## Deployment

Deployed on [GitHub Pages](https://derektypist.github.io/mersenne-numbers) at the main branch.

## Credits

### Content

Written by me.

### Acknowledgements

- [Geeks for Geeks](https://www.geeksforgeeks.org)
- [Wikipedia](https://www.wikipedia.org)

