<div itemscope itemtype="http://developers.google.com/ReferenceObject">
<meta itemprop="name" content="tf.tpu.experimental.initialize_tpu_system" />
<meta itemprop="path" content="Stable" />
</div>

# tf.tpu.experimental.initialize_tpu_system

### Aliases:

* `tf.contrib.distribute.initialize_tpu_system`
* `tf.tpu.experimental.initialize_tpu_system`

``` python
tf.tpu.experimental.initialize_tpu_system(cluster_resolver=None)
```

Initialize the TPU devices.

#### Args:

* <b>`cluster_resolver`</b>: A tf.distribute.cluster_resolver.TPUClusterResolver,
      which provides information about the TPU cluster.

#### Returns:

The tf.tpu.Topology object for the topology of the TPU cluster.


#### Raises:

* <b>`RuntimeError`</b>: If no TPU devices found for eager execution.