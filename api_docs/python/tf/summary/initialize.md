<div itemscope itemtype="http://developers.google.com/ReferenceObject">
<meta itemprop="name" content="tf.summary.initialize" />
<meta itemprop="path" content="Stable" />
</div>

# tf.summary.initialize

### Aliases:

* `tf.contrib.summary.initialize`
* `tf.summary.initialize`

``` python
tf.summary.initialize(
    graph=None,
    session=None
)
```

Initializes summary writing for graph execution mode.

This operation is a no-op when executing eagerly.

This helper method provides a higher-level alternative to using
<a href="../../tf/contrib/summary/summary_writer_initializer_op.md"><code>tf.contrib.summary.summary_writer_initializer_op</code></a> and
<a href="../../tf/contrib/summary/graph.md"><code>tf.contrib.summary.graph</code></a>.

Most users will also want to call `tf.compat.v1.train.create_global_step`
which can happen before or after this function is called.

#### Args:

* <b>`graph`</b>: A <a href="../../tf/Graph.md"><code>tf.Graph</code></a> or `tf.compat.v1.GraphDef` to output to the writer.
    This function will not write the default graph by default. When
    writing to an event log file, the associated step will be zero.
* <b>`session`</b>: So this method can call <a href="../../tf/InteractiveSession.md#run"><code>tf.Session.run</code></a>. This defaults
    to `tf.compat.v1.get_default_session`.


#### Raises:

* <b>`RuntimeError`</b>: If  the current thread has no default
    <a href="../../tf/contrib/summary/SummaryWriter.md"><code>tf.contrib.summary.SummaryWriter</code></a>.
* <b>`ValueError`</b>: If session wasn't passed and no default session.