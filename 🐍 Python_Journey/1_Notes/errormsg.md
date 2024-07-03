# Python-felmeddelanden

## SyntaxError: invalid syntax

Exempel: Du har en felaktig syntax i din kod, vilket kan vara något så enkelt som en saknad parentes eller kolon. <br />
Description: There's an error in the syntax of the code.

Kod | Code:

```python
print("Hello, world"
```

Felmeddelande | Error Message:

```javascript
SyntaxError: invalid syntax
```

## IndexError: list index out of range

Exempel: Du försöker få åtkomst till en lista med ett index som är utanför listans giltiga intervall. <br />
Description: Trying to access an index that is outside the valid range of a list.

Kod | Code:

```python
my_list = [1, 2, 3]
print(my_list[5])
```

Felmeddelande | Error Message:

```sql
IndexError: list index out of range
```

## NameError: name 'variable' is not defined

Exempel: Du försöker använda en variabel som inte har definierats. <br />
Description: Trying to use a variable that has not been defined.

Kod | Code:

```python
print(my_variable)
```

Felmeddelande | Error Message:

```csharp
NameError: name 'my_variable' is not defined
```

## ModuleNotFoundError: No module named 'module'

Exempel: Du försöker importera ett modul som inte finns installerat eller är felstavat. <br />
Description: Attempting to import a module that does not exist or is misspelled.<br/>

Kod | Code:

```python
import non_existent_module
```

Felmeddelande | Error Message:

```vbnet
ModuleNotFoundError: No module named 'non_existent_module'
```

## KeyError: 'key'

Exempel: Du försöker få åtkomst till en nyckel i en dictionary som inte existerar. <br />
Description: Trying to access a key in a dictionary that does not exist.

Kod | Code:

```python
my_dict = {'name': 'Alice'}
print(my_dict['age'])
```

Felmeddelande | Error Message:

```vbnet
KeyError: 'age'
```

## ImportError: cannot import name 'name' from 'module'

Exempel: Du försöker importera en specifik funktion eller klass från en modul som inte existerar.<br />
Description: Trying to import a specific function or class from a module that does not exist.

Kod | Code:

```python
from math import non_existent_function
```

Felmeddelande | Error Message:

```javascript
ImportError: cannot import name 'non_existent_function' from 'math'
```

## AttributeError: 'object' object has no attribute 'attribute'

Exempel: Du försöker få åtkomst till ett attribut eller en metod som inte existerar för ett objekt. <br />
Description: Trying to access an attribute or method that does not exist for an object.

Kod | Code:

```python
my_list = [1, 2, 3]
my_list.non_existent_method()
```

Felmeddelande | Error Message:

```csharp
AttributeError: 'list' object has no attribute 'non_existent_method'
```

## TypeError: unsupported operand type(s) for +: 'int' and 'str'

Exempel: Du försöker använda en operator på inkompatibla datatyper.<br />
Description: Using an operator on incompatible data types.

Kod | Code:

```python
result = 1 + '1'
```

Felmeddelande | Error Message:

```bash
TypeError: unsupported operand type(s) for +: 'int' and 'str'
```

## ValueError: invalid literal for int() with base 10: 'string'

Exempel: Du försöker konvertera en sträng till ett tal, men strängen har ett ogiltigt format.<br />
Description: Trying to convert a string to a number, but the string has an invalid format.

Kod | Code:

```python
number = int('abc')
```

Felmeddelande | Error Message:

```csharp
ValueError: invalid literal for int() with base 10: 'abc'
```

## ZeroDivisionError: division by zero

Exempel: Du försöker dela ett tal med noll. <br />
Description: Attempting to divide a number by zero.

Kod | Code:

```python
result = 10 / 0
```

Felmeddelande | Error Message:

```vbnet
ZeroDivisionError: division by zero
```

## FileNotFoundError: [Errno 2] No such file or directory: 'filename'

Exempel: Du försöker öppna en fil som inte existerar. <br />
Description: Trying to open a file that does not exist.

Kod | Code:

```python
open('non_existent_file.txt')
```

Felmeddelande | Error Message:

```vbnet
FileNotFoundError: [Errno 2] No such file or directory: 'non_existent_file.txt'
```

## PermissionError: [Errno 13] Permission denied: 'filename'

Exempel: Du försöker öppna en fil som du inte har rättigheter till. <br />
Description: Trying to open a file that you do not have permissions to access.

Kod | Code:

```python
open('/root/secret_file.txt')
```

Felmeddelande | Error Message:

```vbnet
PermissionError: [Errno 13] Permission denied: '/root/secret_file.txt'
```

## OSError: [Errno error_code] error_message

Exempel: Ett generellt felmeddelande för olika operativsystemfel, t.ex. för att skapa en fil i en icke-existerande katalog.<br />
Description: A general error for various OS-related issues, such as trying to create a file in a non-existent directory.

Kod | Code:

```python
open('/non_existent_directory/file.txt', 'w')
```

Felmeddelande | Error Message:

```vbnet
OSError: [Errno 2] No such file or directory: '/non_existent_directory/file.txt'
```

## RuntimeError: error_message

Exempel: Ett generellt fel som uppstår under programmets körning när inget annat fel passar.<br />
Description: A general error that occurs during the runtime when no other error is suitable.

Kod | Code:

```python
raise RuntimeError("This is a runtime error")
```

Felmeddelande | Error Message:

```vbnet
RuntimeError: This is a runtime error
```

## IndentationError: unexpected indent

Exempel: Du har felaktig indentering i din kod.<br />
Description: There's incorrect indentation in the code.

Kod | Code:

```python
def my_function():
    print("Hello")
   print("World")  # Fel indentering | Incorrect indentation
```

Felmeddelande | Error Message:

```makefile
IndentationError: unexpected indent
```

## TabError: inconsistent use of tabs and spaces in indentation

Exempel: Du blandar tabbar och mellanslag för att indentera din kod.<br />
Description: Mixing tabs and spaces for indentation.

Kod | Code:

```python
def my_function():
    print("Hello")
    print("World")  # Blandade tabbar och mellanslag | Mixed tabs and spaces
```

Felmeddelande | Error Message:

```makefile
TabError: inconsistent use of tabs and spaces in indentation
```

## MemoryError

Exempel: Programmet försöker använda mer minne än vad som är tillgängligt. <br />
Description: The program tries to use more memory than is available.

Kod | Code:

```python
a = [1] * (10**10)
```

Felmeddelande | Error Message:

```makefile
MemoryError
```

## OverflowError: integer division result too large for a float

Exempel: Resultatet av en beräkning är för stort för att hanteras. <br />
Description: The result of a computation is too large to handle.

Kod | Code:

```python
import math
math.exp(1000)
```

Felmeddelande | Error Message:

```go
OverflowError: math range error
```

## FloatingPointError

Exempel:
Ett problem med flyttal beräkningar, t.ex. division med ett väldigt litet tal.

Kod | Code:

```python
import sys
sys.float_info.min * 0.1
```

Felmeddelande | Error Message:

```makefile
FloatingPointError: (varies depending on implementation)   # kan variera beroende på implementation
```

## StopIteration

Exempel: Ett försök att få nästa element från en iterator som inte har några fler element. <br />
Description: Attempting to get the next element from an iterator that has no more elements.

Kod | Code:

```python
it = iter([1, 2, 3])
next(it)
next(it)
next(it)
next(it)  # Inga fler element | No more elements
```

Felmeddelande | Error Message:

```makefile
StopIteration
```
