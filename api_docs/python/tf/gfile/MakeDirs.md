<div itemscope itemtype="http://developers.google.com/ReferenceObject">
<meta itemprop="name" content="tf.gfile.MakeDirs" />
<meta itemprop="path" content="Stable" />
</div>

# tf.gfile.MakeDirs

``` python
tf.gfile.MakeDirs(dirname)
```

Creates a directory and all parent/intermediate directories.

It succeeds if dirname already exists and is writable.

#### Args:

* <b>`dirname`</b>: string, name of the directory to be created


#### Raises:

* <b>`errors.OpError`</b>: If the operation fails.