<div itemscope itemtype="http://developers.google.com/ReferenceObject">
<meta itemprop="name" content="tf.gfile.Stat" />
<meta itemprop="path" content="Stable" />
</div>

# tf.gfile.Stat

``` python
tf.gfile.Stat(filename)
```

Returns file statistics for a given path.

#### Args:

* <b>`filename`</b>: string, path to a file


#### Returns:

FileStatistics struct that contains information about the path


#### Raises:

* <b>`errors.OpError`</b>: If the operation fails.