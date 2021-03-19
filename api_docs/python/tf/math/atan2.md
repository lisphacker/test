<div itemscope itemtype="http://developers.google.com/ReferenceObject">
<meta itemprop="name" content="tf.math.atan2" />
<meta itemprop="path" content="Stable" />
</div>

# tf.math.atan2

### Aliases:

* `tf.atan2`
* `tf.math.atan2`

``` python
tf.math.atan2(
    y,
    x,
    name=None
)
```

Computes arctangent of `y/x` element-wise, respecting signs of the arguments.

This is the angle \( \theta \in [-\pi, \pi] \) such that
\[ x = r \cos(\theta) \]
and
\[ y = r \sin(\theta) \]
where \(r = \sqrt(x^2 + y^2) \).

#### Args:

* <b>`y`</b>: A `Tensor`. Must be one of the following types: `bfloat16`, `half`, `float32`, `float64`.
* <b>`x`</b>: A `Tensor`. Must have the same type as `y`.
* <b>`name`</b>: A name for the operation (optional).


#### Returns:

A `Tensor`. Has the same type as `y`.