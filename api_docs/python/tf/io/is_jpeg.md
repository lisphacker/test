<div itemscope itemtype="http://developers.google.com/ReferenceObject">
<meta itemprop="name" content="tf.io.is_jpeg" />
<meta itemprop="path" content="Stable" />
</div>

# tf.io.is_jpeg

### Aliases:

* `tf.image.is_jpeg`
* `tf.io.is_jpeg`

``` python
tf.io.is_jpeg(
    contents,
    name=None
)
```

Convenience function to check if the 'contents' encodes a JPEG image.

#### Args:

* <b>`contents`</b>: 0-D `string`. The encoded image bytes.
* <b>`name`</b>: A name for the operation (optional)


#### Returns:

A scalar boolean tensor indicating if 'contents' may be a JPEG image.
is_jpeg is susceptible to false positives.