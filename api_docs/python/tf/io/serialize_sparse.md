<div itemscope itemtype="http://developers.google.com/ReferenceObject">
<meta itemprop="name" content="tf.io.serialize_sparse" />
<meta itemprop="path" content="Stable" />
</div>

# tf.io.serialize_sparse

### Aliases:

* `tf.io.serialize_sparse`
* `tf.serialize_sparse`

``` python
tf.io.serialize_sparse(
    sp_input,
    name=None,
    out_type=tf.dtypes.string
)
```

Serialize a `SparseTensor` into a 3-vector (1-D `Tensor`) object.

#### Args:

* <b>`sp_input`</b>: The input `SparseTensor`.
* <b>`name`</b>: A name prefix for the returned tensors (optional).
* <b>`out_type`</b>: The `dtype` to use for serialization.


#### Returns:

A 3-vector (1-D `Tensor`), with each column representing the serialized
`SparseTensor`'s indices, values, and shape (respectively).


#### Raises:

* <b>`TypeError`</b>: If `sp_input` is not a `SparseTensor`.