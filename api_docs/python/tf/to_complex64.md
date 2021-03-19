<div itemscope itemtype="http://developers.google.com/ReferenceObject">
<meta itemprop="name" content="tf.to_complex64" />
<meta itemprop="path" content="Stable" />
</div>

# tf.to_complex64

``` python
tf.to_complex64(
    x,
    name='ToComplex64'
)
```

Casts a tensor to type `complex64`. (deprecated)

Warning: THIS FUNCTION IS DEPRECATED. It will be removed in a future version.
Instructions for updating:
Use <a href="../tf/cast.md"><code>tf.cast</code></a> instead.

#### Args:

* <b>`x`</b>: A `Tensor` or `SparseTensor` or `IndexedSlices`.
* <b>`name`</b>: A name for the operation (optional).


#### Returns:

A `Tensor` or `SparseTensor` or `IndexedSlices` with same shape as `x` with
type `complex64`.


#### Raises:

* <b>`TypeError`</b>: If `x` cannot be cast to the `complex64`.