---
title: 'Insert title here'
key: ae3238dcc7feb9adecfee0c395fc8dc8
---

## 2D Numpy Arrays

```yaml
type: TitleSlide
key: 0cc8abf493
```

`@lower_third`
name: Filip Schouwenaars
title: Instructor

`@script`
Let's recreate the numpy arrays from the previous video.

If you ask for the type of these arrays, Python tells you that they are numpy-dot-ndarray. numpy dot tells you it's a type that was defined in the numpy package. ndarray stands for n-dimensional array. The arrays np_height and np_weight are one-dimensional arrays, but it's perfectly possible to create 2 dimensional, three dimensional, heck even seven dimensional arrays! Let's stick to 2 in this video though.

You can create a 2D numpy array from a regular Python list of lists. Let's try to create one numpy array for all height and weight data of your family, like this.

If you print out np_2d now, you'll see that it is a rectangular data structure: Each sublist in the list, corresponds to a row in the two dimensional numpy array. From np_2d-dot-shape, you can see that we indeed have 2 rows and 5 columns. shape is a so-called attribute of the np2d array, that can give you more information about what the data structure looks like.

Also for 2D arrays, the Numpy rule applies: an array can only contain a single type. If you change one float to be string, all the array elements will be coerced to strings, to end up with a homogeneous array.

You can think of the 2D numpy array as an improved list of lists: you can perform calculations on the arrays, like I showed before, and you can do more advanced ways of subsetting.

Suppose you want the first row, and then the third element in that row. To select the row, you need the index 0 in square brackets.

To then select the third element, you can extend the same call with another pair of brackets, this time with the index 2, like this. Basically you're selecting the row, and then from that row do another selection.

There's also an alternative way of subsetting, using single square brackets and a comma. This call returns the exact same value as before. The value before the comma specifies the row, the value after the comma specifies the column. The intersection of the rows and columns you specified, are returned.

Once you get used to it, this syntax is more intuitive and opens up more possibilities. Suppose you want to select the height and weight of the second and third family member. You want both rows, so you put in a colon before the comma. You only want the second and third column, so you put in the indices 1 to 3 after the comma. Remember that the third index is not included here. The intersection gives us a 2D array with 2 rows and 2 columns:

Similarly, you can select the weight of all family members like this: you only want the second row, so put 1 before the comma. You want all columns, so you use a colon after the comma. The intersection gives us the entire second row.

Finally, 2D numpy arrays enable you to do element-wise calculations, the same way you did it with 1D numpy arrays. That's something you can experiment with in the exercises, along with creating and subsetting 2D numpy arrays! Exciting

---

## Type of Numpy Arrays

```yaml
type: FullSlide
key: 1b9db47fd2
```

`@part1`
```py
import numpy as np
np_height = np.array([1.73, 1.68, 1.71, 1.89, 1.79])
np_weight = np.array([65.4, 59.2, 63.6, 88.4, 68.7])
type(np_height)
```

```out
numpy.ndarray
```

```py
type(np_weight)
```

```out
numpy.ndarray
```

`@script`


---

## 2D Numpy Arrays

```yaml
type: FullSlide
key: ebb550dcba
```

`@part1`
```py
np_2d = np.array([[1.73, 1.68, 1.71, 1.89, 1.79],
```

```out
[65.4, 59.2, 63.6, 88.4, 68.7]])
```

```py
np_2d
```

```out
array([[  1.73,   1.68,   1.71,   1.89,   1.79],
       [ 65.4 ,  59.2 ,  63.6 ,  88.4 ,  68.7 ]])
```

```py
np_2d.shape
```

```out
2 rows, 5 columns
```

```py
np.array([[1.73, 1.68, 1.71, 1.89, 1.79],
```

```out
[65.4, 59.2, 63.6, 88.4, "68.7"]])

```

`@script`


---

## Subsetting

```yaml
type: FullSlide
key: e0062fa1e4
```

`@part1`
0                       1                        2                      3                       4


```py
np_2d[0]
```

```out
array([ 1.73,  1.68,  1.71,  1.89,  1.79])
```

```py
np_2d[0][2]
```

```out
1.71
```

`@script`


---

## Subsetting

```yaml
type: FullSlide
key: 5417c722e9
```

`@part1`
0                       1                        2                      3                       4


```py
np_2d[0]
```

```out
array([ 1.73,  1.68,  1.71,  1.89,  1.79])
```

```py
np_2d[0,2]
```

```out
1.71
```

```py
np_2d[:,1:3]
```

```out
array([[  1.68,   1.71],
       [ 59.2 ,  63.6 ]])
```

`@script`


---

## Subsetting

```yaml
type: FullSlide
key: e71d2fc8b8
```

`@part1`
0                       1                        2                      3                       4
                   4

```py
np_2d[0]
```

```out
array([ 1.73,  1.68,  1.71,  1.89,  1.79])
```

```py
np_2d[0][2]
```

```out
1.71
```

```

```py
np_2d[:,1:3]
```

```out
array([[  1.68,   1.71],
       [ 59.2 ,  63.6 ]])
```

```py
np_2d[1,:]
```

```out
array([ 65.4,  59.2,  63.6,  88.4,  68.7])
```

`@script`


---

## Let's practice!

```yaml
type: FinalSlide
key: 6047b27c09
```

`@script`
