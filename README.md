
# Day 1
## String Calculator (30 min)

http://osherove.com/tdd-kata-1/

1. create a calculator with method add
  - for empty string, return zero
  - numbers are separated by commas
  - for string with 1 to 2 numbers, it returns their sum
2. allow to handle an unknown amount of numbers
3. allow to handle newline as delimiter instead of commas
4. allow different types of delimiters
  - //[delimiter]\n[numbers…]
  - delimiter will  be followed by a newline
  - previous scenarios should still be supported
5. adding a negative number(s) throws an error
6. numbers bigger than 1000 should be ignored
7. delimiters of any length
8. multiple delimiters allowed //[delim1][delim2]\n
9. multiple delimiters with length lower than one char
