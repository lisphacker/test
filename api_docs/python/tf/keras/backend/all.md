<div itemscope itemtype="http://developers.google.com/ReferenceObject">
<meta itemprop="name" content="tf.keras.backend.all" />
<meta itemprop="path" content="Stable" />
</div>

# tf.keras.backend.all

``` python
tf.keras.backend.all(
    x,
    axis=None,
    keepdims=False
)
```

Bitwise reduction (logical AND).

#### Arguments:

* <b>`x`</b>: Tensor or variable.
* <b>`axis`</b>: axis along which to perform the reduction.
* <b>`keepdims`</b>: whether the drop or broadcast the reduction axes.


#### Returns:

A uint8 tensor (0s and 1s).