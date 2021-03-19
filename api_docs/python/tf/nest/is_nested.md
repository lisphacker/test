<div itemscope itemtype="http://developers.google.com/ReferenceObject">
<meta itemprop="name" content="tf.nest.is_nested" />
<meta itemprop="path" content="Stable" />
</div>

# tf.nest.is_nested

### Aliases:

* `tf.contrib.framework.nest.is_nested`
* `tf.nest.is_nested`

``` python
tf.nest.is_nested(seq)
```

Returns true if its input is a collections.abc.Sequence (except strings).

#### Args:

* <b>`seq`</b>: an input sequence.


#### Returns:

True if the sequence is a not a string and is a collections.abc.Sequence
or a dict.