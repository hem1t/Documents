# Mutable and Immutable types in Python

Defined variables in python have certain `id`s assigned at the time initiation. They can be accessed using `.id()`.

Immutable object's values cannot be changed after initiation without changing the `id`.
Whereas with mutable objects we can change inner values.

For examples `int` is an immutable object.
```python
a = 23; ai = id(a)
a += 12
id(a) == ai # Returns False
```

