<div itemscope itemtype="http://developers.google.com/ReferenceObject">
<meta itemprop="name" content="tf.batch_gather" />
<meta itemprop="path" content="Stable" />
</div>

# tf.batch_gather

``` python
tf.batch_gather(
    params,
    indices,
    name=None
)
```

Gather slices from params according to indices with leading batch dims. (deprecated)

Warning: THIS FUNCTION IS DEPRECATED. It will be removed after 2017-10-25.
Instructions for updating:
<a href="../tf/batch_gather.md"><code>tf.batch_gather</code></a> is deprecated, please use <a href="../tf/gather.md"><code>tf.gather</code></a> with `batch_dims=-1` instead.