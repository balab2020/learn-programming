# Class

## Basic

```
Class Rectange {
  height:number;
  width:number;
  getArea : function()
  {
  }
}
```

### javascript

```js
 class Rectangle {
 
  //constructor
  constructor(height, width) {
    this.height = height;
    this.width = width;
  }
  
  getArea(){
    //calculate area
  }
}

//es5

function Rectangle(height, width){
   this.height = height;
   this.width = width;
   this.getArea = function(){
    //calculate area
  }
}
```

### csharp

```csharp
class Rectangle {

  private float height;
  
  private float width;
  
  //constructor
  public Rectangle(float height, float width) {
    this.height = height;
    this.width = width;
  }
  
  public float GetArea(){
    //calculate area
  }
}
```

### python

```python
class Rectangle:

    #constructor
    def __init__(self, height, width):
        self.height = height
        self.width = width

    def getArea(this):
        #calculate area
        area=0
        return area
```
