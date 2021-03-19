<div itemscope itemtype="http://developers.google.com/ReferenceObject">
<meta itemprop="name" content="tf.train.checkpoint_exists" />
<meta itemprop="path" content="Stable" />
</div>

# tf.train.checkpoint_exists

``` python
tf.train.checkpoint_exists(checkpoint_prefix)
```

Checks whether a V1 or V2 checkpoint exists with the specified prefix. (deprecated)

Warning: THIS FUNCTION IS DEPRECATED. It will be removed in a future version.
Instructions for updating:
Use standard file APIs to check for files with this prefix.

This is the recommended way to check if a checkpoint exists, since it takes
into account the naming difference between V1 and V2 formats.

#### Args:

* <b>`checkpoint_prefix`</b>: the prefix of a V1 or V2 checkpoint, with V2 taking
    priority.  Typically the result of `Saver.save()` or that of
    `tf.train.latest_checkpoint()`, regardless of sharded/non-sharded or
    V1/V2.


#### Returns:

A bool, true if a checkpoint referred to by `checkpoint_prefix` exists.