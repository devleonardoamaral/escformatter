# EscFormatter

## Description

This Python package provides a class named `Esc` that enables the execution of ANSI escape commands in the console. It offers functionalities for advanced text formatting, changing font colors in the console, applying text styles, and positioning the cursor.

## Usage Example

```python
from escformatter import esc

# Register cleanup to reset console styles and colors to default
esc.register_cleanup()

# Display 'Hello, World!' in red
print(esc.fg_red + 'Hello, World!')
