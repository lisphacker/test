<div itemscope itemtype="http://developers.google.com/ReferenceObject">
<meta itemprop="name" content="tf.io.serialize_tensor" />
<meta itemprop="path" content="Stable" />
</div>

# tf.io.serialize_tensor

### Aliases:

* `tf.io.serialize_tensor`
* `tf.serialize_tensor`

``` python
tf.io.serialize_tensor(
    tensor,
    name=None
)
```

Transforms a Tensor into a serialized TensorProto proto.

#### Args:

* <b>`tensor`</b>: A `Tensor`. A Tensor of type `T`.
* <b>`name`</b>: A name for the operation (optional).


#### Returns:

A `Tensor` of type `string`.