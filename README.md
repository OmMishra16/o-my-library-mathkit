# mathkit

A Python library built from first principles for educational purposes.

## Philosophy

This library intentionally avoids:
- External dependencies
- Standard library helpers (`str.lower()`, `str.split()`, `re`, `collections`, `itertools`)
- Built-in shortcuts

Everything is implemented using only:
- Loops and conditionals
- Lists and dicts
- Strings
- `ord()` and `chr()`

## Installation

```bash
pip install mathkit
```

## Usage

```python
import mathkit

# Arithmetic (implemented via repeated addition/subtraction)
mathkit.multiply(7, 8)    # 56
mathkit.divide(100, 7)    # 14
mathkit.power(2, 10)      # 1024

# Geometry
mathkit.circle_area(5)    # 78.53975
mathkit.cube_volume(3)    # 27

# Strings (implemented via ord/chr, no str methods)
mathkit.to_lowercase("HELLO")           # "hello"
mathkit.split_by_char("a,b,c", ",")     # ['a', 'b', 'c']
mathkit.is_palindrome("A man a plan")   # True
```

## Modules

- `mathkit.arithmetic` - Basic operations: add, subtract, multiply, divide, modulo, power
- `mathkit.geometry` - Shapes: circle_area, rectangle_area, triangle_area, cube_volume
- `mathkit.strings` - Text: to_lowercase, split_by_char, reverse_string, is_palindrome

## License

MIT
