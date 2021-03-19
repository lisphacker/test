<div itemscope itemtype="http://developers.google.com/ReferenceObject">
<meta itemprop="name" content="tf.fixed_size_partitioner" />
<meta itemprop="path" content="Stable" />
</div>

# tf.fixed_size_partitioner

``` python
tf.fixed_size_partitioner(
    num_shards,
    axis=0
)
```

Partitioner to specify a fixed number of shards along given axis.

#### Args:

* <b>`num_shards`</b>: `int`, number of shards to partition variable.
* <b>`axis`</b>: `int`, axis to partition on.


#### Returns:

A partition function usable as the `partitioner` argument to
`variable_scope` and `get_variable`.