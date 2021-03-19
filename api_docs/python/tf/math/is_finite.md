<div itemscope itemtype="http://developers.google.com/ReferenceObject">
<meta itemprop="name" content="tf.math.is_finite" />
<meta itemprop="path" content="Stable" />
</div>

# tf.math.is_finite

### Aliases:

* `tf.debugging.is_finite`
* `tf.is_finite`
* `tf.math.is_finite`

``` python
tf.math.is_finite(
    x,
    name=None
)
```

Returns which elements of x are finite.



#### Args:

* <b>`x`</b>: A `Tensor`. Must be one of the following types: `bfloat16`, `half`, `float32`, `float64`.
* <b>`name`</b>: A name for the operation (optional).


#### Returns:

A `Tensor` of type `bool`.

#### Numpy Compatibility
Equivalent to np.isfinite

