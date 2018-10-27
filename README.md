
# TDD Katas
do a kata 5 days of the week for __30 min__.

recommended to do one in the mornings.

katas can be switched around, they do not have to be done in the order below.

practice below for a month and switch to new katas.

#### reference links

<http://www.peterprovost.org/blog/2012/05/02/kata-the-only-way-to-learn-tdd/>
<https://github.com/wix/tdd-katas>
<http://www.tddbuddy.com/>

## TDD Steps

1. Write a test for a new function. The test should fail.
2. Write code until the test passes.
3. Refactor until the code is suitable for continued development
4. Goto 1.



## Day 1
### FizzBuzz

http://codingdojo.org/kata/FizzBuzz/

1. print numbers 1 to 100
1. print 'fizz' for multiples of 3
2. print 'buzz' for multiples of 5
3. print 'fizzbuzz' for multiples of 3 and 5
4. print 'fizz' if number is divisible by 3 or has digit 3 in it
5. print 'buzz' if number is divisible by 5 or has digit 5 in it

## Day 2
### String Calculator

http://osherove.com/tdd-kata-1/

1. An empty string returns zero
2. A single number returns the value of that number
3. Two numbers, comma delimited, returns the sum
4. Two numbers, newline delimited, returns the sum
5. Three numbers, delimited either way, returns the sum
6. Negative numbers throw an exception
7. Numbers greater than 1000 are ignored
8. A single char delimiter can be defined on the first line (e.g. //# for a ‘#’ as the delimiter)
9. A multi char delimiter can be defined on the first line (e.g. //[###] for ‘###’ as the delimiter)
10. Many single or multi-char delimiters can be defined (each wrapped in square brackets)

## Day 3
### Bowling Game


1. Gutter game scores zero - When you roll all misses, you get a total score of zero.
2. All ones scores 20 - When you knock down one pin with each ball, your total score is 20.
3. A spare in the first frame, followed by three pins, followed by all misses scores 16.
4. A strike in the first frame, followed by three and then four pins, followed by all misses, scores 24.
5. A perfect game (12 strikes) scores 300.

## Day 4
### Greeting

<https://github.com/testdouble/contributing-tests/wiki/Greeting-Kata>

1. wite function greet(name) and interpolate name in a simple greeting. (e.g. "Hello, [name].")
2. handle nulls (e.g. "Hello, my friend")
3. when name is all uppercase add exclamation at the end of greeting
4. handle two input names as array
5. handle multiple names as array
6. handle mix of normal and shouted names. separate response in two greetings (e.g. "Hello, Amy and Charlotte. AND HELLO BRIAN!")
7. split any entries in the name if they have a comma
8. escape commas with double quotes (e.g. input: ["Bob", ""Charlie, Dianne""] result: "Hello, Bob and Charlie, Dianne.")

## Day 5
### Password Verification

0. write function passwordVerify that returns true if conditions are met
1. password should be larger than 8 chars
2. password cannot be null
3. password should have at least one uppercase letter
4. password should have at least one lowercase letter
5. password should have at least one number
6. return OK if all conditions are met, otherwise return a message for each condition that failed.
