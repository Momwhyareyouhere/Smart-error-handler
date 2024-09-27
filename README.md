# Smart Error Handler

Smart Error Handler is a packge that helps with fixing errror easier on a python script

Installation:
```
pip install smart-error-handler
```

Usage:
```
from smart_error_handler import SmartErrorHandler

handler = SmartErrorHandler()

@handler.handle_error
def divide_numbers(a, b):
    return a / b

result = divide_numbers(10, 0)  # This will trigger the error handler

```
