# Smart Error Handler

Smart Error Handler is a packge that helps with fixing errror easier on a python script

I updated some changes in this repository so it will not gonna be same script with the video

Pypi Website:[Website](<https://pypi.org/project/smart-error-handler/>)

Installation:
```
pip install smart-error-handler
```

Usage:
```
from smart_error_handler.smart_error_handler import SmartErrorHandler

handler = SmartErrorHandler()

@handler.handle_error 
def divide_numbers(a, b):
    return a / b


result1 = divide_numbers(10, 2) 
print("Result:", result1)

result2 = divide_numbers(10, 0)  # Should trigger ZeroDivisionError
print("Result:", result2)

result3 = divide_numbers(10, "two")  # Should trigger TypeError
print("Result:", result3)


```
