<div itemscope itemtype="http://developers.google.com/ReferenceObject">
<meta itemprop="name" content="tf.io.gfile.walk" />
<meta itemprop="path" content="Stable" />
</div>

# tf.io.gfile.walk

``` python
tf.io.gfile.walk(
    top,
    topdown=True,
    onerror=None
)
```

Recursive directory tree generator for directories.

#### Args:

* <b>`top`</b>: string, a Directory name
* <b>`topdown`</b>: bool, Traverse pre order if True, post order if False.
* <b>`onerror`</b>: optional handler for errors. Should be a function, it will be
    called with the error as argument. Rethrowing the error aborts the walk.
    Errors that happen while listing directories are ignored.


#### Yields:

Each yield is a 3-tuple:  the pathname of a directory, followed by lists of
all its subdirectories and leaf files.
(dirname, [subdirname, subdirname, ...], [filename, filename, ...])
as strings