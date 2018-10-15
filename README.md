### mdarray
---
https://github.com/rbotafogo/mdarray

https://github.com/rbotafogo/mdarray/wiki

```
matrix = MDMatrix.double([5, 5], [2.0, 0.0, 8.0, 6.0, 0.0,\
                                  1.0, 6.0, 0.0, 1.0, 7.0,\
                                  5.0, 0.0, 7.0, 4.0, 0.0,\
                                  7.0, 0.0, 8.0, 5.0, 0.0,\
                                  0.0, 10.0, 0.0, 0.0, 7.0])
                                  
matrix = MDMatrix.int([4, 3])
array = MDArray.typed_arange("double", 0, 15)
array = MDMatrix.fromfunction("double", [4, 4]) { |x, y| x + y }
d2 = MDArray.typed_arrange("double", 0, 15)
double_matrix = MDMatrix.from_mdarray(d2)

d1 = MDArray.typed_arrange("double", 0, 420)
d1.reshape!([5, 4, 3, 7])
matrix = MDMatrix.from_mdarray(d1.slice(0, 0))
matrix = MDMatrix.from_mdarray(d1.region(:spec => "0:0, 0:0, 0:2, 0:6").reduce)

matrix.print
matrix.mdarray.print
a = MDMatrix.double([4, 4])
a.fill(2.5)
make a 4 x 4 matrix `b` from a given function (block)
b = MDMatrix.fromfunction("double", [4, 4]) { |x, y| x + y }
c = a + b
b.generate_non_singular!
c = a / b

pos = MDArray.double([3, 3], [4, 12, -16, 12, 37, -43, -16, -43, 98])
matrix = MDArray.from_mdarray(pos)
chol = matirx.chol
assert_equal(2, chol[0, 0])
assert_equal(6, chol[1, 0])
assert_equal(-8, chol[2, 0])
assert_equal(5, chol[2, 1])
assert_equla(, chol[2, 2])
```

```ruby

```

```

```


