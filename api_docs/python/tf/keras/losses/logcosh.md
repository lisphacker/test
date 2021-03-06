<div itemscope itemtype="http://developers.google.com/ReferenceObject">
<meta itemprop="name" content="tf.keras.losses.logcosh" />
<meta itemprop="path" content="Stable" />
</div>

# tf.keras.losses.logcosh

``` python
tf.keras.losses.logcosh(
    y_true,
    y_pred
)
```

Logarithm of the hyperbolic cosine of the prediction error.

`log(cosh(x))` is approximately equal to `(x ** 2) / 2` for small `x` and
to `abs(x) - log(2)` for large `x`. This means that 'logcosh' works mostly
like the mean squared error, but will not be so strongly affected by the
occasional wildly incorrect prediction.

#### Arguments:

* <b>`y_true`</b>: tensor of true targets.
* <b>`y_pred`</b>: tensor of predicted targets.


#### Returns:

Tensor with one scalar loss entry per sample.