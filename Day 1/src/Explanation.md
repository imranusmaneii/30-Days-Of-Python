
# ➖➖➖➖➖➖ DAY 1️⃣ ➖➖➖➖➖➖

## ➖➖➖➖ Topics ➖➖➖➖

1. Basic Methods
2. Data Types

---

# 1. Basic Methods

## 1.1 Addition (`+`)

```python
print(2 + 3)
```

**Output**

```text
5
```

Adds two numbers together.

---

## 1.2 Subtraction (`-`)

```python
print(2 - 3)
```

**Output**

```text
-1
```

Subtracts the second number from the first.

---

## 1.3 Multiplication (`*`)

```python
print(2 * 3)
```

**Output**

```text
6
```

Multiplies two numbers.

---

## 1.4 Division (`/`)

```python
print(3 / 2)
```

**Output**

```text
1.5
```

Performs normal division and always returns a floating-point number.

---

## 1.5 Exponentiation (`**`)

```python
print(3 ** 2)
```

**Output**

```text
9
```

Raises the first number to the power of the second.

---

## 1.6 Modulus (`%`)

```python
print(3 % 2)
```

**Output**

```text
1
```

Returns the remainder after division.

---

## 1.7 Floor Division (`//`)

```python
print(10 // 3)
```

**Output**

```text
3
```

### What is Floor Division?

Floor division divides two numbers and returns the largest whole number less than or equal to the result. In simple words, it removes the decimal part and keeps only the integer quotient.

Example:

```python
10 // 3
```

Result:

```text
3
```

---

# 2. Checking Data Types

The `type()` function is used to determine the data type of a value.

```python
print(type(2))
print(type(3.14))
print(type(1 + 3j))
print(type("Imran"))
print(type([1, 2, 3]))
print(type({"name": "ImranUsmani"}))
print(type((9.8, 3.14, 2.7)))
```

**Output**

```text
<class 'int'>
<class 'float'>
<class 'complex'>
<class 'str'>
<class 'list'>
<class 'dict'>
<class 'tuple'>
```

### Explanation

| Example | Data Type |
|---------|-----------|
| `2` | Integer (`int`) |
| `3.14` | Float (`float`) |
| `1 + 3j` | Complex (`complex`) |
| `"Imran"` | String (`str`) |
| `[1, 2, 3]` | List (`list`) |
| `{"name": "ImranUsmani"}` | Dictionary (`dict`) |
| `(9.8, 3.14, 2.7)` | Tuple (`tuple`) |
