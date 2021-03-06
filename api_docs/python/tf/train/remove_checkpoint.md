<div itemscope itemtype="http://developers.google.com/ReferenceObject">
<meta itemprop="name" content="tf.train.remove_checkpoint" />
<meta itemprop="path" content="Stable" />
</div>

# tf.train.remove_checkpoint

``` python
tf.train.remove_checkpoint(
    checkpoint_prefix,
    checkpoint_format_version=tf.train.SaverDef.V2,
    meta_graph_suffix='meta'
)
```

Removes a checkpoint given by `checkpoint_prefix`. (deprecated)

Warning: THIS FUNCTION IS DEPRECATED. It will be removed in a future version.
Instructions for updating:
Use standard file APIs to delete files with this prefix.

#### Args:

* <b>`checkpoint_prefix`</b>: The prefix of a V1 or V2 checkpoint. Typically the result
    of `Saver.save()` or that of `tf.train.latest_checkpoint()`, regardless of
    sharded/non-sharded or V1/V2.
* <b>`checkpoint_format_version`</b>: `SaverDef.CheckpointFormatVersion`, defaults to
    `SaverDef.V2`.
* <b>`meta_graph_suffix`</b>: Suffix for `MetaGraphDef` file. Defaults to 'meta'.