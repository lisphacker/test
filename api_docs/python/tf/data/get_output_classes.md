<div itemscope itemtype="http://developers.google.com/ReferenceObject">
<meta itemprop="name" content="tf.data.get_output_classes" />
<meta itemprop="path" content="Stable" />
</div>

# tf.data.get_output_classes

``` python
tf.data.get_output_classes(dataset_or_iterator)
```

Returns the output classes of a `Dataset` or `Iterator` elements.

This utility method replaces the deprecated-in-V2
`tf.compat.v1.Dataset.output_classes` property.

#### Args:

* <b>`dataset_or_iterator`</b>: A <a href="../../tf/data/Dataset.md"><code>tf.data.Dataset</code></a> or `tf.data.IteratorV2`.


#### Returns:

A nested structure of Python `type` objects matching the structure of the
dataset / iterator elements and specifying the class of the individual
components.