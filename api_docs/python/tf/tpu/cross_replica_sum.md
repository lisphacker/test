<div itemscope itemtype="http://developers.google.com/ReferenceObject">
<meta itemprop="name" content="tf.tpu.cross_replica_sum" />
<meta itemprop="path" content="Stable" />
</div>

# tf.tpu.cross_replica_sum

### Aliases:

* `tf.contrib.tpu.cross_replica_sum`
* `tf.tpu.cross_replica_sum`

``` python
tf.tpu.cross_replica_sum(
    x,
    group_assignment=None,
    name=None
)
```

Sum the input tensor across replicas according to group_assignment.

#### Args:

* <b>`x`</b>: The local tensor to the sum.
* <b>`group_assignment`</b>: Optional 2d int32 lists with shape [num_groups,
    num_replicas_per_group]. `group_assignment[i]` represents the replica
    ids in the ith subgroup.
* <b>`name`</b>: Optional op name.


#### Returns:

A `Tensor` which is summed across replicas.