<div itemscope itemtype="http://developers.google.com/ReferenceObject">
<meta itemprop="name" content="tf.image.flip_up_down" />
<meta itemprop="path" content="Stable" />
</div>

# tf.image.flip_up_down

``` python
tf.image.flip_up_down(image)
```

Flip an image vertically (upside down).

Outputs the contents of `image` flipped along the height dimension.

See also `reverse()`.

#### Args:

* <b>`image`</b>: 4-D Tensor of shape `[batch, height, width, channels]` or 3-D Tensor
    of shape `[height, width, channels]`.


#### Returns:

A `Tensor` of the same type and shape as `image`.


#### Raises:

* <b>`ValueError`</b>: if the shape of `image` not supported.