#**Python Operators**
### 1. **Arithmetic Operators**
These are used to perform mathematical operations like addition, subtraction, etc.

| Operator | Description          | Example                |
|----------|----------------------|------------------------|
| `+`      | Addition             | `x + y`                |
| `-`      | Subtraction          | `x - y`                |
| `*`      | Multiplication       | `x * y`                |
| `/`      | Division             | `x / y`                |
| `%`      | Modulus              | `x % y`                |
| `**`     | Exponentiation       | `x ** y`               |
| `//`     | Floor Division       | `x // y`               |

### 2. **Comparison (Relational) Operators**
These operators compare two values.

| Operator | Description          | Example                |
|----------|----------------------|------------------------|
| `==`     | Equal to             | `x == y`               |
| `!=`     | Not equal to         | `x != y`               |
| `>`      | Greater than         | `x > y`                |
| `<`      | Less than            | `x < y`                |
| `>=`     | Greater than or equal to | `x >= y`           |
| `<=`     | Less than or equal to   | `x <= y`           |

### 3. **Logical Operators**
These are used to combine conditional statements.

| Operator | Description          | Example                |
|----------|----------------------|------------------------|
| `and`    | True if both are true | `x and y`              |
| `or`     | True if one is true   | `x or y`               |
| `not`    | Reverses the result   | `not x`                |

### 4. **Assignment Operators**
These are used to assign values to variables.

| Operator | Description               | Example                |
|----------|---------------------------|------------------------|
| `=`      | Assigns value              | `x = y`                |
| `+=`     | Adds and assigns           | `x += y`               |
| `-=`     | Subtracts and assigns      | `x -= y`               |
| `*=`     | Multiplies and assigns     | `x *= y`               |
| `/=`     | Divides and assigns        | `x /= y`               |
| `%=`     | Modulus and assigns        | `x %= y`               |
| `**=`    | Exponent and assigns       | `x **= y`              |
| `//=`    | Floor divide and assigns   | `x //= y`              |

### 5. **Bitwise Operators**
These operators perform bit-level operations.

| Operator | Description          | Example                |
|----------|----------------------|------------------------|
| `&`      | Bitwise AND          | `x & y`                |
| `|`      | Bitwise OR           | `x | y`                |
| `^`      | Bitwise XOR          | `x ^ y`                |
| `~`      | Bitwise NOT          | `~x`                   |
| `<<`     | Bitwise left shift   | `x << 2`               |
| `>>`     | Bitwise right shift  | `x >> 2`               |

### 6. **Identity Operators**
These compare the memory locations of two objects.

| Operator | Description          | Example                |
|----------|----------------------|------------------------|
| `is`     | True if the same object | `x is y`             |
| `is not` | True if not the same    | `x is not y`         |

### 7. **Membership Operators**
These check for membership in a sequence, such as strings, lists, or tuples.

| Operator | Description          | Example                |
|----------|----------------------|------------------------|
| `in`     | True if present       | `'a' in x`             |
| `not in` | True if not present   | `'a' not in x`         |

### 8. **Special Operators (Ternary)**
These use the `if` and `else` keywords in a compact syntax.

| Operator | Description                | Example                  |
|----------|----------------------------|--------------------------|
| Ternary  | Conditional expression      | `x if condition else y`  |

---

### Jupyter Notebook Example for GitHub

Here’s how to format the operators in a Jupyter Notebook ready for GitHub:

```python
# Python Operators

## 1. Arithmetic Operators
# These are used to perform mathematical operations.

x = 10
y = 3

print("Addition:", x + y)  # 13
print("Subtraction:", x - y)  # 7
print("Multiplication:", x * y)  # 30
print("Division:", x / y)  # 3.33
print("Modulus:", x % y)  # 1
print("Exponentiation:", x ** y)  # 1000
print("Floor Division:", x // y)  # 3
```

```python
## 2. Comparison Operators
# These compare two values.

x = 10
y = 3

print("Equal to:", x == y)  # False
print("Not equal to:", x != y)  # True
print("Greater than:", x > y)  # True
print("Less than:", x < y)  # False
print("Greater than or equal to:", x >= y)  # True
print("Less than or equal to:", x <= y)  # False
```

```python
## 3. Logical Operators
# These combine conditional statements.

a = True
b = False

print("Logical AND:", a and b)  # False
print("Logical OR:", a or b)  # True
print("Logical NOT:", not a)  # False
```

---

### Steps to Push to GitHub
1. **Create a repository** on GitHub.
2. **Install Jupyter** if you haven’t already (`pip install notebook`).
3. **Create a notebook** (`.ipynb`) file locally using Jupyter Notebook.
4. **Commit and push** the `.ipynb` file to your GitHub repository:
   ```bash
   git add your_notebook.ipynb
   git commit -m "Added Python operators notebook"
   git push origin main
   ```

Would you like a sample Jupyter notebook file, or do you want me to walk you through pushing it to a GitHub repository?