---
layout: default
---

<!-- Note: This file is automatically generated from source code comments. Changes made in this file will be overridden. -->

<h1 id="function-sparse">Function sparse <a href="#function-sparse" title="Permalink">#</a></h1>

Create a Sparse Matrix. The function creates a new `math.type.Matrix` object from
an `Array`. A Matrix has utility functions to manipulate the data in the
matrix, like getting the size and getting or setting values in the matrix.


<h2 id="syntax">Syntax <a href="#syntax" title="Permalink">#</a></h2>

```js
math.sparse()               // creates an empty sparse matrix.
math.sparse(data)           // creates a sparse matrix with initial data.
math.sparse(data, 'number') // creates a sparse matrix with initial data, number datatype.
```

<h3 id="parameters">Parameters <a href="#parameters" title="Permalink">#</a></h3>

Parameter | Type | Description
--------- | ---- | -----------
`data` | Array &#124; Matrix | A two dimensional array

<h3 id="returns">Returns <a href="#returns" title="Permalink">#</a></h3>

Type | Description
---- | -----------
Matrix | The created matrix


<h2 id="examples">Examples <a href="#examples" title="Permalink">#</a></h2>

```js
var m = math.sparse([[1, 2], [3, 4]]);
m.size();                        // Array [2, 2]
m.resize([3, 2], 5);
m.valueOf();                     // Array [[1, 2], [3, 4], [5, 5]]
m.get([1, 0])                    // number 3
```


<h2 id="see-also">See also <a href="#see-also" title="Permalink">#</a></h2>

[bignumber](bignumber.html),
[boolean](boolean.html),
[complex](complex.html),
[index](index.html),
[number](number.html),
[string](string.html),
[unit](unit.html),
[matrix](matrix.html)