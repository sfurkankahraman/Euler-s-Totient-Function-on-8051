# Euler-s-Totient-Function-on-8051
Euler’s Totient Function

In this section of the assignment, you will have one 8051 MCU compute the number of
positive integers smaller than N that are relatively prime (i.e. have a greatest common
divisor of 1) with N where N is an unsigned positive integer between 1 and 255, including 1
and 255.

Have the string ’PHI(’ be displayed on the first line on an LCD before taking your input.
Take a decimal number with at most three digits as your keypad input (N), and print it on
the first line, following the aforementioned string. Then, when the A button on the keypad
is pressed, close the bracket, print a ’=’ character, and display the result of ϕ(N)

Details:
• Your code does not need to run indefinitely without reset. In other words, while the
LCD is displaying the result of a previous query, the MCU does not need to be able to
accept new input from the keypad.
• While taking input, have each digit be displayed immediately when the corresponding
digit is pressed on the keypad. The closing parenthesis of ’PHI( )’ should be displayed
only when the A button is pressed.
• The primes smaller than 256 are 2, 3, 5, 7, 11, 13, 17, 19, 23, 29, 31, 37, 41, 43, 47, 53,
59, 61, 67, 71, 73, 79, 83, 89, 97, 101, 103, 107, 109, 113, 127, 131, 137, 139, 149, 151,
157, 163, 167, 173, 179, 181, 191, 193, 197, 199, 211, 223, 227, 229, 233, 239, 241, and
251. You may store these values in a look-up table.
• You are not required to be able to display any result for inputs that are not integers
between 1 and 255.
• For those who are curious, ϕ(N) is formally called Euler’s totient function.
