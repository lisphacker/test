<div itemscope itemtype="http://developers.google.com/ReferenceObject">
<meta itemprop="name" content="tf.keras.backend.squeeze" />
<meta itemprop="path" content="Stable" />
</div>

# tf.keras.backend.squeeze

``` python
tf.keras.backend.squeeze(
    x,
    axis
)
```

Removes a 1-dimension from the tensor at index "axis".

#### Arguments:

* <b>`x`</b>: A tensor or variable.
* <b>`axis`</b>: Axis to drop.


#### Returns:

A tensor with the same data as `x` but reduced dimensions.