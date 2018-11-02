
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

## javascript

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

## csharp

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

## python

```python
balance, debit = 1000, 10000
if (balance < debit):
    print('no sufficient balance !!!')
elif (balance < debit):
    print('you are eligible !!!')
else:
    print('balance is same as debit amount request, reduce debit request')
```
