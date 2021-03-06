<div itemscope itemtype="http://developers.google.com/ReferenceObject">
<meta itemprop="name" content="tf.math.zero_fraction" />
<meta itemprop="path" content="Stable" />
</div>

# tf.math.zero_fraction

### Aliases:

* `tf.math.zero_fraction`
* `tf.nn.zero_fraction`

``` python
tf.math.zero_fraction(
    value,
    name=None
)
```

Returns the fraction of zeros in `value`.

If `value` is empty, the result is `nan`.

This is useful in summaries to measure and report sparsity.  For example,

```python
    z = tf.nn.relu(...)
    summ = tf.compat.v1.summary.scalar('sparsity', tf.nn.zero_fraction(z))
```

#### Args:

* <b>`value`</b>: A tensor of numeric type.
* <b>`name`</b>: A name for the operation (optional).


#### Returns:

The fraction of zeros in `value`, with type `float32`.