# function

> A function relates an input to an output. A function uses given inputs with some logic and produces desired output.

**Use case: Sum of 2 Numbers**

Function which accepts two numbers as arguments and return the sum.
```
Function(A, B)
START
     RETURN (A+B)
END
```
## JavaScript 

```js
function sum(a,b)
{
   return (a+b);
}

//or

const sum = (a,b) => a+b;

//calling
sum(1,2);
```

## C#

```csharp
class Calculator 
{
    public int Sum(int a, int b)
    {
	return (a+b);
    }
}

//use it
var calc = new Calculator();
calc.sum(1,2);
```

## Python

```python
def sum(a,b):
    return a+b
sum(1,2)
```
