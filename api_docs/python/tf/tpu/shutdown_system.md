<div itemscope itemtype="http://developers.google.com/ReferenceObject">
<meta itemprop="name" content="tf.tpu.shutdown_system" />
<meta itemprop="path" content="Stable" />
</div>

# tf.tpu.shutdown_system

### Aliases:

* `tf.contrib.tpu.shutdown_system`
* `tf.tpu.shutdown_system`

``` python
tf.tpu.shutdown_system(job=None)
```

Shuts down a running a distributed TPU system.

#### Args:

* <b>`job`</b>: The job (the XXX in TensorFlow device specification /job:XXX) that
    contains the TPU devices that will be shutdown. If job=None it is
    assumed there is only one job in the TensorFlow flock, and an error will
    be returned if this assumption does not hold.