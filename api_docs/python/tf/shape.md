<div itemscope itemtype="http://developers.google.com/ReferenceObject">
<meta itemprop="name" content="tf.shape" />
<meta itemprop="path" content="Stable" />
</div>

# tf.shape

``` python
tf.shape(
    input,
    name=None,
    out_type=tf.dtypes.int32
)
```

Returns the shape of a tensor.

This operation returns a 1-D integer tensor representing the shape of `input`.

For example:

```python
t = tf.constant([[[1, 1, 1], [2, 2, 2]], [[3, 3, 3], [4, 4, 4]]])
tf.shape(t)  # [2, 2, 3]
```

#### Args:

* <b>`input`</b>: A `Tensor` or `SparseTensor`.
* <b>`name`</b>: A name for the operation (optional).
* <b>`out_type`</b>: (Optional) The specified output type of the operation (`int32` or
    `int64`). Defaults to <a href="../tf/dtypes.md#int32"><code>tf.int32</code></a>.


#### Returns:

A `Tensor` of type `out_type`.