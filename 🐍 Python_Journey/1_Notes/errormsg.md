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

Exempel: Du försöker använda en variabel som inte har definierats.
Kod:

```python
print(my_variable)
```

Felmeddelande:

```csharp
NameError: name 'my_variable' is not defined
```

## ModuleNotFoundError: No module named 'module'

Exempel: Du försöker importera ett modul som inte finns installerat eller är felstavat.
Kod:

```python
import non_existent_module
```

Felmeddelande:

```vbnet
ModuleNotFoundError: No module named 'non_existent_module'
```

## KeyError: 'key'

Exempel: Du försöker få åtkomst till en nyckel i en dictionary som inte existerar.
Kod:

```python
my_dict = {'name': 'Alice'}
print(my_dict['age'])
```

Felmeddelande:

```vbnet
KeyError: 'age'
```

## ImportError: cannot import name 'name' from 'module'

Exempel: Du försöker importera en specifik funktion eller klass från en modul som inte existerar.
Kod:

```python
from math import non_existent_function
```

Felmeddelande:

```javascript
ImportError: cannot import name 'non_existent_function' from 'math'
```

## AttributeError: 'object' object has no attribute 'attribute'

Exempel: Du försöker få åtkomst till ett attribut eller en metod som inte existerar för ett objekt.
Kod:

```python
my_list = [1, 2, 3]
my_list.non_existent_method()
```

Felmeddelande:

```csharp
AttributeError: 'list' object has no attribute 'non_existent_method'
```

## TypeError: unsupported operand type(s) for +: 'int' and 'str'

Exempel: Du försöker använda en operator på inkompatibla datatyper.
Kod:

```python
result = 1 + '1'
```

Felmeddelande:

```bash
TypeError: unsupported operand type(s) for +: 'int' and 'str'
```

ValueError: invalid literal for int() with base 10: 'string'

Exempel: Du försöker konvertera en sträng till ett tal, men strängen har ett ogiltigt format.
Kod:

```python
number = int('abc')
```

Felmeddelande:

```csharp
ValueError: invalid literal for int() with base 10: 'abc'
```

## ZeroDivisionError: division by zero

Exempel: Du försöker dela ett tal med noll.
Kod:

```python
result = 10 / 0
```

Felmeddelande:

```vbnet
ZeroDivisionError: division by zero
```

## FileNotFoundError: [Errno 2] No such file or directory: 'filename'

Exempel: Du försöker öppna en fil som inte existerar.
Kod:

```python
open('non_existent_file.txt')
```

Felmeddelande:

```vbnet
FileNotFoundError: [Errno 2] No such file or directory: 'non_existent_file.txt'
```

## PermissionError: [Errno 13] Permission denied: 'filename'

Exempel: Du försöker öppna en fil som du inte har rättigheter till.
Kod:

```python
open('/root/secret_file.txt')
```

Felmeddelande:

```vbnet
PermissionError: [Errno 13] Permission denied: '/root/secret_file.txt'
```

## OSError: [Errno error_code] error_message

Exempel: Ett generellt felmeddelande för olika operativsystemfel, t.ex. för att skapa en fil i en icke-existerande katalog.
Kod:

```python
open('/non_existent_directory/file.txt', 'w')
```

Felmeddelande:

```vbnet
OSError: [Errno 2] No such file or directory: '/non_existent_directory/file.txt'
```

## RuntimeError: error_message

Exempel: Ett generellt fel som uppstår under programmets körning när inget annat fel passar.
Kod:

```python
raise RuntimeError("This is a runtime error")
```

Felmeddelande:

```vbnet
RuntimeError: This is a runtime error
```

## IndentationError: unexpected indent

Exempel: Du har felaktig indentering i din kod.
Kod:

```python
def my_function():
    print("Hello")
   print("World")  # Fel indentering
```

Felmeddelande:

```makefile
IndentationError: unexpected indent
```

## TabError: inconsistent use of tabs and spaces in indentation

Exempel: Du blandar tabbar och mellanslag för att indentera din kod.
Kod:

```python
def my_function():
    print("Hello")
    print("World")  # Blandade tabbar och mellanslag
```

Felmeddelande:

```makefile
TabError: inconsistent use of tabs and spaces in indentation
```

## MemoryError

Exempel: Programmet försöker använda mer minne än vad som är tillgängligt.
Kod:

```python
a = [1] * (10**10)
```

Felmeddelande:

```makefile
MemoryError
```

## OverflowError: integer division result too large for a float

Exempel: Resultatet av en beräkning är för stort för att hanteras.
Kod:

```python
import math
math.exp(1000)
```

Felmeddelande:

```go
OverflowError: math range error
```

## FloatingPointError

Exempel:
Ett problem med flyttal beräkningar, t.ex. division med ett väldigt litet tal.
Kod:

```python
import sys
sys.float_info.min * 0.1
```

Felmeddelande:

```makefile
FloatingPointError: (kan variera beroende på implementation)
```

## StopIteration

Exempel: Ett försök att få nästa element från en iterator som inte har några fler element.
Kod:

```python
it = iter([1, 2, 3])
next(it)
next(it)
next(it)
next(it)  # Inga fler element
```

Felmeddelande:

```makefile
StopIteration
```
