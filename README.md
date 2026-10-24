# Number-Statistics
## Project Overview
This project is a Python program that identifies even and odd numbers in a list and finds the largest and smallest numbers.

## Objective
Practice Python lists, loops, conditional statements, the modulo operator, and built-in functions.

## Tools Used
- Python
- Jupyter Notebook

## Program Code

```python
# Number Statistics Project

# Step 1: Create a list of numbers
numbers = [10, 5, 8, 3, 12, 7, 20, 15, 2]

# Step 2: Create empty lists for even and odd numbers
even_numbers = []
odd_numbers = []

# Step 3: Identify even and odd numbers
for num in numbers:
    if num % 2 == 0:
        even_numbers.append(num)
    else:
        odd_numbers.append(num)

# Step 4: Find the largest and smallest numbers
largest = max(numbers)
smallest = min(numbers)

# Step 5: Display the results
print("Original List:", numbers)
print("Even Numbers:", even_numbers)
print("Odd Numbers:", odd_numbers)
print("Largest Number:", largest)
print("Smallest Number:", smallest)
```

## Sample Input

```python
[10, 5, 8, 3, 12, 7, 20, 15, 2]
```

## Expected Output

```text
Original List: [10, 5, 8, 3, 12, 7, 20, 15, 2]
Even Numbers: [10, 8, 12, 20, 2]
Odd Numbers: [5, 3, 7, 15]
Largest Number: 20
Smallest Number: 2
```

## Concepts Explained
- **List:** Stores multiple numbers in one variable.
- **For loop:** Processes each number in the list.
- **Modulo operator (`%`):** Gives the remainder after division. A number is even when `num % 2 == 0`.
- **`append()`:** Adds a number to a list.
- **`max()`:** Returns the largest value.
- **`min()`:** Returns the smallest value.

## How to Run
1. Install Python and Jupyter Notebook.
2. Create or open `number_statistics.ipynb`.
3. Copy the program code into a notebook cell.
4. Run the cell by pressing `Shift + Enter`.
5. Verify the output.

## Project Files

```text
number-statistics-python/
├── number_statistics.ipynb
└── README.md
```

## Conclusion
This project demonstrates basic numerical data processing in Python by separating even and odd numbers and calculating the maximum and minimum values.
