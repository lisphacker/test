<div itemscope itemtype="http://developers.google.com/ReferenceObject">
<meta itemprop="name" content="tf.contrib.framework.with_same_shape" />
<meta itemprop="path" content="Stable" />
</div>

# tf.contrib.framework.with_same_shape

``` python
tf.contrib.framework.with_same_shape(
    expected_tensor,
    tensor
)
```

Assert tensors are the same shape, from the same graph.

#### Args:

* <b>`expected_tensor`</b>: Tensor with expected shape.
* <b>`tensor`</b>: Tensor of actual values.

#### Returns:

The original tensor argument, possibly with assert ops added.