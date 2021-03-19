<div itemscope itemtype="http://developers.google.com/ReferenceObject">
<meta itemprop="name" content="tf.signal.ifft" />
<meta itemprop="path" content="Stable" />
</div>

# tf.signal.ifft

### Aliases:

* `tf.ifft`
* `tf.signal.ifft`
* `tf.spectral.ifft`

``` python
tf.signal.ifft(
    input,
    name=None
)
```

Inverse fast Fourier transform.

Computes the inverse 1-dimensional discrete Fourier transform over the
inner-most dimension of `input`.

#### Args:

* <b>`input`</b>: A `Tensor`. Must be one of the following types: `complex64`, `complex128`.
    A complex tensor.
* <b>`name`</b>: A name for the operation (optional).


#### Returns:

A `Tensor`. Has the same type as `input`.