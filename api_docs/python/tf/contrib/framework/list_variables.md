<div itemscope itemtype="http://developers.google.com/ReferenceObject">
<meta itemprop="name" content="tf.contrib.framework.list_variables" />
<meta itemprop="path" content="Stable" />
</div>

# tf.contrib.framework.list_variables

``` python
tf.contrib.framework.list_variables(checkpoint_dir)
```

Returns list of all variables in the latest checkpoint.

#### Args:

* <b>`checkpoint_dir`</b>: Directory with checkpoints file or path to checkpoint.


#### Returns:

List of tuples `(name, shape)`.