<div itemscope itemtype="http://developers.google.com/ReferenceObject">
<meta itemprop="name" content="tf.math.negative" />
<meta itemprop="path" content="Stable" />
</div>

# tf.math.negative

### Aliases:

* `tf.Variable.__neg__`
* `tf.contrib.eager.Variable.__neg__`

``` python
tf.math.negative(
    x,
    name=None
)
```

Computes numerical negative value element-wise.

I.e., \\(y = -x\\).

#### Args:

* <b>`x`</b>: A `Tensor`. Must be one of the following types: `bfloat16`, `half`, `float32`, `float64`, `int32`, `int64`, `complex64`, `complex128`.
* <b>`name`</b>: A name for the operation (optional).


#### Returns:

A `Tensor`. Has the same type as `x`.

If `x` is a `SparseTensor`, returns
`SparseTensor(x.indices, tf.math.negative(x.values, ...), x.dense_shape)`