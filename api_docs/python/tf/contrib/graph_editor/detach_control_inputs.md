<div itemscope itemtype="http://developers.google.com/ReferenceObject">
<meta itemprop="name" content="tf.contrib.graph_editor.detach_control_inputs" />
<meta itemprop="path" content="Stable" />
</div>

# tf.contrib.graph_editor.detach_control_inputs

``` python
tf.contrib.graph_editor.detach_control_inputs(sgv)
```

Detach all the external control inputs of the subgraph sgv.

#### Args:

* <b>`sgv`</b>: the subgraph view to be detached. This argument is converted to a
    subgraph using the same rules as the function subgraph.make_view.