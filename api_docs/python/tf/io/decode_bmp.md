<div itemscope itemtype="http://developers.google.com/ReferenceObject">
<meta itemprop="name" content="tf.io.decode_bmp" />
<meta itemprop="path" content="Stable" />
</div>

# tf.io.decode_bmp

### Aliases:

* `tf.image.decode_bmp`
* `tf.io.decode_bmp`

``` python
tf.io.decode_bmp(
    contents,
    channels=0,
    name=None
)
```

Decode the first frame of a BMP-encoded image to a uint8 tensor.

The attr `channels` indicates the desired number of color channels for the
decoded image.

Accepted values are:

*   0: Use the number of channels in the BMP-encoded image.
*   3: output an RGB image.
*   4: output an RGBA image.

#### Args:

* <b>`contents`</b>: A `Tensor` of type `string`. 0-D.  The BMP-encoded image.
* <b>`channels`</b>: An optional `int`. Defaults to `0`.
* <b>`name`</b>: A name for the operation (optional).


#### Returns:

A `Tensor` of type `uint8`.