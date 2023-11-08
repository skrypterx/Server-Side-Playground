### Encapsulation

1. The class variables should not be updated directly from outside of the class.
2. Only class methods should update the variables.
3. Make class variable private.

Note: Default value of int is 0

### Abstraction

1. We dont need to know the inner details of a class.
e.g. Lets say we have a class `Car`, User wants to start `Car` by just calling `start()` function, we do not want to know what start is doing or what else start is calling inorder to start the car.
2. Details of functionlity is abstracted away from the consumer.

### Important Points

1. If no constructor provided, then java will provide 0 argument default constructor.
2. As soon as we declare a constructor, java wont provide default constructor by itself.

### Explicit Type Casting

When casting is done from type of more bytes to type of lesser bytes(e.g. long to int), you have to explicitly cast it. e.g.

`long l = 102109832190339203`<br>
`int i = (int) l; value will not be the same if it exceeds the limit`

### Implicit Type Casting

When casting is done from type of less bytes to type of more bytes(e.g. int to long), just assignment is enough. e.g.

`int i = 10210983`<br>
`long l = i; //value will be the same`