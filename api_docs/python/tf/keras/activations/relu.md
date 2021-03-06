<div itemscope itemtype="http://developers.google.com/ReferenceObject">
<meta itemprop="name" content="tf.keras.activations.relu" />
<meta itemprop="path" content="Stable" />
</div>

# tf.keras.activations.relu

``` python
tf.keras.activations.relu(
    x,
    alpha=0.0,
    max_value=None,
    threshold=0
)
```

Rectified Linear Unit.

With default values, it returns element-wise `max(x, 0)`.

Otherwise, it follows:
`f(x) = max_value` for `x >= max_value`,
`f(x) = x` for `threshold <= x < max_value`,
`f(x) = alpha * (x - threshold)` otherwise.

#### Arguments:

* <b>`x`</b>: A tensor or variable.
* <b>`alpha`</b>: A scalar, slope of negative section (default=`0.`).
* <b>`max_value`</b>: float. Saturation threshold.
* <b>`threshold`</b>: float. Threshold value for thresholded activation.


#### Returns:

A tensor.