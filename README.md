# Collatz-Conjecture
This is a code to learn the Collatz conjecture also known as 3n+1 conjecture in mathematics

In general terms, the program done in java pretends to simulate the Collatz conjecture, also called
3n + 1 conjecture, amongst other names. The conjecture can be outlined as this: Take any positive
integer n. If n is even, divide it by 2 to get n / 2. If n is odd, multiply it by 3 and add 1 to obtain 3n +
1. The curios fact on this problem resides in that doing that for any given number you'll arrive to a
simple solution: 1.

The code written by myself tries to approach an easier way to get the number of iterations and, also,
to percieve readily the process to reach the final sequence 4,2,1.

Moreover, there can be overflow if you try numbers higher than (2 ^ 63) -1=
9223372036854775807 due to that is the maximum rank of the type 'long'. In some cases you can
even enter on an infinite loop.
