<div itemscope itemtype="http://developers.google.com/ReferenceObject">
<meta itemprop="name" content="tf.contrib.graph_editor.detach_control_outputs" />
<meta itemprop="path" content="Stable" />
</div>

# tf.contrib.graph_editor.detach_control_outputs

``` python
tf.contrib.graph_editor.detach_control_outputs(
    sgv,
    control_outputs
)
```

Detach all the external control outputs of the subgraph sgv.

#### Args:

* <b>`sgv`</b>: the subgraph view to be detached. This argument is converted to a
    subgraph using the same rules as the function subgraph.make_view.
* <b>`control_outputs`</b>: a util.ControlOutputs instance.