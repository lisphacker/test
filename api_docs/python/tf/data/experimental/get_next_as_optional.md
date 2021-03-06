<div itemscope itemtype="http://developers.google.com/ReferenceObject">
<meta itemprop="name" content="tf.data.experimental.get_next_as_optional" />
<meta itemprop="path" content="Stable" />
</div>

# tf.data.experimental.get_next_as_optional

### Aliases:

* `tf.contrib.data.get_next_as_optional`
* `tf.data.experimental.get_next_as_optional`

``` python
tf.data.experimental.get_next_as_optional(iterator)
```

Returns an `Optional` that contains the next value from the iterator.

If `iterator` has reached the end of the sequence, the returned `Optional`
will have no value.

#### Args:

* <b>`iterator`</b>: A `tf.compat.v1.data.Iterator` object.


#### Returns:

An `Optional` object representing the next value from the iterator (if it
has one) or no value.