# Magic Square Generator

This Python project generates a **magic square** for odd-sized squares (`n x n`), where `n` is an odd integer. 
The magic square is filled with numbers from `1` to `n^2` in such a way that the sum of the numbers in every row, column, and both diagonals are equal.

## Key Features:
- Generates a magic square of size `n x n` (only for odd `n`).
- Fills the square using the **Siamese method** (also known as the **de La Loubère method**).
- Computes the sum of each row, column, and diagonal, which is constant and equal to:  
  **Magic Constant = (n * (n^2 + 1)) / 2**
- Outputs the magic square in a readable format.

### Example:

For `n = 5`, the generated magic square looks like this:


'''9  3 22 16 15'''
'''2 21 20 14  8'''
25 19 13  7  1
18 12  6  5 24
11 10  4 23 17
The sum of each row/column/diagonal is : 65


