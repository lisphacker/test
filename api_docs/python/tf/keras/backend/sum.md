<div itemscope itemtype="http://developers.google.com/ReferenceObject">
<meta itemprop="name" content="tf.keras.backend.sum" />
<meta itemprop="path" content="Stable" />
</div>

# tf.keras.backend.sum

``` python
tf.keras.backend.sum(
    x,
    axis=None,
    keepdims=False
)
```

Sum of the values in a tensor, alongside the specified axis.

#### Arguments:

* <b>`x`</b>: A tensor or variable.
* <b>`axis`</b>: An integer, the axis to sum over.
* <b>`keepdims`</b>: A boolean, whether to keep the dimensions or not.
        If `keepdims` is `False`, the rank of the tensor is reduced
        by 1. If `keepdims` is `True`,
        the reduced dimension is retained with length 1.


#### Returns:

A tensor with sum of `x`.