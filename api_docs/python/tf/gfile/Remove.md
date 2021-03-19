<div itemscope itemtype="http://developers.google.com/ReferenceObject">
<meta itemprop="name" content="tf.gfile.Remove" />
<meta itemprop="path" content="Stable" />
</div>

# tf.gfile.Remove

``` python
tf.gfile.Remove(filename)
```

Deletes the file located at 'filename'.

#### Args:

* <b>`filename`</b>: string, a filename


#### Raises:

* <b>`errors.OpError`</b>: Propagates any errors reported by the FileSystem API.  E.g.,
  NotFoundError if the file does not exist.