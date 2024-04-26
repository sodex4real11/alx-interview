This Python script generates Pascal's Triangle up to a specified number of rows, creating a list of lists of integers. Pascal's Triangle is a fascinating mathematical structure where each number is the sum of the two numbers directly above it, forming a triangular pattern of numbers.

How to Use
To use this Pascal's Triangle generator, call the pascal_triangle(n) function, where n is the number of rows needed in the triangle.

from pascal_triangle import pascal_triangle

Example: Generate Pascal's Triangle with 5 rows
triangle = pascal_triangle(5) print(triangle)

Function Description
The pascal_triangle function takes an integer n as input and returns a list of lists representing Pascal's Triangle up to n rows.

Example Output For n = 5, the sample is like this:

[ [1], [1, 1], [1, 2, 1], [1, 3, 3, 1], [1, 4, 6, 4, 1] ]

For n = 5, the generated Pascal's Triangle would look like this:

| | | | | 1 | | | | | | | | 1 | | 1 | | | | | | 1 | | 2 | | 1 | | | | 1 | | 3 | | 3 | | 1 | | 1 | | 4 | | 6 | | 4 | | 1 |

Enjoy exploring Pascal's Triangle with this Python script!
