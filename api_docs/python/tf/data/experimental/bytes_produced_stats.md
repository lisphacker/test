<div itemscope itemtype="http://developers.google.com/ReferenceObject">
<meta itemprop="name" content="tf.data.experimental.bytes_produced_stats" />
<meta itemprop="path" content="Stable" />
</div>

# tf.data.experimental.bytes_produced_stats

``` python
tf.data.experimental.bytes_produced_stats(tag)
```

Records the number of bytes produced by each element of the input dataset.

To consume the statistics, associate a `StatsAggregator` with the output
dataset.

#### Args:

* <b>`tag`</b>: String. All statistics recorded by the returned transformation will
    be associated with the given `tag`.


#### Returns:

A `Dataset` transformation function, which can be passed to
<a href="../../../tf/data/Dataset.md#apply"><code>tf.data.Dataset.apply</code></a>.