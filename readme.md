# **Python – The Ignition**

- print(&quot;Hello, World!&quot;)
- indentation
- #This is a comment
- Creating Variables- Python has no command for declaring a variable. A variable is created the moment you first assign a value to it.
  - x = 5
print(x)
  - x = 4       # x is of type int
x = &quot;Sally&quot; # x is now of type str
print(x)
- Casting- If you want to specify the data type of a variable, this can be done with casting.
  - x = str(3)    # x will be &#39;3&#39;
y = int(3)    # y will be 3
z = float(3)  # z will be 3.0

- Get the Type- You can get the data type of a variable with the type()function.
  - x = 5
y = &quot;John&quot;
print(type(x))
print(type(y))
    - output:

\&lt;class &#39;int&#39;\&gt;
\&lt;class &#39;str&#39;\&gt;

- x = &quot;John&quot; == x = &#39;John&#39; #String variables can be declared either by using single or double quotes.
- A != a #case sensitive
- Value Assignment
  - x, y, z = &quot;Orange&quot;, &quot;Banana&quot;, &quot;Cherry&quot;
  - x = y = z = &quot;Orange&quot;
  - fruits = [&quot;apple&quot;, &quot;banana&quot;, &quot;cherry&quot;]
x, y, z = fruits

- \&lt;global\&gt; variable
  - If you use the global keyword, the variable belongs to the global scope
  - x = &quot;awesome&quot;
def myfunc():
  global x
  x = &quot;fantastic&quot;
myfunc()
print(&quot;Python is &quot; + x)
-

| Text Type: | str |
| --- | --- |
| Numeric Types: | int, float, complex |
| Sequence Types: | list, tuple, range |
| Mapping Type: | dict |
| Set Types: | set, frozenset |
| Boolean Type: | bool |
| Binary Types: | bytes, bytearray, memoryview |

Data Types

| **Setting The Data Type** | **Setting The Specific Data Type** | **Data Type** |
| --- | --- | --- |
| x = &quot;Hello World&quot; | x = str(&quot;Hello World&quot;) | str |
| x = 20 | x = int(20) | int |
| x = 20.5 | x = float(20.5) | float |
| x = 1j | x = complex(1j) | complex |
| x = [&quot;apple&quot;, &quot;banana&quot;, &quot;cherry&quot;] | x = list((&quot;apple&quot;, &quot;banana&quot;, &quot;cherry&quot;)) | list |
| x = (&quot;apple&quot;, &quot;banana&quot;, &quot;cherry&quot;) | x = tuple((&quot;apple&quot;, &quot;banana&quot;, &quot;cherry&quot;)) | tuple |
| x = range(6) | x = range(6) | range |
| x = {&quot;name&quot; : &quot;John&quot;, &quot;age&quot; : 36} | x = dict(name=&quot;John&quot;, age=36) | dict |
| x = {&quot;apple&quot;, &quot;banana&quot;, &quot;cherry&quot;} | x = set((&quot;apple&quot;, &quot;banana&quot;, &quot;cherry&quot;)) | set |
| x = frozenset({&quot;apple&quot;, &quot;banana&quot;, &quot;cherry&quot;}) | x = frozenset((&quot;apple&quot;, &quot;banana&quot;, &quot;cherry&quot;)) | frozenset |
| x = True | x = bool(5) | bool |
| x = b&quot;Hello&quot; | x = bytes(5) | bytes |
| x = bytearray(5) | x = bytearray(5) | bytearray |
| x = memoryview(bytes(5)) | x = memoryview(bytes(5)) | memoryview |