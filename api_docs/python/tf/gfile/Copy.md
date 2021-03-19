<div itemscope itemtype="http://developers.google.com/ReferenceObject">
<meta itemprop="name" content="tf.gfile.Copy" />
<meta itemprop="path" content="Stable" />
</div>

# tf.gfile.Copy

``` python
tf.gfile.Copy(
    oldpath,
    newpath,
    overwrite=False
)
```

Copies data from `oldpath` to `newpath`.

#### Args:

* <b>`oldpath`</b>: string, name of the file who's contents need to be copied
* <b>`newpath`</b>: string, name of the file to which to copy to
* <b>`overwrite`</b>: boolean, if false it's an error for `newpath` to be occupied by
    an existing file.


#### Raises:

* <b>`errors.OpError`</b>: If the operation fails.