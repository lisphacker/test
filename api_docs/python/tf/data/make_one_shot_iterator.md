<div itemscope itemtype="http://developers.google.com/ReferenceObject">
<meta itemprop="name" content="tf.data.make_one_shot_iterator" />
<meta itemprop="path" content="Stable" />
</div>

# tf.data.make_one_shot_iterator

``` python
tf.data.make_one_shot_iterator(dataset)
```

Creates a `tf.compat.v1.data.Iterator` for enumerating the elements of a dataset.

Note: The returned iterator will be initialized automatically.
A "one-shot" iterator does not support re-initialization.

#### Args:

* <b>`dataset`</b>: A <a href="../../tf/data/Dataset.md"><code>tf.data.Dataset</code></a>.


#### Returns:

A `tf.compat.v1.data.Iterator` over the elements of this dataset.