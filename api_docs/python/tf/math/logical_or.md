<div itemscope itemtype="http://developers.google.com/ReferenceObject">
<meta itemprop="name" content="tf.math.logical_or" />
<meta itemprop="path" content="Stable" />
</div>

# tf.math.logical_or

### Aliases:

* `tf.RaggedTensor.__or__`
* `tf.logical_or`
* `tf.math.logical_or`

``` python
tf.math.logical_or(
    x,
    y,
    name=None
)
```

Returns the truth value of x OR y element-wise.

*NOTE*: `math.logical_or` supports broadcasting. More about broadcasting
[here](http://docs.scipy.org/doc/numpy/user/basics.broadcasting.html)

#### Args:

* <b>`x`</b>: A `Tensor` of type `bool`.
* <b>`y`</b>: A `Tensor` of type `bool`.
* <b>`name`</b>: A name for the operation (optional).


#### Returns:

A `Tensor` of type `bool`.