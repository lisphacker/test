<div itemscope itemtype="http://developers.google.com/ReferenceObject">
<meta itemprop="name" content="tf.dtypes.saturate_cast" />
<meta itemprop="path" content="Stable" />
</div>

# tf.dtypes.saturate_cast

### Aliases:

* `tf.dtypes.saturate_cast`
* `tf.saturate_cast`

``` python
tf.dtypes.saturate_cast(
    value,
    dtype,
    name=None
)
```

Performs a safe saturating cast of `value` to `dtype`.

This function casts the input to `dtype` without applying any scaling.  If
there is a danger that values would over or underflow in the cast, this op
applies the appropriate clamping before the cast.

#### Args:

* <b>`value`</b>: A `Tensor`.
* <b>`dtype`</b>: The desired output `DType`.
* <b>`name`</b>: A name for the operation (optional).


#### Returns:

`value` safely cast to `dtype`.