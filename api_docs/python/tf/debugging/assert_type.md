<div itemscope itemtype="http://developers.google.com/ReferenceObject">
<meta itemprop="name" content="tf.debugging.assert_type" />
<meta itemprop="path" content="Stable" />
</div>

# tf.debugging.assert_type

### Aliases:

* `tf.assert_type`
* `tf.debugging.assert_type`

``` python
tf.debugging.assert_type(
    tensor,
    tf_type,
    message=None,
    name=None
)
```

Statically asserts that the given `Tensor` is of the specified type.

#### Args:

* <b>`tensor`</b>: A `Tensor`.
* <b>`tf_type`</b>: A tensorflow type (`dtypes.float32`, <a href="../../tf/dtypes.md#int64"><code>tf.int64</code></a>, `dtypes.bool`,
    etc).
* <b>`message`</b>: A string to prefix to the default message.
* <b>`name`</b>:  A name to give this `Op`.  Defaults to "assert_type"


#### Raises:

* <b>`TypeError`</b>: If the tensors data type doesn't match `tf_type`.


#### Returns:

A `no_op` that does nothing.  Type can be determined statically.