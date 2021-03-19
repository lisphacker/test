<div itemscope itemtype="http://developers.google.com/ReferenceObject">
<meta itemprop="name" content="tf.signal.fft" />
<meta itemprop="path" content="Stable" />
</div>

# tf.signal.fft

### Aliases:

* `tf.fft`
* `tf.signal.fft`
* `tf.spectral.fft`

``` python
tf.signal.fft(
    input,
    name=None
)
```

Fast Fourier transform.

Computes the 1-dimensional discrete Fourier transform over the inner-most
dimension of `input`.

#### Args:

* <b>`input`</b>: A `Tensor`. Must be one of the following types: `complex64`, `complex128`.
    A complex tensor.
* <b>`name`</b>: A name for the operation (optional).


#### Returns:

A `Tensor`. Has the same type as `input`.