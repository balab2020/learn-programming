
# Conditional Statements

> if, else, switch, case

## If..Else

```
 variable debit = 10000, balance = 1000;
 if(HasSufficientAmount)
   AllowDebit();
 else if (NoSufficientAmount)
   RejectDebit();
 else 
   AllowWithConcern();
```

### javascript

```js
 //code
 let balance = 1000, debit = 10000;
 if(balance < debit) { 
   console.error('no sufficient balance !!!');
 } else if(balance < debit){
   console.success('you are eligible !!!');
 } else {
   console.warning('balance is same as debit amount request, reduce debit request');
 }
```

### csharp

```csharp
class Account {

  private int balance = 1000;
  
  private int debit = 10000;
  
  public void Debit()
  {
    if(balance < debit) { 
      Console.WriteLine('no sufficient balance !!!');
    } else if(balance < debit){
      Console.WriteLine('you are eligible !!!');
    } else {
      Console.WriteLine('balance is same as debit amount request, reduce debit request');
    }
  }
}
```

### python

```python
balance, debit = 1000, 10000
if (balance < debit):
    print('no sufficient balance !!!')
elif (balance < debit):
    print('you are eligible !!!')
else:
    print('balance is same as debit amount request, reduce debit request')
```

## Switch..Case

```
variable message_type = 'error', message = 'yes, you have learnt something!!!';

Function print_message(message, color)
{
  //prints on some output device
}
switch(message_type)
{
   case 'error':
    print_message(message, 'red');
   break;
   case 'warning':
    print_message(message, 'orange');
   break;
   default:
    print_message(message, 'blue');
   break;     
}
```



### javascript

```js
let message_type = 'error', message = 'yes, you have learnt something!!!';

function print_message(message, color)
{
  //prints on some output device
}
switch(message_type)
{
   case 'error':
    print_message(message, 'red');
   break;
   case 'warning':
    print_message(message, 'orange');
   break;
   default:
    print_message(message, 'blue');
   break;     
}
```

### csharp

```csharp
class SwitchCase {
  private void print_message(message, color)
  {
    //prints on some output device
  }
  public void Print()
  {
     string message_type = 'error', message = 'yes, you have learnt something!!!';
     switch(message_type)
     {
        case 'error':
         print_message(message, 'red');
        break;
        case 'warning':
         print_message(message, 'orange');
        break;
        default:
         print_message(message, 'blue');
        break;     
     }
  }
}
```

### python

```python
#no native support, geeks reolve this with ifElse or dictionary
```
