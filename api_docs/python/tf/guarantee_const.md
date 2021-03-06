<div itemscope itemtype="http://developers.google.com/ReferenceObject">
<meta itemprop="name" content="tf.guarantee_const" />
<meta itemprop="path" content="Stable" />
</div>

# tf.guarantee_const

``` python
tf.guarantee_const(
    input,
    name=None
)
```

Gives a guarantee to the TF runtime that the input tensor is a constant.

The runtime is then free to make optimizations based on this.

Only accepts value typed tensors as inputs and rejects resource variable handles
as input.

Returns the input tensor without modification.

#### Args:

* <b>`input`</b>: A `Tensor`.
* <b>`name`</b>: A name for the operation (optional).


#### Returns:

A `Tensor`. Has the same type as `input`.