# Readme for Python Code

## Description
This Python script takes four integer inputs (`x`, `y`, `z`, and `n`) and generates all possible combinations of three integers (`i`, `j`, and `k`) such that `i + j + k` is not equal to `n`. The script utilizes nested loops to iterate through the ranges specified by the inputs and filters out combinations that satisfy the condition.

## Usage
1. Run the script in a Python environment.
2. Enter four integers when prompted for input (`x`, `y`, `z`, and `n`).
3. The script will output a list of lists representing the valid combinations of `i`, `j`, and `k` that meet the specified condition.

## Input
- `x`: An integer representing the range for `i`.
- `y`: An integer representing the range for `j`.
- `z`: An integer representing the range for `k`.
- `n`: An integer representing the condition for the sum `i + j + k`.

## Output
The output is a list of lists (`result`), where each inner list represents a valid combination of `i`, `j`, and `k` that satisfies the condition `i + j + k != n`. The result is printed to the console.

## Example
```python
# Example Input
3
3
3
2

# Example Output
[[0, 0, 3], [0, 1, 2], [0, 2, 1], [0, 3, 0], [1, 0, 2], [1, 1, 1], [1, 2, 0], [2, 0, 1], [2, 1, 0], [3, 0, 0]]
```

In this example, for the input values `x=3`, `y=3`, `z=3`, and `n=2`, the script generates combinations of `i`, `j`, and `k` where the sum is not equal to `n` and prints the result.

## Note
Ensure that you input valid integers when prompted. The script does not handle input validation or error checking for simplicity.
