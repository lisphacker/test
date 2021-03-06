<div itemscope itemtype="http://developers.google.com/ReferenceObject">
<meta itemprop="name" content="tf.keras.backend.resize_images" />
<meta itemprop="path" content="Stable" />
</div>

# tf.keras.backend.resize_images

``` python
tf.keras.backend.resize_images(
    x,
    height_factor,
    width_factor,
    data_format,
    interpolation='nearest'
)
```

Resizes the images contained in a 4D tensor.

#### Arguments:

* <b>`x`</b>: Tensor or variable to resize.
* <b>`height_factor`</b>: Positive integer.
* <b>`width_factor`</b>: Positive integer.
* <b>`data_format`</b>: One of `"channels_first"`, `"channels_last"`.
* <b>`interpolation`</b>: A string, one of `nearest` or `bilinear`.


#### Returns:

A tensor.


#### Raises:

* <b>`ValueError`</b>: in case of incorrect value for
      `data_format` or `interpolation`.