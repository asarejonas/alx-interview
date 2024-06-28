# Pascal's Triangle

This Python script generates Pascal's Triangle up to a specified number of rows. Pascal's Triangle is a triangular array of the binomial coefficients.

## Function

### `pascal_triangle(n)`

This function returns a list of lists of integers representing Pascal's Triangle up to `n` rows.

#### Parameters
- `n` (int): The number of rows of Pascal's Triangle to generate. If `n` is less than or equal to 0, an empty list is returned.

#### Returns
- `List[List[int]]`: A list of lists of integers representing Pascal's Triangle.

### Example Usage

```
from pascal_triangle import pascal_triangle

# Generate Pascal's Triangle with 5 rows
triangle = pascal_triangle(5)
print(triangle)
```

Output:
```
[
    [1],
    [1, 1],
    [1, 2, 1],
    [1, 3, 3, 1],
    [1, 4, 6, 4, 1]
]
```

## How to Run

1. Ensure you have Python 3 installed on your system.
2. Save the provided code in a file named `pascal_triangle.py`.
3. You can import the `pascal_triangle` function into your own script or run it in a Python interpreter.

## License

This project is licensed under the MIT License.
