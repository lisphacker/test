<div itemscope itemtype="http://developers.google.com/ReferenceObject">
<meta itemprop="name" content="tf.train.SessionRunArgs" />
<meta itemprop="path" content="Stable" />
<meta itemprop="property" content="fetches"/>
<meta itemprop="property" content="feed_dict"/>
<meta itemprop="property" content="options"/>
<meta itemprop="property" content="__new__"/>
</div>

# tf.train.SessionRunArgs

## Class `SessionRunArgs`



### Aliases:

* Class `tf.estimator.SessionRunArgs`
* Class `tf.train.SessionRunArgs`

Represents arguments to be added to a `Session.run()` call.

#### Args:

* <b>`fetches`</b>: Exactly like the 'fetches' argument to Session.Run().
    Can be a single tensor or op, a list of 'fetches' or a dictionary
    of fetches.  For example:
      fetches = global_step_tensor
      fetches = [train_op, summary_op, global_step_tensor]
      fetches = {'step': global_step_tensor, 'summ': summary_op}
    Note that this can recurse as expected:
      fetches = {'step': global_step_tensor,
                 'ops': [train_op, check_nan_op]}
* <b>`feed_dict`</b>: Exactly like the `feed_dict` argument to `Session.Run()`
* <b>`options`</b>: Exactly like the `options` argument to `Session.run()`, i.e., a
    config_pb2.RunOptions proto.

<h2 id="__new__"><code>__new__</code></h2>

``` python
@staticmethod
__new__(
    cls,
    fetches,
    feed_dict=None,
    options=None
)
```

Create new instance of SessionRunArgs(fetches, feed_dict, options)



## Properties

<h3 id="fetches"><code>fetches</code></h3>



<h3 id="feed_dict"><code>feed_dict</code></h3>



<h3 id="options"><code>options</code></h3>





