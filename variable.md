# How to define variable

> private, public, protected, constant, static, string, numbers, array, boolean ...etc

## JavaScript 

```js
var a;                          // variable
var b = "hello";                // string
var c = "Hi" + " " + "Bala";    // = "Hi Bala"
var d = 1 + 2 + "3";            // = "33"
var e = [2,3,5,8];              // array
var f = false;                  // boolean
var g = /()/;                   // RegEx
var h = function(){};           // function object
const PI = 3.14;                // constant
var a = 1, b = 2, c = a + b;    // one line
let z = 'zzz';                  // block scope local variable
let Null = null, Undefined = undefined;
```

## C#

```csharp
class ConsoleApplication 
{
    private string _private = 'private';    
    
    protected int Protected = 1;
    
    public float Public = 1.0;
    
    public decimal[] DecimalArray = new decimal[0];
    
    public bool Boolean = true;//false
    
    //constant
    public const float PI = 3.14; 
    
    //static
    public static CLASS_NAME  = "ConsoleApplication"; 
    
    //string initialized with null
    public string NullVariable = null;
    
    static void Main(string[] args)
    {    	
	var local_variable = "local variable";	
    }
}
```

## Python

```python
helloWorld = "Hello World";
one, two = 1,'two'
null = undefined = None #None is equal to null/undefined in python
```
