<div itemscope itemtype="http://developers.google.com/ReferenceObject">
<meta itemprop="name" content="tf.get_collection_ref" />
<meta itemprop="path" content="Stable" />
</div>

# tf.get_collection_ref

``` python
tf.get_collection_ref(key)
```

Wrapper for `Graph.get_collection_ref()` using the default graph.

See <a href="../tf/Graph.md#get_collection_ref"><code>tf.Graph.get_collection_ref</code></a>
for more details.

#### Args:

* <b>`key`</b>: The key for the collection. For example, the `GraphKeys` class contains
    many standard names for collections.


#### Returns:

The list of values in the collection with the given `name`, or an empty
list if no value has been added to that collection.  Note that this returns
the collection list itself, which can be modified in place to change the
collection.



#### Eager Compatibility
Collections are not supported when eager execution is enabled.

