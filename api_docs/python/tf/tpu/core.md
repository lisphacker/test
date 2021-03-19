<div itemscope itemtype="http://developers.google.com/ReferenceObject">
<meta itemprop="name" content="tf.tpu.core" />
<meta itemprop="path" content="Stable" />
</div>

# tf.tpu.core

### Aliases:

* `tf.contrib.tpu.core`
* `tf.tpu.core`

``` python
tf.tpu.core(num)
```

Returns the device name for a core in a replicated TPU computation.

#### Args:

* <b>`num`</b>: the virtual core number within each replica to which operators should
  be assigned.

#### Returns:

A device name, suitable for passing to `tf.device()`.