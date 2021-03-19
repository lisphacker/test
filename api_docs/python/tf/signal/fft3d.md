<div itemscope itemtype="http://developers.google.com/ReferenceObject">
<meta itemprop="name" content="tf.signal.fft3d" />
<meta itemprop="path" content="Stable" />
</div>

# tf.signal.fft3d

### Aliases:

* `tf.fft3d`
* `tf.signal.fft3d`
* `tf.spectral.fft3d`

``` python
tf.signal.fft3d(
    input,
    name=None
)
```

3D fast Fourier transform.

Computes the 3-dimensional discrete Fourier transform over the inner-most 3
dimensions of `input`.

#### Args:

* <b>`input`</b>: A `Tensor`. Must be one of the following types: `complex64`, `complex128`.
    A complex64 tensor.
* <b>`name`</b>: A name for the operation (optional).


#### Returns:

A `Tensor`. Has the same type as `input`.