# Lesson 103: Python String Formatting

Welcome to Lesson 103 of the Python Learning Lounge! In this lesson, we will cover various methods for formatting strings in Python.

## Table of Contents

- [Introduction](#introduction)
- [String Formatting Methods](#string-formatting-methods)
  - [Old Style `%` Formatting](#old-style--formatting)
  - [New Style `.format()` Method](#new-style-format-method)
  - [f-Strings (Literal String Interpolation)](#f-strings-literal-string-interpolation)
- [Examples](#examples)
- [Exercises](#exercises)
- [Conclusion](#conclusion)

## Introduction

String formatting is a crucial part of writing clean and readable code in Python. It allows you to create strings that include variable values, making your code more dynamic and versatile.

## String Formatting Methods

### Old Style `%` Formatting

The old style of string formatting uses the `%` operator. This method is less commonly used in modern Python code but is still worth knowing.

```python
name = "Alice"
age = 30
formatted_string = "Hello, %s! You are %d years old." % (name, age)
print(formatted_string)
```

### New Style `.format()` Method

The `.format()` method is more powerful and flexible than the old style. It uses curly braces `{}` as placeholders in the string.

```python
name = "Alice"
age = 30
formatted_string = "Hello, {}! You are {} years old.".format(name, age)
print(formatted_string)
```

### f-Strings (Literal String Interpolation)

Introduced in Python 3.6, f-strings are the most modern and preferred way of formatting strings. They provide a concise and readable syntax.

```python
name = "Alice"
age = 30
formatted_string = f"Hello, {name}! You are {age} years old."
print(formatted_string)
```

## Examples

Here are a few more examples of string formatting:

1. Using the old style `%` formatting:

    ```python
    value = 42
    formatted_string = "The answer is %d." % value
    print(formatted_string)
    ```

2. Using the `.format()` method:

    ```python
    temperature = 20.5
    formatted_string = "The temperature is {:.1f} degrees Celsius.".format(temperature)
    print(formatted_string)
    ```

3. Using f-strings:

    ```python
    pi = 3.14159
    formatted_string = f"The value of pi is approximately {pi:.2f}."
    print(formatted_string)
    ```

## Exercises

1. Write a string that includes your name and your favorite hobby using the old style `%` formatting.
2. Create a string that includes your age and the current year using the `.format()` method.
3. Use an f-string to create a string that includes your hometown and your favorite food.

## Conclusion

String formatting is a fundamental skill for any Python programmer. By mastering these three methods, you'll be well-equipped to handle any string formatting task that comes your way.

Happy coding!

---

For more lessons and tutorials, visit the [Python Learning Lounge](https://github.com/Python-leatning-lounge).
