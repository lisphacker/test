<div itemscope itemtype="http://developers.google.com/ReferenceObject">
<meta itemprop="name" content="tf.graph_util.remove_training_nodes" />
<meta itemprop="path" content="Stable" />
</div>

# tf.graph_util.remove_training_nodes

``` python
tf.graph_util.remove_training_nodes(
    input_graph,
    protected_nodes=None
)
```

Prunes out nodes that aren't needed for inference. (deprecated)

Warning: THIS FUNCTION IS DEPRECATED. It will be removed in a future version.
Instructions for updating:
Use `tf.compat.v1.graph_util.remove_training_nodes`

There are nodes like Identity and CheckNumerics that are only useful
during training, and can be removed in graphs that will be used for
nothing but inference. Here we identify and remove them, returning an
equivalent graph. To be specific, CheckNumerics nodes are always removed, and
Identity nodes that aren't involved in control edges are spliced out so that
their input and outputs are directly connected.

#### Args:

* <b>`input_graph`</b>: Model to analyze and prune.
* <b>`protected_nodes`</b>: An optional list of names of nodes to be kept
    unconditionally. This is for example useful to preserve Identity output
    nodes.


#### Returns:

A list of nodes with the unnecessary ones removed.