<div itemscope itemtype="http://developers.google.com/ReferenceObject">
<meta itemprop="name" content="tf.signal.ifft3d" />
<meta itemprop="path" content="Stable" />
</div>

# tf.signal.ifft3d

### Aliases:

* `tf.ifft3d`
* `tf.signal.ifft3d`
* `tf.spectral.ifft3d`

``` python
tf.signal.ifft3d(
    input,
    name=None
)
```

Inverse 3D fast Fourier transform.

Computes the inverse 3-dimensional discrete Fourier transform over the
inner-most 3 dimensions of `input`.

#### Args:

* <b>`input`</b>: A `Tensor`. Must be one of the following types: `complex64`, `complex128`.
    A complex64 tensor.
* <b>`name`</b>: A name for the operation (optional).


#### Returns:

A `Tensor`. Has the same type as `input`.